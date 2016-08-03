#### Test 796897756b82a43_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-03 19:50:26.619  1980  1980 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-03 19:50:26.619  1980  1980 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
--------- beginning of system
08-03 19:50:26.620  1041  1889 W libprocessgroup: failed to open /acct/uid_10085/pid_4916/cgroup.procs: No such file or directory
08-03 19:50:26.624  1980  1980 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-03 19:50:26.628  3666  3666 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 19:50:26.632  3666  3666 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-03 19:50:26.648   333   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 19:50:26.650  3184  5836 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 19:50:26.692  1041  1679 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5837 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:50:26.882  5837  5837 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-03 19:50:27.010  5837  5837 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:50:27.011  5837  5837 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:50:27.087  5837  5837 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-03 19:50:27.116  5837  5837 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-03 19:50:27.118  5837  5837 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-03 19:50:27.149  5837  5837 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-03 19:50:27.149  5837  5837 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-03 19:50:27.167  1041  2027 I ActivityManager: Killing 5285:com.lge.clock/u0a10 (adj 15): empty #17
08-03 19:50:27.200  1041  1762 W libprocessgroup: failed to open /acct/uid_10010/pid_5285/cgroup.procs: No such file or directory
08-03 19:50:27.213  3430  4508 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-03 19:50:27.215  3430  4508 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@46af89a on behalf of 5837
08-03 19:50:27.218  4534  5899 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-03 19:50:27.264  1041  1889 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5900 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:50:27.302  5837  5837 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-03 19:50:27.335  5837  5837 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-03 19:50:27.422  5900  5900 D DocsApplication: Installing DEX configuration.
08-03 19:50:27.440  5900  5900 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-03 19:50:27.445  5900  5900 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{9f426a9 com.google.android.apps.docs}
08-03 19:50:27.460  5900  5900 D TAG     : onCreate()
08-03 19:50:27.477  5900  5900 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-03 19:50:27.580  1041  2027 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:50:27.649  4534  5899 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 431 ms] updated apps [took 431 ms] 
,08-03 19:50:28.541  5939  5939 D AndroidRuntime: 
08-03 19:50:28.541  5939  5939 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 19:50:28.543  5939  5939 D AndroidRuntime: CheckJNI is OFF
08-03 19:50:28.653  1802  4666 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-03 19:50:28.660  5939  5939 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 19:50:28.665  1041  1889 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 19:50:28.676  1926  1941 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-03 19:50:28.679  1041  1889 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-03 19:50:28.680  1041  1889 D ActivityManager: setTaskToReturnTo : TaskRecord{18590d5f #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 19:50:28.680  1041  1889 D ActivityManager: setTaskToReturnTo : TaskRecord{18590d5f #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 19:50:28.681  1041  1889 D WindowStateEx: AppWindowTokenEx init.. 
08-03 19:50:28.682   341   359 E GBMv2   : DFP En is all cleared set to be enabled
08-03 19:50:28.688  5900  5900 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:50:28.688  5900  5900 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:50:28.716  1041  1889 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5955 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-03 19:50:28.719  5939  5939 D AndroidRuntime: Shutting down VM
08-03 19:50:28.758  1926  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-03 19:50:28.758  1926  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c3fc45f co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 19:50:28.759  1926  2517 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-03 19:50:28.759  1926  2517 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1575beac co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 19:50:28.805  5955  5955 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-03 19:50:28.815  1802  4666 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-03 19:50:28.870  5900  5900 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-03 19:50:28.871  5955  5955 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-03 19:50:28.880  1802  4666 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-03 19:50:28.888  1041  1907 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5991 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-03 19:50:28.896  5955  5955 I LibraryLoader: Loading: webviewchromium
08-03 19:50:28.899  5955  5955 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3329-3332)
08-03 19:50:28.899  5955  5955 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:50:28.914  5955  5955 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2df825eb}
08-03 19:50:28.915  5955  5955 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:50:28.915  5955  5955 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 19:50:28.928  5955  5955 I BrowserStartupController: Initializing chromium process, renderers=0
,08-03 19:50:28.929  5955  5955 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:50:28.933  5955  6010 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-03 19:50:28.938  5955  5955 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 19:50:28.939   317  2162 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-03 19:50:28.939  5955  5955 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-03 19:50:28.939  5955  5955 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-03 19:50:28.944  1041  1119 D BluetoothManagerService: Message: 20
08-03 19:50:28.944  1041  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cf812d:true
08-03 19:50:28.950  5991  5991 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-03 19:50:28.951  5955  5955 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:50:28.951  5955  5955 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:50:28.951  5955  5955 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:50:28.951  5955  5955 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:50:28.951  5955  5955 I Adreno-EGL: Remote Branch: 
08-03 19:50:28.951  5955  5955 I Adreno-EGL: Local Patches: 
08-03 19:50:28.951  5955  5955 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:50:28.975  5991  5991 I LockScreenSettings: New app installed broadcast received ..
,08-03 19:50:28.980  5991  5991 I LockScreenSettings: Number of installed packages  1
08-03 19:50:29.016  1041  1888 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6024 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-03 19:50:29.018  1041  1888 I ActivityManager: Killing 5061:com.lge.bnr/1000 (adj 15): empty #17
,08-03 19:50:29.042   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 31.219ms
,08-03 19:50:29.063   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 19.538ms
,08-03 19:50:29.081   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.295ms
,08-03 19:50:29.088  1041  1943 W libprocessgroup: failed to open /acct/uid_1000/pid_5061/cgroup.procs: No such file or directory
08-03 19:50:29.121  5955  6020 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-03 19:50:29.122  5955  5955 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-03 19:50:29.133  6024  6024 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:50:29.136  5955  5955 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:50:29.140  5955  5955 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 19:50:29.142  5955  5955 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-03 19:50:29.145  5955  5955 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-03 19:50:29.145  5955  5955 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-03 19:50:29.156  5955  5955 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-03 19:50:29.162  5955  5955 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:50:29.162  5955  5955 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 19:50:29.195  5955  6049 D OpenGLRenderer: Render dirty regions requested: true
08-03 19:50:29.196  5955  6049 I OpenGLRenderer: Initialized EGL, version 1.4
08-03 19:50:29.209  5955  6049 D OpenGLRenderer: Enabling debug mode 0
,08-03 19:50:29.218  5955  5955 D Atlas   : Validating map...
08-03 19:50:29.221  1041  1998 D SplitWindow: check instance of lgWin Window{1a28a73f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 19:50:29.264  5955  6047 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:50:29.264  5955  6047 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:50:29.374  1041  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +619ms (total +692ms)
08-03 19:50:29.375  1041  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3677d3ac u0 com.test.thalitest/.MainActivity t40} time:133809
,08-03 19:50:29.384  5955  5955 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b15c1b6 time:133817
08-03 19:50:29.484  5955  5955 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-03 19:50:29.484  5955  5955 I chromium: 
,08-03 19:50:29.503  5955  5955 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 19:50:29.574  5955  6047 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-03 19:50:29.574  5955  6047 I chromium: 
,08-03 19:50:29.597  1041  2027 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:50:29.642  1041  1888 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6078 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:50:29.686  5955  6095 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435120640
,08-03 19:50:29.697  5955  6095 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 19:50:29.697  5955  6095 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 19:50:29.697  5955  6095 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 19:50:29.697  5955  6095 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 19:50:29.697  5955  6095 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-03 19:50:29.697  5955  6095 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46af89a added. We now have 1 listener(s)
08-03 19:50:29.701  1041  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:29.703  5955  6095 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-03 19:50:29.706  5955  6095 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-03 19:50:29.707  5955  6095 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:50:29.707  5955  6095 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 19:50:29.713  5955  6095 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@386904c1 added. We now have 1 listener(s)
08-03 19:50:29.713  5955  6095 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:50:29.717  1041  1529 D WifiService: New client listening to asynchronous messages
08-03 19:50:29.717  6078  6078 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-03 19:50:29.717  6078  6078 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-03 19:50:29.720  5955  6095 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:50:29.720  5955  6095 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 19:50:29.720  5955  6095 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 19:50:29.720  5955  6095 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 19:50:29.721  5955  6095 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 19:50:29.763  1041  1888 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6101 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 19:50:29.764  1041  1888 I ActivityManager: Killing 5366:com.google.android.gm/u0a64 (adj 15): empty #17
,08-03 19:50:29.800  1041  1560 I art     : Explicit concurrent mark sweep GC freed 26727(1330KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 4.132ms total 128.236ms
,08-03 19:50:29.837  5955  6095 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:50:29.837  1041  1907 W libprocessgroup: failed to open /acct/uid_10064/pid_5366/cgroup.procs: No such file or directory
,08-03 19:50:29.839  1041  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:29.840  5955  6095 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-03 19:50:29.848  5955  6095 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:29.849  5955  6095 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:29.849  5955  6095 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 19:50:29.849  5955  6095 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:50:29.851  5955  6095 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 19:50:29.852  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:29.901  5955  5955 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 19:50:29.910  6101  6101 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-03 19:50:29.930  1041  1925 I ActivityManager: Killing 5411:com.google.android.talk/u0a72 (adj 15): empty #17
,08-03 19:50:29.932  6101  6101 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 19:50:30.029  1041  1058 W libprocessgroup: failed to open /acct/uid_10072/pid_5411/cgroup.procs: No such file or directory
,08-03 19:50:30.323   341   362 E GBMv2   : DFP En is all cleared set to be enabled
08-03 19:50:30.324   341   362 E GBMv2   : Set value is all cleared set the max
08-03 19:50:30.324   341   362 I GBMv2   : DFP Enabled. Ignore VFP set
,08-03 19:50:30.543  2115  2115 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-03 19:50:30.544  2115  2115 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-03 19:50:31.001  5955  6118 W jxcore-log: Initializing JXcore engine
08-03 19:50:31.001  5955  6118 W jxcore-log: JXcore engine is ready
,08-03 19:50:31.055  6118  6118 W Thread-671: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[7528]" dev="sockfs" ino=7528 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-03 19:50:31.065  6118  6118 W Thread-671: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-03 19:50:31.065  6118  6118 W Thread-671: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7648]" dev="sockfs" ino=7648 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-03 19:50:31.065  6118  6118 W Thread-671: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-03 19:50:31.065  6118  6118 W Thread-671: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[24264]" dev="sockfs" ino=24264 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-03 19:50:31.084  5955  6118 W jxcore-log: Starting JXcore engine
,08-03 19:50:31.175  5955  6118 W jxcore-log: Platform android
08-03 19:50:31.175  5955  6118 W jxcore-log: 
08-03 19:50:31.175  5955  6118 W jxcore-log: Process ARCH arm
08-03 19:50:31.175  5955  6118 W jxcore-log: 
,08-03 19:50:31.403  5955  6118 I jxcore-log: JXcore Cordova bridge is ready!
08-03 19:50:31.403  5955  6118 I jxcore-log: 
08-03 19:50:31.403  5955  6118 W jxcore-log: JXcore engine is started
,08-03 19:50:31.419  5955  6095 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 19:50:31.422  5955  5955 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-03 19:50:32.775  5900  5900 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-03 19:50:32.779  1041  1889 I ActivityManager: Killing 5189:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 19:50:32.790  5164  5164 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 19:50:32.790  5164  5164 W System.err: android.os.DeadObjectException
08-03 19:50:32.790  5164  5164 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:50:32.790  5164  5164 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 19:50:32.790  5164  5164 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 19:50:32.790  5164  5164 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 19:50:32.790  5164  5164 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:50:32.790  5164  5164 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:50:32.790  5164  5164 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:50:32.790  5164  5164 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:50:32.790  5164  5164 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:50:32.790  5164  5164 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:50:32.790  5164  5164 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:50:32.790  5164  5164 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:50:32.790  5164  5164 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:50:32.790  5164  5164 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:50:32.791  5164  5164 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 19:50:32.791  5164  5164 W System.err: android.os.DeadObjectException
08-03 19:50:32.791  5164  5164 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:50:32.791  5164  5164 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 19:50:32.791  5164  5164 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 19:50:32.791  5164  5164 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 19:50:32.791  5164  5164 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:50:32.791  5164  5164 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:50:32.791  5164  5164 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:50:32.791  5164  5164 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:50:32.791  5164  5164 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:50:32.791  5164  5164 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:50:32.791  5164  5164 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:50:32.791  5164  5164 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:50:32.791  5164  5164 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:50:32.791  5164  5164 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:50:32.791  5164  5164 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 19:50:32.791  5164  5164 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-03 19:50:33.009  1041  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_5189/cgroup.procs: No such file or directory
,08-03 19:50:33.014  1041  1925 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-03 19:50:33.024  5164  5164 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 19:50:33.025  5164  5164 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-03 19:50:33.089  1041  1059 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6137 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:50:33.090  5164  5164 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-03 19:50:33.142  6137  6137 D UEI.SmartControl: Quickset Services start...
,08-03 19:50:33.144  6137  6137 I UEI.SmartControl: Manufacture = LGE
08-03 19:50:33.144  6137  6137 D UEI.SmartControl: Id = LGNevo
,08-03 19:50:33.146  6137  6137 D UEI.SmartControl: File observer start...
08-03 19:50:33.147  6137  6137 E UEI.SmartControl: IR Port is disabled: false
08-03 19:50:33.147  6137  6137 D UEI.SmartControl: Starting file observer...
08-03 19:50:33.147  6137  6137 D UEI.SmartControl: Extracting JNI libs...
08-03 19:50:33.147  6137  6137 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 19:50:33.231  6137  6137 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 19:50:33.231  6137  6137 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 19:50:33.231  6137  6137 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-03 19:50:33.258  6137  6137 I UEI.SmartControl: --- Selecting new region: 6
08-03 19:50:33.260  6137  6137 I UEI.SmartControl: Model = LG-D855
08-03 19:50:33.261  6137  6137 D UEI.SmartControl: QS Service created
,08-03 19:50:33.271  6137  6137 I UEI.SmartControl: Service initServices...
,08-03 19:50:33.275  6137  6137 D UEI.SmartControl: QS start get config
08-03 19:50:33.356  6137  6137 D UEI.SmartControl: Loading JNI Libs...
,08-03 19:50:33.605  6137  6137 I UEI.SmartControl: Supports setup maps: true
,08-03 19:50:33.608  6137  6137 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 19:50:33.609  6137  6137 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 19:50:33.609  6137  6137 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 19:50:33.609  6137  6137 I UEI.SmartControl: ### init IR Blaster...
08-03 19:50:33.615  6137  6137 D serial_port: Configuring serial port
08-03 19:50:33.619  6137  6137 E UEI.SmartControl: UEIBLaster setting for 616
08-03 19:50:33.619  6137  6137 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 19:50:33.620  6137  6137 I UEI.SmartControl: configuring settings for MAXQ616
08-03 19:50:33.620  6137  6137 I UEI.SmartControl: Get version...
,08-03 19:50:33.636  6137  6169 D UEI.SmartControl: serial port data available: 21
,08-03 19:50:33.662  6137  6137 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 19:50:33.662  6137  6137 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 19:50:33.662  6137  6137 I UEI.SmartControl: QS saving settings...
08-03 19:50:33.663  6137  6137 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 19:50:33.676  6137  6169 D UEI.SmartControl: serial port data available: 4
,08-03 19:50:33.712  6137  6172 I UEI.SmartControl: Device manager: loading config....
,08-03 19:50:33.714  6137  6172 D UEI.SmartControl: ----------- loading internal config...
08-03 19:50:33.717  6137  6137 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 19:50:33.724  6137  6137 E UEI.SmartControl: Services init done
08-03 19:50:33.724  6137  6137 D UEI.SmartControl: QS Service init finished
08-03 19:50:33.728  6137  6137 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 19:50:33.728  6137  6137 D UEI.SmartControl: QS Service version code: 201091
08-03 19:50:33.730  6137  6137 D UEI.SmartControl: Service requested: Control
08-03 19:50:33.735  6137  6172 E UEI.SmartControl: Loading SETTINGS...
,08-03 19:50:33.739  6137  6137 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 19:50:33.742  6137  6172 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 19:50:33.747  1041  1888 I ActivityManager: Killing 5164:com.lge.qremote/u0a112 (adj 15): empty #17
,08-03 19:50:33.753  6137  6171 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 19:50:33.754  6137  6171 D UEI.SmartControl: -----service ready thread exits
08-03 19:50:33.920  6137  6137 D UEI.SmartControl: Internal service binding...
08-03 19:50:33.921  1041  1762 W libprocessgroup: failed to open /acct/uid_10112/pid_5164/cgroup.procs: No such file or directory
,08-03 19:50:33.949  5900  5954 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 19:50:34.573  1041  1961 I ActivityManager: Killing 5106:com.android.calendar/u0a13 (adj 15): empty #17
,08-03 19:50:34.678  1041  1679 W libprocessgroup: failed to open /acct/uid_10013/pid_5106/cgroup.procs: No such file or directory
,08-03 19:50:34.888  1802  5695 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-03 19:50:34.890   313  6180 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-03 19:50:34.891  1041  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:50:34.892  1802  5695 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-03 19:50:34.892  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
08-03 19:50:34.893  1802  1802 I ConfigFetchService: stopping self
08-03 19:50:34.898  2146  2146 I ConfigService: onDestroy
,08-03 19:50:38.711  6137  6173 D UEI.SmartControl: Internal timer expired: 1
08-03 19:50:38.711  6137  6173 D UEI.SmartControl: unbind internal service
,08-03 19:50:38.726  6137  6137 D UEI.SmartControl: Service.onUnbind: IControl
,08-03 19:50:38.736  6137  6137 D UEI.SmartControl: Service.onDestroy
08-03 19:50:38.736  6137  6137 D UEI.SmartControl: Lock is in USE false
08-03 19:50:38.736  6137  6137 D UEI.SmartControl: unbind internal service
08-03 19:50:38.737  6137  6137 D serial_port: close(fd = 25)
,08-03 19:50:38.807  6137  6137 I UEI.SmartControl: Serial port is closed.
,08-03 19:50:38.817  6137  6137 I UEI.SmartControl: Serial port is closed.
08-03 19:50:38.817  6137  6137 D UEI.SmartControl: Blaster closed
08-03 19:50:38.818  6137  6137 D UEI.SmartControl: Shut down QS...
08-03 19:50:38.818  6137  6137 D UEI.SmartControl: Stopping QS lib
08-03 19:50:38.818  6137  6137 D UEI.SmartControl: QS lib stop result = true
08-03 19:50:38.818  6137  6137 D UEI.SmartControl: Stopped QS lib
08-03 19:50:38.818  6137  6137 D UEI.SmartControl: Stopped file observer...
08-03 19:50:38.818  6137  6137 D UEI.SmartControl: QS shutdown complete
08-03 19:50:39.973  1041  1106 I ActivityManager: Waited long enough for: ServiceRecord{17cfdf2 u0 com.google.android.gms/.wearable.service.WearableService}
,08-03 19:50:47.853  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 19:50:47.853  5955  6118 I jxcore-log: 
,08-03 19:50:47.856  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 19:50:47.856  5955  6118 I jxcore-log: 
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:47.860  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:47.862  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:47.865  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 19:50:47.865  5955  6118 I jxcore-log: 
08-03 19:50:47.867  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 19:50:47.867  5955  6118 I jxcore-log: 
,08-03 19:50:48.202  5955  6118 D ExecuteNativeTests: Running unit tests
,08-03 19:50:48.290  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 19:50:48.290  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 added. We now have 2 listener(s)
,08-03 19:50:48.291  1041  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:50:48.293  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-03 19:50:48.293  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:50:48.293  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 19:50:48.293  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-03 19:50:48.293  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a added. We now have 2 listener(s)
,08-03 19:50:48.293  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:50:48.293  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:50:48.296  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-03 19:50:48.298  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:48.298  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-03 19:50:48.299  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:50:48.299  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.302  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:50:48.302  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:50:48.302  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:50:48.304  5955  6118 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-03 19:50:48.304  5955  6118 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 19:50:48.304  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:50:48.304  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:50:48.304  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:50:48.305  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.305  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:50:48.305  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.307  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.307  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.307  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:50:48.308  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:50:48.308  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 removed from the list
08-03 19:50:48.308  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.308  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a removed from the list
08-03 19:50:48.308  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.308  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.309  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.309  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.310  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.310  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.310  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:50:48.310  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.312  5955  6118 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 19:50:48.313  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.313  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.313  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.313  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-03 19:50:48.313  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.314  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.314  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list,
08-03 19:50:48.314  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.314  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.314  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.314  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.314  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:50:48.314  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.314  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:50:48.315  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.315  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.315  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.315  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 19:50:48.319  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 19:50:48.320  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 19:50:48.320  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 19:50:48.320  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 19:50:48.320  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 19:50:48.320  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.320  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.320  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.320  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.320  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.320  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.320  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.320  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.320  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.320  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.320  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.320  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.320  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.320  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.321  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.321  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.321  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.321  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.321  5955  6118 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 19:50:48.322  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:48.324  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:48.324  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:48.325  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:50:48.325  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.325  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:50:48.326  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:50:48.326  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:50:48.326  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.326  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:50:48.328  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:50:48.328  1041  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:48.332  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 19:50:48.335  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:50:48.337  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 19:50:48.337  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:50:48.337  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:50:48.338  5955  6118 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:50:48.339  5955  6118 I io.jxcore.node.ConnectionHelper: start: OK
08-03 19:50:48.341  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.341  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.341  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.341  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.341  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.341  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:50:48.341  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.341  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.341  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.341  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.341  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.341  5955  6118 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 19:50:48.342  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:48.344  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:48.345  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:48.345  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:50:48.345  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:50:48.345  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:50:48.345  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:50:48.345  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.345  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:50:48.346  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.348  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:50:48.348  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:50:48.349  5955  6118 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:50:48.349  5955  6118 I io.jxcore.node.ConnectionHelper: start: OK
08-03 19:50:48.351  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.351  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.351  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.351  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.351  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.351  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:50:48.351  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.351  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.351  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.351  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.351  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.351  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.351  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.352  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.352  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.354  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.354  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.354  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.354  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.355  5955  6118 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 19:50:48.357  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:48.358  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:48.359  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:48.359  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:50:48.360  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:50:48.360  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:50:48.360  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:50:48.360  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.360  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:50:48.361  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.363  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:50:48.363  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:50:48.364  5955  6118 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:50:48.364  5955  6118 I io.jxcore.node.ConnectionHelper: start: OK
08-03 19:50:48.364  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.364  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.364  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.364  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.364  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.364  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 19:50:48.365  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.365  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.365  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:50:48.365  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.365  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.365  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.365  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.365  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.365  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.365  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.365  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.365  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.366  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.366  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.366  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.366  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.366  5955  6118 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 19:50:48.366  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.366  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.366  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.367  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.367  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.367  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.367  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.367  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.367  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.367  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.367  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.367  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.367  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.367  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.368  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.368  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.368  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.368  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.368  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.368  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.369  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 19:50:48.369  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.369  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.369  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.369  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.369  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.369  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.369  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.369  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.369  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.369  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.369  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.369  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.369  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.369  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.370  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.370  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.371  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.371  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.371  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.371  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.371  5955  6118 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 19:50:48.372  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.372  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.372  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.372  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.372  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.372  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.372  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.372  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.372  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.372  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.372  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.372  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.372  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.372  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.373  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.373  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.373  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.373  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.373  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.373  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.373  5955  6118 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 19:50:48.373  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.374  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.374  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.374  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.374  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.374  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.374  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.374  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.374  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.374  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.374  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.374  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.374  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.374  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.375  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.375  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.375  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.375  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.376  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.376  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.376  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:50:48.377  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:50:48.377  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:50:48.377  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:50:48.378  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:50:48.378  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:50:48.378  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.378  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.378  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.378  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.378  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.378  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.378  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.378  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.378  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.378  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.378  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.378  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.378  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.378  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.379  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.379  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.380  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.380  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.380  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.380  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.380  5955  6118 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:50:48.380  5955  6118 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 19:50:48.380  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 19:50:48.383  5955  6118 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:50:48.383  5955  6118 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 19:50:48.383  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 19:50:48.384  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 19:50:48.384  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 19:50:48.384  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 19:50:48.384  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 19:50:48.384  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 19:50:48.384  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 19:50:48.384  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 19:50:48.385  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 19:50:48.385  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 19:50:48.385  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 19:50:48.385  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 19:50:48.385  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 19:50:48.385  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 19:50:48.385  5955  6118 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 19:50:48.385  5955  6118 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:50:48.385  5955  6118 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 19:50:48.385  5955  6118 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:50:48.385  5955  6118 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:50:48.385  5955  6118 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 19:50:48.385  5955  6118 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:50:48.385  5955  6118 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:50:48.385  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 19:50:48.387  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 19:50:48.388  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 19:50:48.388  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 19:50:48.390  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 19:50:48.390  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 19:50:48.390  5955  6118 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 19:50:48.390  5955  6118 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:50:48.390  5955  6118 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 19:50:48.391  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.391  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.391  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.391  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.391  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.391  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.391  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 19:50:48.393  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.393  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.393  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.393  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.393  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.393  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.393  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.393  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.393  5955  6209 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 735)
08-03 19:50:48.394  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.394  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.394  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.395  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.395  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.395  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.407  5955  6118 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 19:50:48.407  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.407  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.407  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.407  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.407  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.407  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.407  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.408  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.408  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.408  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.408  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.408  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.408  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.408  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.409  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.409  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.409  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.409  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.409  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.411  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.412  5955  6210 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 735
08-03 19:50:48.412  5955  6210 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 735)
08-03 19:50:48.412  5955  6210 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 735)
08-03 19:50:48.412  5955  6118 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 19:50:48.413  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.413  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.413  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.413  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.413  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.413  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.413  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.413  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.414  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.414  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.414  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.414  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.414  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.414  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.415  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.415  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.415  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.415  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.415  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.415  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.416  5955  6118 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 19:50:48.416  5955  6118 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 19:50:48.416  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:50:48.416  5955  6118 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 19:50:48.417  5955  6118 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 19:50:48.417  5955  6118 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 19:50:48.417  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:50:48.417  5955  6118 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 19:50:48.417  5955  6118 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 19:50:48.417  5955  6118 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 19:50:48.417  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:50:48.417  5955  6118 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 19:50:48.417  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.421  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.421  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.421  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.421  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.421  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.421  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.421  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.421  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.421  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.421  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.421  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.421  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.422  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.423  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.423  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.424  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.424  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.424  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.424  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.425  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.425  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.425  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.425  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.425  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.425  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.425  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.425  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.425  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.426  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.426  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.426  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.426  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.426  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.426  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.426  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.427  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.427  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.427  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.427  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.427  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.427  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.427  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.427  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.427  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.427  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.427  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.427  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.427  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.428  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.428  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.429  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.429  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.429  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.429  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.431  5955  6118 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 19:50:48.431  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.432  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 19:50:48.434  5955  6118 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 19:50:48.434  5955  6118 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 19:50:48.435  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 19:50:48.436  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 19:50:48.436  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 19:50:48.436  1041  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:48.437  5955  6212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:50:48.437  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.438  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 19:50:48.438  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 19:50:48.438  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 19:50:48.438  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.438  5955  6118 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 19:50:48.438  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 19:50:48.438  3774  3791 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-03 19:50:48.438  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.438  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.438  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:50:48.438  5955  6118 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 19:50:48.438  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 19:50:48.439  5955  6212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-03 19:50:48.439  5955  6212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 19:50:48.439  5955  6212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 19:50:48.440  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 19:50:48.440  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:50:48.440  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:50:48.440  5955  6118 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 19:50:48.440  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.440  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.441  5955  6118 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:50:48.442  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:50:48.442  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 19:50:48.442  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:50:48.442  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:50:48.442  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.442  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.442  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.442  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.442  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.442  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.442  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.442  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.442  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.442  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.443  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.443  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.443  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.443  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.443  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.443  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.443  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.443  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.443  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.444  5955  6118 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 19:50:48.445  5955  6118 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 19:50:48.445  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:50:48.445  5955  6118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:50:48.445  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.445  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.445  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.446  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.446  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.446  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.446  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
,08-03 19:50:48.446  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.446  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.446  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.446  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.446  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.446  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.446  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.451  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.451  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.451  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.451  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.453  1041  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:48.453  1041  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:48.454  1041  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:48.454  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.454  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.454  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.455  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.455  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.455  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.455  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.455  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.455  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.455  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.455  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.455  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.455  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.455  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.456  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.456  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.456  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.456  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.458  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:50:48.458  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:50:48.458  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:50:48.458  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:50:48.458  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.458  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.458  5955  6118 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d45a05 not in the list
08-03 19:50:48.458  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.458  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.458  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:50:48.458  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.458  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.458  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:50:48.458  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:50:48.466  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:50:48.466  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:50:48.466  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:50:48.466  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb60a5a not in the list
08-03 19:50:48.468  5955  6118 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 19:50:48.468  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:50:48.468  5955  6118 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 19:50:48.468  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:50:48.468  5955  6118 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 19:50:48.468  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:50:48.470  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 19:50:48.470  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 19:50:48.471  5955  6118 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 19:50:48.471  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 19:50:48.471  5955  6118 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 19:50:48.471  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 19:50:48.471  5955  6118 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 19:50:48.471  5955  6118 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 19:50:48.472  5955  6118 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 19:50:48.472  5955  6118 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 19:50:48.472  5955  6118 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 19:50:48.472  5955  6118 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 19:50:48.472  5955  6118 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 19:50:48.472  5955  6118 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 19:50:48.473  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:50:48.473  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18187a03 added. We now have 2 listener(s)
08-03 19:50:48.473  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:50:48.479  5955  6118 D BluetoothAdapter: enable(): BT is already enabled..!
,08-03 19:50:48.482  1041  1907 D WifiServiceImplEx: setWifiEnabled: true pid=5955, uid=10118, package= com.test.thalitest, App Lable : ThaliTest,
08-03 19:50:48.483  1041  1907 D WifiService: setWifiEnabled: true pid=5955, uid=10118
08-03 19:50:48.483  1041  1907 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 19:50:48.487  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:50:48.487  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18eb0d80 added. We now have 3 listener(s)
08-03 19:50:48.487  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:50:48.492  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:50:48.492  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b31efb9 added. We now have 4 listener(s)
,08-03 19:50:48.492  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:50:48.497  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:50:48.497  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d639ffe added. We now have 5 listener(s)
08-03 19:50:48.497  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:50:48.500  1041  2027 D WifiServiceImplEx: setWifiEnabled: false pid=5955, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:50:48.500  1041  2027 D WifiService: setWifiEnabled: false pid=5955, uid=10118
08-03 19:50:48.500  1041  2027 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 19:50:48.509  5955  6209 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-03 19:50:48.511  5955  6209 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 735)
08-03 19:50:48.521  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:50:48.522  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:50:48.522  1041  1041 D Ulp_jni : JNI:system_update. Event-4
,08-03 19:50:48.523  1041  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:48.524  1041  1889 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3560d67a mBinding = false
08-03 19:50:48.524  1041  1523 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:48.524  1041  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:48.525  1041  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:48.526  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:48.526  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 19:50:48.526  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:48.527  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:48.527  1041  1041 D RttService: SCAN_AVAILABLE : 1
08-03 19:50:48.527  1041  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d43b081
08-03 19:50:48.527  1041  1522 D LGWifiP2pService: P2pDisablingState
08-03 19:50:48.527  1041  1522 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:48.527  1041  1522 D LGWifiP2pService: p2p socket connection lost
08-03 19:50:48.527  1041  1522 D LGWifiP2pService: P2pDisabledState
08-03 19:50:48.527  1041  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:48.528  1041  1542 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:48.528  1041  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 19:50:48.529  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:50:48.529  1926  1926 D WfdsService: WifiP2pState is changed : false
08-03 19:50:48.530  1926  2288 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 19:50:48.530  1926  2288 D WfdsService: Set the WFDS Monitor: false
08-03 19:50:48.530  1926  2288 D WfdsMonitor: WFDS Monitor is stopped
08-03 19:50:48.530  1926  2843 D CtrlSupplicant: Received on exit socket, terminate
08-03 19:50:48.531  1926  2843 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 19:50:48.531  1926  2843 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 19:50:48.531  1926  2843 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 19:50:48.531  1926  2288 D WfdsService: STATE : WfdsDisabledState - enter
08-03 19:50:48.532  1926  2288 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 19:50:48.532  1926  2296 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 19:50:48.534   313   892 D CommandListener: Clearing all IP addresses on wlan0
,08-03 19:50:48.539  1041  1041 D WifiHS20: hidePasspointNotification off =false
08-03 19:50:48.540  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:48.540  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:48.540  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:50:48.541  1041  1119 D BluetoothManagerService: Message: 2
08-03 19:50:48.541  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:50:48.541  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:50:48.541  1041  1041 D Ulp_jni : JNI:system_update. Event-4
08-03 19:50:48.542  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 19:50:48.542  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:48.543  1041  1119 D BluetoothManagerService: Sending off request.
08-03 19:50:48.543  3774  3791 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 19:50:48.543  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:50:48.544  3774  3855 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 19:50:48.544  3774  3855 D BluetoothAdapterProperties: Setting state to 13
08-03 19:50:48.544  3774  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 19:50:48.544  3774  3855 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 19:50:48.545  3774  3855 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 19:50:48.545  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:50:48.545  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 19:50:48.545  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 19:50:48.547  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:50:48.548  1041  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 19:50:48.548  3774  3860 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:50:48.549  3774  3855 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 19:50:48.549  1041  1523 D WifiNative-p2p0: TERMINATE: returned true
08-03 19:50:48.549  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:50:48.549  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:50:48.549  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 19:50:48.549  3774  4153 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 19:50:48.549  3774  3855 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 19:50:48.550  3774  4155 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:50:48.550  3774  4217 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:50:48.550  3774  4218 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:50:48.551  3774  4220 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:50:48.551  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 19:50:48.551  3774  3958 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 19:50:48.553  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 19:50:48.553  3774  3958 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 19:50:48.554  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:50:48.556  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the, check when the Bluetooth is disabled - will return stored value
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:48.556  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:48.557  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:48.557  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:48.558  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:50:48.558  1041  1041 D WifiHS20: hidePasspointNotification off =false
08-03 19:50:48.558  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:48.559  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:48.559  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:48.560  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:48.561  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.564  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 19:50:48.564  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:48.568  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:48.568  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:48.568  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:50:48.569  3774  3774 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 19:50:48.569  3774  3774 D BluetoothMapService: STATE_TURNING_OFF
08-03 19:50:48.570  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:48.570  3774  3774 V BtOppService: Receiver DISABLED_ACTION 
08-03 19:50:48.570  3774  3774 V BluetoothMapService: Handler(): got msg=4
08-03 19:50:48.570  3774  3774 D BluetoothMapService: MAP Service closeService in
08-03 19:50:48.570  3774  3774 D BluetoothMapMasInstance: MAP Service shutdown
08-03 19:50:48.573  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 19:50:48.573  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:48.574  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.574  3774  3774 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:50:48.575  3774  3774 V BluetoothMapService: MAP Service closeService out
08-03 19:50:48.575  3774  3774 I BtOppRfcommListener: stopping Accept Thread
08-03 19:50:48.575  3774  3774 V BtOppRfcommListener: close mBtServerSocket
08-03 19:50:48.575  3774  3774 V BtOppRfcommListener: waiting for thread to terminate
08-03 19:50:48.575  3774  4217 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 19:50:48.576  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.576  3774  3774 V BtOppRfcommListener: done waiting for thread to terminate
08-03 19:50:48.577  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.578  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.579  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.596  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:50:48.600  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:50:48.617  1041  1106 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6216 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 19:50:48.617  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 19:50:48.618  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:48.618  1041  1041 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-03 19:50:48.619  3774  3774 V BtOppService: onDestroy
08-03 19:50:48.659  2666  2666 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 19:50:48.659  2666  2666 I wpa_supplicant: monitor socket send errors count : 1
08-03 19:50:48.659  2666  2666 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-2\x00 that cannot receive messages
08-03 19:50:48.661  1041  2838 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 19:50:48.661  1041  2838 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-03 19:50:48.668  1041  1763 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6238 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 19:50:48.669  3774  3774 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 19:50:48.675  1041  1363 V AlarmManager: RTC_WAKEUP set : Alarm{22ca0207 type 0 when 1470246642156 com.android.vending} when 1470246642156
,08-03 19:50:48.692  6216  6216 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:50:48.692  6216  6216 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-03 19:50:48.692  6216  6216 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:50:48.693  6216  6216 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-03 19:50:48.694  6216  6216 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:50:48.695  6216  6216 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 19:50:48.698  2666  2666 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:50:48.699  1041  2838 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 19:50:48.699  1041  2838 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:50:48.699  1041  2838 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:50:48.699  1041  2838 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 19:50:48.699  2666  2666 W wpa_supplicant: USIM:  scard_deinit function
08-03 19:50:48.700  1041  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153122
08-03 19:50:48.700  1041  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153122
08-03 19:50:48.702  1041  2838 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:50:48.702  1041  2838 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:50:48.702  1041  1119 D Tethering: InitialState.processMessage what=4
08-03 19:50:48.703  1041  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 19:50:48.703  1041  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=153124  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 19:50:48.703  1041  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=153125  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 19:50:48.704  1041  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:48.704  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:48.705   313  6256 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 19:50:48.706  1041  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-03 19:50:48.746  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-03 19:50:48.753  6238  6238 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:50:48.753  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:48.760  1041  1762 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:50:48.804  6216  6216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 19:50:48.807  3774  3774 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:50:48.807  3774  3774 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:48.807  3774  3774 V BluetoothPbapReceiver: ***********state = 13
08-03 19:50:48.808  3774  3774 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-03 19:50:48.810  3774  3774 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:48.810  3774  3774 V BluetoothPbapService: state: 13
08-03 19:50:48.810  3774  3774 V BluetoothPbapService: Pbap Service closeService in
08-03 19:50:48.814  3774  3774 V BluetoothPbapService: successfully stopped pbap service
08-03 19:50:48.814  3774  3774 V BluetoothPbapService: Pbap Service closeService out
08-03 19:50:48.814  3774  3774 V BluetoothPbapService: Pbap Service onDestroy
08-03 19:50:48.814  3774  3774 V BluetoothPbapService: Pbap Service closeService in
08-03 19:50:48.814  3774  3774 V BluetoothPbapService: Pbap Service closeService out
08-03 19:50:48.814  3774  3774 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 19:50:48.814  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:50:48.815  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:48.840  1041  1943 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6261 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 19:50:48.843  2666  2666 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-03 19:50:48.846  1041  2838 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 19:50:48.846  1041  2838 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 19:50:48.846  1041  2838 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 19:50:48.847  1041  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
08-03 19:50:48.854  6216  6216 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:50:48.854  6216  6216 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:50:48.880  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:48.888  1041  1119 D BluetoothManagerService: Message: 20
08-03 19:50:48.888  1041  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16bfbad2:true
08-03 19:50:48.900  1041  1119 D BluetoothManagerService: Message: 30
,08-03 19:50:48.903  1041  1119 D BluetoothManagerService: Message: 30
08-03 19:50:48.906  6216  6216 D LocalBluetoothProfileManager: Adding local MAP profile
08-03 19:50:48.907  6216  6216 D BluetoothMap: Create BluetoothMap proxy object
08-03 19:50:48.908  1041  1119 D BluetoothManagerService: Message: 30
08-03 19:50:48.911  1041  1119 D BluetoothManagerService: Message: 30
08-03 19:50:48.912  6216  6216 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-03 19:50:48.914  6216  6216 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-03 19:50:48.917  6261  6261 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 19:50:48.918  6261  6261 W LG Account v2.2: No ProfileInfo entries
08-03 19:50:48.918  6261  6261 I LG Account v2.2: isEnabled: false
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Country: EU
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Operator: OPEN
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Ranking support: false
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Comfort support: false
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Accessory: true
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Health device: true
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Extra Pedometer: false
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Blood glucose device: false
08-03 19:50:48.918  6261  6261 I Feature : [Lifetracker]Device Number: 3
08-03 19:50:48.920  1041  1961 I ActivityManager: Killing 4824:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-03 19:50:48.942  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 19:50:48.969  5837  5837 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-03 19:50:48.978  1041  1679 W libprocessgroup: failed to open /acct/uid_10014/pid_4824/cgroup.procs: No such file or directory
08-03 19:50:48.980  1041  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 19:50:48.980  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:50:48.980  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:50:48.980  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:50:48.981  6216  6216 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-03 19:50:48.982  1926  1926 D WfdsService: Supplicant Connection state is changed : false
08-03 19:50:48.982  1926  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 19:50:48.982  1926  2288 D WfdsService: Set the WFDS Monitor: false
08-03 19:50:48.982  1926  2288 D WfdsMonitor: WFDS Monitor is stopped
08-03 19:50:48.983  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:50:48.983  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:48.985  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 19:50:48.985  1041  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 19:50:48.985  1041  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 19:50:48.985  6216  6216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-03 19:50:48.986  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.988  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:48.990  2492  2492 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:48.991  1041  2027 I ActivityManager: Killing 2115:com.lge.music/u0a34 (adj 15): empty #17
,08-03 19:50:49.009   317  1370 V AudioFlinger: 2115 died, releasing its sessions
08-03 19:50:49.009   317  1370 V AudioFlinger:  pid 1837 @ 0
08-03 19:50:49.009   317  1370 V AudioFlinger:  pid 3339 @ 1
08-03 19:50:49.009   317  1370 V AudioFlinger:  pid 3339 @ 2
,08-03 19:50:49.020  6216  6216 D DockEventReceiver: finishStartingService: stopping service
08-03 19:50:49.021  1041  1059 W libprocessgroup: failed to open /acct/uid_10034/pid_2115/cgroup.procs: No such file or directory
,08-03 19:50:49.028  6216  6216 D BluetoothInputDevice: Proxy object connected
08-03 19:50:49.029  6216  6216 D HidProfile: Bluetooth service connected
08-03 19:50:49.030  6216  6216 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 19:50:49.030  6216  6216 D PanProfile: Bluetooth service connected
08-03 19:50:49.031  6216  6216 D BluetoothMap: Proxy object connected
08-03 19:50:49.031  6216  6216 D MapProfile: Bluetooth service connected
08-03 19:50:49.031  6216  6216 D BluetoothMap: getConnectedDevices()
08-03 19:50:49.032  6216  6216 D BluetoothMap: Bluetooth is Not enabled
08-03 19:50:49.034  6216  6216 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 19:50:49.035  6216  6216 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 19:50:49.048  6216  6216 D BluetoothPermissionRequest: onReceive
,08-03 19:50:49.050  6216  6216 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-03 19:50:49.056  1041  1961 I ActivityManager: Killing 5700:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-03 19:50:49.061  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-03 19:50:49.086  3774  3774 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-03 19:50:49.086  3774  3774 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-03 19:50:49.087  3774  3774 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-03 19:50:49.148  1041  1961 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6289 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-03 19:50:49.153  1041  1762 W libprocessgroup: failed to open /acct/uid_10008/pid_5700/cgroup.procs: No such file or directory
08-03 19:50:49.158  3774  3774 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:49.158  3774  3774 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 19:50:49.162  3774  3774 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:50:49.162  3774  3774 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:49.162  3774  3774 V BluetoothFtpService: Ftp Service closeService
,08-03 19:50:49.162  3774  3774 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-03 19:50:49.164  3774  3774 V BluetoothFtpService: successfully stopped ftp service
08-03 19:50:49.165  3774  3774 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:50:49.165  3774  3774 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:50:49.165  3774  3774 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:50:49.165  3774  3774 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:49.165  3774  3774 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 19:50:49.165  3774  3774 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:50:49.167  3774  3774 V BluetoothFtpService: Ftp Service onDestroy
08-03 19:50:49.167  3774  3774 V BluetoothFtpService: Ftp Service closeService
08-03 19:50:49.220  1041  1907 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6306 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:50:49.229  3774  3774 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:49.229  3774  3774 V BluetoothSapService: state: 13
08-03 19:50:49.229  3774  3774 V BluetoothSapService: Stopping SAP server process
08-03 19:50:49.231  3774  3774 V BluetoothSapService: Sap Service closeSapService in
08-03 19:50:49.231  3774  3774 V BluetoothSapService: Close listen Socket : 
08-03 19:50:49.231  3774  3774 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:50:49.231  3774  3774 V BluetoothSapService: Close sapd  Socket : 
08-03 19:50:49.232  3774  3774 V BluetoothSapService: Sap Service closeSapService out
08-03 19:50:49.233  3774  3774 V BluetoothSapService: Sap Service onDestroy
08-03 19:50:49.233  3774  3774 V BluetoothSapService: Sap Service closeSapService in
08-03 19:50:49.233  3774  3774 V BluetoothSapService: Close listen Socket : 
08-03 19:50:49.233  3774  3774 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:50:49.233  3774  3774 V BluetoothSapService: Close sapd  Socket : 
08-03 19:50:49.234  3774  3774 V BluetoothSapService: Sap Service closeSapService out
,08-03 19:50:49.258  6289  6289 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 19:50:49.275  6306  6306 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 19:50:49.283  6289  6289 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-03 19:50:49.288  1041  1889 I ActivityManager: Killing 5731:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-03 19:50:49.312  6289  6289 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-03 19:50:49.312  6289  6289 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-03 19:50:49.312  6289  6289 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 19:50:49.313  6289  6289 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 19:50:49.313  6289  6289 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 19:50:49.315  6289  6289 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-03 19:50:49.319  6289  6289 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 19:50:49.409  1041  1943 W libprocessgroup: failed to open /acct/uid_10011/pid_5731/cgroup.procs: No such file or directory
,08-03 19:50:49.426  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:50:49.431  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:49.459  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 19:50:49.465  6289  6289 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-03 19:50:49.469  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:49.472  6289  6289 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-03 19:50:49.476  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-03 19:50:49.476  6238  6238 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:50:49.476  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:49.480  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:49.488  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:49.497  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:49.498  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:49.500  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 19:50:49.556  3774  3958 W bt-btif : ag scb idx 1 not allocated
08-03 19:50:49.556  3774  3860 D bt_hci_bdroid: cleanup
08-03 19:50:49.556  3774  3958 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 19:50:49.556  3774  3963 I bt_lpm  : LPM is already off!!!
08-03 19:50:49.556  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:50:49.556  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:50:49.556  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:50:49.556  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:50:49.557  3774  3958 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:50:49.557  3774  3958 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-03 19:50:49.559  3774  4122 I bt_userial_mct: exiting userial_read_thread
,08-03 19:50:49.559  3774  4122 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 19:50:49.562  3774  3860 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 19:50:49.562  3774  3963 I bt_vendor: hw_epilog_process
08-03 19:50:49.563  3774  3860 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 19:50:49.563  3774  3860 D bt_userial_mct: userial_close
08-03 19:50:49.563  3774  3860 E bt_userial_mct: pthread_join() FAILED result:3
08-03 19:50:49.563  3774  3860 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 19:50:49.569  1041  1059 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6329 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 19:50:49.670  3774  3860 D bt_hci_bdroid: set_power 0
08-03 19:50:49.670  3774  3860 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 19:50:49.670  3774  3860 I bt_vendor: bluetooth satus is on
08-03 19:50:49.670  3774  3860 I bt_vendor: bt-vendor : resetting BT status
08-03 19:50:49.670  3774  3860 I bt_vendor: Starting hciattach daemon
08-03 19:50:49.670  3774  3860 I bt_vendor: try to set false
,08-03 19:50:49.672  3774  3860 I bt_vendor: Starting hciattach daemon
08-03 19:50:49.672  3774  3860 I bt_vendor: try to set false
08-03 19:50:49.674  3774  3860 I bt_vendor: cleanup
08-03 19:50:49.676  3774  3958 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 19:50:49.676  3774  3860 I GKI_LINUX: GKI_exit_task 0 done
08-03 19:50:49.677  3774  3860 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 19:50:49.680  3774  3855 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 19:50:49.687  3774  3774 D HeadsetService: Received stop request...Stopping profile...
,08-03 19:50:49.691  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:49.694  3774  3774 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:50:49.694  3774  3774 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:50:49.694  3774  3774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cf7ef48
08-03 19:50:49.694  3774  3890 D HeadsetStateMachine: Exit Disconnected: -1
08-03 19:50:49.696  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-03 19:50:49.696  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-03 19:50:49.696  1041  1041 D BluetoothHeadset: Proxy object disconnected
08-03 19:50:49.697  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 19:50:49.697  3774  3774 D A2dpService: Received stop request...Stopping profile...
08-03 19:50:49.698  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-03 19:50:49.698  3774  3940 D A2dpStateMachine: Exit Disconnected: -1
08-03 19:50:49.699  3774  3774 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-03 19:50:49.707  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 19:50:49.709  3774  3774 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 19:50:49.709  3774  3774 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:50:49.709  3774  3774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cf7ef48
08-03 19:50:49.710  1041  1041 D BluetoothA2dp: Proxy object disconnected
08-03 19:50:49.710  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 19:50:49.710  3774  3855 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 19:50:49.711  3774  3774 D HeadsetStateMachine: Unbinding service...
,08-03 19:50:49.712  3774  3774 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:50:49.712  3774  3774 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:50:49.712  3774  3774 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:50:49.712  3774  3774 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:50:49.712  3774  3774 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 19:50:49.712  3774  3774 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:50:49.712  3774  3774 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:50:49.714  3774  3774 D HidService: Received stop request...Stopping profile...
08-03 19:50:49.714  3774  3774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cf7ef48
08-03 19:50:49.715  3774  3774 D HealthService: Received stop request...Stopping profile...
08-03 19:50:49.715  3774  3774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cf7ef48
08-03 19:50:49.716  3774  3774 D PanService: Received stop request...Stopping profile...
08-03 19:50:49.717  3774  3774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cf7ef48
08-03 19:50:49.718  3774  3774 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 19:50:49.718  3774  3774 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 19:50:49.718  3774  3774 D BtGatt.GattService: stop()
08-03 19:50:49.718  3774  3774 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 19:50:49.719  3774  3774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cf7ef48
08-03 19:50:49.720  3774  3774 I BluetoothA2dpServiceJni: cleanupNative
08-03 19:50:49.720  3774  3942 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 19:50:49.720  3774  3774 I GKI_LINUX: GKI_exit_task 2 done
08-03 19:50:49.720  3774  3774 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 19:50:49.721  3774  3774 D BluetoothMapService: Received stop request...Stopping profile...
08-03 19:50:49.721  3774  3774 D BluetoothMapService: stop()
08-03 19:50:49.721  3774  3774 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 19:50:49.721  3774  3774 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 19:50:49.722  3774  3774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cf7ef48
08-03 19:50:49.722  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:49.722  6216  6216 D BluetoothInputDevice: Proxy object disconnected
08-03 19:50:49.722  6216  6216 D HidProfile: Bluetooth service disconnected
08-03 19:50:49.723  6216  6216 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 19:50:49.723  6216  6216 D PanProfile: Bluetooth service disconnected
08-03 19:50:49.723  6216  6216 D BluetoothMap: Proxy object disconnected
08-03 19:50:49.723  6216  6216 D MapProfile: Bluetooth service disconnected
08-03 19:50:49.723  3774  3774 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 19:50:49.723  3774  3774 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 19:50:49.723  3774  3774 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 19:50:49.724  3774  3774 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:50:49.724  3774  3774 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:50:49.724  3774  3774 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 19:50:49.724  3774  3774 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-03 19:50:49.727  3774  3774 V BluetoothMapService: Handler(): got msg=4
08-03 19:50:49.727  3774  3774 D BluetoothMapService: MAP Service closeService in
08-03 19:50:49.727  3774  3774 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:50:49.727  3774  3774 V BluetoothMapService: MAP Service closeService out
08-03 19:50:49.728  3774  3855 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 19:50:49.728  3774  3855 D BluetoothAdapterProperties: Setting state to 10
08-03 19:50:49.728  3774  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 19:50:49.728  3774  3774 D BluetoothMapService: cleanup()
08-03 19:50:49.728  3774  3774 D BluetoothMapService: MAP Service closeService in
08-03 19:50:49.728  3774  3774 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:50:49.728  3774  3774 V BluetoothMapService: MAP Service closeService out
08-03 19:50:49.729  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:50:49.729  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 19:50:49.729  3774  3855 I BluetoothAdapterState: Entering OffState
08-03 19:50:49.729  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-03 19:50:49.730  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:50:49.731  1837  4354 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:50:49.731  6216  6237 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 19:50:49.732  6216  6236 D BluetoothPan: onBluetoothStateChange on: false
08-03 19:50:49.733  1041  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:50:49.734  1837  2423 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:50:49.735  6216  6237 D BluetoothMap: onBluetoothStateChange: up=false
08-03 19:50:49.737  1041  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 19:50:49.737  6216  6236 D BluetoothPbap: onBluetoothStateChange: up=false
,08-03 19:50:49.738  1041  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 19:50:49.738  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 19:50:49.741  1041  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 19:50:49.741  1041  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 19:50:49.742  1041  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3560d67a mBinding = false
08-03 19:50:49.742  6329  6349 W FormManager: Network not available. Please check & try again.
08-03 19:50:49.742  1041  1119 D BluetoothManagerService: Sending unbind request.
08-03 19:50:49.744  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 19:50:49.749  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:49.750  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:50:49.752  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:49.752  3774  3860 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 19:50:49.752  1926  2111 D LGBluetoothAPIService: Message: 2
08-03 19:50:49.753  1926  2111 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2842c775 mBinding = false
08-03 19:50:49.753  1926  2111 D LGBluetoothAPIService: Sending unbind request.
08-03 19:50:49.753  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-03 19:50:49.754  3774  3774 I GKI_LINUX: GKI_exit_task 1 done
08-03 19:50:49.754  3774  3774 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 19:50:49.755  3774  3774 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 19:50:49.755  3774  3774 I art     : --- WEIRD: removing null entry 246
08-03 19:50:49.755  3774  3774 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-03 19:50:49.755  3774  3774 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 19:50:49.757  6216  6216 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 19:50:49.757  6216  6216 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 19:50:49.757  6216  6216 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 19:50:49.759  1587  1587 D BluetoothAdapter: 723473891: getState() :  mService = null. Returning STATE_OFF
08-03 19:50:49.759  1587  1587 D BluetoothAdapter: 723473891: getState() :  mService = null. Returning STATE_OFF
08-03 19:50:49.760  6216  6216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 19:50:49.761  3774  3774 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 19:50:49.764  3774  3774 I art     : System.exit called, status: 0
08-03 19:50:49.764  3774  3774 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 19:50:49.775  6329  6350 V FormManager: Network unavailable.
,08-03 19:50:49.779  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:50:49.779  6329  6350 V FormManager: Network unavailable.
08-03 19:50:49.779  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:50:49.779  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:50:49.779  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:50:49.780  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:50:49.791   317   317 V AudioFlinger: 3774 died, releasing its sessions
,08-03 19:50:49.791   317   317 V AudioFlinger:  pid 1837 @ 0
08-03 19:50:49.791   317   317 V AudioFlinger:  pid 3339 @ 1
08-03 19:50:49.791   317   317 V AudioFlinger:  pid 3339 @ 2
08-03 19:50:49.794  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:50:49.794  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 19:50:49.795  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:50:49.795  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:50:49.795  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:50:49.795  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-03 19:50:49.816  1041  1925 I ActivityManager: Process com.android.bluetooth (pid 3774) has died
08-03 19:50:49.817  1041  1925 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-03 19:50:49.823  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:50:49.823  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:50:49.824  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:50:49.825  6216  6216 D DockEventReceiver: finishStartingService: stopping service
08-03 19:50:49.826  6216  6216 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-03 19:50:49.827  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:50:49.830  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:50:49.851  4264  6361 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:50:49.856  6238  6238 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 19:50:49.856  4264  6363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:50:49.856  6238  6238 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:50:49.856  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:49.856  6216  6216 D BluetoothPermissionRequest: onReceive
08-03 19:50:49.859  4264  6363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:50:49.861  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:50:49.867  6329  6365 W FormManager: Network not available. Please check & try again.
08-03 19:50:49.871  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:49.872  6329  6366 V FormManager: Network unavailable.
08-03 19:50:49.872  6216  6216 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 19:50:49.873  6216  6216 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 19:50:49.875  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:50:49.931  1041  1925 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6367 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 19:50:49.943  6329  6366 V FormManager: Network unavailable.
08-03 19:50:49.950  1041  1560 I ActivityManager: Killing 5625:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-03 19:50:49.999  1041  1943 W libprocessgroup: failed to open /acct/uid_10004/pid_5625/cgroup.procs: No such file or directory
,08-03 19:50:50.025  6289  6289 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-03 19:50:50.027  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 19:50:50.028  6289  6289 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-03 19:50:50.030  6367  6367 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-03 19:50:50.031  6367  6367 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:50:50.032  6367  6367 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 19:50:50.033  6367  6367 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 19:50:50.055  6367  6367 D BluetoothAdapterApp: Loading JNI Library
,08-03 19:50:50.075  6289  6289 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:50:50.075  6289  6289 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:50:50.085  6289  6289 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-03 19:50:50.086  6289  6289 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 19:50:50.086  6289  6289 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 19:50:50.086  6289  6289 V SoundPool: doLoad: loading sample sampleID=1
08-03 19:50:50.087  6289  6289 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 19:50:50.091  6289  6386 V SoundPool: Start decode
08-03 19:50:50.091  6289  6386 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-03 19:50:50.092  6367  6367 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@9f426a9 Instance Count = 1
08-03 19:50:50.093   317  1370 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 19:50:50.093   317  1370 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 19:50:50.093   317  1370 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 19:50:50.093   317  1370 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 19:50:50.093   317  1370 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 19:50:50.093   317  1370 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 19:50:50.093   317  1370 V MediaPlayerService: player type = 3
08-03 19:50:50.093   317  1370 V AwesomePlayer: AwesomePlayer create()
08-03 19:50:50.094   317  1370 V AwesomePlayer: reset_l() 
08-03 19:50:50.094   317  1370 V AwesomePlayer: cancelPlayerEvents
08-03 19:50:50.094   317  1370 V AwesomePlayer: setAudioSink() 
08-03 19:50:50.094   317  1370 V AwesomePlayer: reset_l() 
08-03 19:50:50.094   317  1370 V AudioCache: notify(0xb10102c0, 8, 0, 0)
08-03 19:50:50.095   317  1370 V AudioCache: ignored
08-03 19:50:50.095   317  1370 V AwesomePlayer: cancelPlayerEvents
08-03 19:50:50.095   317  1370 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 19:50:50.095   317  1370 V AwesomePlayer: setDataSource_l dataSource
08-03 19:50:50.095   317  1370 V LGParserOSAL: SniffLGParser start
08-03 19:50:50.095   317  1370 V LGParserOSAL: MainType:5, SubType=0
08-03 19:50:50.095   317  1370 V LGParserOSAL: #### check Mime : application/ogg
08-03 19:50:50.096   317  1370 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 19:50:50.096   317  1370 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 19:50:50.099  6367  6367 D BluetoothAdapterApp: onCreate
08-03 19:50:50.105  6137  6137 D UEI.SmartControl: QS Service created
,08-03 19:50:50.118  6289  6289 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 19:50:50.119  6289  6289 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:50:50.120  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-03 19:50:50.125  6137  6137 I UEI.SmartControl: Service initServices...
08-03 19:50:50.125  6137  6137 D UEI.SmartControl: QS start get config
08-03 19:50:50.127  6367  6367 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 19:50:50.128  6367  6367 D ProfileConfigQcom: Adding HeadsetService
08-03 19:50:50.128  6367  6367 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 19:50:50.128  6367  6367 D ProfileConfigQcom: Adding A2dpService
08-03 19:50:50.128  6367  6367 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 19:50:50.128  6367  6367 D ProfileConfigQcom: Adding HidService
08-03 19:50:50.129  6367  6367 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 19:50:50.129  6367  6367 D ProfileConfigQcom: Adding HealthService
08-03 19:50:50.129  6367  6367 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 19:50:50.130  6367  6367 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 19:50:50.130  6367  6367 D ProfileConfigQcom: Adding PanService
08-03 19:50:50.131  6367  6367 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 19:50:50.131  6367  6367 D ProfileConfigQcom: Adding GattService
08-03 19:50:50.131  6367  6367 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 19:50:50.131  6367  6367 D ProfileConfigQcom: Adding BluetoothMapService
08-03 19:50:50.132  6367  6367 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 19:50:50.134  6367  6367 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-03 19:50:50.134  6289  6289 V LGMDMManager: Create singleton instance
,08-03 19:50:50.140  6216  6216 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 19:50:50.143  6367  6367 V LGMDMManagerInternal: Create singleton instance
08-03 19:50:50.151   317  1370 V LGParserOSAL: supported mime: application/ogg
08-03 19:50:50.151   317  1370 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 19:50:50.151   317  1370 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 19:50:50.151   317  1370 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 19:50:50.151   317  1370 V AwesomePlayer: AudioTrack Setting
08-03 19:50:50.151   317  1370 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 19:50:50.151   317  1370 V AwesomePlayer: setAudioSource() 
08-03 19:50:50.151   317  1370 V MediaPlayerService: prepare
,08-03 19:50:50.151   317  1370 V AwesomePlayer: prepareAsync_l() 
08-03 19:50:50.151   317  1370 V MediaPlayerService: wait for prepare
08-03 19:50:50.151   317  6388 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 19:50:50.151   317  6388 V AwesomePlayer: initAudioDecoder() 
08-03 19:50:50.151   317  6388 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 19:50:50.151   317  6388 V AudioSystem: isOffloadSupported()
08-03 19:50:50.151   317  6388 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 19:50:50.151   317  6388 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 19:50:50.151   317  6388 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 19:50:50.151   317  6388 V AwesomePlayer: getUseOffload() = 0 
08-03 19:50:50.151   317  6388 V OMXCodec: OMXCodec::Create
08-03 19:50:50.151   317  6388 V OMXCodec: findMatchingCodecs()
08-03 19:50:50.151   317  6388 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 19:50:50.151   317  6388 V OMXCodec: matchingCodecs.size()=1
08-03 19:50:50.151   317  6388 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 19:50:50.153   317  6388 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 19:50:50.153   317  6388 V LGCodecAdapter: LG Codec Adapter start
08-03 19:50:50.153   317  6388 V OMXCodec: OMXCodec Createtor
08-03 19:50:50.153   317  6388 V OMXCodec: setComponentRole
08-03 19:50:50.153   317  6388 V OMXCodec: configureCodec protected=0
,08-03 19:50:50.153   317  6388 V LGCodecAdapter: called getLGCodecSpecificData
08-03 19:50:50.153   317  6388 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 19:50:50.154   317  6388 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 19:50:50.154   317  6388 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 19:50:50.154   317  6388 V LGCodecOSAL: Not support LGCodec
08-03 19:50:50.154   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 19:50:50.154   317  6388 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 19:50:50.154   317  6388 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 19:50:50.154   317  6388 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 19:50:50.154   317  6388 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 19:50:50.154   317  6388 V AudioSystem: isOffloadSupported()
08-03 19:50:50.154   317  6388 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 19:50:50.154   317  6388 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 19:50:50.154   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 19:50:50.154   317  6388 V OMXCodec: init()
08-03 19:50:50.154   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 19:50:50.154   317  6388 V OMXCodec: allocateBuffers
08-03 19:50:50.154   317  6388 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 19:50:50.154   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 19:50:50.154   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-03 19:50:50.154   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-03 19:50:50.154   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-03 19:50:50.155   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-03 19:50:50.155   317  6388 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 19:50:50.155   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 19:50:50.155   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-03 19:50:50.155   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 19:50:50.155   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-03 19:50:50.155   317  6388 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-03 19:50:50.155   317  6388 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 19:50:50.155   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 19:50:50.155   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 19:50:50.155   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 19:50:50.155   317  6388 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 19:50:50.155   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 19:50:50.155   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 19:50:50.155   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 19:50:50.155   317  6388 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 19:50:50.155   317  6388 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 19:50:50.155   317  6388 V AudioCache: notify(0xb10102c0, 5, 0, 0)
08-03 19:50:50.155   317  6388 V AudioCache: ignored
08-03 19:50,:50.155   317  6388 V AudioCache: notify(0xb10102c0, 1, 0, 0)
08-03 19:50:50.155   317  6388 V AudioCache: prepared
08-03 19:50:50.155   317  1370 V AudioCache: wait - success
08-03 19:50:50.155   317  1370 V MediaPlayerService: start
08-03 19:50:50.155   317  1370 V AwesomePlayer: play_l() 
08-03 19:50:50.156   317  1370 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 19:50:50.156   317  1370 V AwesomePlayer: createAudioPlayer_l
08-03 19:50:50.156   317  1370 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 19:50:50.156   317  1370 V AwesomePlayer: startAudioPlayer_l() 
08-03 19:50:50.156   317  1370 D AudioPlayer: start of Playback, useOffload 0
08-03 19:50:50.156   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 19:50:50.156   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-03 19:50:50.168   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 19:50:50.168   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 19:50:50.168   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 19:50:50.168   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 19:50:50.168   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 19:50:50.168   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 19:50:50.176   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-03 19:50:50.176   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:50:50.176   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-03 19:50:50.176   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 19:50:50.177   317  6390 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f920 on output port
,08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 19:50:50.177   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 19:50:50.178   317  1370 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 19:50:50.178   317  1370 V AudioCache: notify(0xb10102c0, 6, 0, 0)
08-03 19:50:50.178   317  1370 V AudioCache: ignored
08-03 19:50:50.179   317  1370 V MediaPlayerService: wait for playback complete
08-03 19:50:50.180   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.180   317  6391 V AudioCache: memcpy(0xac300000, 0xb16e7000, 4096)
08-03 19:50:50.185   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.185   317  6391 V AudioCache: memcpy(0xac301000, 0xb16e7000, 4096)
08-03 19:50:50.186   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.186   317  6391 V AudioCache: memcpy(0xac302000, 0xb16e7000, 4096)
08-03 19:50:50.188   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.188   317  6391 V AudioCache: memcpy(0xac303000, 0xb16e7000, 4096)
08-03 19:50:50.188   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.188   317  6391 V AudioCache: memcpy(0xac304000, 0xb16e7000, 4096)
08-03 19:50:50.189   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.189   317  6391 V AudioCache: memcpy(0xac305000, 0xb16e7000, 4096)
08-03 19:50:50.190   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.190   317  6391 V AudioCache: memcpy(0xac306000, 0xb16e7000, 4096)
08-03 19:50:50.190   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.190   317  6391 V AudioCache: memcpy(0xac307000, 0xb16e7000, 4096)
08-03 19:50:50.191   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.191   317  6391 V AudioCache: memcpy(0xac308000, 0xb16e7000, 4096)
08-03 19:50:50.192   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.192   317  6391 V AudioCache: memcpy(0xac309000, 0xb16e7000, 4096)
08-03 19:50:50.192   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.192   317  6391 V AudioCache: memcpy(0xac30a000, 0xb16e7000, 4096)
08-03 19:50:50.193   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.193   317  6391 V AudioCache: memcpy(0xac30b000, 0xb16e7000, 4096)
08-03 19:50:50.194   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.194   317  6391 V AudioCache: memcpy(0xac30c000, 0xb16e7000, 4096)
08-03 19:50:50.195   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.195   317  6391 V AudioCache: memcpy(0xac30d000, 0xb16e7000, 4096)
08-03 19:50:50.195   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.195   317  6391 V AudioCache: memcpy(0xac30e000, 0xb16e7000, 4096)
08-03 19:50:50.196   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.196   317  6391 V AudioCache: memcpy(0xac30f000, 0xb16e7000, 4096)
08-03 19:50:50.197   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.197   317  6391 V AudioCache: memcpy(0xac310000, 0xb16e7000, 4096)
08-03 19:50:50.197   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.197   317  6391 V AudioCache: memcpy(0xac311000, 0xb16e7000, 4096)
,08-03 19:50:50.198   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.198   317  6391 V AudioCache: memcpy(0xac312000, 0xb16e7000, 4096)
08-03 19:50:50.199   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.199   317  6391 V AudioCache: memcpy(0xac313000, 0xb16e7000, 4096)
08-03 19:50:50.199   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.199   317  6391 V AudioCache: memcpy(0xac314000, 0xb16e7000, 4096)
08-03 19:50:50.200   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.200   317  6391 V AudioCache: memcpy(0xac315000, 0xb16e7000, 4096)
08-03 19:50:50.201   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.201   317  6391 V AudioCache: memcpy(0xac316000, 0xb16e7000, 4096)
08-03 19:50:50.201   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.201   317  6391 V AudioCache: memcpy(0xac317000, 0xb16e7000, 4096)
08-03 19:50:50.202   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.202   317  6391 V AudioCache: memcpy(0xac318000, 0xb16e7000, 4096)
08-03 19:50:50.203   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.203   317  6391 V AudioCache: memcpy(0xac319000, 0xb16e7000, 4096)
08-03 19:50:50.203   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.203   317  6391 V AudioCache: memcpy(0xac31a000, 0xb16e7000, 4096)
08-03 19:50:50.204   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.204   317  6391 V AudioCache: memcpy(0xac31b000, 0xb16e7000, 4096)
08-03 19:50:50.205   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.205   317  6391 V AudioCache: memcpy(0xac31c000, 0xb16e7000, 4096)
08-03 19:50:50.205   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.205   317  6391 V AudioCache: memcpy(0xac31d000, 0xb16e7000, 4096)
08-03 19:50:50.206   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.206   317  6391 V AudioCache: memcpy(0xac31e000, 0xb16e7000, 4096)
08-03 19:50:50.207   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.207   317  6391 V AudioCache: memcpy(0xac31f000, 0xb16e7000, 4096)
08-03 19:50:50.208   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.208   317  6391 V AudioCache: memcpy(0xac320000, 0xb16e7000, 4096)
08-03 19:50:50.208   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.208   317  6391 V AudioCache: memcpy(0xac321000, 0xb16e7000, 4096)
08-03 19:50:50.209   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.209   317  6391 V AudioCache: memcpy(0xac322000, 0xb16e7000, 4096)
08-03 19:50:50.209   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.210   317  6391 V AudioCache: memcpy(0xac323000, 0xb16e7000, 4096)
08-03 19:50:50.210   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.210   317  6391 V AudioCache: memcpy(0xac324000, 0xb16e7000, 4096)
08-03 19:50:50.211   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.211   317  6391 V AudioCache: memcpy(0xac325000, 0xb16e7000, 4096)
08-03 19:50:50.211   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.212   317  6391 V AudioCache: memcpy(0xac326000, 0xb16e7000, 4096)
08-03 19:50:50.212   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.212   317  6391 V AudioCache: memcpy(0xac327000, 0xb16e7000, 4096)
08-03 19:50:50.213   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.213   317  6391 V AudioCache: memcpy(0xac328000, 0xb16e7000, 4096)
08-03 19:50:50.213   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.213   317  6391 V AudioCache: memcpy(0xac329000, 0xb16e7000, 4096)
08-03 19:50:50.214   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.214   317  6391 V AudioCache: memcpy(0xac32a000, 0xb16e7000, 4096)
08-03 19:50:50.215   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.215   317  6391 V AudioCache: memcpy(0xac32b000, 0xb16e7000, 4096)
08-03 19:50:50.215   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.215   317  6391 V AudioCache: mem,cpy(0xac32c000, 0xb16e7000, 4096)
08-03 19:50:50.216   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.216   317  6391 V AudioCache: memcpy(0xac32d000, 0xb16e7000, 4096)
08-03 19:50:50.217   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.217   317  6391 V AudioCache: memcpy(0xac32e000, 0xb16e7000, 4096)
08-03 19:50:50.218   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.218   317  6391 V AudioCache: memcpy(0xac32f000, 0xb16e7000, 4096)
08-03 19:50:50.218   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.218   317  6391 V AudioCache: memcpy(0xac330000, 0xb16e7000, 4096)
08-03 19:50:50.219   317  6391 V AudioCache: write(0xb16e7000, 4096)
08-03 19:50:50.219   317  6391 V AudioCache: memcpy(0xac331000, 0xb16e7000, 4096)
08-03 19:50:50.219   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 19:50:50.219   317  6391 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 19:50:50.219   317  6391 V AwesomePlayer: postAudioEOS() 
08-03 19:50:50.219   317  6391 V AudioCache: write(0xb16e7000, 280)
08-03 19:50:50.219   317  6391 V AudioCache: memcpy(0xac332000, 0xb16e7000, 280)
08-03 19:50:50.226   317  6388 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 19:50:50.226   317  6388 V AwesomePlayer: onStreamDone
08-03 19:50:50.226   317  6388 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 19:50:50.226   317  6388 V AudioCache: notify(0xb10102c0, 2, 0, 0)
08-03 19:50:50.226   317  6388 V AudioCache: playback complete
08-03 19:50:50.226   317  6388 V AwesomePlayer: pause_l() 
08-03 19:50:50.226   317  6388 V AudioCache: notify(0xb10102c0, 7, 0, 0)
08-03 19:50:50.226   317  6388 V AudioCache: ignored
08-03 19:50:50.226   317  6388 V AwesomePlayer: cancelPlayerEvents
08-03 19:50:50.226   317  1370 V AudioCache: wait - success
08-03 19:50:50.226   317  1370 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-03 19:50:50.226   317  6388 D AudioPlayer: Pause Playback at 1068125
08-03 19:50:50.227   317  1370 V AwesomePlayer: reset_l() 
08-03 19:50:50.227   317  1370 V AudioCache: notify(0xb10102c0, 8, 0, 0)
08-03 19:50:50.227   317  1370 V AudioCache: ignored
08-03 19:50:50.227   317  1370 V AwesomePlayer: cancelPlayerEvents
08-03 19:50:50.227   317  1370 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 19:50:50.227   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 19:50:50.227   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 19:50:50.227   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 19:50:50.227   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
,08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-03 19:50:50.227   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f920 on port 1
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 19:50:50.228   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 19:50:50.228   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
,08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 19:50:50.228   317  6390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 19:50:50.228   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 19:50:50.228   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 19:50:50.228   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 19:50:50.229   317  1370 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 19:50:50.229   317  1370 D AudioPlayer: AudioPlayer releasing audio source
08-03 19:50:50.229   317  1370 D AudioPlayer: AudioPlayer done releasing audio source
08-03 19:50:50.230   317  1370 V AwesomePlayer: reset_l() 
,08-03 19:50:50.230   317  1370 V AwesomePlayer: cancelPlayerEvents
08-03 19:50:50.230   317  1370 V AwesomePlayer: ~AwesomePlayer call
08-03 19:50:50.230   317  1370 V AwesomePlayer: reset_l() 
08-03 19:50:50.230   317  1370 V AwesomePlayer: cancelPlayerEvents
08-03 19:50:50.230  6289  6386 V SoundPool: close(31)
08-03 19:50:50.230  6289  6386 V SoundPool: pointer = 0xa0039000, size = 205080, sampleRate = 48000, numChannels = 2
08-03 19:50:50.235  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 19:50:50.237  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-03 19:50:50.239  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1323
,08-03 19:50:50.245  6367  6367 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:50.248  6367  6367 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:50:50.249  6367  6367 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:50:50.250  6367  6367 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:50:50.251  6367  6367 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:50.251  6367  6367 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-03 19:50:50.258  6306  6306 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-03 19:50:50.354  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-03 19:50:50.354  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-03 19:50:50.363  1587  1587 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
08-03 19:50:50.363  1587  1587 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-03 19:50:50.366  1041  1529 D WifiController: battery changed pluggedType: 2
,08-03 19:50:50.369  1926  2078 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-03 19:50:50.369  1587  1587 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-03 19:50:50.369  1926  2078 D LEDHandler: Battery Level Remaining: 100%
08-03 19:50:50.370  1926  2078 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
08-03 19:50:50.378  6101  6101 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-03 19:50:50.440  6137  6137 I UEI.SmartControl: Supports setup maps: true
,08-03 19:50:50.443  6137  6137 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 19:50:50.443  6137  6137 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 19:50:50.443  6137  6137 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-03 19:50:50.443  6137  6137 I UEI.SmartControl: ### init IR Blaster...
08-03 19:50:50.446  6137  6137 D serial_port: Configuring serial port
08-03 19:50:50.446  6137  6137 E UEI.SmartControl: UEIBLaster setting for 616
08-03 19:50:50.446  6137  6137 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 19:50:50.446  6137  6137 I UEI.SmartControl: configuring settings for MAXQ616
,08-03 19:50:50.446  6137  6137 I UEI.SmartControl: Get version...
08-03 19:50:50.465  6137  6393 D UEI.SmartControl: serial port data available: 21
,08-03 19:50:50.491  6137  6137 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-03 19:50:50.491  6137  6137 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 19:50:50.491  6137  6137 I UEI.SmartControl: QS saving settings...
08-03 19:50:50.493  6137  6137 D UEI.SmartControl: IR Blaster version: 25672567
08-03 19:50:50.509  6137  6393 D UEI.SmartControl: serial port data available: 4
,08-03 19:50:50.543  6137  6396 I UEI.SmartControl: Device manager: loading config....
,08-03 19:50:50.545  6137  6396 D UEI.SmartControl: ----------- loading internal config...
,08-03 19:50:50.545  6137  6137 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 19:50:50.549  6137  6137 E UEI.SmartControl: Services init done
08-03 19:50:50.549  6137  6137 D UEI.SmartControl: QS Service init finished
08-03 19:50:50.551  6137  6137 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 19:50:50.551  6137  6137 D UEI.SmartControl: QS Service version code: 201091
08-03 19:50:50.553  6137  6137 D UEI.SmartControl: Service requested: Control
08-03 19:50:50.558  6137  6137 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 19:50:50.560  6137  6396 E UEI.SmartControl: Loading SETTINGS...
,08-03 19:50:50.564  6137  6137 D UEI.SmartControl: Internal service binding...
08-03 19:50:50.564  6289  6289 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 19:50:50.567  6137  6153 I UEI.SmartControl: ------ IControl API: 11
08-03 19:50:50.567  6137  6153 D UEI.SmartControl: File observer start...
08-03 19:50:50.568  6137  6153 E UEI.SmartControl: IR Port is disabled: false
08-03 19:50:50.568  6137  6153 D UEI.SmartControl: Starting file observer...
08-03 19:50:50.569  6137  6153 I UEI.SmartControl: Registering callback...
08-03 19:50:50.570  6137  6152 I UEI.SmartControl: ------ IControl API: 19
08-03 19:50:50.572  6137  6152 I UEI.SmartControl: Registering Services Ready callback...
08-03 19:50:50.575  6137  6396 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-03 19:50:50.604  6137  6395 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 19:50:50.605  6289  6304 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-03 19:50:50.606  6137  6395 D UEI.SmartControl: -----service ready thread exits
08-03 19:50:50.607  6289  6384 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 19:50:50.607  6289  6384 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 19:50:50.609  6289  6289 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 19:50:50.610  6289  6289 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 19:50:50.610  6137  6153 I UEI.SmartControl: ------ IControl API: 8
08-03 19:50:50.615  6289  6289 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 19:50:50.616  6289  6289 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 19:50:50.617  6289  6289 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 19:50:50.618  6289  6289 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-03 19:50:50.620  6289  6289 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 19:50:50.621  6289  6289 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-03 19:50:50.627  6289  6289 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-03 19:50:50.633  6289  6289 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-03 19:50:50.635  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-03 19:50:50.637  6289  6289 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-03 19:50:50.638  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 19:50:50.640  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 19:50:50.643  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 19:50:50.645  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 19:50:50.648  6289  6289 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470246650647]
,08-03 19:50:50.656  6289  6289 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-03 19:50:50.661  1041  1763 I ActivityManager: Killing 5785:com.lge.email/u0a23 (adj 15): empty #17
,08-03 19:50:50.688  6289  6398 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-03 19:50:50.718  1041  1763 I ActivityManager: Killing 5748:com.android.contacts/u0a19 (adj 15): empty #18
,08-03 19:50:50.810  1041  1907 W libprocessgroup: failed to open /acct/uid_10023/pid_5785/cgroup.procs: No such file or directory
,08-03 19:50:50.818  1041  1961 W libprocessgroup: failed to open /acct/uid_10019/pid_5748/cgroup.procs: No such file or directory
08-03 19:50:50.829  6289  6289 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-03 19:50:50.832  6289  6289 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:50:50.834  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 19:50:50.835  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 19:50:50.836  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 19:50:50.837  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 19:50:50.838  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 19:50:50.861  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-03 19:50:51.562  1041  1889 D WifiServiceImplEx: setWifiEnabled: true pid=5955, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:50:51.564  1041  1889 D WifiService: setWifiEnabled: true pid=5955, uid=10118
08-03 19:50:51.564  1041  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:50:51.592  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:50:51.592  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:50:51.592  1041  1041 D Ulp_jni : JNI:system_update. Event-4
08-03 19:50:51.593  1041  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 19:50:51.594  1041  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-03 19:50:51.596  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 19:50:51.596  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 19:50:51.596  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 19:50:51.596  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 19:50:51.597  1041  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 19:50:51.597  1041  1523 E WifiHW  : unknown target_country: EU , set to default
08-03 19:50:51.597  1041  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 19:50:51.597  1041  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 19:50:51.597  1041  1523 I WifiUtil: gEnableBmps=1
08-03 19:50:52.195   313   892 D SoftapController: Softap fwReload - Ok
,08-03 19:50:52.207  1041  1523 E NetdConnector: NDC Command {36 softap fwreload wlan0 STA} took too long (606ms)
08-03 19:50:52.210   313   892 D CommandListener: Setting iface cfg
08-03 19:50:52.210   313   892 D CommandListener: Trying to bring down wlan0
,08-03 19:50:52.213  1041  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 19:50:52.213  1041  1119 D Tethering: InitialState.processMessage what=4
08-03 19:50:52.227   313  6416 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-03 19:50:52.232   313   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:50:52.234  1041  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:50:52.234  1041  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 19:50:52.237  1041  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-03 19:50:52.245  6417  6417 W wpa_supplicant: type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:52.255  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:50:52.255  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:50:52.255  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:50:52.258  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:52.255  6417  6417 W wpa_supplicant: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:52.267  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-03 19:50:52.293  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:50:52.296  1041  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 19:50:52.296  1041  1523 D WifiMonitor: connecting to supplicant
08-03 19:50:52.305  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:50:52.305  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:50:52.305  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:50:52.305  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:50:52.313  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-03 19:50:52.316  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:52.318  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:50:52.320  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-03 19:50:52.321  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 19:50:52.321  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:50:52.321  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:50:52.321  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:50:52.321  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 19:50:52.322  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-03 19:50:52.327  6417  6417 I wpa_supplicant: Successfully initialized wpa_supplicant
08-03 19:50:52.327  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:50:52.328  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:50:52.328  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:50:52.328  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:50:52.330  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-03 19:50:52.357  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-03 19:50:52.357  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 19:50:52.357  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:50:52.357  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:50:52.357  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:50:52.357  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:50:52.368  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:52.377  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:50:52.377  6417  6417 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 19:50:52.378  6417  6417 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-03 19:50:52.383  6329  6436 V FormManager: Network unavailable.
08-03 19:50:52.383  6329  6435 W FormManager: Network not available. Please check & try again.
08-03 19:50:52.385  6329  6436 V FormManager: Network unavailable.
08-03 19:50:52.387  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:52.460  6417  6417 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 19:50:52.546  6417  6417 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-03 19:50:52.560  6417  6417 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-03 19:50:52.560  6417  6417 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 19:50:52.563  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-03 19:50:52.564  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 19:50:52.565  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:50:52.566  1041  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:50:52.567  1041  6438 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-03 19:50:52.567  1041  6438 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 19:50:52.567  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 19:50:52.568  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-03 19:50:52.568  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:52.568  1041  6438 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:50:52.568  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:50:52.569  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:52.570  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:52.571  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:52.572  1041  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 19:50:52.572  1041  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 19:50:52.573  1041  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 19:50:52.573  1041  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 19:50:52.573  1041  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 19:50:52.575  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:50:52.575  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:50:52.575  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:50:52.575  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:52.575  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:52.575  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:52.576  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:52.576  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-03 19:50:52.580  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:52.582  1926  1926 D WfdService: Waiting for WifiP2p enabling
08-03 19:50:52.584  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:52.585  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:52.585  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:52.585  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:52.586  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 19:50:52.587  1041  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 19:50:52.587  1041  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 19:50:52.587  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:52.588  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:52.588  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:52.588  1041  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-03 19:50:52.588  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:52.588  1041  1523 D WifiConfigStore: Loading config and enabling all networks 
08-03 19:50:52.588  1041  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 19:50:52.589  1041  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-03 19:50:52.597  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:52.602  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:50:52.608  6329  6441 W FormManager: Network not available. Please check & try again.
08-03 19:50:52.608  1041  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-03 19:50:52.612  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:52.619  6329  6442 V FormManager: Network unavailable.
,08-03 19:50:52.622  6329  6442 V FormManager: Network unavailable.
08-03 19:50:52.627  1041  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 19:50:52.627  1041  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 19:50:52.628  1041  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-03 19:50:52.629  1041  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 19:50:52.629  1041  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 19:50:52.629  1041  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 19:50:52.629  1041  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 19:50:52.629  1041  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 19:50:52.630  1041  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 19:50:52.630  1041  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 19:50:52.630  1041  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 19:50:52.630  1041  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-03 19:50:52.630  1041  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 19:50:52.631  1041  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 19:50:52.631  1041  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 19:50:52.631  1041  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 19:50:52.631  1041  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 19:50:52.633  1926  1926 D WfdsService: Supplicant Connection state is changed : true
08-03 19:50:52.633  1926  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 19:50:52.633  1926  2288 D WfdsService: Set the WFDS Monitor: true
08-03 19:50:52.633  1926  2288 D WfdsMonitor: WfdsMonitorThread create
08-03 19:50:52.633  1926  2288 D WfdsMonitor: WFDS Monitor is created and started
08-03 19:50:52.633  1926  2288 D WfdsService: WiFi: Supplicant connection re-established
08-03 19:50:52.633  1041  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:50:52.633  1041  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 19:50:52.634  1041  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 19:50:52.634  1041  1523 D WifiNative-HAL: Setting external_sim to 1
08-03 19:50:52.634  1041  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 19:50:52.634  1926  6443 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 19:50:52.634  1041  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 19:50:52.634  1041  1523 I WifiNative-HAL: startHal
08-03 19:50:52.634  1041  1523 D wifi    : setting scan oui 0xaf725360
08-03 19:50:52.635  1041  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:50:52.635  1926  6443 E CtrlSupplicant: Succeed to open control connection
08-03 19:50:52.635  1041  1523 I WifiNative-HAL: startHal
08-03 19:50:52.635  1041  1523 D wifi    : setting scan oui 0xaf725360
08-03 19:50:52.635  1926  6443 E CtrlSupplicant: Succeed to open monitor connection
08-03 19:50:52.635  1041  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 19:50:52.635  1926  6443 D WfdsMonitor: Supplicant connection established
08-03 19:50:52.635  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:50:52.635  1041  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 19:50:52.635  1926  2288 D WfdsService: Connected to the supplicant for wfds
08-03 19:50:52.635  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 19:50:52.635  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 19:50:52.636  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:50:52.636  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 19:50:52.636  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:50:52.636  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 19:50:52.637  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:50:52.637  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 19:50:52.637  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 19:50:52.637  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 19:50:52.637  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-03 19:50:52.637  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:50:52.637  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:50:52.637  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-03 19:50:52.637  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:50:52.638  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 19:50:52.638  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:50:52.638  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 19:50:52.638  6417  6417 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 19:50:52.638  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 19:50:52.638  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 19:50:52.639  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:50:52.639  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 19:50:52.640  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:50:52.640  1041  1523 E WifiNative: : [157,061,147 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 19:50:52.640  1041  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 19:50:52.641  1041  1523 D WifiNative-wlan0: RECONNECT: returned true
08-03 19:50:52.641  1041  1523 D WifiNative-wlan0: doString: [STATUS]
08-03 19:50:52.641  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:50:52.641  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 19:50:52.641  1041  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:50:52.641  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:50:52.642  1041  1523 D WifiNative-wlan0: SET ps 1: returned true
,08-03 19:50:52.642  1041  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.644   313   892 D CommandListener: Setting iface cfg
08-03 19:50:52.644   313   892 D CommandListener: Trying to bring up p2p0
08-03 19:50:52.644  1041  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 19:50:52.644  1041  1522 D LGWifiP2pService: P2pEnablingState
08-03 19:50:52.644  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 19:50:52.644  1041  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.644  1041  1522 D LGWifiP2pService: P2p socket connection successful
08-03 19:50:52.644  1041  1522 D LGWifiP2pService: P2pEnabledState
,08-03 19:50:52.644  1041  1041 D RttService: SCAN_AVAILABLE : 3
08-03 19:50:52.644  1041  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.645  1041  1541 I WifiNative-HAL: startHal
08-03 19:50:52.645  1041  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 19:50:52.645  1041  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf725360
08-03 19:50:52.645  1041  1541 D wifi    : failed to get capabilities : -3
08-03 19:50:52.645  1041  1541 E WifiScanningService: could not get scan capabilities
08-03 19:50:52.645  1041  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:50:52.645  1041  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-03 19:50:52.647  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 19:50:52.647  1926  1926 D WfdsService: WifiP2pState is changed : true
08-03 19:50:52.647  1926  2288 D WfdsService: Receive the WFDS_ENABLE Method
08-03 19:50:52.647  1926  2288 D WfdsService: Set the WFDS Monitor: true
08-03 19:50:52.647  1926  2288 D WfdsService: Connected to the supplicant for wfds
08-03 19:50:52.647  1926  2288 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 19:50:52.647  6417  6417 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 19:50:52.647  1926  2288 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-03 19:50:52.647  6417  6417 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-03 19:50:52.648  1926  2288 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-03 19:50:52.648  1926  2288 D WfdsService: selectPreferredScanChannel [36]
08-03 19:50:52.648  1926  2288 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 19:50:52.648  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 19:50:52.649  1926  1926 D WfdsService: isConnected: false
08-03 19:50:52.650  4264  6444 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:50:52.651  1041  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 19:50:52.652  1041  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 19:50:52.653  1041  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-03 19:50:52.653  1041  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 19:50:52.653  1041  1522 D LGWifiP2pService: before postfix = G3
08-03 19:50:52.653  1041  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 19:50:52.653  1041  1522 D WifiServerServiceExt: postfix byte check : 2
08-03 19:50:52.653  1041  1522 D LGWifiP2pService: after postfix = G3
08-03 19:50:52.653  1041  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 19:50:52.653  1041  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 19:50:52.653  1041  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 19:50:52.653  1041  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 19:50:52.653  1041  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 19:50:52.654  1041  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 19:50:52.654  1041  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 19:50:52.654  1041  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 19:50:52.654  1041  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 19:50:52.654  1041  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 19:50:52.654  6101  6101 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 19:50:52.654  1041  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-03 19:50:52.654  6101  6101 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-03 19:50:52.654  1041  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 19:50:52.654  1041  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-03 19:50:52.655  1041  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 19:50:52.655  1041  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 19:50:52.655  1041  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 19:50:52.655  1041  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 19:50:52.655  6417  6417 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 19:50:52.655  1041  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 19:50:52.655  1041  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 19:50:52.656  1041  1523 ,E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 19:50:52.657  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 19:50:52.657  1041  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 19:50:52.657  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 19:50:52.657  1926  1926 D WfdsService: Update P2p Interface State: 3
08-03 19:50:52.657  1041  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 19:50:52.657  1041  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 19:50:52.657  6417  6417 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 19:50:52.658  1041  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 19:50:52.658  1041  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 19:50:52.658  1041  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 19:50:52.658  1041  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 19:50:52.658  1041  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 19:50:52.658  1041  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 19:50:52.658  1041  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 19:50:52.659  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-03 19:50:52.659  1041  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 19:50:52.659  1041  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-03 19:50:52.662  6101  6101 V [BNRBootReceiver]: Boot Receiver Return
08-03 19:50:52.663  4264  6445 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:50:52.663  4264  6445 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:50:52.667  1041  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 19:50:52.667  1041  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 19:50:52.668  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 19:50:52.668  6417  6417 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.668  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:50:52.668  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.668  1041  1522 D LGWifiP2pService: InactiveState
08-03 19:50:52.668  1041  6438 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.668  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.668  1041  1522 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.669  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.669  1041  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 19:50:52.669  6417  6417 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 19:50:52.669  6417  6417 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.669  1041  6438 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.669  1041  6438 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.669  1041  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 19:50:52.669  1041  6438 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.669  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.669  6417  6417 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.670  1041  6438 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.670  1041  6438 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.670  1041  6438 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.670  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.670  1041  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:50:52.670  1926  6443 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.670  1041  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,08-03 19:50:52.670  1926  6443 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.670  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 19:50:52.671  1041  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:50:52.671  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 19:50:52.671  6417  6417 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.671  1041  6438 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:50:52.671  1041  6438 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.671  1041  6438 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.671  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:50:52.671  1926  6443 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:50:52.671  6417  6417 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 19:50:52.672  6417  6417 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.672  1926  6443 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.672  1041  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 19:50:52.672  1041  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.672  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.672  6417  6417 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.672  1041  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.672  1041  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.672  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.672  1041  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.673  1041  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.673  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.673  1041  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.673  1041  6438 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.673  1041  6438 E WifiMonitor: WifiMonitor:p2p0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.673  1041  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.673  1041  6438 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.673  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.673  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.673  1041  6438 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.673  1041  6438 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.673  1041  6438 E WifiMonitor: handleEvent 14  C,TRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.673  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:50:52.673  1926  6443 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:50:52.673  1926  2288 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 19:50:52.674  1041  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.674  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 19:50:52.674  6417  6417 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:50:52.675  1041  1041 E WifiServerServiceExt: No p2p device connected
08-03 19:50:52.675  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 19:50:52.675  1041  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.675  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:50:52.675  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:52.675  1041  6438 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:50:52.675  1041  6438 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:50:52.675  1041  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 19:50:52.675  1041  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 19:50:52.676  1041  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 19:50:52.676  1041  1523 D WifiNative-wlan0: doBoolean: SCAN
08-03 19:50:52.676  1041  1523 D WifiNative-wlan0: SCAN: returned false
08-03 19:50:52.677  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=157098  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:50:52.677  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=157099  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:50:52.678  1041  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:50:52.678  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:52.678  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 19:50:52.678  1041  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:50:52.679  1041  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:50:52.679  1041  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-03 19:50:52.679  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:52.679  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:52.679  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:52.679  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 19:50:52.679  1041  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:50:52.682  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:52.682  1041  1041 D WifiServerServiceExt: setSupplicantStateSCANNING
08-03 19:50:52.682  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:50:52.687  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:52.695  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:52.700  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:52.700  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:50:52.701  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:50:53.209  6417  6417 E wpa_supplicant: USIM:  scard_init function
08-03 19:50:53.211  6417  6417 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-03 19:50:53.219  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 19:50:53.219  1041  6438 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 19:50:53.220  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-03 19:50:53.220  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: WPS-AP-AVAILABLE 
08-03 19:50:53.220  1041  6438 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 19:50:53.220  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:50:53.220  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-03 19:50:53.221  1041  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 19:50:53.222  1041  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 19:50:53.222  1041  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 19:50:53.222  1041  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 19:50:53.222  1041  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 19:50:53.241  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=157663  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 19:50:53.250  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:53.250  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:53.253  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:53.256  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.256  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.256  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-03 19:50:53.266  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.266  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.266  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 19:50:53.267  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=157688  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 19:50:53.268  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:53.268  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-03 19:50:53.274  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:53.274  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 19:50:53.280  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:53.284  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-03 19:50:53.293  6216  6216 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 19:50:53.301  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:50:53.313  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:53.320  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:53.329  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:53.329  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:50:53.335  6417  6417 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-03 19:50:53.340  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 19:50:53.340  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 19:50:53.340  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 19:50:53.340  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 19:50:53.340  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:50:53.340  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:50:53.344  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=157765  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 19:50:53.344  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=157766  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-03 19:50:53.349  6417  6417 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:50:53.349  6417  6417 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:50:53.352  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:50:53.353  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:50:53.353  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 19:50:53.353  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:50:53.353  1041  6438 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:50:53.353  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 19:50:53.353  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:50:53.353  1041  6438 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:50:53.354  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:50:53.354  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:50:53.355  1041  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-03 19:50:53.363  1041  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157767
08-03 19:50:53.363  1041  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157785
08-03 19:50:53.364  1041  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157786
08-03 19:50:53.365  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157786
08-03 19:50:53.365  1041  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157787
08-03 19:50:53.365  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=157787  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:50:53.370  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.370  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.370  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 19:50:53.372  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:53.372  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 19:50:53.377  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:53.393  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 19:50:53.396  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-03 19:50:53.396  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.396  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 19:50:53.399  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:53.399  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:53.399  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=157821  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:50:53.400  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:53.400  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:53.401  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:53.402  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 19:50:53.402  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=157823  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:50:53.404  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=157825  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:50:53.405  1041  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=157827
,08-03 19:50:53.407  1041  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=157828
08-03 19:50:53.408  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:50:53.408  1041  1523 D WifiNative-wlan0: doString: [STATUS]
08-03 19:50:53.409  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:50:53.409  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:50:53.410  1041  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:50:53.413  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:50:53.416  1041  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 19:50:53.421  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:53.421  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:53.422  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:50:53.425  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:50:53.425  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:50:53.425  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:50:53.425  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:50:53.426  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:50:53.426  1041  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 19:50:53.427  1041  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-03 19:50:53.429  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:50:53.429  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 19:50:53.429  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:50:53.429  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:50:53.429  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:50:53.429  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 19:50:53.429  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:53.429  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:50:53.429  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:53.431  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.431  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.432  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-03 19:50:53.432  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:53.434  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.435  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:53.435  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 19:50:53.437  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:53.444  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:53.451  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:53.451  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:53.451  1041  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 19:50:53.451  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:53.452  1041  1530 D ConnectivityService: Got NetworkAgent Messenger
08-03 19:50:53.452  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:53.452  1041  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 19:50:53.452  1041  1530 D ConnectivityService: NetworkAgent connected
08-03 19:50:53.453  1041  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:50:53.453  1041  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:50:53.454  1041  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:50:53.454  1041  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:50:53.457  1041  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-03 19:50:53.457  1041  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:50:53.457  1041  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:50:53.458  1041  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-03 19:50:53.458  1041  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:50:53.459  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:53.460  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:53.460  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:50:53.461  1041  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:50:53.464   313   892 D CommandListener: Setting iface cfg
08-03 19:50:53.466  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:53.469  1041  1523 E WifiStateMachine: Start Dhcp Watchdog 1
08-03 19:50:53.470  1041  6473 D DhcpStateMachine: StoppedState
08-03 19:50:53.470  1041  6473 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:53.470  1041  6473 D DhcpStateMachine: WaitBeforeStartState
08-03 19:50:53.470  1041  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=157892  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-03 19:50:53.471  1041  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=157892  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:50:53.471  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=157893  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:50:53.472  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:53.472  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:53.472  1041  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:53.473  1041  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:53.473  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:53.473  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:53.473  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:53.474  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:53.474  1041  1041 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-03 19:50:53.475  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:53.475  1041  1041 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-03 19:50:53.476  1041  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=157897  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:50:53.477  1041  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=157898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:50:53.477  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=157899  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:50:53.477  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:53.479  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1367838247] from screen [on:0 period:1367838247]
08-03 19:50:53.481  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:53.481  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:53.481  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:50:53.482  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1367838250]
08-03 19:50:53.482  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 19:50:53.483  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:50:53.488  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:53.489  1041  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-03 19:50:53.489  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.489  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.489  1041  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.490  1041  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.490  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:50:53.490  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.490  1041  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.491  1041  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-03 19:50:53.491  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-03 19:50:53.491  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-03 19:50:53.491  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 19:50:53.492  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 19:50:53.492  1041  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 19:50:53.492  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 19:50:53.492  1041  1523 D WifiNative-wlan0: SET ps 0: returned true
08-03 19:50:53.493  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 19:50:53.493  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-03 19:50:53.493  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 19:50:53.493  1041  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 19:50:53.493  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b31c753 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:53.493  1041  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:50:53.493  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b31c753 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:53.493  1041  6473 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:53.493  1041  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:50:53.493  1041  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-03 19:50:53.494  1041  6473 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 19:50:53.494  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:53.494  1041  1041 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 19:50:53.494  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:53.494  1041  1041 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-03 19:50:53.496  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:53.502  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:53.502  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:53.502  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:50:53.506  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:53.512  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:53.516  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:53.522  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:53.523  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:53.523  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:50:53.528  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:53.528  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:53.528  1041  1522 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:50:53.551  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:50:53.552  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-03 19:50:53.553  1041  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:50:53.554  1041  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:50:53.555  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:50:53.556  1041  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:50:53.697  1041  6473 D DhcpStateMachine: DHCPV4 request on wlan0
08-03 19:50:53.699  1041  6473 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 19:50:53.699  1041  6473 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-03 19:50:53.705  6476  6476 W dhcpcd  : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:53.705  6476  6476 W dhcpcd  : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:53.726  6476  6476 I dhcpcd  : version 5.5.6 starting
,08-03 19:50:53.734  6476  6476 E dhcpcd  : get_duid: m
08-03 19:50:53.734  6476  6476 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 19:50:53.734  6476  6476 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 19:50:53.809  6476  6476 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:50:53.810  6476  6476 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:50:53.810  6476  6476 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-03 19:50:53.813  6476  6476 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 19:50:53.813  6476  6476 D dhcpcd  : wlan0: sending REQUEST (xid 0xcc741cc8), next in 4.53 seconds
08-03 19:50:53.828  6476  6476 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-03 19:50:53.836  6476  6476 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-03 19:50:53.836  6476  6476 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 19:50:53.838  6476  6476 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 19:50:53.838  6476  6476 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 19:50:53.839  6476  6476 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 19:50:53.839  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.839  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.839  6476  6476 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:50:53.840  6476  6476 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:50:53.840  1041  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.840  6476  6476 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 19:50:53.840  1041  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.840  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.841  1041  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:53.842  1041  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,08-03 19:50:54.102  1041  6473 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-03 19:50:54.104  1041  6473 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 19:50:54.105  1041  6473 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:50:54.105  1041  6473 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 19:50:54.105  1041  6473 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 19:50:54.105  1041  6473 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:50:54.105  1041  6473 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-03 19:50:54.106  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 19:50:54.107  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 19:50:54.107  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:50:54.108  1041  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.108  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.108  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:50:54.109  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:50:54.109  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 19:50:54.109  1041  6473 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 19:50:54.109  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 19:50:54.109  1041  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 19:50:54.109  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:50:54.110  1041  6473 D DhcpStateMachine: RunningState
08-03 19:50:54.127  1041  1523 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:50:54.127  1041  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-03 19:50:54.128  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:50:54.128  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:50:54.129  1041  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 19:50:54.130  1041  1530 D ConnectivityService: ignoring duplicate network state non-change
,08-03 19:50:54.146  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:54.146  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 19:50:54.148  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.150  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.151  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.151  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 19:50:54.165  1041  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 19:50:54.167  1041  1530 D ConnectivityService: Adding iface wlan0 to network 100
08-03 19:50:54.173  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:54.173  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:54.181  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:50:54.185  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.185  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.185  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 19:50:54.190  1041  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 19:50:54.192  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 19:50:54.195  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-03 19:50:54.194  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:54.198  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.198  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.198  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 19:50:54.198  1041  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 19:50:54.198  1041  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-03 19:50:54.200  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 19:50:54.201  1041  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-03 19:50:54.202  1041  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-03 19:50:54.203  1041  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 19:50:54.203  1041  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-03 19:50:54.204  1041  1530 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-03 19:50:54.207  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.207  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.207  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 19:50:54.208  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:54.208  1041  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 19:50:54.208  1041  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.208  1041  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.210  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:50:54.211  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:50:54.213  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.213  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 19:50:54.213  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.215  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 19:50:54.219  1041  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.219  1041  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:50:54.219  1041  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.219  1041  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:50:54.219  1041  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.220  1041  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 19:50:54.220  1041  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-03 19:50:54.220  1041  1530 D ConnectivityService:    accepting network in place of null
08-03 19:50:54.220  1041  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.221  1041  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.221  1041  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:50:54.222  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.222  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:50:54.223  1041  1530 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-03 19:50:54.229   313  6517 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 19:50:54.231  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 19:50:54.236  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:50:54.236  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.238  1041  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 19:50:54.239  1041  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 19:50:54.239  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:50:54.241  1041  1041 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 19:50:54.241  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:50:54.242  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:50:54.242  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:50:54.242  1041  1041 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-03 19:50:54.245   313  6524 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:50:54.246   313  6524 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-03 19:50:54.247   313  6523 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:50:54.247   313  6523 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-03 19:50:54.247   313  6524 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-03 19:50:54.248   313  6523 D libc-netbsd: res_queryN name = europe.pool.ntp.org., class = 1, type = 1
,08-03 19:50:54.249  1041  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:50:54.249  1041  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:50:54.249  1041  6522 D LocSvc_java: requestTime failed
08-03 19:50:54.249  1041  6522 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-03 19:50:54.251  1041  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:54.251  1041  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 19:50:54.251  1041  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-03 19:50:54.252  1041  1530 D ConnectivityService: validation of new default Network = false
08-03 19:50:54.252  1041  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-03 19:50:54.252  1041  1530 D DSQN    : enableDataServiceNotify 
08-03 19:50:54.253  1041  1530 D DSQN    : start dsqn bin
,08-03 19:50:54.262  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:50:54.268  1041  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.268  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.268  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.268  1041  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.265  6526  6526 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:54.265  6526  6526 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:54.270  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 19:50:54.271  1041  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-03 19:50:54.278  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.282   313  6517 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 19:50:54.283  6526  6526 E DSQN    : DSQN ssw
,08-03 19:50:54.287  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:54.287  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:54.292  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:50:54.293  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.293  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:50:54.293  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.296  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:50:54.304  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:54.308  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.313  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:54.313  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:54.314  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:50:54.317   313  6517 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 19:50:54.318  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:54.322  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 19:50:54.326  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:50:54.328  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:54.333  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.339  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:54.339  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:54.339  6289  6289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 19:50:54.340  6289  6289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:50:54.340  6289  6289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-03 19:50:54.345  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:50:54.349  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 19:50:54.349  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:54.352  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:54.359  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.361   313   891 D LGDataListener: argv[0]=dsqncommand
08-03 19:50:54.361   313   891 D LGDataListener: argv[1]=wlan0
08-03 19:50:54.361   313   891 D LGDataListener: argv[2]=1
08-03 19:50:54.361   313   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-03 19:50:54.362  1041  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 19:50:54.363  1041  1117 D DSQN    : start to monitor internet connection
08-03 19:50:54.369  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:50:54.369  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:54.371  6289  6289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 19:50:54.372  6289  6289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:50:54.373  6289  6289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 19:50:54.405  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 17:50:54 GMT], X-Android-Received-Millis=[1470246654403], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470246654361]}
08-03 19:50:54.405  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 19:50:54.405  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 19:50:54.406  1041  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.407  1041  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.407  1041  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:50:54.407  1041  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.407  1041  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:50:54.408  1041  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
,08-03 19:50:54.408  1041  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.408  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.409  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.410  1041  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.410  1041  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.410  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 19:50:54.411  1041  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.412  1041  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:50:54.412  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 19:50:54.412  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.413  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:50:54.454  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-03 19:50:54.456  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
,08-03 19:50:54.458  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.598  1041  1762 D WifiServiceImplEx: setWifiEnabled: false pid=5955, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:50:54.598  1041  1762 D WifiService: setWifiEnabled: false pid=5955, uid=10118
08-03 19:50:54.598  1041  1762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:50:54.620  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:50:54.621  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:50:54.621  1041  1041 D Ulp_jni : JNI:system_update. Event-4
08-03 19:50:54.623  1041  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:54.624  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:54.625  1041  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:54.626  1041  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:54.627  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:50:54.627  1041  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 19:50:54.627  1041  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:50:54.627  1041  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:50:54.628  1041  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:50:54.628  1041  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:50:54.642  1041  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:50:54.642  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:50:54.642  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.642  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.642  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-03 19:50:54.645  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:50:54.645  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:50:54.646  1041  1523 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:50:54.646  1041  6473 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.647   313   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:50:54.679  1041  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 19:50:54.680  1041  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-03 19:50:54.684  1041  1041 D WifiHS20: hidePasspointNotification off =false
08-03 19:50:54.685  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:54.685  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:54.688  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 19:50:54.689  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.698  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.698  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.698  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-03 19:50:54.720  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.720  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.720  1041  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d43b081
08-03 19:50:54.721  1041  1522 D LGWifiP2pService: P2pDisablingState
08-03 19:50:54.721  1041  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.721  1041  1522 D LGWifiP2pService: p2p socket connection lost
08-03 19:50:54.721  1041  1522 D LGWifiP2pService: P2pDisabledState
,08-03 19:50:54.724  1041  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:54.724  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:54.725  1041  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:54.725  1041  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:54.726  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:54.728  1041  1041 D WifiHS20: hidePasspointNotification off =false
08-03 19:50:54.733  1041  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:50:54.736  1041  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-03 19:50:54.737  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:54.737  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:54.739  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.743  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.743  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.743  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:50:54.743  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 19:50:54.743  1041  1041 D RttService: SCAN_AVAILABLE : 1
08-03 19:50:54.744  1041  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.744  1041  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.745  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:54.747  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:50:54.747  1926  1926 D WfdsService: WifiP2pState is changed : false
08-03 19:50:54.748  1926  2288 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 19:50:54.748  1926  2288 D WfdsService: Set the WFDS Monitor: false
08-03 19:50:54.748  1926  2288 D WfdsMonitor: WFDS Monitor is stopped
08-03 19:50:54.748  1926  2288 D WfdsService: STATE : WfdsDisabledState - enter
08-03 19:50:54.749  1041  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 19:50:54.749  1041  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.749  1041  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.749  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:50:54.750  6417  6417 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:50:54.750  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:50:54.750  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:50:54.751  1041  1523 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:50:54.751  1926  6443 D CtrlSupplicant: Received on exit socket, terminate
08-03 19:50:54.751  1926  6443 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 19:50:54.751  1926  6443 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 19:50:54.751  1926  6443 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 19:50:54.752  1926  2296 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 19:50:54.752  1926  2288 W WfdsService: DefaultState - msg [9445378] is not handled
,08-03 19:50:54.760  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:50:54.760  6238  6238 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-03 19:50:54.760  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:54.765  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:54.774   313   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:50:54.775  1041  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 19:50:54.775  1041  1530 D DSQN    : disableDataServiceNotify
08-03 19:50:54.775  1041  1530 D DSQN    : stop dsqn bin
08-03 19:50:54.776  1041  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 19:50:54.777  1041  1041 D WifiHS20: hidePasspointNotification off =false
08-03 19:50:54.777  1041  1523 D WifiNative-p2p0: TERMINATE: returned true
08-03 19:50:54.777  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:50:54.777  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:50:54.777  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:50:54.778  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-03 19:50:54.778  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:50:54.780  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.780  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.781  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.781  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:50:54.782  1041  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-03 19:50:54.783  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.783  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.784  1041  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:50:54.785  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 19:50:54.786  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 19:50:54.786  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:50:54.786  1041  1041 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-03 19:50:54.787  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:54.787  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:54.787  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:50:54.787  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:54.787  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.787  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:54.787  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 19:50:54.787  1041  6472 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 19:50:54.788  1041  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 19:50:54.788  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:54.788  5955  5955 V i,o.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:54.788  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:54.788  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:54.788  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:54.788  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:54.788  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:54.788  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:54.788  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:50:54.789  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:54.789  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:50:54.789  1041  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 19:50:54.789  1041  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 19:50:54.789  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:50:54.790  1041  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-03 19:50:54.791  1041  1041 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 19:50:54.791  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:50:54.791  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:50:54.791  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:50:54.793  1041  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:54.793  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:50:54.793  1041  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:54.793  1041  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.793  1041  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.794  1041  1530 D NetworkManagementService: Removing idletimer
08-03 19:50:54.794  1041  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.794  1041  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:50:54.794  1041  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:54.795  1041  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-03 19:50:54.795  1041  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 19:50:54.796  1041  1041 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 19:50:54.796  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:50:54.796  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:50:54.796  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:50:54.797  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:50:54.797  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:50:54.800  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.800  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.807  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:54.808  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:50:54.813  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:50:54.816  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:54.820  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:50:54.820  6238  6238 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:50:54.820  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:54.824  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:54.827  6417  6417 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 19:50:54.827  6417  6417 I wpa_supplicant: monitor socket send errors count : 1
08-03 19:50:54.827  6417  6417 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-4\x00 that cannot receive messages
08-03 19:50:54.828  1041  6438 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 19:50:54.828  1041  6438 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 19:50:54.831  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.838  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:54.839  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:50:54.841  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:50:54.845  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:50:54.850  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:50:54.850  6238  6238 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:50:54.850  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:54.856  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:50:54.859  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:50:54.861  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.862  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.863  1041  6473 D DhcpStateMachine: StoppedState
08-03 19:50:54.863  1041  6473 D DhcpStateMachine: StoppedState{ when=-113ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:54.864  1041  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 19:50:54.865  1041  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-03 19:50:54.866  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.867  6417  6417 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:50:54.867  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 19:50:54.867  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:50:54.867  1041  6438 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:50:54.868  1041  6438 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 19:50:54.868  6417  6417 W wpa_supplicant: USIM:  scard_deinit function
08-03 19:50:54.868  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-03 19:50:54.869  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:50:54.870  1041  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=159292
,08-03 19:50:54.871  1041  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=159293
08-03 19:50:54.872  1041  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=159293  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 19:50:54.872  1041  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=159294  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 19:50:54.873  1041  1119 D Tethering: InitialState.processMessage what=4
08-03 19:50:54.877  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:50:54.877  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:50:54.878  1041  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 19:50:54.879  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:50:54.879  1041  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:50:54.880  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-03 19:50:54.891  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:50:54.899  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:50:54.901  6329  6557 W FormManager: Network not available. Please check & try again.
,08-03 19:50:54.910  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:54.910  6329  6558 V FormManager: Network unavailable.
08-03 19:50:54.911  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:50:54.913  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.913  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:54.924  6329  6558 V FormManager: Network unavailable.
,08-03 19:50:54.930  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:50:54.930  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:50:54.930  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:50:54.930  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:50:54.932  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:50:54.933  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:50:54.933  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 19:50:54.933  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:50:54.933  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:50:54.933  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:50:54.933  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:50:54.938  6417  6417 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-03 19:50:54.938  1041  6438 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 19:50:54.938  1041  6438 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 19:50:54.938  1041  6438 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 19:50:54.939  1041  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 36 0
,08-03 19:50:55.041  1041  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 19:50:55.041  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:50:55.041  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:50:55.041  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 19:50:55.047  1926  1926 D WfdsService: Supplicant Connection state is changed : false
08-03 19:50:55.048  1926  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 19:50:55.048  1926  2288 D WfdsService: Set the WFDS Monitor: false
08-03 19:50:55.048  1926  2288 D WfdsMonitor: WFDS Monitor is stopped
08-03 19:50:55.051  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:50:55.051  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:50:55.052  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:50:55.053  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:50:55.057  2492  2492 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:55.057  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 19:50:55.058  1041  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 19:50:55.058  1041  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 19:50:55.060  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:55.060  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:50:55.062  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:55.062  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:55.063  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:50:55.067  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:50:55.074  4264  6559 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:50:55.076  4264  6560 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:50:55.076  4264  6560 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:50:55.082  6238  6238 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 19:50:55.082  6238  6238 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:50:55.082  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:50:55.086  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:50:55.088  6329  6562 W FormManager: Network not available. Please check & try again.
08-03 19:50:55.092  6329  6563 V FormManager: Network unavailable.
08-03 19:50:55.094  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:50:55.100  6329  6563 V FormManager: Network unavailable.
,08-03 19:50:55.544  6137  6397 D UEI.SmartControl: Internal timer expired: 2
08-03 19:50:55.544  6137  6397 D UEI.SmartControl: unbind internal service
,08-03 19:50:55.769  6137  6394 D serial_port: close(fd = 24)
,08-03 19:50:55.778  6137  6394 I UEI.SmartControl: Serial port is closed.
08-03 19:50:56.492  1041  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1367841259] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:50:56.494  1041  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1367841262] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-03 19:50:57.254  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:50:57.268  1041  1119 D Tethering: MasterInitialState.processMessage what=3
08-03 19:50:57.279  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:50:57.283  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:57.285  1041  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:57.290  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 19:50:57.292  3666  3700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-03 19:50:57.307  5326  5326 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 19:50:57.364  1041  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 19:50:57.378  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:50:57.451  1041  1943 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6584 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-03 19:50:57.461  1041  1103 E GpsLocationProvider: No APN found to select.
08-03 19:50:57.473   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 24.004ms
,08-03 19:50:57.494   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 19.729ms
08-03 19:50:57.513  6584  6584 I AppUp4:AppBoxCP: onCreate
08-03 19:50:57.514  6584  6584 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-03 19:50:57.514   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 19.182ms
,08-03 19:50:57.520  6584  6584 I AppUp4:DB:  setFingerPrint start
08-03 19:50:57.520  6584  6584 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-03 19:50:57.525  6584  6584 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-03 19:50:57.525  6584  6584 I AppUp4:DB:  SDK version = 21
,08-03 19:50:57.526  6584  6584 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-03 19:50:57.527  6584  6584 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-03 19:50:57.528  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-03 19:50:57.528  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:57.530  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:50:57.530  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 19:50:57.533  6584  6584 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 19:50:57.566  6584  6584 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:50:57.566  6584  6584 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:50:57.577  6584  6584 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2df825eb
,08-03 19:50:57.577  6584  6584 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:50:57.578  6584  6584 D AppUp4:CustFacade: isPhone : true
08-03 19:50:57.579  6584  6584 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:50:57.580  6584  6584 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-03 19:50:57.580  6584  6584 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-03 19:50:57.601  6584  6604 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-03 19:50:57.601  6584  6604 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-03 19:50:57.601  6584  6604 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-03 19:50:57.603  1041  1907 I ActivityManager: Killing 5808:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-03 19:50:57.638  1041  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:57.638  1041  2027 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 19:50:57.640  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:57.640  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:50:57.641  1041  1058 W libprocessgroup: failed to open /acct/uid_10027/pid_5808/cgroup.procs: No such file or directory
08-03 19:50:57.642  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:50:57.646  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:50:57.654  4264  6606 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:50:57.659  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-03 19:50:57.659  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:50:57.660  1041  1041 D Ulp_jni : JNI:system_update. Event-4
08-03 19:50:57.660  1041  1119 D BluetoothManagerService: Message: 1
08-03 19:50:57.660  1041  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 19:50:57.670  4264  6607 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:57.670  4264  6607 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 19:50:57.694  1041  1679 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6609 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 19:50:57.723  1041  1119 D BluetoothManagerService: Message: 20
08-03 19:50:57.723  1041  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@328b2b43:true
08-03 19:50:57.724  6367  6367 D BluetoothAdapterState: make
,08-03 19:50:57.729  6367  6367 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 19:50:57.730  6367  6367 I bluedroid-qcom: init
08-03 19:50:57.731  6367  6624 I BluetoothAdapterState: Entering OffState
08-03 19:50:57.732  6367  6367 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 19:50:57.732  6367  6367 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 19:50:57.733  6367  6367 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 19:50:57.733  6367  6367 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 19:50:57.733  6367  6367 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 19:50:57.725  6629  6629 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:57.725  6629  6629 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:57.734  6367  6367 I bluedroid-qcom: get_profile_interface socket
08-03 19:50:57.734  6367  6367 I bluedroid-qcom: get_profile_interface map_client
08-03 19:50:57.736  6367  6628 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 19:50:57.739  6367  6628 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-03 19:50:57.743  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 19:50:57.744  6367  6628 D BluetoothAdapterProperties: Name is: G3
08-03 19:50:57.744  1041  1119 D BluetoothManagerService: Message: 40
08-03 19:50:57.744  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 19:50:57.744  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:50:57.744  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 19:50:57.745  6367  6383 I bluedroid-qcom: config_hci_snoop_log
08-03 19:50:57.745  6629  6629 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 19:50:57.745  6629  6629 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 19:50:57.745  6629  6629 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-03 19:50:57.747  1041  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 19:50:57.747  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-03 19:50:57.750  6629  6629 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-03 19:50:57.757  6367  6624 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 19:50:57.758  6367  6624 D BluetoothAdapterProperties: Setting state to 11
08-03 19:50:57.758  6367  6624 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-03 19:50:57.759  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:50:57.759  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 19:50:57.759  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 19:50:57.760  6367  6624 I LGBluetoothServiceJni: classInitNative: succeeds
08-03 19:50:57.761  6629  6629 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 19:50:57.761  6629  6629 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-03 19:50:57.771  6367  6624 D BluetoothBondStateMachine: make
08-03 19:50:57.772  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:57.772  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:50:57.775  6216  6216 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 19:50:57.776  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:57.777  6367  6624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:57.777  6367  6624 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 19:50:57.777  6367  6624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:57.777  6367  6624 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 19:50:57.778  6367  6624 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 19:50:57.778  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:57.782  6367  6367 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-03 19:50:57.783  6367  6367 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:57.783  6367  6367 V BluetoothPbapReceiver: ***********state = 11
08-03 19:50:57.785  6367  6631 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 19:50:57.790  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:50:57.792  6367  6624 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:50:57.793  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:57.799  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:50:57.801  6367  6367 D HeadsetService: Received start request. Starting profile...
08-03 19:50:57.802  6367  6367 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:50:57.802  6367  6367 D LGBluetoothHfpAdapter: Version 1.6
08-03 19:50:57.802  6367  6624 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:50:57.804  1041  1119 D Tethering: MasterInitialState.processMessage what=3
08-03 19:50:57.805  6367  6367 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 19:50:57.806  6367  6367 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:50:57.806  6367  6367 D HeadsetStateMachine: make
08-03 19:50:57.807  1041  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:57.811  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:57.813  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:50:57.814  6216  6216 D BluetoothPermissionRequest: onReceive
08-03 19:50:57.814  5326  5326 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 19:50:57.819  1041  1119 D Tethering: MasterInitialState.processMessage what=3
08-03 19:50:57.825  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:57.828  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:50:57.829  6609  6609 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:50:57.830  6609  6609 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:50:57.831  6609  6609 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:50:57.831  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:57.831  6609  6609 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:50:57.832  6367  6624 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:50:57.840  1041  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:57.840  1041  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:57.840  1041  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:50:57.841  6367  6624 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:50:57.843  6367  6367 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:50:57.843  6367  6367 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:50:57.845  5326  5326 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 19:50:57.847  6367  6367 D HeadsetStateMachine: max_hf_connections = 1
08-03 19:50:57.847  6367  6367 I bluedroid-qcom: get_profile_interface handsfree
08-03 19:50:57.848  6367  6624 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:50:57.849  6367  6367 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 19:50:57.849   317   317 V AudioPolicyService: registerClient() client 0xb1004180, uid 1002
08-03 19:50:57.849   317   317 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:50:57.850   317   317 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:50:57.850   317   317 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:50:57.850  6367  6367 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 19:50:57.850   317  2163 V AudioFlinger: registerClient() client 0xb5581610, pid 6367
08-03 19:50:57.850  6367  6367 V ToneGenerator: Create Track: 0xb4928a80
08-03 19:50:57.851  6367  6367 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 19:50:57.851  6367  6367 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 19:50:57.851   317  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:50:57.851   317   317 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:50:57.851   317  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:50:57.851   317   317 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:50:57.851   317   317 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:50:57.852   317   317 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:50:57.852  1041  1961 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:50:57.852  1041  1961 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:50:57.852  1587  2515 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:50:57.852  1587  2515 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:50:57.852  6367  6367 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 19:50:57.853  3339  3355 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:50:57.853  6367  6382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:50:57.853  3339  3355 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:50:57.853  6367  6382 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 19:50:57.853  1837  4354 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:50:57.853  1837  4354 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:50:57.853   317  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:50:57.853   317  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:50:57.853  1041  1059 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:50:57.853  1041  1059 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:50:57.853  1587  3092 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:50:57.853  1587  3092 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:50:57.853   317  1370 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 19:50:57.853  1837  2423 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:50:57.853  1837  2423 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:50:57.853  6367  6383 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:50:57.853  6367  6383 ,V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 19:50:57.853   317  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:50:57.853   317  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 19:50:57.853   317  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:50:57.853   317  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:50:57.854  3339  3354 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:50:57.854  3339  3354 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:50:57.854  6367  6367 V AudioSystem: getLatency() output 2, latency 50
08-03 19:50:57.854  6367  6367 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 19:50:57.854  6367  6367 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 19:50:57.854   317  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:50:57.854   317  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:50:57.854   317  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:50:57.854   317  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:50:57.854   317  1370 V AudioFlinger: createTrack() lSessionId: 22
08-03 19:50:57.855  6367  6367 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,08-03 19:50:57.857   317  1370 V AudioFlinger: acquiring 22 from 6367, for 6367
08-03 19:50:57.857   317  1370 V AudioFlinger:  added new entry for 22
08-03 19:50:57.858  6367  6367 V ToneGenerator: ToneGenerator INIT OK, time: 162291
08-03 19:50:57.858  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:57.859  6367  6632 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 19:50:57.859  6367  6632 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:50:57.859  6367  6632 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:50:57.859  6367  6632 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 19:50:57.860   317  1369 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6367
08-03 19:50:57.860   317  1369 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 19:50:57.860  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:57.860   317  1369 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 19:50:57.860   317  1369 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 19:50:57.860   317  1369 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 19:50:57.860   317  1369 V voice   : voice_set_parameters: exit with code(0)
08-03 19:50:57.860   317  1369 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 19:50:57.860   317  1369 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 19:50:57.860   317  1369 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 19:50:57.860   317  1369 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 19:50:57.860   317  1369 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 19:50:57.860   317  1369 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 19:50:57.861  6367  6632 V ToneGenerator: ToneGenerator destructor
08-03 19:50:57.861  6367  6632 V ToneGenerator: stopTone
08-03 19:50:57.861  6367  6632 V ToneGenerator: Delete Track: 0xb4928a80
08-03 19:50:57.861  6367  6632 V AudioTrack: ~AudioTrack, releasing session id from 6367 on behalf of 6367
08-03 19:50:57.861   317  2162 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 19:50:57.861   317  2162 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 19:50:57.861   317   317 V AudioFlinger: releasing 22 from 6367 for 6367
08-03 19:50:57.861   317   317 V AudioFlinger:  decremented refcount to 0
08-03 19:50:57.861   317  2162 V AudioFlinger: PlaybackThread::Track destructor
08-03 19:50:57.861   317  1273 V AudioPolicyService: AudioCommandThread() waking up
08-03 19:50:57.861   317   317 V AudioFlinger: purging stale effects
08-03 19:50:57.861   317  2162 V AudioFlinger: removeClient_l() pid 6367, calling pid 317
08-03 19:50:57.861   317  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 19:50:57.861   317  1273 V AudioPolicyManager: releaseOutput() 2
08-03 19:50:57.861   317  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 19:50:57.862  6367  6367 D A2dpService: Received start request. Starting profile...
08-03 19:50:57.862  6367  6624 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:50:57.863  6367  6367 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 19:50:57.863  6367  6367 V Avrcp   : make
08-03 19:50:57.864  1041  1059 W Process : Unable to open /proc/6638/status
08-03 19:50:57.864  6367  6367 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 19:50:57.864  6367  6367 I bluedroid-qcom: get_profile_interface avrcp
08-03 19:50:57.867  6367  6624 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:50:57.872  6367  6367 V AudioManager: registerRemoteController: size of Media player list: 0
08-03 19:50:57.875  6367  6367 E AudioManager: No RCC entry present to update
08-03 19:50:57.875  6367  6367 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 19:50:57.879  6367  6367 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 19:50:57.880  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 19:50:57.880  6367  6367 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 19:50:57.883  6367  6624 V LGMDMManager: Create singleton instance
08-03 19:50:57.884  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-03 19:50:57.886  6367  6624 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-03 19:50:57.920  6609  6609 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 19:50:57.933  6609  6609 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-03 19:50:57.962  6609  6609 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 19:50:57.984  6609  6609 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:50:57.985  6609  6609 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:50:58.002  1041  1961 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:50:58.002  1041  1961 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:50:58.111  1041  1763 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-03 19:50:58.114  6609  6609 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 19:50:58.136  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-03 19:50:58.142  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 19:50:58.143  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 19:50:58.143  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 19:50:58.143  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 19:50:58.144  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:50:58.144  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 19:50:58.144  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 19:50:58.144  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 19:50:58.144  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:50:58.144  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 19:50:58.144  6367  6367 I BluetoothA2dpServiceJni: classInitNative
08-03 19:50:58.145  6367  6367 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:50:58.145  6367  6367 D A2dpStateMachine: make
08-03 19:50:58.147  6367  6367 I bluedroid-qcom: get_profile_interface a2dp
08-03 19:50:58.147  6367  6651 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 19:50:58.149  6367  6367 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:50:58.149  6367  6367 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 19:50:58.151  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:58.151  6367  6649 D A2dpStateMachine: Enter Disconnected: -2
,08-03 19:50:58.152  6367  6367 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 19:50:58.154  6367  6367 D HidService: Received start request. Starting profile...
08-03 19:50:58.154  6367  6367 I bluedroid-qcom: get_profile_interface hidhost
08-03 19:50:58.155  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:58.155  6367  6367 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:50:58.157  6367  6367 D HealthService: Received start request. Starting profile...
08-03 19:50:58.160  6367  6367 I bluedroid-qcom: get_profile_interface health
08-03 19:50:58.160  6367  6367 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:50:58.160  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:58.160  6367  6367 D HeadsetStateMachine: Proxy object connected
08-03 19:50:58.161  3339  3339 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:50:58.161  3339  3339 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:50:58.161  6367  6367 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 19:50:58.161  6367  6367 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-03 19:50:58.163  6367  6367 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 19:50:58.164  3339  3339 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 19:50:58.164  3339  3339 D PhoneState: setPdpRejectCasuse : false
,08-03 19:50:58.167  6367  6367 D PanService: Received start request. Starting profile...
08-03 19:50:58.167  6367  6367 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 19:50:58.167  6367  6367 I bluedroid-qcom: get_profile_interface pan
08-03 19:50:58.170  6609  6609 I HubEmail: JNI_OnLoad()
08-03 19:50:58.170  6609  6609 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:50:58.170  6609  6609 I HubEmail: registerNatives()
08-03 19:50:58.171  6609  6609 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:50:58.171  6609  6609 I HubEmail: registerNativeMethods()
08-03 19:50:58.171  6609  6609 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:50:58.171  6609  6609 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-03 19:50:58.215  1041  1889 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6660 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-03 19:50:58.223  6367  6367 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 19:50:58.223  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:58.225  6367  6632 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 19:50:58.226  6367  6632 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 19:50:58.226  6367  6632 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 19:50:58.230  6367  6367 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:50:58.230  6329  6657 V FormManager: Network unavailable.
08-03 19:50:58.230  6609  6659 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:50:58.231  6367  6367 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 19:50:58.231  6329  6656 W FormManager: Network not available. Please check & try again.
08-03 19:50:58.232  6329  6657 V FormManager: Network unavailable.
,08-03 19:50:58.236  6367  6367 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 19:50:58.237  6367  6367 D BtGatt.GattService: Received start request. Starting profile...
08-03 19:50:58.237  6367  6367 D BtGatt.GattService: start()
08-03 19:50:58.237  6367  6367 I bluedroid-qcom: get_profile_interface gatt
08-03 19:50:58.238  6367  6367 D BtGatt.AdvertiseManager: advertise manager created
08-03 19:50:58.384  1041  1888 I art     : Explicit concurrent mark sweep GC freed 134830(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.267ms total 142.240ms
,08-03 19:50:58.396  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:58.398  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:58.399  6367  6367 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 19:50:58.400  6367  6367 V BluetoothMapService: BluetoothMapBinder()
08-03 19:50:58.401  6367  6367 D BluetoothMapService: Received start request. Starting profile...
,08-03 19:50:58.401  6367  6367 D BluetoothMapService: start()
08-03 19:50:58.405  6367  6367 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 19:50:58.405  6367  6367 D BluetoothMapEmailAppObserver: createReceiver()
08-03 19:50:58.407  6367  6367 D BluetoothMapEmailAppObserver: initObservers()
08-03 19:50:58.407  6367  6367 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-03 19:50:58.418  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
,08-03 19:50:58.421  6367  6367 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:50:58.424  6367  6367 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:58.428  6367  6367 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:50:58.431  6367  6367 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 19:50:58.438  6367  6367 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:50:58.439  6367  6367 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 19:50:58.443  6367  6367 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 19:50:58.443  6367  6367 V BluetoothMapService: Handler(): got msg=1
08-03 19:50:58.444  6367  6367 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-03 19:50:58.444  6367  6367 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:50:58.444  6367  6367 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:50:58.444  6367  6367 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:58.444  6367  6367 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 19:50:58.447  6367  6624 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 19:50:58.447  6367  6624 I bluedroid-qcom: enable
08-03 19:50:58.448  6367  6624 I bt_hci_bdroid: init
08-03 19:50:58.449  6367  6679 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 19:50:58.449  6367  6679 I bt-btu  : btu_task pending for preload complete event
08-03 19:50:58.449  6367  6624 I bt_vendor: bt-vendor : init
08-03 19:50:58.449  6367  6624 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 19:50:58.449  6367  6624 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 19:50:58.449  6367  6624 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
,08-03 19:50:58.449  6367  6624 D bt_userial_mct: userial_init
08-03 19:50:58.450  6367  6624 D bt_hci_bdroid: set_power 1
08-03 19:50:58.450  6367  6624 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 19:50:58.450  6367  6624 I bt_vendor: Starting hciattach daemon
08-03 19:50:58.450  6367  6624 I bt_vendor: try to set true
08-03 19:50:58.445  6682  6682 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:58.445  6682  6682 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:58.474  6683  6683 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 19:50:58.495  6660  6660 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:50:58.495  6660  6660 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:50:58.498  6660  6660 D PhoneMonitor: Register our PhoneStateListener
08-03 19:50:58.509  6660  6660 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:50:58.511  6660  6660 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 19:50:58.523  6660  6660 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-03 19:50:58.524  6660  6660 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 19:50:58.525  6660  6660 D TelephonyAutoProfiling: [parse] Load xml
08-03 19:50:58.527  6660  6660 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 19:50:58.527  6660  6660 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 19:50:58.528  6660  6660 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-03 19:50:58.534  6660  6660 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-03 19:50:58.536  6696  6696 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 19:50:58.541  1041  1058 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6697 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:50:58.541  1041  1058 I ActivityManager: Killing 5900:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-03 19:50:58.549  6698  6698 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 19:50:58.572  6716  6716 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:50:58.583  6717  6717 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-03 19:50:58.592  6719  6719 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:50:58.597  1041  1943 W libprocessgroup: failed to open /acct/uid_10061/pid_5900/cgroup.procs: No such file or directory
,08-03 19:50:58.603  6720  6720 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-03 19:50:58.623  6722  6722 I libmdmdetect: ESOC framework not supported
08-03 19:50:58.625  6722  6722 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-03 19:50:58.633  6722  6722 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-03 19:50:58.633  6722  6722 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 19:50:58.633  6722  6722 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 19:50:58.633  6722  6722 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 19:50:58.633  6722  6722 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 19:50:58.633  6722  6722 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 19:50:58.633  6722  6722 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 19:50:58.669  6722  6723 E QC-QMI  : qmi_client [6722] 14: failed to locate client data
,08-03 19:50:58.669   482   482 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 19:50:58.670   482   482 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-03 19:50:58.695  6724  6724 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 19:50:58.711  6725  6725 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 19:50:58.751  6367  6624 I bt_vendor: bluetooth satus is on
08-03 19:50:58.752  6367  6624 D bt_hci_bdroid: preload
,08-03 19:50:58.752  6367  6681 D bt_userial_mct: userial_open(port:0)
08-03 19:50:58.752  6367  6681 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-03 19:50:58.756  6367  6681 I bt_vendor: Done intiailizing UART
08-03 19:50:58.756  6367  6681 I bt_vendor: Done intiailizing UART
08-03 19:50:58.756  6367  6681 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 19:50:58.757  6367  6681 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-03 19:50:58.757  6367  6727 D bt_userial_mct: Entering userial_read_thread()
08-03 19:50:58.757  6367  6679 I bt-btu  : btu_task received preload complete event
08-03 19:50:58.759  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-03 19:50:58.759  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 19:50:58.764  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-03 19:50:58.771  6367  6679 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 19:50:58.771  6367  6679 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 19:50:58.771  6367  6679 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 19:50:58.771  6367  6679 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 19:50:58.771  6367  6679 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 19:50:58.771  6367  6679 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 19:50:58.772  6367  6679 I         : BTE_InitTraceLevels -- TRC_BTIF
08-03 19:50:58.823  6367  6679 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-03 19:50:58.824  6367  6679 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c2061 
08-03 19:50:58.824  6367  6679 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c2061 
,08-03 19:50:58.850  6367  6628 E bt-btif : Calling BTA_HhEnable
,08-03 19:50:58.850  6367  6628 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-03 19:50:58.850  6367  6628 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 19:50:58.853  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 19:50:58.853  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 19:50:58.854  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 19:50:58.854  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 19:50:58.854  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 19:50:58.854  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:50:58.854  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
,08-03 19:50:58.855  6367  6628 D BluetoothAdapterProperties: Name is: G3
08-03 19:50:58.857  6367  6628 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:50:58.857  6367  6628 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:50:58.858  6367  6628 D bt_hci_bdroid: postload
08-03 19:50:58.858  6367  6681 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:50:58.859  6367  6681 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:50:58.859  6367  6679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 19:50:58.859  6367  6628 D bte_conf: Device ID record 1 : primary
08-03 19:50:58.859  6367  6628 D bte_conf:   vendorId            = 00c4
08-03 19:50:58.859  6367  6628 D bte_conf:   vendorIdSource      = 0001
08-03 19:50:58.859  6367  6628 D bte_conf:   product             = 13a1
08-03 19:50:58.859  6367  6628 D bte_conf:   version             = 1000
08-03 19:50:58.859  6367  6628 D bte_conf:   clientExecutableURL = 
08-03 19:50:58.859  6367  6628 D bte_conf:   serviceDescription  = 
08-03 19:50:58.859  6367  6628 D bte_conf:   documentationURL    = 
08-03 19:50:58.859  6367  6628 D bte_conf: bte_load_did_conf no section named DID2.
08-03 19:50:58.860  6367  6681 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:50:58.860  6367  6681 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:50:58.862  6367  6624 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 19:50:58.862  6367  6624 D BluetoothAdapterProperties: ScanMode =  20
08-03 19:50:58.862  6367  6624 D BluetoothAdapterProperties: State =  11
08-03 19:50:58.863  6367  6624 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 19:50:58.863  6367  6624 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 19:50:58.863  6367  6624 D BluetoothAdapterProperties: Setting state to 12
08-03 19:50:58.863  6367  6624 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 19:50:58.863  6367  6628 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 19:50:58.864  6367  6628 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 19:50:58.855  6733  6733 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:58.855  6733  6733 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:58.867  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:50:58.867  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 19:50:58.867  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-03 19:50:58.869  6367  6681 D bt_hci_bdroid: Used up Tx Cmd credits
,08-03 19:50:58.870  6367  6727 E bt_mct  : hci lib postload completed
08-03 19:50:58.872  6367  6624 I BluetoothAdapterState: Entering On State
08-03 19:50:58.872  1837  2423 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:58.872  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:58.875  6367  6624 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 19:50:58.875  6367  6624 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 19:50:58.876  6367  6624 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-03 19:50:58.877  6367  6624 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 19:50:58.877  6367  6679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:50:58.877  6367  6679 W bt-smp  : Plain text(LSB ~ MSB) = 86 94 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:50:58.877  6367  6679 W bt-smp  : Encrypted text(LSB ~ MSB) = 40 be a4 be 4e 47 11 24 95 97 b9 49 b8 33 44 42 
08-03 19:50:58.877  6367  6679 W bt-btm  : Stopping oneshot timer
08-03 19:50:58.882  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:50:58.888  1837  1837 D BluetoothHeadset: Proxy object connected
08-03 19:50:58.888  1837  2686 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:50:58.890  6367  6628 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:50:58.890  6367  6628 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 19:50:58.892  1837  1837 D BluetoothHeadset: Proxy object connected
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:50:58.892  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:50:58.893  6216  6236 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 19:50:58.894  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:50:58.903  6216  6236 D BluetoothPan: onBluetoothStateChange on: true
08-03 19:50:58.903  6216  6236 D BluetoothPan: onBluetoothStateChange call bindService
08-03 19:50:58.903  6216  6216 D BluetoothInputDevice: Proxy object connected
08-03 19:50:58.903  6216  6216 D HidProfile: Bluetooth service connected
08-03 19:50:58.906  6367  6679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:50:58.906  6367  6679 W bt-smp  : Plain text(LSB ~ MSB) = f6 e6 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:50:58.906  6367  6679 W bt-smp  : Encrypted text(LSB ~ MSB) = b5 c9 f0 de 22 d0 3f f3 c3 44 6a 8e ec 9f 68 65 
08-03 19:50:58.906  6367  6679 W bt-btm  : Stopping oneshot timer
08-03 19:50:58.908  6216  6216 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 19:50:58.908  6216  6216 D PanProfile: Bluetooth service connected
08-03 19:50:58.910  1041  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:50:58.911  1041  1041 D BluetoothHeadset: Proxy object connected
,08-03 19:50:58.912  1837  4360 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:50:58.914  1837  1837 D BluetoothHeadset: Proxy object connected
08-03 19:50:58.915  6216  6237 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 19:50:58.918  1041  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 19:50:58.919  6216  6216 D BluetoothMap: Proxy object connected
08-03 19:50:58.919  6216  6216 D MapProfile: Bluetooth service connected
08-03 19:50:58.919  6216  6216 D BluetoothMap: getConnectedDevices()
08-03 19:50:58.920  6367  6383 V BluetoothMapService: getConnectedDevices()
08-03 19:50:58.922  6367  6624 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-03 19:50:58.923  6216  6236 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 19:50:58.926  6367  6679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:50:58.926  1041  1041 D BluetoothA2dp: Proxy object connected
08-03 19:50:58.926  6367  6679 W bt-smp  : Plain text(LSB ~ MSB) = 26 5a 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:50:58.926  6367  6679 W bt-smp  : Encrypted text(LSB ~ MSB) = ee 67 e6 bd e6 78 5b da f9 dc 6f 1b 79 75 18 65 
08-03 19:50:58.926  6367  6679 W bt-btm  : Stopping oneshot timer
08-03 19:50:58.934  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 19:50:58.935  1041  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 19:50:58.936  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 19:50:58.937  6740  6740 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-03 19:50:58.939  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:58.940  1926  2111 D LGBluetoothAPIService: Message: 1
08-03 19:50:58.940  1926  2111 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 19:50:58.940  6367  6679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:50:58.940  6367  6679 W bt-smp  : Plain text(LSB ~ MSB) = ac 45 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:50:58.940  6367  6679 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 00 23 0a ab db 48 e5 52 8e c1 aa dd b6 90 46 
08-03 19:50:58.940  6367  6679 W bt-btm  : Stopping oneshot timer
08-03 19:50:58.942  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:50:58.943  1041  1119 D BluetoothManagerService: Message: 40
08-03 19:50:58.943  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 19:50:58.945  1926  2111 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-03 19:50:58.947  5955  5955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 19:50:58.951  6367  6367 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:58.951  6367  6367 D BluetoothMapService: STATE_ON
08-03 19:50:58.951  6367  6679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:50:58.951  6367  6679 W bt-smp  : Plain text(LSB ~ MSB) = 6f 69 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-03 19:50:58.951  6367  6679 W bt-smp  : Encrypted text(LSB ~ MSB) = 57 a8 f1 2d 88 4b 04 d2 25 c9 b3 06 6f 32 9b 61 
08-03 19:50:58.951  6367  6679 W bt-btm  : Stopping oneshot timer
08-03 19:50:58.952  6216  6216 D LocalBluetoothProfileManager: Adding local A2DP profile
08-03 19:50:58.953  1041  1119 D BluetoothManagerService: Message: 30
08-03 19:50:58.954  6216  6216 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 19:50:58.956  1041  1119 D BluetoothManagerService: Message: 30
08-03 19:50:58.957  6367  6367 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 19:50:58.958  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:58.959  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:58.959  6367  6367 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 19:50:58.960  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 19:50:58.960  1926  2111 D LGBluetoothAPIService: Message: 100
08-03 19:50:58.960  1926  2111 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 19:50:58.961  6367  6367 V BluetoothMapService: Handler(): got msg=1
08-03 19:50:58.961  6367  6367 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 19:50:58.961  6216  6216 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 19:50:58.962  6367  6747 D BluetoothMapMasInstance: MAS initSocket()
08-03 19:50:58.963  6367  6747 D BluetoothMapMasInstance:   masId = 00
08-03 19:50:58.963  6367  6747 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 19:50:58.963  6367  6747 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 19:50:58.963  6367  6747 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 19:50:58.964  1041  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:58.964  6216  6216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 19:50:58.965  6367  6747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:50:58.966  6367  6747 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 19:50:58.966  6216  6216 D BluetoothA2dp: Proxy object connected
08-03 19:50:58.966  6367  6747 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 19:50:58.966  6367  6747 D BluetoothMapMasInstance: Accepting socket connection...
08-03 19:50:58.966  6216  6216 D A2dpProfile: Bluetooth service connected
08-03 19:50:58.968  6367  6628 D BluetoothAdapterProperties: Scan Mode:21
08-03 19:50:58.968  6367  6628 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-03 19:50:58.969  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:58.970  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:50:58.971  6216  6216 D BluetoothHeadset: Proxy object connected
08-03 19:50:58.972  6216  6216 D HeadsetProfile: Bluetooth service connected
,08-03 19:50:58.976  6216  6216 D DockEventReceiver: finishStartingService: stopping service
08-03 19:50:58.979  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:58.979  6367  6367 V BluetoothPbapService: Pbap Service onCreate
08-03 19:50:58.979  6367  6367 V BluetoothPbapService: Starting PBAP service
08-03 19:50:58.980  6367  6367 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 19:50:58.981  6367  6367 V BluetoothPbapService: Pbap Service onBind
08-03 19:50:58.981  6216  6216 D BluetoothPbap: Proxy object connected
08-03 19:50:58.981  6367  6367 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:58.981  6367  6367 V BluetoothPbapService: state: 12
08-03 19:50:58.982  6367  6367 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:50:58.982  6367  6367 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:58.982  6216  6216 D PbapServerProfile: Bluetooth service connected
08-03 19:50:58.982  6367  6367 V BluetoothPbapReceiver: ***********state = 12
08-03 19:50:58.983  6367  6367 V BluetoothPbapService: Handler(): got msg=1
,08-03 19:50:58.986  6367  6367 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 19:50:58.988  6367  6750 V BluetoothPbapService: Pbap Service initSocket
08-03 19:50:58.988  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:50:58.988  2146  2146 D c       : Getting all permits...
08-03 19:50:58.988  2146  2146 D a       : Opening database...
08-03 19:50:58.993  2146  2146 D a       : Opening database auth.proximity.permit_store...
08-03 19:50:58.993  2146  2146 D a       : Closing database...
08-03 19:50:59.032  1041  1560 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6751 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-03 19:50:59.032  1041  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:59.033  6367  6750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:50:59.034  1041  1560 I ActivityManager: Killing 5991:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-03 19:50:59.148  1041  1907 W libprocessgroup: failed to open /acct/uid_10080/pid_5991/cgroup.procs: No such file or directory
,08-03 19:50:59.168  6367  6750 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 19:50:59.169  6367  6750 V BluetoothPbapService: Succeed to create listening socket 
08-03 19:50:59.169  6367  6750 V BluetoothPbapService: Accepting socket connection...
,08-03 19:50:59.184  6216  6216 D BluetoothPermissionRequest: onReceive
,08-03 19:50:59.189  6216  6216 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-03 19:50:59.192  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:50:59.198  6367  6367 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 19:50:59.201  6367  6367 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-03 19:50:59.211  6367  6367 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-03 19:50:59.224  6751  6751 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-03 19:50:59.227  6751  6751 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-03 19:50:59.233  6751  6751 V DrmService: Service onCreate
08-03 19:50:59.234  6751  6751 D DrmService: Received new request = 2
,08-03 19:50:59.238  6751  6771 I DrmSntpClient: Start Sync process
08-03 19:50:59.238  6751  6771 D DrmSntpClient: Server : 0
08-03 19:50:59.247  6367  6367 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 19:50:59.247  6367  6367 V BtOppService: onCreate
,08-03 19:50:59.252  6367  6367 V BluetoothOppNotification: send message
08-03 19:50:59.268  6367  6775 V BtOppService: Deleted complete outbound shares, number =  0
,08-03 19:50:59.272  6367  6775 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 19:50:59.273  6367  6775 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 19:50:59.275  6367  6775 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16590e6d on behalf of 
08-03 19:50:59.280  1041  1058 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6776 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:50:59.283  6367  6367 V BtOppService: Starting RfcommListener
,08-03 19:50:59.285  6751  6771 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-03 19:50:59.285  6751  6751 D DrmService: Completed !! request = 2
08-03 19:50:59.285  6751  6751 D DrmService: Request count = 0
08-03 19:50:59.288  6367  6367 D BluetoothOppPreference: Dumping Names:  
08-03 19:50:59.288  6367  6367 D BluetoothOppPreference: {}
08-03 19:50:59.288  6367  6367 D BluetoothOppPreference: Dumping Channels:  
08-03 19:50:59.288  6367  6367 D BluetoothOppPreference: {}
08-03 19:50:59.288  6751  6751 V DrmService: Service onDestroy
08-03 19:50:59.289  6367  6367 V BtOppService: onStartCommand
08-03 19:50:59.290  1041  1679 I ActivityManager: Killing 6024:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-03 19:50:59.293  6367  6788 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:50:59.293  6367  6788 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 19:50:59.299  6367  6788 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c0a9333 on behalf of 
08-03 19:50:59.301  6367  6788 V BluetoothOppNotification: update too frequent, put in queue
,08-03 19:50:59.304  6367  6788 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-03 19:50:59.328  6367  6367 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:59.328  6367  6367 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-03 19:50:59.332  1041  1925 W libprocessgroup: failed to open /acct/uid_10097/pid_6024/cgroup.procs: No such file or directory
08-03 19:50:59.336  6367  6367 V BluetoothOppNotification: new notify threadi!
08-03 19:50:59.337  6367  6367 V BluetoothOppNotification: send delay message
08-03 19:50:59.337  6367  6367 V BtOppService: ContentObserver received notification
08-03 19:50:59.338  6367  6367 V BtOppService: ContentObserver received notification
08-03 19:50:59.339  6367  6367 V BtOppService: start RfcommListener
08-03 19:50:59.339  6367  6796 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 19:50:59.340  6367  6797 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:50:59.340  6367  6797 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-03 19:50:59.341  6367  6796 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25cc66f0 on behalf of 
08-03 19:50:59.342  6367  6796 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 19:50:59.342  6367  6367 V BtOppService: RfcommListener started
08-03 19:50:59.343  6367  6796 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:50:59.345  6367  6796 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d052469 on behalf of 
08-03 19:50:59.345  6367  6796 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 19:50:59.347  6367  6798 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 19:50:59.348  1041  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:59.348  6367  6797 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e7eaeee on behalf of 
08-03 19:50:59.349  6367  6798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:50:59.350  6367  6796 V BluetoothOppNotification: outbound notification was removed.
08-03 19:50:59.350  6367  6796 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 19:50:59.353  6367  6798 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,08-03 19:50:59.354  6367  6798 V BtOppRfcommListener: Started RFCOMM listener....
08-03 19:50:59.354  6367  6798 I BtOppRfcommListener: Accept thread started.
08-03 19:50:59.355  6367  6798 V BtOppRfcommListener: Accepting connection...
08-03 19:50:59.357  6367  6797 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 19:50:59.358  6367  6796 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f512f8f on behalf of 
08-03 19:50:59.359  6367  6796 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:50:59.359  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:59.359  6367  6367 V BluetoothFtpService: Ftp Service onCreate
08-03 19:50:59.359  6367  6367 I BluetoothFtpService: Ftp Service onCreate
08-03 19:50:59.359  6367  6367 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:50:59.360  6367  6367 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:59.360  6367  6367 V BluetoothFtpService: Starting Listening on sockets
08-03 19:50:59.360  6367  6367 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:50:59.360  6367  6367 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:50:59.360  6367  6367 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:50:59.360  6367  6367 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:59.360  6367  6367 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 19:50:59.360  6367  6367 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:50:59.362  6367  6796 V BluetoothOppNotification: inbound notification was removed.
08-03 19:50:59.362  6367  6367 V BluetoothFtpService: Handler(): got msg=1
08-03 19:50:59.364  6367  6367 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 19:50:59.365  6367  6367 V BluetoothFtpService: Ftp Service initSocket
08-03 19:50:59.367  1041  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:50:59.369  6367  6796 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:50:59.370  6367  6367 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:50:59.372  6367  6796 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19429e25 on behalf of 
08-03 19:50:59.373  6367  6367 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-03 19:50:59.373  6367  6367 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 19:50:59.374  6367  6799 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 19:50:59.377  6776  6776 I art     : Almond Protected OAT
08-03 19:50:59.390  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:50:59.390  6367  6367 V BluetoothSapService: Sap Service onCreate
,08-03 19:50:59.392  6367  6367 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:50:59.392  6367  6367 V BluetoothSapService: state: 12
08-03 19:50:59.392  6367  6367 V BluetoothSapService: Starting SAP server process
08-03 19:50:59.394  6367  6367 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 19:50:59.396  6367  6805 V BluetoothSapService: Sap Service initRfcommSocket
08-03 19:50:59.396  1041  1679 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:50:59.385  6804  6804 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:59.385  6804  6804 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:50:59.397  6367  6805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:50:59.398  6367  6805 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-03 19:50:59.398  6367  6805 V BluetoothSapService: Succeed to create listening socket 
08-03 19:50:59.398  6367  6805 V BluetoothSapService: Accepting socket connection...
08-03 19:50:59.408  6804  6804 V BT_SAP  : Event pipe created
08-03 19:50:59.408  6804  6804 V BT_SAP  : create_server_socket qcom.sap.server
08-03 19:50:59.408  6804  6804 V BT_SAP  : created socket fd 6
,08-03 19:50:59.433  6776  6776 D WeatherApplication: removeAccount
,08-03 19:50:59.434  6776  6776 D WeatherApplication: Account.length = 0
08-03 19:50:59.434  6776  6776 E WeatherApplication: OPERATOR:OPEN
08-03 19:50:59.439  6776  6776 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:50:59
08-03 19:50:59.442  6776  6776 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:50:59.443  6776  6776 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:50:59.444  6776  6776 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-03 19:50:59.447  6776  6776 D WeatherAncestor: connectivity changed - connection : true
,08-03 19:50:59.448  6776  6776 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-03 19:50:59.459  6776  6776 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:50:59.459  6776  6776 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:50:59.459  6776  6776 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-03 19:50:59.491  6776  6776 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:50:59.492  6776  6776 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:50:59
,08-03 19:50:59.551  1041  1679 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6808 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:50:59.553  1041  1679 I ActivityManager: Killing 6078:com.lge.eula/1000 (adj 15): empty #17
,08-03 19:50:59.607  1041  1888 W libprocessgroup: failed to open /acct/uid_1000/pid_6078/cgroup.procs: No such file or directory
,08-03 19:50:59.707   278   377 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:50:59.707   278   377 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-03 19:50:59.707   278   377 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:50:59.708  6808  6829 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 19:50:59.710   278   377 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:50:59.710   278   377 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 19:50:59.710   278   377 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:50:59.710  6808  6829 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 19:50:59.716   278   377 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:50:59.716   278   377 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 19:50:59.716   278   377 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:50:59.717  6808  6832 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 19:50:59.718   278   377 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:50:59.718   278   377 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 19:50:59.718   278   377 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:50:59.719  6808  6832 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 19:50:59.724  1041  1522 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:50:59.724  1041  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:50:59.781  1041  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-03 19:50:59.782  1041  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-03 19:50:59.977  6808  6808 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 19:50:59.993  6808  6808 I LibraryLoader: Loading: webviewchromium
,08-03 19:50:59.998  6808  6808 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 4426-4431)
08-03 19:50:59.998  6808  6808 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:51:00.001  1041  1363 D PowerManagerServiceEx: acquireWakeLockInternal: lock=845290486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
08-03 19:51:00.004  6808  6808 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {177c0624}
08-03 19:51:00.006  6808  6808 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:51:00.006  6808  6808 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 19:51:00.021  6808  6808 I BrowserStartupController: Initializing chromium process, renderers=0
,08-03 19:51:00.022  6808  6808 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:51:00.040  2573  2573 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 19:51:00.047  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 19:51:00.047  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 19:51:00.047  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 19:51:00.047  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
08-03 19:51:00.049  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 19:51:00.049  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-03 19:51:00.050  6808  6808 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 19:51:00.050  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-03 19:51:00.050  6808  6808 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-03 19:51:00.051  6808  6808 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-03 19:51:00.052  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 19:51:00.067   317  1369 V AudioPolicyService: registerClient() client 0xb10040e0, uid 10093
,08-03 19:51:00.070  6808  6853 W AudioManagerAndroid: Requires BLUETOOTH permission
08-03 19:51:00.087  6808  6808 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:51:00.087  6808  6808 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:51:00.087  6808  6808 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:51:00.087  6808  6808 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:51:00.087  6808  6808 I Adreno-EGL: Remote Branch: 
08-03 19:51:00.087  6808  6808 I Adreno-EGL: Local Patches: 
08-03 19:51:00.087  6808  6808 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:51:00.195  6808  6808 I NSApplication: Starting up...
,08-03 19:51:00.258  1041  1059 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6866 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-03 19:51:00.260  1041  1059 I ActivityManager: Killing 5837:com.android.vending/u0a44 (adj 15): empty #17
,08-03 19:51:00.329  1041  1998 W libprocessgroup: failed to open /acct/uid_10044/pid_5837/cgroup.procs: No such file or directory
,08-03 19:51:00.338  6367  6367 V BluetoothOppNotification: new notify threadi!
08-03 19:51:00.338  6367  6367 V BluetoothOppNotification: send delay message
08-03 19:51:00.340  6367  6883 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 19:51:00.342  6367  6883 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b23f7a1 on behalf of 
08-03 19:51:00.342  6367  6883 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-03 19:51:00.343  6367  6883 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:51:00.345  6367  6883 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b49adc6 on behalf of 
08-03 19:51:00.346  6367  6883 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 19:51:00.347  6367  6883 V BluetoothOppNotification: outbound notification was removed.
08-03 19:51:00.347  6367  6883 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 19:51:00.348  6367  6883 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e758187 on behalf of 
08-03 19:51:00.348  6367  6883 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:51:00.350  6367  6883 V BluetoothOppNotification: inbound notification was removed.
08-03 19:51:00.350  6367  6883 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:51:00.351  6367  6883 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ae978b4 on behalf of 
08-03 19:51:00.368  6866  6866 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:51:00.662  1041  1679 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:00.662  1041  1679 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3ff2c01f mBinding = false
,08-03 19:51:00.681  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:51:00.682  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:51:00.682  1041  1041 D Ulp_jni : JNI:system_update. Event-4
,08-03 19:51:00.685  1041  1119 D BluetoothManagerService: Message: 2
08-03 19:51:00.686  1041  1119 D BluetoothManagerService: Sending off request.
08-03 19:51:00.687  6367  6745 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 19:51:00.687  6367  6624 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 19:51:00.688  6367  6624 D BluetoothAdapterProperties: Setting state to 13
08-03 19:51:00.688  6367  6624 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 19:51:00.688  6367  6624 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 19:51:00.689  6367  6624 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 19:51:00.690  6367  6628 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:51:00.692  6367  6624 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 19:51:00.693  6367  6624 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 19:51:00.694  6367  6747 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 19:51:00.696  6367  6750 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-03 19:51:00.699  6367  6798 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:51:00.700  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 19:51:00.700  6367  6679 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 19:51:00.701  6367  6799 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:51:00.701  6367  6805 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 19:51:00.709  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 19:51:00.709  6367  6679 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-03 19:51:00.715  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:51:00.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:51:00.718  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:51:00.718  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:51:00.721  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:51:00.721  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:51:00.724  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:51:00.724  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:51:00.728  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:51:00.728  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 19:51:00.729  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 19:51:00.732  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:51:00.734  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:00.738  6367  6367 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:00.738  6367  6367 D BluetoothMapService: STATE_TURNING_OFF
08-03 19:51:00.738  6367  6367 V BluetoothMapService: Handler(): got msg=4
08-03 19:51:00.739  6367  6367 D BluetoothMapService: MAP Service closeService in
08-03 19:51:00.739  6367  6367 D BluetoothMapMasInstance: MAP Service shutdown
,08-03 19:51:00.741  6367  6367 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:51:00.741  6367  6367 V BluetoothMapService: MAP Service closeService out
08-03 19:51:00.743  6367  6367 V BtOppService: Receiver DISABLED_ACTION 
08-03 19:51:00.743  6367  6367 I BtOppRfcommListener: stopping Accept Thread
08-03 19:51:00.743  6367  6367 V BtOppRfcommListener: close mBtServerSocket
08-03 19:51:00.744  6367  6798 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 19:51:00.744  6367  6367 V BtOppRfcommListener: waiting for thread to terminate
08-03 19:51:00.744  6367  6367 V BtOppRfcommListener: done waiting for thread to terminate
08-03 19:51:00.745  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:00.752  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:51:00.760  6216  6216 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-03 19:51:00.769  6216  6216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 19:51:00.778  6367  6367 V BtOppService: onDestroy
08-03 19:51:00.784  6367  6367 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 19:51:00.784  6367  6367 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:51:00.784  6367  6367 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-03 19:51:00.784  6367  6367 V BluetoothPbapReceiver: ***********state = 13
08-03 19:51:00.787  6216  6216 D DockEventReceiver: finishStartingService: stopping service
08-03 19:51:00.788  6367  6367 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 19:51:00.791  6367  6367 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:00.791  6367  6367 V BluetoothPbapService: state: 13
08-03 19:51:00.791  6367  6367 V BluetoothPbapService: Pbap Service closeService in
08-03 19:51:00.794  6367  6367 V BluetoothPbapService: successfully stopped pbap service
08-03 19:51:00.794  6367  6367 V BluetoothPbapService: Pbap Service closeService out
08-03 19:51:00.794  6367  6367 V BluetoothPbapService: Pbap Service onDestroy
08-03 19:51:00.794  6367  6367 V BluetoothPbapService: Pbap Service closeService in
08-03 19:51:00.794  6367  6367 V BluetoothPbapService: Pbap Service closeService out
08-03 19:51:00.795  6367  6367 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 19:51:00.795  6216  6216 D BluetoothPbap: Proxy object disconnected
08-03 19:51:00.795  6216  6216 D PbapServerProfile: Bluetooth service disconnected
08-03 19:51:00.797  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:51:00.821  6216  6216 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 19:51:00.829  6216  6216 D BluetoothPermissionRequest: onReceive
08-03 19:51:00.829  6216  6216 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-03 19:51:00.834  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:51:00.838  6367  6367 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 19:51:00.838  6367  6367 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-03 19:51:00.839  6367  6367 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-03 19:51:00.842  6367  6367 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:00.842  6367  6367 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 19:51:00.843  6367  6367 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:51:00.843  6367  6367 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:00.843  6367  6367 V BluetoothFtpService: Ftp Service closeService
08-03 19:51:00.843  6367  6367 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-03 19:51:00.844  6367  6367 V BluetoothFtpService: successfully stopped ftp service
08-03 19:51:00.844  6367  6367 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:51:00.845  6367  6367 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:51:00.845  6367  6367 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:51:00.845  6367  6367 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:00.845  6367  6367 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 19:51:00.845  6367  6367 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:51:00.846  6367  6367 V BluetoothFtpService: Ftp Service onDestroy
08-03 19:51:00.846  6367  6367 V BluetoothFtpService: Ftp Service closeService
08-03 19:51:00.850  6367  6367 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:00.850  6367  6367 V BluetoothSapService: state: 13
08-03 19:51:00.850  6367  6367 V BluetoothSapService: Stopping SAP server process
08-03 19:51:00.851  6367  6367 V BluetoothSapService: Sap Service closeSapService in
08-03 19:51:00.851  6367  6367 V BluetoothSapService: Close listen Socket : 
08-03 19:51:00.851  6367  6367 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:51:00.852  6367  6367 V BluetoothSapService: Close sapd  Socket : 
,08-03 19:51:00.853  6367  6367 V BluetoothSapService: Sap Service closeSapService out
08-03 19:51:00.853  6367  6367 V BluetoothSapService: Sap Service onDestroy
08-03 19:51:00.853  6367  6367 V BluetoothSapService: Sap Service closeSapService in
08-03 19:51:00.853  6367  6367 V BluetoothSapService: Close listen Socket : 
08-03 19:51:00.853  6367  6367 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:51:00.853  6367  6367 V BluetoothSapService: Close sapd  Socket : 
08-03 19:51:00.853  6367  6367 V BluetoothSapService: Sap Service closeSapService out
,08-03 19:51:00.873  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-03 19:51:00.874  3666  3700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 19:51:00.888  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:51:00.905  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:51:00.905  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:51:00.906  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:51:00.906  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 19:51:00.909  6584  6584 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:51:00.912  6584  6584 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2df825eb
08-03 19:51:00.912  6584  6584 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:51:00.912  6584  6584 D AppUp4:CustFacade: isPhone : true
08-03 19:51:00.913  6584  6584 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:51:00.913  6584  6584 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 19:51:00.915  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:00.916  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:51:00.917  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:51:00.920  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:51:00.928  4264  6921 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:51:00.929  6609  6609 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 19:51:00.936  4264  6922 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:00.936  4264  6922 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:51:00.954  3339  3339 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-03 19:51:00.954  3339  3339 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:00.954  3339  3339 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 19:51:00.958  6609  6924 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:00.961  6329  6927 W FormManager: Network not available. Please check & try again.
08-03 19:51:00.961  6660  6660 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:51:00.962  6660  6660 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 19:51:00.981  6329  6928 V FormManager: Network unavailable.
,08-03 19:51:00.984  6776  6776 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:51:0
08-03 19:51:00.986  6329  6928 V FormManager: Network unavailable.
08-03 19:51:00.987  6776  6776 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:51:00.987  6776  6776 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:51:00.988  6776  6776 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:51:00.988  6776  6776 D WeatherAncestor: connectivity changed - connection : true
08-03 19:51:00.988  6776  6776 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a2901e1
08-03 19:51:00.989  6776  6776 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:51:00.989  6776  6776 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:51:00.989  6776  6776 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 19:51:00.989  6776  6776 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:51:00.989  6776  6776 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:51:0
08-03 19:51:01.029  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-03 19:51:01.032  3666  3700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 19:51:01.052  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:51:01.065  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:51:01.065  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:01.065  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:51:01.065  6584  6584 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 19:51:01.067  6584  6584 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 19:51:01.071  6584  6584 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2df825eb
08-03 19:51:01.071  6584  6584 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:51:01.071  6584  6584 D AppUp4:CustFacade: isPhone : true
08-03 19:51:01.072  6584  6584 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:51:01.072  6584  6584 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 19:51:01.076  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:01.076  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:51:01.078  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:51:01.082  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:51:01.087  4264  6929 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:51:01.089  4264  6930 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:01.089  4264  6930 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:51:01.092  6609  6609 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 19:51:01.113  6609  6931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 19:51:01.118  3339  3339 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-03 19:51:01.118  3339  3339 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:01.118  3339  3339 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 19:51:01.122  6329  6933 W FormManager: Network not available. Please check & try again.
08-03 19:51:01.125  6660  6660 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:51:01.125  6660  6660 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 19:51:01.127  6329  6934 V FormManager: Network unavailable.
,08-03 19:51:01.133  6329  6934 V FormManager: Network unavailable.
08-03 19:51:01.144  6776  6776 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:51:1
08-03 19:51:01.146  6776  6776 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-03 19:51:01.146  6776  6776 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:51:01.147  6776  6776 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:51:01.147  6776  6776 D WeatherAncestor: connectivity changed - connection : true
08-03 19:51:01.147  6776  6776 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a2901e1
08-03 19:51:01.148  6776  6776 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:51:01.148  6776  6776 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:51:01.148  6776  6776 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-03 19:51:01.148  6776  6776 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:51:01.149  6776  6776 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:51:1
08-03 19:51:01.184  6289  6289 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-03 19:51:01.185  6289  6289 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1323
08-03 19:51:01.186  1041  1041 D PowerManagerServiceEx: releaseWakeLockInternal: lock=845290486 [*alarm*], flags=0x0
,08-03 19:51:01.612  6367  6628 D bt_hci_bdroid: cleanup
,08-03 19:51:01.619  6367  6681 I bt_lpm  : LPM is already off!!!
08-03 19:51:01.620  6367  6727 I bt_userial_mct: exiting userial_read_thread
08-03 19:51:01.620  6367  6727 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 19:51:01.621  6367  6679 W bt-btif : ag scb idx 1 not allocated
08-03 19:51:01.621  6367  6679 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:51:01.621  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:51:01.622  6367  6679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:51:01.622  6367  6679 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 19:51:01.627  6367  6628 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 19:51:01.628  6367  6681 I bt_vendor: hw_epilog_process
08-03 19:51:01.629  6367  6628 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 19:51:01.629  6367  6628 D bt_userial_mct: userial_close
08-03 19:51:01.629  6367  6628 E bt_userial_mct: pthread_join() FAILED result:3
08-03 19:51:01.629  6367  6628 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-03 19:51:01.647  6367  6628 D bt_hci_bdroid: set_power 0
,08-03 19:51:01.649  6367  6628 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 19:51:01.650  6367  6628 I bt_vendor: bluetooth satus is on
08-03 19:51:01.650  6367  6628 I bt_vendor: bt-vendor : resetting BT status
08-03 19:51:01.650  6367  6628 I bt_vendor: Starting hciattach daemon
08-03 19:51:01.650  6367  6628 I bt_vendor: try to set false
08-03 19:51:01.652  6367  6628 I bt_vendor: Starting hciattach daemon
08-03 19:51:01.652  6367  6628 I bt_vendor: try to set false
08-03 19:51:01.653  6367  6628 I bt_vendor: cleanup
08-03 19:51:01.654  6367  6679 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 19:51:01.654  6367  6628 I GKI_LINUX: GKI_exit_task 0 done
08-03 19:51:01.654  6367  6628 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 19:51:01.656  6367  6624 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 19:51:01.660  6367  6367 D HeadsetService: Received stop request...Stopping profile...
,08-03 19:51:01.665  6367  6367 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:51:01.665  6367  6367 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:51:01.665  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:51:01.666  6367  6632 D HeadsetStateMachine: Exit Disconnected: -1
08-03 19:51:01.670  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-03 19:51:01.670  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-03 19:51:01.670  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-03 19:51:01.670  1041  1041 D BluetoothHeadset: Proxy object disconnected
08-03 19:51:01.670  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 19:51:01.673  6367  6367 D A2dpService: Received stop request...Stopping profile...
,08-03 19:51:01.677  6367  6649 D A2dpStateMachine: Exit Disconnected: -1
08-03 19:51:01.679  6367  6624 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 19:51:01.680  6367  6367 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-03 19:51:01.681  6367  6367 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 19:51:01.681  6367  6367 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:51:01.681  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:51:01.683  1041  1041 D BluetoothA2dp: Proxy object disconnected
08-03 19:51:01.683  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 19:51:01.684  6367  6367 D HidService: Received stop request...Stopping profile...
08-03 19:51:01.684  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:51:01.688  6367  6367 D HealthService: Received stop request...Stopping profile...
,08-03 19:51:01.691  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:51:01.693  6367  6367 D HeadsetStateMachine: Unbinding service...
08-03 19:51:01.694  6367  6367 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:51:01.694  6367  6367 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:51:01.694  6367  6367 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:51:01.694  6367  6367 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:51:01.694  6367  6367 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 19:51:01.694  6367  6367 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:51:01.694  6367  6367 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:51:01.695  6367  6367 D PanService: Received stop request...Stopping profile...
08-03 19:51:01.696  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:51:01.697  6367  6367 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 19:51:01.698  6367  6367 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 19:51:01.698  6367  6367 D BtGatt.GattService: stop()
08-03 19:51:01.698  6367  6367 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 19:51:01.700  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:51:01.702  6367  6367 D BluetoothMapService: Received stop request...Stopping profile...
08-03 19:51:01.702  6367  6367 D BluetoothMapService: stop()
,08-03 19:51:01.704  6367  6367 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 19:51:01.705  6367  6367 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 19:51:01.705  6367  6367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2901e1
08-03 19:51:01.707  6367  6367 I BluetoothA2dpServiceJni: cleanupNative
08-03 19:51:01.707  6367  6651 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 19:51:01.707  6367  6367 I GKI_LINUX: GKI_exit_task 2 done
08-03 19:51:01.707  6367  6367 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 19:51:01.708  6367  6367 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 19:51:01.708  6367  6367 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 19:51:01.708  6367  6367 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 19:51:01.708  6367  6367 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:51:01.709  6367  6367 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:51:01.710  6367  6367 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 19:51:01.710  6367  6367 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 19:51:01.714  6367  6367 V BluetoothMapService: Handler(): got msg=4
08-03 19:51:01.714  6367  6367 D BluetoothMapService: MAP Service closeService in
08-03 19:51:01.714  6367  6367 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:51:01.714  6367  6367 V BluetoothMapService: MAP Service closeService out
,08-03 19:51:01.717  6367  6624 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 19:51:01.717  6367  6624 D BluetoothAdapterProperties: Setting state to 10
08-03 19:51:01.717  6367  6624 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 19:51:01.718  6367  6367 D BluetoothMapService: cleanup()
08-03 19:51:01.719  6367  6367 D BluetoothMapService: MAP Service closeService in
08-03 19:51:01.719  6367  6367 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:51:01.719  6367  6367 V BluetoothMapService: MAP Service closeService out
08-03 19:51:01.719  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:51:01.719  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 19:51:01.719  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-03 19:51:01.720  6367  6624 I BluetoothAdapterState: Entering OffState
08-03 19:51:01.720  1837  2423 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:51:01.721  6216  6237 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 19:51:01.721  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:51:01.722  6216  6237 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 19:51:01.723  6216  6237 D BluetoothPan: onBluetoothStateChange on: false
08-03 19:51:01.723  1041  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:51:01.723  6216  6237 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:51:01.724  1837  4360 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:51:01.725  6216  6237 D BluetoothMap: onBluetoothStateChange: up=false
08-03 19:51:01.725  1041  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 19:51:01.727  6216  6237 D BluetoothPbap: onBluetoothStateChange: up=false
,08-03 19:51:01.730  1041  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 19:51:01.730  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 19:51:01.732  1041  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 19:51:01.732  1041  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 19:51:01.732  1041  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3ff2c01f mBinding = false
08-03 19:51:01.732  1041  1119 D BluetoothManagerService: Sending unbind request.
08-03 19:51:01.737  6367  6628 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 19:51:01.737  6367  6367 I GKI_LINUX: GKI_exit_task 1 done
08-03 19:51:01.737  6367  6367 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 19:51:01.738  6367  6367 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 19:51:01.738  6367  6367 I art     : --- WEIRD: removing null entry 248
08-03 19:51:01.738  6367  6367 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-03 19:51:01.738  6367  6367 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 19:51:01.740  6367  6367 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-03 19:51:01.743  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 19:51:01.745  6367  6367 I art     : System.exit called, status: 0
08-03 19:51:01.745  6367  6367 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 19:51:01.763   317  2163 V AudioFlinger: 6367 died, releasing its sessions
08-03 19:51:01.763   317  2163 V AudioFlinger:  pid 1837 @ 0
08-03 19:51:01.763   317  2163 V AudioFlinger:  pid 3339 @ 1
08-03 19:51:01.763   317  2163 V AudioFlinger:  pid 3339 @ 2
,08-03 19:51:01.767  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-03 19:51:01.767  1926  2111 D LGBluetoothAPIService: Message: 101
08-03 19:51:01.767  1926  2111 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-03 19:51:01.767  1926  2111 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-03 19:51:01.767  1926  2111 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-03 19:51:01.769  6216  6216 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-03 19:51:01.777  1041  2027 I ActivityManager: Process com.android.bluetooth (pid 6367) has died
08-03 19:51:01.777  1041  2027 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-03 19:51:01.777  1041  2027 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-03 19:51:01.785  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-03 19:51:01.786  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:51:01.788  1926  2111 D LGBluetoothAPIService: Message: 2
08-03 19:51:01.788  1926  2111 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-03 19:51:01.790  6216  6216 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 19:51:01.790  6216  6216 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 19:51:01.794  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:51:01.800  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:01.807  6216  6216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 19:51:01.813  1587  1587 D BluetoothAdapter: 723473891: getState() :  mService = null. Returning STATE_OFF
08-03 19:51:01.813  1587  1587 D BluetoothAdapter: 723473891: getState() :  mService = null. Returning STATE_OFF
08-03 19:51:01.860  1041  1888 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6965 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 19:51:01.862  6216  6216 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:51:01.913  6965  6965 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-03 19:51:01.914  6965  6965 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:51:01.914  6965  6965 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 19:51:01.915  6965  6965 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-03 19:51:01.952  6965  6965 D BluetoothAdapterApp: Loading JNI Library
,08-03 19:51:01.990  6965  6965 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@9f426a9 Instance Count = 1
,08-03 19:51:01.996  6965  6965 D BluetoothAdapterApp: onCreate
08-03 19:51:02.022  6965  6965 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 19:51:02.022  6965  6965 D ProfileConfigQcom: Adding HeadsetService
,08-03 19:51:02.022  6965  6965 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 19:51:02.022  6965  6965 D ProfileConfigQcom: Adding A2dpService
08-03 19:51:02.023  6965  6965 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 19:51:02.023  6965  6965 D ProfileConfigQcom: Adding HidService
08-03 19:51:02.023  6965  6965 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 19:51:02.023  6965  6965 D ProfileConfigQcom: Adding HealthService
08-03 19:51:02.024  6965  6965 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 19:51:02.025  6965  6965 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 19:51:02.025  6965  6965 D ProfileConfigQcom: Adding PanService
08-03 19:51:02.026  6965  6965 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 19:51:02.026  6965  6965 D ProfileConfigQcom: Adding GattService
08-03 19:51:02.026  6965  6965 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 19:51:02.026  6965  6965 D ProfileConfigQcom: Adding BluetoothMapService
08-03 19:51:02.027  6965  6965 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 19:51:02.028  6965  6965 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:51:02.029  6965  6965 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:02.029  6965  6965 V BluetoothPbapReceiver: ***********state = 10
08-03 19:51:02.031  6965  6965 V LGMDMManagerInternal: Create singleton instance
08-03 19:51:02.101  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:51:02.103  6965  6965 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 19:51:02.103  6965  6965 D LGBluetoothAPIServer: [BTUI] onBind()
,08-03 19:51:02.109  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 19:51:02.109  1926  2111 D LGBluetoothAPIService: Message: 100
08-03 19:51:02.109  1926  2111 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 19:51:02.122  6216  6216 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-03 19:51:02.129  6216  6216 D BluetoothPermissionRequest: onReceive
08-03 19:51:02.132  6216  6216 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 19:51:02.132  6216  6216 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 19:51:02.137  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-03 19:51:02.149  6965  6965 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-03 19:51:02.154  6965  6965 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-03 19:51:02.157  6965  6965 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:51:02.157  6965  6965 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:51:02.157  6965  6965 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:51:02.158  6965  6965 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:02.158  6965  6965 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-03 19:51:02.160  6306  6306 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-03 19:51:03.759  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 19:51:03.759  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:51:04.739  6808  6831 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-03 19:51:04.805  1041  1530 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-03 19:51:05.888  1041  1058 I ActivityManager: Killing 6101:com.lge.bnr/1000 (adj 15): empty #17
,08-03 19:51:05.920  1041  1943 W libprocessgroup: failed to open /acct/uid_1000/pid_6101/cgroup.procs: No such file or directory
,08-03 19:51:06.779  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:51:06.780  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a55be0a added. We now have 6 listener(s)
08-03 19:51:06.788  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:06.791  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:06.791  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c25267b added. We now have 7 listener(s)
08-03 19:51:06.791  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:06.793  5955  6118 I System.out: IsBluetoothEnabled
08-03 19:51:06.795  1041  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:06.795  1041  1059 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-03 19:51:06.795  1041  1119 D BluetoothManagerService: Message: 2
,08-03 19:51:06.801  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:06.801  1041  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:06.801  1041  2027 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 19:51:06.814  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:51:06.815  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:51:06.815  1041  1041 D Ulp_jni : JNI:system_update. Event-4
08-03 19:51:06.815  1041  1119 D BluetoothManagerService: Message: 1
08-03 19:51:06.816  1041  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 19:51:06.840  1041  1119 D BluetoothManagerService: Message: 20
08-03 19:51:06.840  1041  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f1ee85d:true
,08-03 19:51:06.844  6965  6965 D BluetoothAdapterState: make
08-03 19:51:06.849  6965  6965 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 19:51:06.849  6965  6965 I bluedroid-qcom: init
08-03 19:51:06.851  6965  6998 I BluetoothAdapterState: Entering OffState
08-03 19:51:06.851  6965  6965 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 19:51:06.851  6965  6965 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 19:51:06.851  6965  6965 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 19:51:06.851  6965  6965 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 19:51:06.851  6965  6965 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 19:51:06.853  6965  6965 I bluedroid-qcom: get_profile_interface socket
08-03 19:51:06.853  6965  6965 I bluedroid-qcom: get_profile_interface map_client
,08-03 19:51:06.858  6965  7002 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 19:51:06.855  7001  7001 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:06.863  6965  7002 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 19:51:06.855  7001  7001 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:06.874  7001  7001 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 19:51:06.874  7001  7001 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 19:51:06.874  7001  7001 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-03 19:51:06.878  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 19:51:06.878  1041  1119 D BluetoothManagerService: Message: 40
08-03 19:51:06.878  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 19:51:06.880  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:51:06.880  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 19:51:06.880  6965  6980 I bluedroid-qcom: config_hci_snoop_log
08-03 19:51:06.881  1041  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 19:51:06.881  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-03 19:51:06.882  7001  7001 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-03 19:51:06.888  7001  7001 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 19:51:06.888  7001  7001 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-03 19:51:06.894  6965  6998 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 19:51:06.894  6965  7002 D BluetoothAdapterProperties: Name is: G3
08-03 19:51:06.895  6965  6998 D BluetoothAdapterProperties: Setting state to 11
08-03 19:51:06.895  6965  6998 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 19:51:06.896  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:51:06.896  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 19:51:06.896  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 19:51:06.898  6965  6998 I LGBluetoothServiceJni: classInitNative: succeeds
,08-03 19:51:06.911  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:06.913  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:51:06.916  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:06.917  6216  6216 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 19:51:07.068  1041  1961 I art     : Explicit concurrent mark sweep GC freed 34712(1656KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.289ms total 166.917ms
,08-03 19:51:07.074  6965  6965 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:51:07.074  6965  6965 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-03 19:51:07.074  6965  6965 V BluetoothPbapReceiver: ***********state = 11
08-03 19:51:07.078  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:51:07.079  6965  6998 D BluetoothBondStateMachine: make
08-03 19:51:07.082  6965  6998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.083  6965  6998 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 19:51:07.083  6965  7020 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 19:51:07.083  6965  6998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.083  6965  6998 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 19:51:07.083  6965  6998 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 19:51:07.087  6965  6998 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:51:07.093  6216  6216 D BluetoothPermissionRequest: onReceive
,08-03 19:51:07.094  6965  6965 D HeadsetService: Received start request. Starting profile...
08-03 19:51:07.094  6965  6965 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:51:07.095  6965  6965 D LGBluetoothHfpAdapter: Version 1.6
08-03 19:51:07.096  6965  6998 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:51:07.097  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:51:07.097  6965  6965 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 19:51:07.099  6965  6965 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:51:07.099  6965  6965 D HeadsetStateMachine: make
,08-03 19:51:07.103  6965  6998 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:51:07.109  6965  6998 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:51:07.112  6965  6998 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:51:07.116  6965  6998 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:51:07.120  6965  6998 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:51:07.129  6965  6998 V LGMDMManager: Create singleton instance
,08-03 19:51:07.135  6965  6965 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:51:07.135  6965  6965 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:51:07.136  6965  6998 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-03 19:51:07.139  6965  6965 D HeadsetStateMachine: max_hf_connections = 1
08-03 19:51:07.139  6965  6965 I bluedroid-qcom: get_profile_interface handsfree
08-03 19:51:07.140  6965  6965 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 19:51:07.141   317  1370 V AudioPolicyService: registerClient() client 0xb1004720, uid 1002
,08-03 19:51:07.142   317  1369 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:51:07.142   317  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-03 19:51:07.142   317  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:51:07.142  6965  6965 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 19:51:07.142   317   317 V AudioFlinger: registerClient() client 0xb55815f8, pid 6965
08-03 19:51:07.143   317  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:51:07.143   317  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:51:07.143  1041  1888 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:51:07.143  1041  1888 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:51:07.143  6965  6980 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:51:07.143  1837  4354 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:51:07.143  1837  4354 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:51:07.143  1587  3092 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:51:07.144   317  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:51:07.144  1587  3092 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:51:07.144   317  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:51:07.144  3339  3354 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:51:07.144  1587  3092 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:51:07.144  3339  3354 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:51:07.144  1587  3092 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:51:07.144  3339  3354 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:51:07.144  3339  3354 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:51:07.144  6965  6980 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 19:51:07.144  6965  6980 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:51:07.144  6965  6980 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 19:51:07.144  1041  1889 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:51:07.144  1041  1889 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:51:07.144  6965  6965 V ToneGenerator: Create Track: 0xb4928080
,08-03 19:51:07.144  6965  6965 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 19:51:07.144  6965  6965 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 19:51:07.144  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:51:07.144  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:51:07.144   317  2163 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:51:07.144   317  2163 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:51:07.144   317  2163 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:51:07.144   317  2163 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:51:07.145   317  1370 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 19:51:07.145   317  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:51:07.145   317  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 19:51:07.145   317  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:51:07.145   317  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:51:07.145  6965  6965 V AudioSystem: getLatency() output 2, latency 50
,08-03 19:51:07.145  6965  6965 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 19:51:07.145  6965  6965 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 19:51:07.145   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:51:07.145   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:51:07.145   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:51:07.145   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:51:07.145   317   317 V AudioFlinger: createTrack() lSessionId: 23
08-03 19:51:07.146  6965  6965 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 19:51:07.146   317   317 V AudioFlinger: acquiring 23 from 6965, for 6965
08-03 19:51:07.146   317   317 V AudioFlinger:  added new entry for 23
08-03 19:51:07.147  6965  6965 V ToneGenerator: ToneGenerator INIT OK, time: 171580
08-03 19:51:07.147  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.148  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.148  6965  7021 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 19:51:07.148  6965  7021 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:51:07.149  6965  7021 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:51:07.149  6965  7021 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 19:51:07.149   317  2162 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6965
08-03 19:51:07.150  6965  6965 D A2dpService: Received start request. Starting profile...
08-03 19:51:07.150   317  2162 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 19:51:07.150   317  2162 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 19:51:07.150   317  2162 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 19:51:07.150   317  2162 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 19:51:07.150   317  2162 V voice   : voice_set_parameters: exit with code(0)
08-03 19:51:07.150   317  2162 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 19:51:07.150   317  2162 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 19:51:07.150   317  2162 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 19:51:07.150   317  2162 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 19:51:07.150   317  2162 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 19:51:07.150   317  2162 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 19:51:07.151  6965  7021 V ToneGenerator: ToneGenerator destructor
08-03 19:51:07.151  6965  7021 V ToneGenerator: stopTone
08-03 19:51:07.151  6965  7021 V ToneGenerator: Delete Track: 0xb4928080
08-03 19:51:07.151  6965  7021 V AudioTrack: ~AudioTrack, releasing session id from 6965 on behalf of 6965
08-03 19:51:07.151   317  1369 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 19:51:07.151   317  1369 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 19:51:07.151   317  1273 V AudioPolicyService: AudioCommandThread() waking up
08-03 19:51:07.151   317  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 19:51:07.151   317  1273 V AudioPolicyManager: releaseOutput() 2
08-03 19:51:07.151   317  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 19:51:07.151   317   317 V AudioFlinger: releasing 23 from 6965 for 6965
08-03 19:51:07.151   317  1369 V AudioFlinger: PlaybackThread::Track destructor
08-03 19:5,1:07.151   317   317 V AudioFlinger:  decremented refcount to 0
08-03 19:51:07.151   317  1369 V AudioFlinger: removeClient_l() pid 6965, calling pid 317
08-03 19:51:07.151   317   317 V AudioFlinger: purging stale effects
08-03 19:51:07.151  6965  6965 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 19:51:07.154  6965  6965 V Avrcp   : make
08-03 19:51:07.154  1041  2027 W Process : Unable to open /proc/7022/status
08-03 19:51:07.155  6965  6965 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 19:51:07.155  6965  6965 I bluedroid-qcom: get_profile_interface avrcp
,08-03 19:51:07.174  6965  6965 V AudioManager: registerRemoteController: size of Media player list: 0
,08-03 19:51:07.177  6965  6965 E AudioManager: No RCC entry present to update
08-03 19:51:07.178  6965  6965 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 19:51:07.182  6965  6965 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 19:51:07.183  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 19:51:07.183  6965  6965 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 19:51:07.189  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-03 19:51:07.316  1041  1998 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:51:07.316  1041  1998 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:51:07.474  1041  1763 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-03 19:51:07.487  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-03 19:51:07.493  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:51:07.494  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 19:51:07.495  6965  6965 I BluetoothA2dpServiceJni: classInitNative
08-03 19:51:07.495  6965  6965 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:51:07.495  6965  6965 D A2dpStateMachine: make
08-03 19:51:07.497  6965  6965 I bluedroid-qcom: get_profile_interface a2dp
08-03 19:51:07.497  6965  7034 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 19:51:07.499  6965  6965 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:51:07.499  6965  6965 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 19:51:07.500  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.501  6965  6965 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 19:51:07.503  6965  7033 D A2dpStateMachine: Enter Disconnected: -2
,08-03 19:51:07.505  6965  6965 D HidService: Received start request. Starting profile...
08-03 19:51:07.505  6965  6965 I bluedroid-qcom: get_profile_interface hidhost
08-03 19:51:07.505  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.506  6965  6965 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:51:07.507  6965  6965 D HealthService: Received start request. Starting profile...
08-03 19:51:07.509  6965  6965 I bluedroid-qcom: get_profile_interface health
08-03 19:51:07.510  6965  6965 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:51:07.510  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.511  6965  6965 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 19:51:07.513  6965  6965 D PanService: Received start request. Starting profile...
08-03 19:51:07.513  6965  6965 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 19:51:07.513  6965  6965 I bluedroid-qcom: get_profile_interface pan
08-03 19:51:07.519  6965  6965 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 19:51:07.519  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
,08-03 19:51:07.521  6965  6965 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 19:51:07.528  6965  6965 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 19:51:07.529  6965  6965 D BtGatt.GattService: Received start request. Starting profile...
08-03 19:51:07.529  6965  6965 D BtGatt.GattService: start()
08-03 19:51:07.529  6965  6965 I bluedroid-qcom: get_profile_interface gatt
08-03 19:51:07.529  6965  6965 D BtGatt.AdvertiseManager: advertise manager created
08-03 19:51:07.535  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
,08-03 19:51:07.536  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.537  6965  6965 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 19:51:07.538  6965  6965 V BluetoothMapService: BluetoothMapBinder()
08-03 19:51:07.539  6965  6965 D BluetoothMapService: Received start request. Starting profile...
08-03 19:51:07.539  6965  6965 D BluetoothMapService: start()
08-03 19:51:07.543  6965  6965 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 19:51:07.543  6965  6965 D BluetoothMapEmailAppObserver: createReceiver()
08-03 19:51:07.544  6965  6965 D BluetoothMapEmailAppObserver: initObservers()
08-03 19:51:07.544  6965  6965 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-03 19:51:07.554  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:07.555  6965  6965 D HeadsetStateMachine: Proxy object connected
08-03 19:51:07.556  6965  6965 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 19:51:07.556  6965  6965 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-03 19:51:07.560  6965  6965 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 19:51:07.561  6965  7021 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 19:51:07.562  6965  7021 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 19:51:07.562  6965  7021 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 19:51:07.565  6965  6965 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:07.569  6965  6965 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:51:07.572  6965  6965 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 19:51:07.576  6965  6965 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:51:07.576  6965  6965 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 19:51:07.579  6965  6965 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:51:07.583  6965  6965 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-03 19:51:07.583  6965  6965 V BluetoothMapService: Handler(): got msg=1
08-03 19:51:07.584  6965  6998 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 19:51:07.584  6965  6998 I bluedroid-qcom: enable
08-03 19:51:07.584  6965  6998 I bt_hci_bdroid: init
08-03 19:51:07.586  6965  6998 I bt_vendor: bt-vendor : init
08-03 19:51:07.586  6965  6998 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 19:51:07.586  6965  7041 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 19:51:07.586  6965  6998 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 19:51:07.586  6965  6998 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 19:51:07.586  6965  6998 D bt_userial_mct: userial_init
08-03 19:51:07.587  6965  6965 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:51:07.587  6965  7041 I bt-btu  : btu_task pending for preload complete event
08-03 19:51:07.587  6965  6965 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:51:07.587  6965  6965 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:51:07.587  6965  6965 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:07.587  6965  6998 D bt_hci_bdroid: set_power 1
08-03 19:51:07.587  6965  6965 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 19:51:07.587  6965  6998 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 19:51:07.587  6965  6998 I bt_vendor: Starting hciattach daemon
08-03 19:51:07.587  6965  6998 I bt_vendor: try to set true
08-03 19:51:07.585  7044  7044 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:07.585  7044  7044 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:07.617  7045  7045 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 19:51:07.708  7051  7051 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 19:51:07.721  7052  7052 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 19:51:07.750  7054  7054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:51:07.768  7055  7055 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-03 19:51:07.781  7056  7056 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:51:07.793  7057  7057 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-03 19:51:07.818  7059  7059 I libmdmdetect: ESOC framework not supported
,08-03 19:51:07.819  7059  7059 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-03 19:51:07.827  7059  7059 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-03 19:51:07.827  7059  7059 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 19:51:07.827  7059  7059 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 19:51:07.827  7059  7059 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 19:51:07.827  7059  7059 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 19:51:07.827  7059  7059 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 19:51:07.827  7059  7059 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 19:51:07.868  7059  7060 E QC-QMI  : qmi_client [7059] 15: failed to locate client data
08-03 19:51:07.869   482   482 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 19:51:07.869   482   482 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-03 19:51:07.907  7061  7061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 19:51:07.920  7062  7062 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-03 19:51:07.941  6965  6998 I bt_vendor: bluetooth satus is on
08-03 19:51:07.941  6965  6998 D bt_hci_bdroid: preload
,08-03 19:51:07.942  6965  7043 D bt_userial_mct: userial_open(port:0)
08-03 19:51:07.942  6965  7043 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-03 19:51:07.946  6965  7043 I bt_vendor: Done intiailizing UART
08-03 19:51:07.947  6965  7043 I bt_vendor: Done intiailizing UART
08-03 19:51:07.947  6965  7043 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 19:51:07.947  6965  7043 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-03 19:51:07.947  6965  7041 I bt-btu  : btu_task received preload complete event
08-03 19:51:07.948  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-03 19:51:07.948  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 19:51:07.950  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-03 19:51:07.952  6965  7064 D bt_userial_mct: Entering userial_read_thread()
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_HCI
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 19:51:07.953  6965  7041 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 19:51:08.046  6965  7041 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-03 19:51:08.047  6965  7041 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c2061 
08-03 19:51:08.047  6965  7041 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c2061 
,08-03 19:51:08.105  6965  7002 E bt-btif : Calling BTA_HhEnable
,08-03 19:51:08.105  6965  7002 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-03 19:51:08.112  6965  7002 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 19:51:08.117  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 19:51:08.117  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 19:51:08.117  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 19:51:08.117  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 19:51:08.118  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 19:51:08.118  6965  7002 D BluetoothAdapterProperties: Name is: G3
08-03 19:51:08.120  6965  7002 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:51:08.120  6965  7002 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:51:08.121  6965  7002 D bt_hci_bdroid: postload
08-03 19:51:08.121  6965  7043 D bt_hci_bdroid: Used up Tx Cmd credits
,08-03 19:51:08.124  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:51:08.125  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 19:51:08.128  6965  7002 D bte_conf: Device ID record 1 : primary
08-03 19:51:08.128  6965  7002 D bte_conf:   vendorId            = 00c4
08-03 19:51:08.128  6965  7002 D bte_conf:   vendorIdSource      = 0001
08-03 19:51:08.128  6965  7002 D bte_conf:   product             = 13a1
08-03 19:51:08.128  6965  7002 D bte_conf:   version             = 1000
08-03 19:51:08.128  6965  7002 D bte_conf:   clientExecutableURL = 
08-03 19:51:08.128  6965  7002 D bte_conf:   serviceDescription  = 
08-03 19:51:08.128  6965  7002 D bte_conf:   documentationURL    = 
08-03 19:51:08.128  6965  7002 D bte_conf: bte_load_did_conf no section named DID2.
08-03 19:51:08.129  6965  7041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 19:51:08.129  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:08.132  6965  6998 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 19:51:08.132  6965  6998 D BluetoothAdapterProperties: ScanMode =  20
08-03 19:51:08.132  6965  6998 D BluetoothAdapterProperties: State =  11
08-03 19:51:08.132  6965  6998 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 19:51:08.132  6965  6998 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 19:51:08.132  6965  6998 D BluetoothAdapterProperties: Setting state to 12
08-03 19:51:08.132  6965  6998 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 19:51:08.134  6965  7002 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 19:51:08.135  6965  7002 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-03 19:51:08.135  7069  7069 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:08.135  7069  7069 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:08.147  1041  1119 D BluetoothManagerService: Message: 60
08-03 19:51:08.147  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 19:51:08.147  1041  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-03 19:51:08.150  6965  7043 D bt_hci_bdroid: Used up Tx Cmd credits
,08-03 19:51:08.153  6965  6998 I BluetoothAdapterState: Entering On State
08-03 19:51:08.154  1837  4359 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:51:08.154  6965  7043 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:51:08.158  6965  7043 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:51:08.159  6965  7064 E bt_mct  : hci lib postload completed
08-03 19:51:08.167  6965  7041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:51:08.167  6965  7041 W bt-smp  : Plain text(LSB ~ MSB) = e8 49 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:51:08.167  6965  7041 W bt-smp  : Encrypted text(LSB ~ MSB) = aa a8 cc b8 a1 a1 ec 24 17 9c 35 a1 4f 95 46 1b 
,08-03 19:51:08.169  6965  7041 W bt-btm  : Stopping oneshot timer
08-03 19:51:08.189  6965  6998 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 19:51:08.189  6965  6998 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 19:51:08.189  6965  6998 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-03 19:51:08.193  6965  6998 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 19:51:08.204  6965  6998 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-03 19:51:08.207  6965  7002 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:51:08.207  6965  7002 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 19:51:08.208  1837  1837 D BluetoothHeadset: Proxy object connected
08-03 19:51:08.211  6216  6737 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 19:51:08.239  7074  7074 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-03 19:51:08.244  6965  7041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:51:08.244  6965  7041 W bt-smp  : Plain text(LSB ~ MSB) = b9 f2 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:51:08.244  6965  7041 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 ae b8 08 36 b7 9a 37 f0 36 76 50 d1 b4 8d b9 
08-03 19:51:08.244  6965  7041 W bt-btm  : Stopping oneshot timer
08-03 19:51:08.256  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:51:08.259  6216  6216 D BluetoothA2dp: Proxy object connected
08-03 19:51:08.259  6216  6216 D A2dpProfile: Bluetooth service connected
08-03 19:51:08.260  1837  1837 D BluetoothHeadset: Proxy object connected
08-03 19:51:08.260  6216  6236 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 19:51:08.263  6216  6737 D BluetoothPan: onBluetoothStateChange on: true
08-03 19:51:08.263  6216  6737 D BluetoothPan: onBluetoothStateChange call bindService
08-03 19:51:08.264  6216  6216 D BluetoothInputDevice: Proxy object connected
08-03 19:51:08.264  6216  6216 D HidProfile: Bluetooth service connected
08-03 19:51:08.265  1041  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:51:08.266  1041  1041 D BluetoothHeadset: Proxy object connected
08-03 19:51:08.267  6965  7041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:51:08.267  6965  7041 W bt-smp  : Plain text(LSB ~ MSB) = 54 20 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:51:08.268  6216  6237 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:51:08.268  6965  7041 W bt-smp  : Encrypted text(LSB ~ MSB) = 34 8e 9d 92 89 00 81 8c 92 02 47 a5 f0 b8 a8 54 
08-03 19:51:08.268  6965  7041 W bt-btm  : Stopping oneshot timer
08-03 19:51:08.268  6216  6216 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 19:51:08.268  6216  6216 D PanProfile: Bluetooth service connected
,08-03 19:51:08.272  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:51:08.272  6216  6216 D BluetoothHeadset: Proxy object connected
08-03 19:51:08.272  6216  6216 D HeadsetProfile: Bluetooth service connected
08-03 19:51:08.274  1837  1837 D BluetoothHeadset: Proxy object connected
08-03 19:51:08.275  6216  6236 D BluetoothMap: onBluetoothStateChange: up=true
08-03 19:51:08.277  1041  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 19:51:08.278  6216  6216 D BluetoothMap: Proxy object connected
08-03 19:51:08.278  6216  6216 D MapProfile: Bluetooth service connected
08-03 19:51:08.278  6216  6216 D BluetoothMap: getConnectedDevices()
08-03 19:51:08.278  1041  1041 D BluetoothA2dp: Proxy object connected
08-03 19:51:08.278  6216  6737 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 19:51:08.280  6965  6981 V BluetoothMapService: getConnectedDevices()
08-03 19:51:08.280  6965  7041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:51:08.280  6965  7041 W bt-smp  : Plain text(LSB ~ MSB) = 19 c2 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:51:08.281  6965  7041 W bt-smp  : Encrypted text(LSB ~ MSB) = e2 6a b5 0c 13 ff 31 9c d0 a9 01 04 7f 4f b1 84 
08-03 19:51:08.281  6965  7041 W bt-btm  : Stopping oneshot timer
08-03 19:51:08.281  1041  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 19:51:08.281  1041  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-03 19:51:08.285  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.285  1926  2111 D LGBluetoothAPIService: Message: 1
08-03 19:51:08.285  1926  2111 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 19:51:08.285  1926  2111 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-03 19:51:08.285  1926  2111 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-03 19:51:08.286  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:51:08.289  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:51:08.290  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 19:51:08.291  1041  1119 D BluetoothManagerService: Message: 40
08-03 19:51:08.291  1041  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 19:51:08.292  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:51:08.293  6965  6965 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.293  6965  6965 D BluetoothMapService: STATE_ON
08-03 19:51:08.295  6216  6216 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-03 19:51:08.298  6965  7041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:51:08.298  6965  7041 W bt-smp  : Plain text(LSB ~ MSB) = 37 97 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:51:08.298  6965  7041 W bt-smp  : Encrypted text(LSB ~ MSB) = c6 9d 8f e5 e4 e6 ef 6b 77 ee 3b 73 0f f6 d2 34 
08-03 19:51:08.298  6965  7041 W bt-btm  : Stopping oneshot timer
08-03 19:51:08.301  6216  6216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 19:51:08.311  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:08.311  6965  6965 V BluetoothPbapService: Pbap Service onCreate
08-03 19:51:08.311  6965  6965 V BluetoothPbapService: Starting PBAP service
,08-03 19:51:08.313  6965  6965 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 19:51:08.313  6216  6216 D DockEventReceiver: finishStartingService: stopping service
08-03 19:51:08.314  6965  6965 V BluetoothMapService: Handler(): got msg=1
08-03 19:51:08.314  6965  6965 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 19:51:08.315  6965  6965 V BluetoothPbapService: Pbap Service onBind
08-03 19:51:08.315  6965  7093 D BluetoothMapMasInstance: MAS initSocket()
08-03 19:51:08.316  6965  7093 D BluetoothMapMasInstance:   masId = 00
08-03 19:51:08.316  6965  7093 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 19:51:08.316  6965  7093 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 19:51:08.316  6965  7093 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 19:51:08.318  1041  1679 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:08.318  6965  6965 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.318  6965  6965 V BluetoothPbapService: state: 12
08-03 19:51:08.318  6965  6965 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:51:08.318  6965  6965 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.318  6216  6216 D BluetoothPbap: Proxy object connected
08-03 19:51:08.318  6965  6965 V BluetoothPbapReceiver: ***********state = 12
08-03 19:51:08.318  6216  6216 D PbapServerProfile: Bluetooth service connected
08-03 19:51:08.319  6965  7093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:51:08.320  6965  6965 V BluetoothPbapService: Handler(): got msg=1
08-03 19:51:08.320  6965  7093 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 19:51:08.320  6965  6965 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 19:51:08.321  6965  7093 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 19:51:08.321  6965  7093 D BluetoothMapMasInstance: Accepting socket connection...
08-03 19:51:08.321  6965  7002 D BluetoothAdapterProperties: Scan Mode:21
08-03 19:51:08.321  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:51:08.322  6965  7002 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-03 19:51:08.322  6965  7094 V BluetoothPbapService: Pbap Service initSocket
08-03 19:51:08.322  2146  2146 D c       : Getting all permits...
08-03 19:51:08.322  2146  2146 D a       : Opening database...
08-03 19:51:08.323  1041  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:08.325  2146  2146 D a       : Opening database auth.proximity.permit_store...
08-03 19:51:08.326  6965  7094 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:51:08.327  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:08.327  2146  2146 D a       : Closing database...
08-03 19:51:08.327  6965  7094 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 19:51:08.328  6965  7094 V BluetoothPbapService: Succeed to create listening socket 
08-03 19:51:08.328  6965  7094 V BluetoothPbapService: Accepting socket connection...
08-03 19:51:08.337  6216  6216 D BluetoothPermissionRequest: onReceive
,08-03 19:51:08.340  6216  6216 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-03 19:51:08.341  6216  6216 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:51:08.343  6965  6965 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 19:51:08.344  6965  6965 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-03 19:51:08.349  6965  6965 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-03 19:51:08.365  6965  6965 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-03 19:51:08.365  6965  6965 V BtOppService: onCreate
,08-03 19:51:08.368  6965  6965 V BluetoothOppNotification: send message
08-03 19:51:08.370  6965  6965 V BtOppService: Starting RfcommListener
08-03 19:51:08.373  6965  6965 D BluetoothOppPreference: Dumping Names:  
08-03 19:51:08.373  6965  6965 D BluetoothOppPreference: {}
08-03 19:51:08.373  6965  6965 D BluetoothOppPreference: Dumping Channels:  
08-03 19:51:08.373  6965  6965 D BluetoothOppPreference: {}
08-03 19:51:08.373  6965  6965 V BtOppService: onStartCommand
08-03 19:51:08.375  6965  7101 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:51:08.376  6965  6965 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.376  6965  6965 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-03 19:51:08.378  6965  6965 V BluetoothOppNotification: new notify threadi!
,08-03 19:51:08.379  6965  6965 V BluetoothOppNotification: send delay message
08-03 19:51:08.380  6965  6965 V BtOppService: start RfcommListener
08-03 19:51:08.382  6965  6965 V BtOppService: RfcommListener started
08-03 19:51:08.383  6965  7103 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 19:51:08.384  1041  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:08.384  6965  7103 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:51:08.385  6965  7103 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-03 19:51:08.386  6965  7103 V BtOppRfcommListener: Started RFCOMM listener....
08-03 19:51:08.386  6965  7103 I BtOppRfcommListener: Accept thread started.
08-03 19:51:08.386  6965  7103 V BtOppRfcommListener: Accepting connection...
08-03 19:51:08.388  6965  7102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 19:51:08.388  6965  7101 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-03 19:51:08.393  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
08-03 19:51:08.393  6965  6965 V BluetoothFtpService: Ftp Service onCreate
08-03 19:51:08.393  6965  6965 I BluetoothFtpService: Ftp Service onCreate
08-03 19:51:08.393  6965  6965 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:51:08.393  6965  6965 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.393  6965  6965 V BluetoothFtpService: Starting Listening on sockets
08-03 19:51:08.394  6965  6965 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:51:08.394  6965  6965 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:51:08.394  6965  6965 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:51:08.394  6965  6965 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.394  6965  6965 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 19:51:08.394  6965  6965 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:51:08.394  6965  7102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c0a9333 on behalf of 
08-03 19:51:08.396  6965  6965 V BluetoothFtpService: Handler(): got msg=1
08-03 19:51:08.397  6965  6965 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 19:51:08.397  6965  6965 V BluetoothFtpService: Ftp Service initSocket
08-03 19:51:08.399  6965  7101 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25cc66f0 on behalf of 
08-03 19:51:08.399  6965  7102 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 19:51:08.400  1041  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:08.401  6965  6965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:51:08.401  6965  7101 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 19:51:08.404  6965  7098 V BtOppService: Deleted complete outbound shares, number =  0
08-03 19:51:08.404  6965  6965 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-03 19:51:08.405  6965  6965 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 19:51:08.405  6965  7098 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 19:51:08.406  6965  7098 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 19:51:08.406  6965  7104 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 19:51:08.407  6965  7102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:51:08.408  6965  7098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d052469 on behalf of 
08-03 19:51:08.409  6965  7102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e7eaeee on behalf of 
08-03 19:51:08.410  6965  7102 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 19:51:08.411  6965  7102 V BluetoothOppNotification: outbound notification was removed.
08-03 19:51:08.411  6965  7102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-03 19:51:08.412  6965  7102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f512f8f on behalf of 
08-03 19:51:08.413  6965  7102 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:51:08.415  6965  7102 V BluetoothOppNotification: inbound notification was removed.
08-03 19:51:08.415  6965  7102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:51:08.416  6965  7102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9a9021c on behalf of 
08-03 19:51:08.426  6965  6965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@270e8b06
,08-03 19:51:08.426  6965  6965 V BluetoothSapService: Sap Service onCreate
08-03 19:51:08.428  6965  6965 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:51:08.428  6965  6965 V BluetoothSapService: state: 12
08-03 19:51:08.429  6965  6965 V BluetoothSapService: Starting SAP server process
08-03 19:51:08.430  6965  6965 V BtOppService: ContentObserver received notification
08-03 19:51:08.431  6965  6965 V BtOppService: ContentObserver received notification
08-03 19:51:08.431  6965  6965 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 19:51:08.425  7105  7105 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:08.425  7105  7105 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:08.432  6965  7106 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:51:08.432  6965  7106 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 19:51:08.433  6965  7106 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27522408 on behalf of 
08-03 19:51:08.433  6965  7107 V BluetoothSapService: Sap Service initRfcommSocket
08-03 19:51:08.434  6965  7106 V BluetoothOppNotification: update too frequent, put in queue
08-03 19:51:08.434  1041  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:08.434  6965  7106 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 19:51:08.435  6965  7107 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:51:08.436  6965  7107 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-03 19:51:08.436  6965  7107 V BluetoothSapService: Succeed to create listening socket 
08-03 19:51:08.436  6965  7107 V BluetoothSapService: Accepting socket connection...
08-03 19:51:08.453  7105  7105 V BT_SAP  : Event pipe created
08-03 19:51:08.453  7105  7105 V BT_SAP  : create_server_socket qcom.sap.server
08-03 19:51:08.453  7105  7105 V BT_SAP  : created socket fd 6
,08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:51:08.843  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:51:08.859  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:51:08.861  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:08.861  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bad0c98 added. We now have 8 listener(s)
08-03 19:51:08.861  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:08.865  1041  1907 D WifiServiceImplEx: setWifiEnabled: false pid=5955, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-03 19:51:08.868  1041  1907 D WifiService: setWifiEnabled: false pid=5955, uid=10118
08-03 19:51:08.868  1041  1907 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 19:51:08.873  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:08.874  1041  1925 D WifiServiceImplEx: setWifiEnabled: true pid=5955, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:51:08.875  1041  1925 D WifiService: setWifiEnabled: true pid=5955, uid=10118
08-03 19:51:08.875  1041  1925 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:51:08.894  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-03 19:51:08.894  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-03 19:51:08.894  1041  1041 D Ulp_jni : JNI:system_update. Event-4
08-03 19:51:08.896  1041  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 19:51:08.896  1041  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-03 19:51:08.899  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 19:51:08.899  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-03 19:51:08.899  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin],
08-03 19:51:08.899  1041  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
08-03 19:51:08.899  1041  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
08-03 19:51:08.899  1041  1523 E WifiHW  : unknown target_country: EU , set to default
08-03 19:51:08.899  1041  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 19:51:08.899  1041  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-03 19:51:08.899  1041  1523 I WifiUtil: gEnableBmps=1
08-03 19:51:09.381  6965  6965 V BluetoothOppNotification: new notify threadi!
08-03 19:51:09.382  6965  6965 V BluetoothOppNotification: send delay message
,08-03 19:51:09.400  6965  7126 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 19:51:09.403  6965  7126 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b23f7a1 on behalf of 
08-03 19:51:09.404  6965  7126 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 19:51:09.405  6965  7126 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:51:09.406  6965  7126 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b49adc6 on behalf of 
08-03 19:51:09.407  6965  7126 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-03 19:51:09.411  6965  7126 V BluetoothOppNotification: outbound notification was removed.
08-03 19:51:09.411  6965  7126 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 19:51:09.412  6965  7126 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e758187 on behalf of 
08-03 19:51:09.413  6965  7126 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:51:09.416  6965  7126 V BluetoothOppNotification: inbound notification was removed.
08-03 19:51:09.416  6965  7126 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:51:09.417  6965  7126 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ae978b4 on behalf of 
08-03 19:51:09.486   313   892 D SoftapController: Softap fwReload - Ok
,08-03 19:51:09.491  1041  1523 E NetdConnector: NDC Command {66 softap fwreload wlan0 STA} took too long (588ms)
08-03 19:51:09.498   313   892 D CommandListener: Setting iface cfg
08-03 19:51:09.498   313   892 D CommandListener: Trying to bring down wlan0
08-03 19:51:09.509   313   892 D CommandListener: Clearing all IP addresses on wlan0
,08-03 19:51:09.520  1041  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 19:51:09.520  1041  1119 D Tethering: InitialState.processMessage what=4
08-03 19:51:09.521  1041  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 19:51:09.526   313  7128 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-03 19:51:09.544  1041  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-03 19:51:09.544  1041  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:51:09.555  7129  7129 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 19:51:09.555  7129  7129 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:09.567  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:51:09.567  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:51:09.567  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:51:09.589  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-03 19:51:09.593  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:09.597  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 19:51:09.612  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:09.613  1041  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 19:51:09.613  1041  1523 D WifiMonitor: connecting to supplicant
,08-03 19:51:09.618  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:51:09.618  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:51:09.618  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:51:09.619  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:51:09.620  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-03 19:51:09.622  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:51:09.622  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 19:51:09.622  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:51:09.622  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:51:09.622  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:51:09.622  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 19:51:09.623  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:51:09.624  7129  7129 I wpa_supplicant: Successfully initialized wpa_supplicant
08-03 19:51:09.628  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:51:09.628  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:51:09.628  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:51:09.628  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:51:09.633  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-03 19:51:09.637  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-03 19:51:09.637  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 19:51:09.637  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:51:09.637  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:51:09.637  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:51:09.637  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:51:09.644  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:51:09.647  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:51:09.654  7129  7129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 19:51:09.654  7129  7129 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-03 19:51:09.656  6329  7148 W FormManager: Network not available. Please check & try again.
08-03 19:51:09.657  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:09.662  6329  7149 V FormManager: Network unavailable.
,08-03 19:51:09.669  6329  7149 V FormManager: Network unavailable.
08-03 19:51:09.713  7129  7129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 19:51:09.759  7129  7129 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-03 19:51:09.765  7129  7129 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-03 19:51:09.767  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 19:51:09.767  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 19:51:09.768  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:51:09.768  1041  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:51:09.769  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:09.769  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:09.769  1041  7150 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-03 19:51:09.769  1041  7150 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 19:51:09.769  1041  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:09.770  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:09.770  1041  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 19:51:09.770  1041  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 19:51:09.771  1041  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 19:51:09.771  1041  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 19:51:09.771  1041  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 19:51:09.772  1041  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:51:09.772  1041  1523 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:51:09.772  1041  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:51:09.772  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.772  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.772  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.772  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.772  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-03 19:51:09.778  1926  1926 D WfdService: Waiting for WifiP2p enabling
08-03 19:51:09.778  7129  7129 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 19:51:09.779  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:09.779  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:51:09.779  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 19:51:09.779  1041  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 19:51:09.779  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 19:51:09.779  1041  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-03 19:51:09.779  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 19:51:09.779  1041  1523 D WifiConfigStore: Loading config and enabling all networks 
08-03 19:51:09.779  1041  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 19:51:09.779  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:51:09.779  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:51:09.780  1041  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-03 19:51:09.785  1041  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:51:09.786  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:51:09.791  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 19:51:09.791  1041  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 19:51:09.792  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:51:09.800  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:51:09.802  1041  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 19:51:09.802  1041  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 19:51:09.805  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 19:51:09.807  1041  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-03 19:51:09.807  1041  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 19:51:09.807  1041  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-03 19:51:09.807  1041  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 19:51:09.808  1041  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 19:51:09.808  1041  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 19:51:09.808  1041  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 19:51:09.808  1041  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 19:51:09.808  1041  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 19:51:09.809  1041  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 19:51:09.809  1041  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 19:51:09.809  1041  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 19:51:09.810  1041  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 19:51:09.810  1041  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 19:51:09.810  1041  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 19:51:09.810  1041  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:51:09.811  1041  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 19:51:09.811  1041  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 19:51:09.811  1041  1523 D WifiNative-HAL: Setting external_sim to 1
08-03 19:51:09.811  1041  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 19:51:09.811  1926  1926 D WfdsService: Supplicant Connection state is changed : true
08-03 19:51:09.811  1926  2288 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 19:51:09.811  1926  2288 D WfdsService: Set the WFDS Monitor: true
08-03 19:51:09.811  1041  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 19:51:09.811  1926  2288 D WfdsMonitor: WfdsMonitorThread create
08-03 19:51:09.811  1041  1523 I WifiNative-HAL: startHal
08-03 19:51:09.811  1041  1523 D wifi    : setting scan oui 0xaf725360
08-03 19:51:09.811  1926  2288 D WfdsMonitor: WFDS Monitor is created and started
08-03 19:51:09.811  1926  2288 D WfdsService: WiFi: Supplicant connection re-established
08-03 19:51:09.812  1041  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:51:09.812  1041  1523 I WifiNative-HAL: startHal
08-03 19:51:09.812  1041  1523 D wifi    : setting scan oui 0xaf725360
08-03 19:51:09.812  1041  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 19:51:09.812  1041  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 19:51:09.812  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 19:51:09.812  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 19:51:09.812  1926  7155 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 19:51:09.812  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 19:51:09.813  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:51:09.813  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 19:51:09.813  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:51:09.813  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 19:51:09.813  1926  7155 E CtrlSupplicant: Succeed to open control connection
08-03 19:51:09.813  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 19:51:09.813  1926  7155 E CtrlSupplicant: Succeed to open monitor connection
08-03 19:51:09.813  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 19:51:09.813  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 19:51:09.813  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:51:09.814  1926  7155 D WfdsMonitor: Supplicant connection established
08-03 19:51:09.814  1926  2288 D WfdsService: Connected to the supplicant for wfds
08-03 19:51:09.814  62,16  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:09.814  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 19:51:09.814  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:51:09.814  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 19:51:09.814  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:51:09.815  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 19:51:09.815  7129  7129 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 19:51:09.815  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 19:51:09.815  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 19:51:09.815  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:51:09.815  1041  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-03 19:51:09.816  1041  1523 E WifiNative: : [174,237,528 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 19:51:09.816  1041  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 19:51:09.817  1041  1523 D WifiNative-wlan0: RECONNECT: returned true
08-03 19:51:09.817  1041  1523 D WifiNative-wlan0: doString: [STATUS]
08-03 19:51:09.817  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:51:09.817  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 19:51:09.817  6329  7154 V FormManager: Network unavailable.
08-03 19:51:09.817  1041  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:51:09.817  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:51:09.818  1041  1523 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:51:09.818  1041  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.818  6329  7154 V FormManager: Network unavailable.
08-03 19:51:09.819   313   892 D CommandListener: Setting iface cfg
08-03 19:51:09.819   313   892 D CommandListener: Trying to bring up p2p0
08-03 19:51:09.820  1041  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 19:51:09.820  1041  1522 D LGWifiP2pService: P2pEnablingState
08-03 19:51:09.820  1041  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.820  1041  1522 D LGWifiP2pService: P2p socket connection successful
08-03 19:51:09.820  1041  1522 D LGWifiP2pService: P2pEnabledState
08-03 19:51:09.821  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 19:51:09.821  6329  7153 W FormManager: Network not available. Please check & try again.
08-03 19:51:09.821  1926  1926 D WfdsService: WifiP2pState is changed : true
08-03 19:51:09.821  1926  2288 D WfdsService: Receive the WFDS_ENABLE Method
08-03 19:51:09.821  1926  2288 D WfdsService: Set the WFDS Monitor: true
08-03 19:51:09.821  1926  2288 D WfdsService: Connected to the supplicant for wfds
08-03 19:51:09.821  1926  2288 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 19:51:09.821  7129  7129 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 19:51:09.822  1926  2288 D WfdsService: selectPreferredScanChannel [36]
08-03 19:51:09.822  1926  2288 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 19:51:09.824  1041  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 19:51:09.825  1041  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 19:51:09.826  1041  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 19:51:09.826  1041  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 19:51:09.827  1041  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-03 19:51:09.827  1041  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 19:51:09.828  1041  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 19:51:09.828  1041  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 19:51:09.828  1041  1522 D LGWifiP2pService: before postfix = G3
08-03 19:51:09.828  1041  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 19:51:09.828  1041  1522 D WifiServerServiceExt: postfix byte check : 2
08-03 19:51:09.828  1041  1522 D LGWifiP2pService: after postfix = G3
08-03 19:51:09.828  1041  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 19:51:09.828  1041  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 19:51:09.829  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=17425,0  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:51:09.829  1041  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 19:51:09.829  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=174251  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:51:09.830  1041  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-03 19:51:09.830  1041  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 19:51:09.830  1041  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 19:51:09.830  1041  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 19:51:09.830  7129  7129 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 19:51:09.831  1041  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 19:51:09.831  1041  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 19:51:09.831  1041  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 19:51:09.831  1041  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 19:51:09.832  7129  7129 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 19:51:09.832  1041  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 19:51:09.832  1041  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 19:51:09.833  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 19:51:09.833  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 19:51:09.833  1041  1041 D RttService: SCAN_AVAILABLE : 3
08-03 19:51:09.833  1926  1926 D WfdsService: isConnected: false
08-03 19:51:09.833  1041  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.833  1041  1541 I WifiNative-HAL: startHal
08-03 19:51:09.833  1041  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf725360
08-03 19:51:09.833  1041  1541 D wifi    : failed to get capabilities : -3
08-03 19:51:09.833  1041  1541 E WifiScanningService: could not get scan capabilities
08-03 19:51:09.833  1041  1542 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:51:09.834  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:09.834  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:09.835  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:09.835  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.835  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.836  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 19:51:09.836  1041  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 19:51:09.836  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-03 19:51:09.836  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 19:51:09.837  7129  7129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.837  7129  7129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,08-03 19:51:09.837  7129  7129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.838  7129  7129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.838  1041  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 19:51:09.838  1041  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:51:09.838  1041  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:51:09.838  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:51:09.838  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.838  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.838  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.839  1041  7150 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.839  1041  7150 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.839  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.839  1041  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:51:09.839  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.839  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 19:51:09.839  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 19:51:09.839  7129  7129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:51:09.839  1926  7155 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.839  1926  7155 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.839  1041  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 19:51:09.839  1041  7150 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.840  1041  7150 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.840  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.840  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.840  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 19:51:09.840  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:51:09.840  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:51:09.840  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:51:09.840  1041  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 19:51:09.840  1041  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 19:51:09.841  1041  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 19:51:09.841  1041  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 19:51:09.841  1041  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 19:51:09.841  1041  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 19:51:09.842  1041  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 19:51:09.842  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:51:09.842  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] ,: Device Action doAction
08-03 19:51:09.842  1041  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 19:51:09.842  1041  1523 D WifiNative-wlan0: doBoolean: SCAN
08-03 19:51:09.842  1041  1523 D WifiNative-wlan0: SCAN: returned false
08-03 19:51:09.843  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=174264  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:51:09.843  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:51:09.844  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=174265  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:51:09.844  1041  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:51:09.845  1041  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:51:09.845  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:51:09.846  1041  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:51:09.846  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.846  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:09.846  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 19:51:09.846  1041  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:51:09.846  1041  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:51:09.847  1041  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-03 19:51:09.847  1041  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-03 19:51:09.850  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 19:51:09.850  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:51:09.850  1041  1041 D WifiServerServiceExt: setSupplicantStateSCANNING
08-03 19:51:09.850  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 19:51:09.850  1926  1926 D WfdsService: Update P2p Interface State: 3
08-03 19:51:09.851  1041  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 19:51:09.852  1041  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-03 19:51:09.853  1041  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 19:51:09.853  1041  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 19:51:09.854  1041  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 19:51:09.854  1041  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 19:51:09.854  1041  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 19:51:09.854  1041  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 19:51:09.855  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:09.855  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:09.856  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:09.859  4264  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:51:09.859  4264  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:51:09.860  4264  7156 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:51:09.862  1041  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 19:51:09.862  1041  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 19:51:09.880  1041  1059 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7158 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-03 19:51:09.883  1041  1522 D LGWifiP2pService: InactiveState
08-03 19:51:09.883  1041  1522 D LGWifiP2pService: InactiveState{ when=-45ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.883  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-45ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.883  1041  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 19:51:09.884  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 19:51:09.884  7129  7129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.886  1926  7155 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:51:09.886  7129  7129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 19:51:09.886  1041  7150 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:51:09.886  1041  7150 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.886  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.886  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:51:09.886  7129  7129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.887  1041  7150 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.887  1041  7150 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.887  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.887  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.888  1926  7155 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.888  7129  7129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.888  1041  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 19:51:09.888  1041  1522 D LGWifiP2pService: InactiveState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.888  1041  7150 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.888  1041  7150 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.888  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.888  1041  7150 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.888  1041  7150 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:51:09.888  1041  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.888  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.888  1041  1522 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.888  1041  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.889  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.889  1041  1522 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.889  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.intern,al.util.StateMachine$SmHandler }
08-03 19:51:09.889  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.889  1926  7155 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:51:09.889  1926  2288 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 19:51:09.890  1041  1522 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.890  1041  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.890  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.890  1041  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:09.890  1041  1041 E WifiServerServiceExt: No p2p device connected
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:51:09.909  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:51:09.911  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:51:09.916  5955  7175 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-03 19:51:09.916  5955  7175 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-03 19:51:09.954  7158  7158 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 19:51:09.954  7158  7158 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-03 19:51:09.967  7158  7158 V [BNRBootReceiver]: Boot Receiver Return
08-03 19:51:09.968  7158  7158 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 19:51:09.974  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:51:09.986  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:09.992  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.001  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.002  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:51:10.005  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:51:10.007  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.013  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:10.019  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.030  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.031  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:51:10.034  6289  6289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:51:10.037  1041  1998 I ActivityManager: Killing 6584:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-03 19:51:10.078  1041  1961 W libprocessgroup: failed to open /acct/uid_10011/pid_6584/cgroup.procs: No such file or directory
,08-03 19:51:10.422  7129  7129 E wpa_supplicant: USIM:  scard_init function
,08-03 19:51:10.423  7129  7129 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-03 19:51:10.432  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 19:51:10.433  1041  7150 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 19:51:10.434  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-03 19:51:10.434  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-03 19:51:10.434  1041  7150 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 19:51:10.434  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:51:10.434  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-03 19:51:10.439  1041  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-03 19:51:10.439  1041  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-03 19:51:10.440  1041  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-03 19:51:10.440  1041  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-03 19:51:10.440  1041  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 19:51:10.461  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=174882  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 19:51:10.467  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.468  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:10.469  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.473  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.475  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.475  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-03 19:51:10.483  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=174904  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 19:51:10.484  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:51:10.484  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-03 19:51:10.490  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-03 19:51:10.504  6216  6216 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 19:51:10.509  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.519  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:10.527  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.534  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.535  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:10.535  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:51:10.559  7129  7129 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 19:51:10.566  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 19:51:10.566  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 19:51:10.568  7129  7129 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:51:10.568  7129  7129 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:51:10.572  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 19:51:10.572  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 19:51:10.573  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:51:10.573  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:51:10.573  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:51:10.573  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:51:10.573  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 19:51:10.573  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:51:10.573  1041  7150 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:51:10.573  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 19:51:10.573  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:51:10.573  1041  7150 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:51:10.573  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:51:10.574  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:51:10.575  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=174997  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 19:51:10.576  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=174997  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-03 19:51:10.581  1041  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175003
08-03 19:51:10.582  1041  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175003
08-03 19:51:10.582  1041  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175004
08-03 19:51:10.583  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175004
08-03 19:51:10.583  1041  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175005
08-03 19:51:10.583  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=175005  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:51:10.587  1041  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 19:51:10.589  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.589  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.589  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-03 19:51:10.597  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.597  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:10.599  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:51:10.614  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 19:51:10.614  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.614  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 19:51:10.615  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=175036  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:51:10.615  1041  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=175037  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:51:10.619  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=175040  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:51:10.621  1041  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175042
08-03 19:51:10.622  1041  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175043
08-03 19:51:10.623  1041  1523 D WifiNative-wlan0: doString: [STATUS]
,08-03 19:51:10.629  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:51:10.633  1041  7150 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:51:10.634  1041  7150 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:51:10.635  1041  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:51:10.635  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.635  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:10.639  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.639  1041  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 19:51:10.649  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:10.649  1041  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 19:51:10.649  1041  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-03 19:51:10.652  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.652  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.652  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 19:51:10.658  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.658  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.658  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 19:51:10.659  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.659  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:10.660  1041  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-03 19:51:10.660  1041  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:51:10.660  1041  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:51:10.660  1041  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:51:10.660  1041  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:51:10.662  1041  1530 D ConnectivityService: Got NetworkAgent Messenger
08-03 19:51:10.662  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.662  1041  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 19:51:10.662  1041  1530 D ConnectivityService: NetworkAgent connected
08-03 19:51:10.664  1041  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:51:10.664  1041  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:51:10.664  1041  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:51:10.664  1041  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-03 19:51:10.664  1041  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:51:10.665  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.666  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:10.667  1041  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:51:10.668  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.669   313   892 D CommandListener: Setting iface cfg
08-03 19:51:10.671  1041  1523 E WifiStateMachine: Start Dhcp Watchdog 2
08-03 19:51:10.671  1041  7204 D DhcpStateMachine: StoppedState
08-03 19:51:10.672  1041  7204 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.672  1041  7204 D DhcpStateMachine: WaitBeforeStartState
08-03 19:51:10.672  1041  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175094  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:51:10.673  1041  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175094  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:51:10.673  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175095  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-03 19:51:10.674  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:51:10.674  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 19:51:10.675  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:10.676  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:10.676  1041  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:10.676  1041  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:10.677  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:10.677  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.677  1041  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:51:10.678  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:51:10.678  1041  1041 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-03 19:51:10.682  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:51:10.682  1041  1041 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-03 19:51:10.683  1041  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175105  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:51:10.683  1041  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175105  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:51:10.684  1041  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175106  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:51:10.685  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14190] from screen [on:0 period:1367855453] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:51:10.686  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1367855454] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:51:10.686  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 19:51:10.686  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.687  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:10.687  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:51:10.690  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:51:10.690  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:51:10.690  6216  6216 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:51:10.690  6216  6216 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:51:10.690  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:51:10.692  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.692  6216  6216 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:51:10.692  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 19:51:10.692  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:51:10.692  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:51:10.692  6216  6216 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:51:10.692  6216  6216 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 19:51:10.692  6216  6216 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:51:10.693  1041  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-03 19:51:10.694  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:51:10.694  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:51:10.695  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.695  1041  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:51:10.695  1041  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:51:10.696  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:51:10.696  1041  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:51:10.696  1041  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 19:51:10.697  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=9,0,0
08-03 19:51:10.697  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=9,0,0
08-03 19:51:10.697  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 19:51:10.698  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-03 19:51:10.699  1041  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 19:51:10.699  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 19:51:10.700  1041  1523 D WifiNative-wlan0: SET ps 0: returned true
08-03 19:51:10.700  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 19:51:10.700  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-03 19:51:10.701  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 19:51:10.701  1041  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 19:51:10.701  1041  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:51:10.701  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3aca5efa target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.701  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3aca5efa target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.701  1041  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:51:10.701  1041  7204 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.701  1041  7204 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 19:51:10.702   313   892 D CommandListener: Setting iface cfg
08-03 19:51:10.702   313   892 D CommandListener: Trying to bring up wlan0
08-03 19:51:10.702  1041  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 19:51:10.703  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:51:10.703  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:51:10.703  1041  1041 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 19:51:10.704  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:51:10.704  1041  1041 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 19:51:10.705  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-03 19:51:10.705  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-03 19:51:10.705  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:51:10.705  1041  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.705  1041  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.705  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:51:10.706  1041  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:51:10.706  1041  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 19:51:10.706  7129  7129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 19:51:10.706  1041  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 19:51:10.706  1041  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:51:10.709  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:51:10.715  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.715  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:10.715  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:51:10.720  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.724  1041  1523 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:51:10.724  1041  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-03 19:51:10.725  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:10.725  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:10.726  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:51:10.726  1041  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:10.727  1041  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:10.727  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:10.728  1041  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:10.728  1041  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 19:51:10.729  1041  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:51:10.729  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:51:10.729  1041  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 19:51:10.730  1041  1530 D ConnectivityService: ignoring duplicate network state non-change
08-03 19:51:10.732  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.732  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:10.733  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.734  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.734  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 19:51:10.734  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.734  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.736  1041  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 19:51:10.737  1041  1530 D ConnectivityService: Adding iface wlan0 to network 101
,08-03 19:51:10.740  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.740  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.740  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 19:51:10.753  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 19:51:10.753  1041  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 19:51:10.755  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-03 19:51:10.758  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.758  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:51:10.759  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.760  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.760  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.760  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 19:51:10.761  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 19:51:10.763  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.763  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:51:10.763  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
08-03 19:51:10.766  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:10.766  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 19:51:10.766  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 19:51:10.769  1041  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 19:51:10.769  1041  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 19:51:10.771  1041  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-03 19:51:10.772   313   892 E Netd    : netlink response contains error (File exists)
08-03 19:51:10.772  1041  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-03 19:51:10.773  1041  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 19:51:10.773  1041  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-03 19:51:10.773  1041  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-03 19:51:10.774  1041  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2076ccab type 2 when 175195 com.google.android.gms} when 175195
08-03 19:51:10.774  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.774  1041  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 19:51:10.774  1041  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-03 19:51:10.774  1041  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-03 19:51:10.775  1041  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 19:51:10.775  1041  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:51:10.775  1041  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:10.775  1041  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:51:10.775  1041  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.775  1041  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 19:51:10.778  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.778  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 19:51:10.778  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:10.778  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 19:51:10.781  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:51:10.782  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:51:10.782   313  7209 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 19:51:10.784  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:51:10.784  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:51:10.784  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.775  1041  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-03 19:51:10.785  1041  1530 D ConnectivityService:    accepting network in place of null
,08-03 19:51:10.786  1041  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.786  1041  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.786  1041  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:51:10.789  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.789  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.789  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:51:10.789  1041  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 19:51:10.789  1041  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 19:51:10.789  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:51:10.790  1041  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:10.790  1041  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 19:51:10.790  1041  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-03 19:51:10.791   313  7210 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 19:51:10.792  1041  1530 D ConnectivityService: validation of new default Network = false
08-03 19:51:10.792  1041  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:51:10.792  1041  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-03 19:51:10.792  1041  1530 D DSQN    : enableDataServiceNotify 
08-03 19:51:10.792  1041  1530 D DSQN    : start dsqn bin
08-03 19:51:10.793  1041  1041 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 19:51:10.793  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:51:10.793  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming:, false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:51:10.793  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-03 19:51:10.799  1041  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 19:51:10.799  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.799  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:10.799  1041  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:10.795  7211  7211 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:10.795  7211  7211 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:10.801  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 19:51:10.809  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:10.817  7211  7211 E DSQN    : DSQN ssw
08-03 19:51:10.820  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:51:10.829  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.829  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:10.829  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:51:10.831   313  7209 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 19:51:10.835  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.842  1041  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-03 19:51:10.848  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:10.861  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:51:10.863  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.864  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.865  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:10.872  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.872  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:10.873  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:51:10.875  1802  7215 I CheckinService: active receiver: enabled
08-03 19:51:10.876   313  7209 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-03 19:51:10.879  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:51:10.889  1802  7215 I CheckinService: Preparing to send checkin request
08-03 19:51:10.890  1802  7215 I EventLogService: Accumulating logs since 1470246121901
08-03 19:51:10.896  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:10.903  1041  7204 D DhcpStateMachine: DHCPV4 request on wlan0
08-03 19:51:10.904  1041  7204 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 19:51:10.904  1041  7204 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-03 19:51:10.904  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.905  7216  7216 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:10.905  7216  7216 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:51:10.916  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.917  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:10.918  6289  6289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:51:10.923  7216  7216 I dhcpcd  : version 5.5.6 starting
08-03 19:51:10.926   313   891 D LGDataListener: argv[0]=dsqncommand
08-03 19:51:10.926   313   891 D LGDataListener: argv[1]=wlan0
08-03 19:51:10.926   313   891 D LGDataListener: argv[2]=1
08-03 19:51:10.926   313   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-03 19:51:10.926  7216  7216 E dhcpcd  : get_duid: m
08-03 19:51:10.927  7216  7216 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 19:51:10.927  7216  7216 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 19:51:10.927  1041  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 19:51:10.927  1041  1117 D DSQN    : start to monitor internet connection
08-03 19:51:10.928  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.933  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 19:51:10.933  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:51:10.937  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:51:10.947  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:51:10.957  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:10.957  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:10.958  6289  6289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 19:51:10.959  6289  6289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:51:10.959  6289  6289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-03 19:51:10.965  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:51:10.970  1802  7215 W EventLogAggregator: Unknown tag: snet_gcore
08-03 19:51:10.970  1802  7215 W EventLogAggregator: Unknown tag: snet_launch_service
08-03 19:51:10.970  6238  6238 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 19:51:10.971  6238  6238 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:51:10.972  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 17:51:10 GMT], X-Android-Received-Millis=[1470246670972], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470246670925]}
08-03 19:51:10.972  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 19:51:10.972  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 19:51:10.973  1041  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
,08-03 19:51:10.973  1041  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,08-03 19:51:10.973  1041  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:51:10.973  1041  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:10.973  1041  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-03 19:51:10.973  1041  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-03 19:51:10.973  1041  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 19:51:10.973  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.973  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:10.974  1041  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:10.974  1041  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.974  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 19:51:10.975  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-03 19:51:10.976  6216  6216 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:51:10.976  1041  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.976  1041  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:51:10.978  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:10.980  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-03 19:51:10.993  6216  6216 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:51:11.001  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:51:11.002  6289  6289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:51:11.002  6289  6289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:51:11.002  7216  7216 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:51:11.002  7216  7216 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:51:11.003  7216  7216 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 19:51:11.003  7216  7216 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 19:51:11.003  7216  7216 D dhcpcd  : wlan0: sending REQUEST (xid 0xd9b53d2d), next in 4.87 seconds
08-03 19:51:11.003  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:11.003  6289  6289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 19:51:11.004  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:51:11.004  6289  6289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:51:11.004  6289  6289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 19:51:11.022  7216  7216 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-03 19:51:11.029  7216  7216 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-03 19:51:11.029  7216  7216 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 19:51:11.029  7216  7216 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 19:51:11.029  7216  7216 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 19:51:11.029  7216  7216 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 19:51:11.030  7216  7216 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:51:11.030  7216  7216 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:51:11.030  7216  7216 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 19:51:11.043  1802  7215 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 19:51:11.048  1041  1529 D WifiService: New client listening to asynchronous messages
,08-03 19:51:11.159  1041  1998 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7237 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-03 19:51:11.230  7237  7237 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-03 19:51:11.231  7237  7237 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-03 19:51:11.269  7237  7237 I MultiDex: VM with version 2.1.0 has multidex support
08-03 19:51:11.269  7237  7237 I MultiDex: install
08-03 19:51:11.269  7237  7237 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-03 19:51:11.287  7237  7237 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-03 19:51:11.292  2146  2146 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-03 19:51:11.307  1041  7204 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-03 19:51:11.312  1041  7204 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 19:51:11.313  1041  7204 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:51:11.313  2146  2146 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-03 19:51:11.313  1041  7204 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 19:51:11.313  1041  7204 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 19:51:11.313  1041  7204 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:51:11.313  1041  7204 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 19:51:11.313  1041  7204 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 19:51:11.313  2146  2146 D c       : Getting all permits...
08-03 19:51:11.313  2146  2146 D a       : Opening database...
08-03 19:51:11.313  1041  7204 D DhcpStateMachine: RunningState
08-03 19:51:11.318  2146  2146 D a       : Opening database auth.proximity.permit_store...
08-03 19:51:11.324  2146  2146 D a       : Closing database...
,08-03 19:51:11.682  7237  7255 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:51:11.682  7237  7255 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:51:11.773  7275  7275 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 19:51:11.837  7275  7275 I dex2oat : dex2oat took 63.783ms (threads: 4)
,08-03 19:51:11.848  7237  7255 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:51:11.848  7237  7255 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:51:11.848  7237  7255 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:51:11.848  7237  7255 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:51:11.848  7237  7255 I Adreno-EGL: Remote Branch: 
08-03 19:51:11.848  7237  7255 I Adreno-EGL: Local Patches: 
08-03 19:51:11.848  7237  7255 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:51:12.144  7237  7255 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:51:12.144  7237  7255 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:51:12.144  7237  7255 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:51:12.144  7237  7255 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:51:12.144  7237  7255 I Adreno-EGL: Remote Branch: 
08-03 19:51:12.144  7237  7255 I Adreno-EGL: Local Patches: 
08-03 19:51:12.144  7237  7255 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:51:12.258  7237  7255 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:51:12.258  7237  7255 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:51:12.258  7237  7255 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:51:12.258  7237  7255 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:51:12.258  7237  7255 I Adreno-EGL: Remote Branch: 
08-03 19:51:12.258  7237  7255 I Adreno-EGL: Local Patches: 
08-03 19:51:12.258  7237  7255 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:51:12.271  1041  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-03 19:51:12.271  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-03 19:51:12.272  1041  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:12.272  1041  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:12.272  1041  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:12.273  1041  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:51:12.273  1041  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-03 19:51:12.274  1041  1530 D ConnectivityService: identical MTU - not setting
08-03 19:51:12.275  1041  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 19:51:12.275  1041  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 19:51:12.275  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:12.275  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:12.277  1041  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:12.279  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-03 19:51:12.399   313  7283 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:51:12.399   313  7283 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-03 19:51:12.447   313  7283 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-03 19:51:12.626  1802  7215 I CheckinTask: Sending checkin request (7890 bytes)
,08-03 19:51:12.874  1802  7215 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-03 19:51:12.884  1802  7215 I CheckinService: active receiver: disabled
,08-03 19:51:12.910  2146  2146 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-03 19:51:12.932  5955  7175 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-03 19:51:12.932  5955  7175 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:51:12.932  5955  7175 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:51:12.932  5955  7175 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:51:12.933  5955  7175 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 19:51:12.944  2146  2146 I GCM     : GCM config loaded
08-03 19:51:12.946  5955  7287 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-03 19:51:12.947  5955  7287 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:51:12.947  5955  7287 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:51:12.947  5955  7291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 766, name: OutgoingSocketThread/Receiver)
,08-03 19:51:12.947  5955  7291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 766, thread name: OutgoingSocketThread/Receiver)
08-03 19:51:12.948  5955  7291 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 19:51:12.948  5955  7291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 766, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-03 19:51:12.949  5955  7290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 765, name: OutgoingSocketThread/Sender)
08-03 19:51:12.959  5955  7287 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 19:51:12.961  5955  7287 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 19:51:12.970  5955  7300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 768, name: IncomingSocketThread/Receiver)
08-03 19:51:12.971  5955  7300 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 768, thread name: IncomingSocketThread/Receiver)
08-03 19:51:12.971  5955  7300 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 19:51:12.971  5955  7300 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 768, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-03 19:51:12.972   313  7301 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:51:12.972   313  7301 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-03 19:51:12.974  5955  7299 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 767, name: IncomingSocketThread/Sender)
,08-03 19:51:12.983  6660  6660 V SetupWizard: Connected to Gservices successfully
08-03 19:51:13.010   313  7301 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-03 19:51:13.174  2146  7297 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-03 19:51:13.352  2146  7316 D GCM     : Connected
,08-03 19:51:13.405  2146  7316 D GCM     : Message class com.google.e.a.a.q
,08-03 19:51:13.698  1041  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1367858465] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-03 19:51:13.700  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1367858468] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:51:13.701  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:51:13.720  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:51:13.759  1041  1525 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-03 19:51:13.791  1041  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:51:13.798  1041  1119 D Tethering: MasterInitialState.processMessage what=3
08-03 19:51:13.813   313  7326 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-03 19:51:13.818   313  7326 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:51:13.823  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:51:13.825  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:13.827  1041  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:51:13.835  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 19:51:13.836  3666  3700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 19:51:13.846  5326  5326 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-03 19:51:13.861   313  7326 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
,08-03 19:51:13.877  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:51:13.881  1041  1811 D AlarmManagerService: Setting time of day to sec=1470246673
08-03 19:51:13.904  1041  1811 W AlarmManagerService: Unable to set rtc to 1470246673: Invalid argument
08-03 19:51:13.939  1926  1926 I SecureClockService: Intent.ACTION_TIME_CHANGED 
,08-03 19:51:13.949  1587  1587 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-03 19:51:13.950  1587  1587 I LgeClockWidgetControlView: time changed, timezoneChanged : false
08-03 19:51:13.955  2707  2707 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
08-03 19:51:13.956  2707  2707 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-03 19:51:13...... Request
08-03 19:51:13.956  2707  2707 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 44, new day : false...... Request
08-03 19:51:13.956  2707  2707 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 44
08-03 19:51:13.956  2707  2707 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 6
08-03 19:51:13.956  2707  2707 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-03 19:51:13
,08-03 19:51:13.968  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 19:51:13.998  1041  1925 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-03 19:51:14.000  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:14.003  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:14.003  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-03 19:51:14.004  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:51:14.004  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 19:51:14.009  1041  1943 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7340 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-03 19:51:14.010  1041  1997 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
08-03 19:51:14.012  2017  2017 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=3 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
08-03 19:51:14.013  2017  2017 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
08-03 19:51:14.024   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 20.274ms
08-03 19:51:14.024  2017  2017 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
,08-03 19:51:14.024  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:14.041  1041  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 19:51:14.043   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 19.303ms
08-03 19:51:14.050  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 17:51:14 GMT], X-Android-Received-Millis=[1470246674049], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470246674005]}
08-03 19:51:14.050  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 19:51:14.050  1041  7203 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 19:51:14.050  1041  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-03 19:51:14.050  1041  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 19:51:14.050  1041  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:51:14.050  1041  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:14.050  1041  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:51:14.050  1041  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-03 19:51:14.050  1041  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 19:51:14.050  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:51:14.050  1041  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:14.051  1041  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:51:14.051  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 19:51:14.054  2573  2573 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 19:51:14.061   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 352us total 17.575ms
08-03 19:51:14.085  7340  7340 I AppUp4:AppBoxCP: onCreate
08-03 19:51:14.086  7340  7340 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-03 19:51:14.093  7340  7340 I AppUp4:DB:  setFingerPrint start
08-03 19:51:14.093  7340  7340 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-03 19:51:14.099  7340  7340 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-03 19:51:14.099  7340  7340 I AppUp4:DB:  SDK version = 21
,08-03 19:51:14.100  7340  7340 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-03 19:51:14.101  7340  7340 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-03 19:51:14.102  7340  7340 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:51:14.102  7340  7340 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:14.103  7340  7340 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:51:14.104  7340  7340 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 19:51:14.107  7340  7340 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:51:14.137  7340  7340 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:51:14.137  7340  7340 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:51:14.143  7340  7340 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2df825eb
08-03 19:51:14.143  7340  7340 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:51:14.143  7340  7340 D AppUp4:CustFacade: isPhone : true
08-03 19:51:14.144  7340  7340 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:51:14.144  7340  7340 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-03 19:51:14.144  7340  7340 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-03 19:51:14.145  7340  7361 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-03 19:51:14.145  7340  7361 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-03 19:51:14.145  7340  7361 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-03 19:51:14.146  1041  1925 I ActivityManager: Killing 6609:com.lge.email/u0a23 (adj 15): empty #17
08-03 19:51:14.200  1041  1762 W libprocessgroup: failed to open /acct/uid_10023/pid_6609/cgroup.procs: No such file or directory
,08-03 19:51:14.203  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:14.204  4264  4264 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:51:14.208  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:51:14.211  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:51:14.219  3430  3430 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:14.221  4264  7363 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:51:14.222  3430  3430 V DownloadManager: DownloadService onCreate
,08-03 19:51:14.227  3430  7365 I DownloadManager: in removeSpuriousFiles
,08-03 19:51:14.227  4264  7363 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-03 19:51:14.227  4264  7364 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:14.228  4264  7364 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:51:14.228  3430  7365 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-03 19:51:14.231  3430  7365 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@32700466 on behalf of 3430
08-03 19:51:14.232  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-03 19:51:14.233  3430  7365 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-03 19:51:14.235  3430  7365 I DownloadManager: in trimDatabase
08-03 19:51:14.236  3430  7365 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-03 19:51:14.238  3430  7365 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@27ed23a7 on behalf of 3430
08-03 19:51:14.288  1041  1889 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7370 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 19:51:14.292  3430  3430 V DownloadManager: DownloadService onStartCommand
08-03 19:51:14.292  3430  7366 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-03 19:51:14.294  3430  7366 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@306800f2 on behalf of 3430
08-03 19:51:14.294  4264  7363 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,08-03 19:51:14.297  4264  4264 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-03 19:51:14.298  4264  4264 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-03 19:51:14.298  4264  4264 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-03 19:51:14.300  4264  4264 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-03 19:51:14.305  3430  7366 V DownloadManager: processing inserted download 1
08-03 19:51:14.305  4264  4264 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-03 19:51:14.309  3430  7366 V DownloadManager: processing inserted download 4
,08-03 19:51:14.311  3430  7366 V DownloadManager: processing inserted download 7
08-03 19:51:14.313  3430  7366 V DownloadManager: processing inserted download 8
08-03 19:51:14.314  3430  7366 V DownloadManager: processing inserted download 9
08-03 19:51:14.316  3430  7366 V DownloadManager: processing inserted download 10
08-03 19:51:14.317  3430  7366 V DownloadManager: processing inserted download 11
,08-03 19:51:14.319  3430  7366 V DownloadManager: processing inserted download 12
,08-03 19:51:14.320  3430  7366 V DownloadManager: processing inserted download 13
08-03 19:51:14.321  3430  7366 V DownloadManager: processing inserted download 14
08-03 19:51:14.323  3430  7366 V DownloadManager: processing inserted download 16
08-03 19:51:14.327  3430  3430 V DownloadManager: DownloadService onDestroy
,08-03 19:51:14.363  7370  7370 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:51:14.364  7370  7370 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 19:51:14.366  7370  7370 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:51:14.366  7370  7370 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-03 19:51:14.464  7370  7370 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 19:51:14.475  7370  7370 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-03 19:51:14.544  7370  7370 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 19:51:14.591  7370  7370 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:51:14.592  7370  7370 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:51:14.722  1041  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{227ce25a type 2 when 179120 com.google.android.gms} when 179120
,08-03 19:51:14.760  7370  7370 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 19:51:14.822  7370  7370 I HubEmail: JNI_OnLoad()
08-03 19:51:14.822  7370  7370 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:51:14.822  7370  7370 I HubEmail: registerNatives()
,08-03 19:51:14.822  7370  7370 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:51:14.822  7370  7370 I HubEmail: registerNativeMethods()
08-03 19:51:14.822  7370  7370 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:51:14.822  7370  7370 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-03 19:51:14.823  3339  3339 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:51:14.823  3339  3339 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:51:14.823  3339  3339 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 19:51:14.823  3339  3339 D PhoneState: setPdpRejectCasuse : false
08-03 19:51:14.827  6660  6660 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:51:14.828  6660  6660 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 19:51:14.837  7370  7401 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 19:51:14.848  6776  6776 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:51:14
08-03 19:51:14.850  6776  6776 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-03 19:51:14.850  6776  6776 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:51:14.850  6776  6776 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:51:14.851  6776  6776 D WeatherAncestor: connectivity changed - connection : true
08-03 19:51:14.851  6776  6776 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a2901e1
08-03 19:51:14.852  6776  6776 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:51:14.852  6776  6776 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:51:14.852  6776  6776 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 19:51:14.852  6776  6776 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:51:14.852  6776  6776 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:51:14
08-03 19:51:14.885  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,08-03 19:51:14.905   313  7414 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:51:14.906   313  7414 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-03 19:51:15.008   313  7417 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:51:15.008   313  7417 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-03 19:51:15.012  1041  1925 I art     : Explicit concurrent mark sweep GC freed 80532(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.570ms total 121.215ms
,08-03 19:51:15.045   313  7417 D libc-netbsd: res_queryN name = www.google.com succeed
,08-03 19:51:15.047   313  7421 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:51:15.048   313  7421 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 19:51:15.048   313  7421 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-03 19:51:15.076  1041  1998 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7422 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-03 19:51:15.076  1802  7418 I CheckinService: active receiver: disabled
,08-03 19:51:15.132  1041  1526 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
08-03 19:51:15.198  7422  7439 D ALBootInit: ====action==>android.intent.action.TIME_SET
,08-03 19:51:15.206  7422  7439 D ALBootInit: Alarm ALBootInit: TIME_SET
,08-03 19:51:15.213  7422  7439 D Alarms  : [setNextAlert] start
,08-03 19:51:15.240  7422  7439 D Alarms  : [setNextAlert] (1)
,08-03 19:51:15.243  7422  7439 D Alarms  :  minTime  = 0
,08-03 19:51:15.246  7422  7439 D Alarms  :  -- OK multi -- 0
08-03 19:51:15.247  7422  7439 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-03 19:51:15.247  7422  7439 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
,08-03 19:51:15.273  7422  7439 I CommonUtil: BUILD Country: EU
08-03 19:51:15.275  7422  7439 D Alarms  : broadcastToWidgetProvider : false
,08-03 19:51:15.283  7422  7439 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
08-03 19:51:15.295  1041  1059 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,08-03 19:51:15.303  7422  7422 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-03 19:51:15.310  7422  7422 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2cf7ef48
,08-03 19:51:15.315  7422  7422 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2cf7ef48
08-03 19:51:15.320  7422  7422 D QuickCoverProvider: onReceiver
08-03 19:51:15.328  1543  1543 I indal   : SmartCoverWidgetContext createApplicationContext
08-03 19:51:15.330  1543  1543 I indal   : SmartCoverWidgetContext createApplicationContext
,08-03 19:51:15.359  6776  6776 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 19:51:15
,08-03 19:51:15.364  6776  6776 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:51:15.365  6776  6776 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:51:15.366  6776  6776 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:51:15.371  6776  6776 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a2901e1
08-03 19:51:15.373  6776  6776 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-03 19:51:15.373  6776  6776 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:51:15.373  6776  6776 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 19:51:15.379  6776  6776 D Weather_cast: 2 : set auto-update time : 8/3 22:51
08-03 19:51:15.386  6776  6776 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 19:51:15
,08-03 19:51:15.462  1041  2027 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7447 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 19:51:15.466  1041  2027 I ActivityManager: Killing 6261:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-03 19:51:15.524  1041  1888 W libprocessgroup: failed to open /acct/uid_10037/pid_6261/cgroup.procs: No such file or directory
08-03 19:51:15.575  7447  7447 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470246675575
08-03 19:51:15.576  7447  7447 D         : TimeServiceNative: User Time to be set is 1470246675576
08-03 19:51:15.576  7447  7447 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-03 19:51:15.576  7447  7447 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-03 19:51:15.576  7447  7447 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470246675576
08-03 19:51:15.576   368  1033 D QC-time-services: Daemon: Connection accepted:time_genoff
08-03 19:51:15.577  7447  7447 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470246675576
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470246675576, operation = 0
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/13/70 12:18:56
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:Value read from RTC seconds = 3759536000
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:new time 1470246675576 
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon: delta 1466487139576 genoff 1466487139576 
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487139576 to memory
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-03 19:51:15.577   368  7464 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-03 19:51:15.585   368  7464 D QC-time-services: Updating the TOD offset
,08-03 19:51:15.585   368  7464 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487139576 to memory
08-03 19:51:15.585   368  7464 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-03 19:51:15.585   368  7464 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-03 19:51:15.590   368  7464 E QC-time-services: Daemon:Update to modem bit set
08-03 19:51:15.590   368  7464 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,08-03 19:51:15.590   368  7464 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522339576
,08-03 19:51:15.591  7447  7447 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-03 19:51:15.593   368  1031 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-03 19:51:15.594   368  1033 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-03 19:51:15.602  7158  7158 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
08-03 19:51:15.607  7158  7158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,08-03 19:51:15.613  1587  1587 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-03 19:51:15.616  1587  1587 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-03 19:51:15.616  1587  1587 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-03 19:51:15.620  7158  7158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
08-03 19:51:15.621  7158  7158 V [BNRBootReceiver]: Boot Receiver Return
08-03 19:51:15.687  1041  1560 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7465 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,08-03 19:51:15.690  1041  1560 I ActivityManager: Killing 6306:com.lge.settings.easy/1000 (adj 15): empty #17
08-03 19:51:15.732  1041  1059 W libprocessgroup: failed to open /acct/uid_1000/pid_6306/cgroup.procs: No such file or directory
,08-03 19:51:15.766  7465  7465 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:51:15.803  7465  7465 D CalendarApplication: CalendarApplication.onCreate()
,08-03 19:51:15.816  7465  7465 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
08-03 19:51:15.817  7465  7465 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@11339bcf, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1d8c995c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@24bf8465, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@b00553a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2df825eb, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2cf7ef48, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@a2901e1, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@270e8b06, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3135c7, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1e40b7f4, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1452db1d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3b785192, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@24016763, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1bab5f60, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@23470c19, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1f45f4de, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@231916bf, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2d57118c, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@33b350d5, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3fb880ea, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@37d25fdb, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1c29ba78, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@25652551, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2b15c1b6, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@20d1eb7, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@177c0624, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2d85c58d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3c344342, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@15caef53, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@9856090, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@30962d89, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@32c7518e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3b8b2daf, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@687f5bc, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2b1945, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@46af89a, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1a66f5cb, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2bcb1a8, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@386904c1, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@32700466, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Pre,ferenceKey$KeyData@27ed23a7, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3aff405
08-03 19:51:15.825  7465  7465 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
08-03 19:51:15.842  7465  7465 D Config  : [init]
,08-03 19:51:15.844  7465  7465 I Config  : LGCalendar ver.4.40.16
08-03 19:51:15.844  7465  7465 I Config  : start check model
08-03 19:51:15.844  7465  7465 I Config  : start check native_ca
08-03 19:51:15.845  7465  7465 I Config  : Config Operator=OPEN, Country=EU
08-03 19:51:15.845  7465  7465 D Config  : [setDefaultValuesToPref]
08-03 19:51:15.846  7465  7465 D Config  : [parseProfiles]
08-03 19:51:15.851  7465  7465 D ProfilesParser: [debug_displayParseInfos] profile.country = null
08-03 19:51:15.851  7465  7465 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
08-03 19:51:15.851  7465  7465 D Config  : [updateProfiletoCountryInfo]
08-03 19:51:15.852  7465  7465 D GeneralPreference: [checkAndMigrateOldPreference]
08-03 19:51:15.874  7465  7465 E AgendaWidgetManager: [updateWidgets] 
,08-03 19:51:15.881  7465  7484 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
08-03 19:51:15.885  7465  7484 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
08-03 19:51:15.911  7465  7484 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,08-03 19:51:15.919  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
08-03 19:51:15.923  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
08-03 19:51:15.927  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,08-03 19:51:15.933  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
08-03 19:51:15.941  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,08-03 19:51:15.944  5955  6118 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-03 19:51:15.946  5955  6118 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-03 19:51:15.947  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
08-03 19:51:15.950  5955  6118 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@33b350d5 Bundle[{}]
08-03 19:51:15.951  5955  6118 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 19:51:15.951  5955  6118 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-03 19:51:15.952  5955  6118 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 19:51:15.952  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
08-03 19:51:15.952  5955  6118 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-03 19:51:15.955  5955  6118 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 19:51:15.956  5955  6118 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-03 19:51:15.959  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
08-03 19:51:15.964  5955  6118 I System.out: Running OutgoingSocketThread
08-03 19:51:15.964  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
08-03 19:51:15.965  5955  7485 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-03 19:51:15.965  5955  7485 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-03 19:51:15.970  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,08-03 19:51:15.976  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
08-03 19:51:15.980  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
08-03 19:51:15.985  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,08-03 19:51:15.989  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
08-03 19:51:15.993  7465  7484 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
08-03 19:51:15.993  7465  7484 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
08-03 19:51:15.996  7465  7484 I AlertUtils: set default noti to content://media/internal/audio/media/41
08-03 19:51:16.001  7465  7484 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,08-03 19:51:16.069  7465  7465 D MonthWidgetProvider: [onReceive]
08-03 19:51:16.069  7465  7465 D CalendarWidgetProvider: [onReceive]
08-03 19:51:16.070  7465  7465 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
08-03 19:51:16.070  7465  7488 W HolidayIntentService: onHandleIntent
,08-03 19:51:16.072  7465  7488 D HolidayDataLoader: readJsonAsset : holiday.json
,08-03 19:51:16.074  7465  7465 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-03 19:51:16.083  7465  7465 D WeekWidgetProvider: [onReceive]
,08-03 19:51:16.083  7465  7465 D CalendarWidgetProvider: [onReceive]
,08-03 19:51:16.083  7465  7465 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
08-03 19:51:16.084  7465  7465 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,08-03 19:51:16.095   313  7490 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-03 19:51:16.095  2146  2146 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-03 19:51:16.095   313  7490 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-03 19:51:16.096   313  7490 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-03 19:51:16.112  7422  7422 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
08-03 19:51:16.116  6776  6776 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 19:51:16
,08-03 19:51:16.117  6776  6776 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:51:16.117  6776  6776 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:51:16.118  6776  6776 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:51:16.120  6776  6776 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
08-03 19:51:16.120  6776  6776 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 19:51:16
08-03 19:51:16.123  2017  2017 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-03 19:51:16.124  2017  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-03 19:51:16.125  2017  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-03 19:51:16.125  2017  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-03 19:51:16.125  2017  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-03 19:51:16.126  2017  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-03 19:51:16.126  7158  7158 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
08-03 19:51:16.127  7158  7158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-03 19:51:16.129  1587  1587 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-03 19:51:16.129  1587  1587 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
,08-03 19:51:16.129  1587  1587 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-03 19:51:16.131  7158  7158 V [BNRBootReceiver]: Boot Receiver Return
08-03 19:51:16.134  2017  2017 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-03 19:51:16.135  2017  5356 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-03 19:51:16.135  2017  5356 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-03 19:51:16.135  2017  5356 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-03 19:51:16.135  2017  5356 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-03 19:51:16.136  2017  5356 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-03 19:51:16.160  7465  7488 E HolidayIntentService: onHandleIntent:holiday data empty
,08-03 19:51:16.161  1041  1925 I ActivityManager: Killing 6238:com.lge.sync/1000 (adj 15): empty #17
08-03 19:51:16.212  1041  1997 W libprocessgroup: failed to open /acct/uid_1000/pid_6238/cgroup.procs: No such file or directory
,08-03 19:51:16.423  2146  7493 D GCM     : Connected
,08-03 19:51:16.460  2146  7493 D GCM     : Message class com.google.e.a.a.q
,08-03 19:51:16.621   313  7414 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-03 19:51:16.672  6329  7399 V FormManager: There are no updated forms. The schedule will be deleted.
,08-03 19:51:16.679  6329  7399 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-03 19:51:16.711  1041  1058 I ActivityManager: Killing 6137:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-03 19:51:16.731  6289  6289 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 19:51:16.732  6289  6289 W System.err: android.os.DeadObjectException
08-03 19:51:16.732  6289  6289 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:51:16.732  6289  6289 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 19:51:16.732  6289  6289 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 19:51:16.732  6289  6289 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 19:51:16.732  6289  6289 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:51:16.732  6289  6289 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:51:16.732  6289  6289 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:51:16.732  6289  6289 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:51:16.732  6289  6289 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:51:16.732  6289  6289 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:51:16.732  6289  6289 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:51:16.732  6289  6289 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:51:16.732  6289  6289 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:51:16.732  6289  6289 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:51:16.733  6289  6289 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 19:51:16.733  6289  6289 W System.err: android.os.DeadObjectException
08-03 19:51:16.733  6289  6289 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:51:16.733  6289  6289 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 19:51:16.733  6289  6289 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 19:51:16.733  6289  6289 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 19:51:16.733  6289  6289 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:51:16.733  6289  6289 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:51:16.733  6289  6289 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:51:16.733  6289  6289 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:51:16.733  6289  6289 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:51:16.733  6289  6289 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:51:16.733  6289  6289 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:51:16.734  6289  6289 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:51:16.734  6289  6289 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:51:16.734  6289  6289 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:51:16.734  6289  6289 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 19:51:16.734  6289  6289 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-03 19:51:16.750  1041  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=17.8, 0.0, 0.0  rx=15.5 bcn=0 [on:0 tx:0 rx:0 period:3025] from screen [on:0 period:1367861517] gl rssi=-37 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:51:16.750  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=17.8, 0.0, 0.0  rx=15.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1367861518] gl rssi=-37 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:51:16.751  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:51:16.768  1041  2027 W libprocessgroup: failed to open /acct/uid_1000/pid_6137/cgroup.procs: No such file or directory
08-03 19:51:16.769  1041  2027 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-03 19:51:16.779  6289  6289 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 19:51:16.779  6289  6289 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 19:51:16.849  1041  1907 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7500 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:51:16.887  6289  6289 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 19:51:16.914  7500  7500 D UEI.SmartControl: Quickset Services start...
08-03 19:51:16.916  7500  7500 I UEI.SmartControl: Manufacture = LGE
08-03 19:51:16.916  7500  7500 D UEI.SmartControl: Id = LGNevo
08-03 19:51:16.917  7500  7500 D UEI.SmartControl: File observer start...
08-03 19:51:16.918  7500  7500 E UEI.SmartControl: IR Port is disabled: false
,08-03 19:51:16.922  7500  7500 D UEI.SmartControl: Starting file observer...
08-03 19:51:16.922  7500  7500 D UEI.SmartControl: Extracting JNI libs...
08-03 19:51:16.923  7500  7500 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 19:51:17.024  7500  7500 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 19:51:17.024  7500  7500 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 19:51:17.024  7500  7500 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-03 19:51:17.064  7500  7500 I UEI.SmartControl: --- Selecting new region: 6
,08-03 19:51:17.067  7500  7500 I UEI.SmartControl: Model = LG-D855
,08-03 19:51:17.070  7500  7500 D UEI.SmartControl: QS Service created
,08-03 19:51:17.088  7500  7500 I UEI.SmartControl: Service initServices...
,08-03 19:51:17.093  7500  7500 D UEI.SmartControl: QS start get config
,08-03 19:51:17.146  7500  7500 D UEI.SmartControl: Loading JNI Libs...
,08-03 19:51:17.377  1041  1925 I ActivityManager: Killing 6216:com.android.settings/1000 (adj 15): empty #17
,08-03 19:51:17.406  7500  7500 I UEI.SmartControl: Supports setup maps: true
,08-03 19:51:17.409  7500  7500 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 19:51:17.409  7500  7500 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 19:51:17.409  7500  7500 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 19:51:17.410  7500  7500 I UEI.SmartControl: ### init IR Blaster...
08-03 19:51:17.414  7500  7500 D serial_port: Configuring serial port
,08-03 19:51:17.417  7500  7500 E UEI.SmartControl: UEIBLaster setting for 616
08-03 19:51:17.417  7500  7500 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 19:51:17.417  7500  7500 I UEI.SmartControl: configuring settings for MAXQ616
08-03 19:51:17.417  7500  7500 I UEI.SmartControl: Get version...
08-03 19:51:17.432  1041  1997 W libprocessgroup: failed to open /acct/uid_1000/pid_6216/cgroup.procs: No such file or directory
,08-03 19:51:17.436  7500  7532 D UEI.SmartControl: serial port data available: 21
08-03 19:51:17.466  7500  7500 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-03 19:51:17.466  7500  7500 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-03 19:51:17.466  7500  7500 I UEI.SmartControl: QS saving settings...
08-03 19:51:17.471  7500  7500 D UEI.SmartControl: IR Blaster version: 25672567
08-03 19:51:17.488  7500  7532 D UEI.SmartControl: serial port data available: 4
,08-03 19:51:17.530  7500  7535 I UEI.SmartControl: Device manager: loading config....
,08-03 19:51:17.533  7500  7500 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 19:51:17.537  7500  7535 D UEI.SmartControl: ----------- loading internal config...
08-03 19:51:17.540  7500  7500 E UEI.SmartControl: Services init done
08-03 19:51:17.540  7500  7500 D UEI.SmartControl: QS Service init finished
08-03 19:51:17.541  7500  7500 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 19:51:17.542  7500  7500 D UEI.SmartControl: QS Service version code: 201091
08-03 19:51:17.542  7500  7500 D UEI.SmartControl: Service requested: Control
08-03 19:51:17.551  7500  7535 E UEI.SmartControl: Loading SETTINGS...
,08-03 19:51:17.553  7500  7500 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 19:51:17.558  1041  1889 I ActivityManager: Killing 6289:com.lge.qremote/u0a112 (adj 15): empty #17
08-03 19:51:17.560  7500  7535 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 19:51:17.566  7500  7534 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 19:51:17.566  7500  7534 D UEI.SmartControl: -----service ready thread exits
,08-03 19:51:17.591  1041  1762 W libprocessgroup: failed to open /acct/uid_10112/pid_6289/cgroup.procs: No such file or directory
,08-03 19:51:17.593  7500  7500 D UEI.SmartControl: Internal service binding...
08-03 19:51:18.980  5955  7485 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-03 19:51:18.980  5955  7485 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:51:18.980  5955  7485 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:51:18.981  5955  7485 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:51:18.981  5955  7485 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 19:51:18.986  5955  7540 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-03 19:51:18.986  5955  7540 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:51:18.986  5955  7540 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:51:18.987  5955  7540 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:51:18.987  5955  7540 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 19:51:18.989  5955  7543 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 778, name: OutgoingSocketThread/Receiver)
08-03 19:51:18.990  5955  7543 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 778, thread name: OutgoingSocketThread/Receiver)
08-03 19:51:18.990  5955  7543 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 19:51:18.990  5955  7543 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 778, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-03 19:51:18.992  5955  7542 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 777, name: OutgoingSocketThread/Sender)
08-03 19:51:18.993  5955  7544 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 779, name: IncomingSocketThread/Sender)
08-03 19:51:18.995  5955  7545 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 780, name: IncomingSocketThread/Receiver)
08-03 19:51:18.995  5955  7545 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 780, thread name: IncomingSocketThread/Receiver)
08-03 19:51:18.995  5955  7545 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 19:51:18.996  5955  7545 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 780, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 19:51:19.762  1041  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=22.4, 0.0, 0.0  rx=18.2 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:1367864530] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:51:19.765  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=22.4, 0.0, 0.0  rx=18.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1367864533] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:51:19.765  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:51:20.989  1041  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 19:51:21.003  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 19:51:21.093  1041  1106 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7546 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-03 19:51:21.102  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-03 19:51:21.103  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-03 19:51:21.124  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 19:51:21.143  1041  1041 D administrator: Handling package changes for user 0
,08-03 19:51:21.147  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:21.176  7546  7546 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-03 19:51:21.252  1041  1041 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-03 19:51:21.252  1041  1041 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 19:51:21.257  7546  7546 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:51:21.257  7546  7546 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:51:21.299  1041  1103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:51:21.307  1041  1103 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 19:51:21.315  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-03 19:51:21.316  2492  2492 V GmsNetworkLocationProvi: DISABLE
,08-03 19:51:21.348  1041  1103 D LocationProviderProxy: applying state to connected service
08-03 19:51:21.349  2492  2492 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 19:51:21.358  7546  7590 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 19:51:21.358  7546  7590 I Babel   : MmsConfig.loadMmsSettings
,08-03 19:51:21.367  7546  7590 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 19:51:21.367  7546  7590 I Babel   : MmsConfig.loadFromDatabase
,08-03 19:51:21.381  7546  7590 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 19:51:21.381  7546  7590 I Babel   : MmsConfig.loadFromResources
08-03 19:51:21.383  7546  7590 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 19:51:21.383  7546  7590 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 19:51:21.385  7546  7546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:51:21.393  7546  7589 W AudioCapabilities: Unsupported mime audio/evrc
,08-03 19:51:21.395  7546  7589 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 19:51:21.397  7546  7589 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-03 19:51:21.404  1802  7593 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-03 19:51:21.404  1802  7593 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-03 19:51:21.406  7340  7340 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 19:51:21.411  7340  7340 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2df825eb
08-03 19:51:21.411  7340  7340 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:51:21.411  7340  7340 D AppUp4:CustFacade: isPhone : true
08-03 19:51:21.412  7340  7340 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:51:21.412  7340  7340 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-03 19:51:21.418  7546  7589 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-03 19:51:21.423  7546  7589 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 19:51:21.432  7546  7589 W AudioCapabilities: Unsupported mime audio/evrc
,08-03 19:51:21.447  1802  1802 I art     : Explicit concurrent mark sweep GC freed 24099(1769KB) AllocSpace objects, 19(304KB) LOS objects, 51% free, 29MB/61MB, paused 1.362ms total 36.403ms
,08-03 19:51:21.451  1041  1560 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7596 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-03 19:51:21.458  1041  1997 I ActivityManager: Killing 6329:com.lge.formmanager/u0a26 (adj 15): empty #17
08-03 19:51:21.480  1802  4666 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-03 19:51:21.487  7546  7589 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-03 19:51:21.489  7546  7589 W VideoCapabilities: Unsupported mime video/divx
08-03 19:51:21.490  7546  7589 W VideoCapabilities: Unsupported mime video/divx311
08-03 19:51:21.492  7546  7589 W VideoCapabilities: Unsupported mime video/divx4
,08-03 19:51:21.500  7546  7589 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-03 19:51:21.514  7546  7589 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 19:51:21.517  7546  7589 W AudioCapabilities: Unsupported mime audio/eac3
08-03 19:51:21.517  7546  7589 W AudioCapabilities: Unsupported mime audio/ac3
08-03 19:51:21.518  7546  7589 W AudioCapabilities: Unsupported mime audio/g726
08-03 19:51:21.519  7546  7589 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 19:51:21.520  7546  7589 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-03 19:51:21.520  7546  7589 W AudioCapabilities: Unsupported mime audio/adpcm
08-03 19:51:21.522  7546  7589 W VideoCapabilities: Unsupported mime video/theora
08-03 19:51:21.523  7546  7589 W VideoCapabilities: Unsupported mime video/mjpg
,08-03 19:51:21.636  1041  1889 W libprocessgroup: failed to open /acct/uid_10026/pid_6329/cgroup.procs: No such file or directory
,08-03 19:51:21.667  7596  7596 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:51:21.667  7596  7596 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:51:21.667  7596  7596 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-03 19:51:21.670  7596  7596 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-03 19:51:21.671  7596  7596 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:51:21.764  7596  7596 I SystemConfig: BUILD Country: EU
08-03 19:51:21.764  7596  7596 I SystemConfig: BUILD Operator: OPEN
,08-03 19:51:21.817  1041  1997 I ActivityManager: Killing 6697:com.android.chrome/u0a57 (adj 15): empty #17
,08-03 19:51:21.850  1041  1961 W libprocessgroup: failed to open /acct/uid_10057/pid_6697/cgroup.procs: No such file or directory
,08-03 19:51:21.856  7596  7616 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-03 19:51:21.856  7596  7616 I SystemConfig: existFile = false
08-03 19:51:21.856  7596  7616 I SystemConfig: canReadFile = false
08-03 19:51:21.856  7596  7616 I SystemConfig: systemFeature RCS result false
08-03 19:51:21.856  7596  7616 D SystemConfig: refreshRcsSupport() :false
08-03 19:51:21.942  1041  1762 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7621 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-03 19:51:21.972  5955  6118 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 789)
,08-03 19:51:21.974  5955  6118 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-03 19:51:21.974  5955  6118 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 790)
08-03 19:51:21.981  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:21.982  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2814dcf1 added. We now have 2 listener(s)
08-03 19:51:21.982  1041  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:21.985  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:21.985  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 19:51:21.985  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:21.985  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:21.985  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f99b0d6 added. We now have 9 listener(s)
08-03 19:51:21.985  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:21.986  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:51:21.989  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:51:21.996  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:51:21.997  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:21.997  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:51:21.998  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:21.998  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31b25a44 added. We now have 3 listener(s)
08-03 19:51:21.998  1041  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.000  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.000  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.000  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.000  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.001  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.001  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1509572d added. We now have 10 listener(s)
08-03 19:51:22.001  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.001  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:51:22.001  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:51:22.001  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 19:51:22.003  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.003  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.003  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.003  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.003  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2814dcf1 removed from the list
08-03 19:51:22.003  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.003  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f99b0d6 removed from the list
08-03 19:51:22.005  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.005  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:51:22.005  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.005  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.006  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.006  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.006  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.006  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.006  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f99b0d6 not in the list
08-03 19:51:22.006  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.006  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.007  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.007  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.007  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.007  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1509572d removed from the list
08-03 19:51:22.007  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.007  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.007  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.007  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.007  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31b25a44 removed from the list
08-03 19:51:22.008  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.008  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.Connectio,nManager@27580462 added. We now have 2 listener(s)
08-03 19:51:22.009  1041  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.011  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.011  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.011  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.011  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.011  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@179be9f3 added. We now have 9 listener(s)
08-03 19:51:22.011  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.012  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:51:22.014  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:51:22.016  7621  7621 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:51:22.016  7621  7621 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 19:51:22.017  7621  7621 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 19:51:22.017  7621  7621 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:51:22.018  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:51:22.021  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.021  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:51:22.021  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.021  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f513929 added. We now have 3 listener(s)
08-03 19:51:22.021  1041  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.024  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.024  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.025  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.025  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.025  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.025  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b604ae added. We now have 10 listener(s)
08-03 19:51:22.025  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.025  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:51:22.025  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:51:22.025  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:51:22.025  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:51:22.025  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:51:22.026  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.029  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:51:22.030  1041  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.035  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 19:51:22.035  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:51:22.037  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:51:22.037  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.039  5955  6118 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:51:22.039  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:51:22.039  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:51:22.041  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:51:22.041  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:51:22.041  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:51:22.041  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.041  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.041  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.041  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.041  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27580462 removed from the list
08-03 19:51:22.041  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.041  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@179be9f3 removed from the list
08-03 19:51:22.041  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:51:22.041  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.041  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.042  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.042  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.043  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.043  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.043  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@179be9f3 not in the list
08-03 19:51:22.043  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.043  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.044  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.044  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:51:22.045  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:51:22.045  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.045  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.045  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b604ae removed from the list
08-03 19:51:22.045  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.045  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.045  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.045  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 19:51:22.045  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f513929 removed from the list
08-03 19:51:22.048  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.048  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1b3ee5 added. We now have 2 listener(s)
08-03 19:51:22.048  1041  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.051  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.051  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.051  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.051  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.051  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e1bdba added. We now have 9 listener(s)
08-03 19:51:22.051  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.051  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:51:22.053  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:51:22.057  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:51:22.060  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.060  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:51:22.060  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.061  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3948cbc8 added. We now have 3 listener(s)
08-03 19:51:22.061  1041  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.063  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.064  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.065  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.066  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.066  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.066  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.066  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36c5e461 added. We now have 10 listener(s)
08-03 19:51:22.066  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.066  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:51:22.067  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:51:22.067  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:51:22.067  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:51:22.067  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:51:22.067  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:51:22.070  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 19:51:22.071  1041  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.075  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 19:51:22.076  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:51:22.077  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:51:22.079  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.090  5955  6118 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:51:22.090  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:51:22.090  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:51:22.090  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:51:22.090  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.090  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.090  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.090  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.090  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1b3ee5 removed from the list
08-03 19:51:22.090  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:51:22.090  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e1bdba removed from the list
08-03 19:51:22.090  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:51:22.090  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.091  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.091  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.092  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.092  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.092  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.092  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e1bdba not in the list
08-03 19:51:22.092  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.092  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.099  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.100  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:51:22.100  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:51:22.100  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.100  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.100  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36c5e461 removed from the list
08-03 19:51:22.100  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.100  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:51:22.100  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.100  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.100  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3948cbc8 removed from the list
08-03 19:51:22.101  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.101  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3802dc74 added. We now have 2 listener(s)
08-03 19:51:22.101  1041  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.105  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-03 19:51:22.105  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.105  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.105  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.105  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e1b659d added. We now have 9 listener(s)
08-03 19:51:22.105  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:51:22.108  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:51:22.111  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:51:22.115  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:51:22.116  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.116  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:51:22.117  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.117  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9335e3 added. We now have 3 listener(s)
08-03 19:51:22.117  1041  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.119  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:51:22.121  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.122  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.123  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.123  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.123  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.123  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cab4be0 added. We now have 10 listener(s)
08-03 19:51:22.123  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.123  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:51:22.123  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:51:22.123  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:51:22.123  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:51:22.123  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:51:22.127  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:51:22.127  1041  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.131  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 19:51:22.132  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 19:51:22.134  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:51:22.135  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.137  5955  6118 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:51:22.138  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:51:22.139  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:51:22.139  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:51:22.139  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.139  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.139  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.139  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.139  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3802dc74 removed from the list
08-03 19:51:22.139  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.139  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e1b659d removed from the list
08-03 19:51:22.139  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:51:22.139  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.139  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.139  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.140  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.140  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.140  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.140  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e1b659d not in the list
08-03 19:51:22.140  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.140  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.141  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.142  5955  6118 D BluetoothLeScanner: could not find callback wrapper
08-03 19:51:22.142  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:51:22.142  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.142  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.142  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cab4be0 removed from the list
08-,03 19:51:22.142  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.142  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.142  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.142  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.142  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9335e3 removed from the list
08-03 19:51:22.143  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.143  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24394d3f added. We now have 2 listener(s)
08-03 19:51:22.143  1041  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.146  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.146  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.146  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.146  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:51:22.146  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa9460c added. We now have 9 listener(s)
08-03 19:51:22.146  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.147  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:51:22.149  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:51:22.153  5955  6118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:51:22.156  5955  6118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:51:22.156  5955  6118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:51:22.158  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:51:22.158  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1005096a added. We now have 3 listener(s)
08-03 19:51:22.159  1041  1679 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:51:22.159  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:51:22.161  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:51:22.162  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:51:22.162  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:51:22.163  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:51:22.163  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:51:22.163  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cff7e5b added. We now have 10 listener(s)
08-03 19:51:22.163  5955  6118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:51:22.164  5955  6118 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:51:22.164  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:51:22.164  5955  6118 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:51:22.164  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.164  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.164  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:51:22.164  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.164  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24394d3f removed from the list
08-03 19:51:22.164  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.164  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa9460c removed from the list
08-03 19:51:22.164  5955  6118 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:51:22.164  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.165  7621  7621 I AppConfig: Total System Memory = 2995761152
08-03 19:51:22.166  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.166  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.167  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.167  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.167  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.167  5955  6118 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa9460c not in the list
08-03 19:51:22.167  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.167  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.170  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:51:22.170  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:51:22.170  5955  6118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:51:22.170  5955  6118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cff7e5b removed from the list
08-03 19:51:22.170  5955  6118 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:51:22.171  5955  6118 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:51:22.171  5955  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:51:22.171  5955  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:51:22.171  5955  6118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1005096a removed from the list
08-03 19:51:22.173  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 19:51:22.174  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 19:51:22.174  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-03 19:51:22.175  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:51:22.175  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-03 19:51:22.175  5955  6118 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 19:51:22.187  7621  7621 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-03 19:51:22.196  5955  7644 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 798, name: My test thread name)
,08-03 19:51:22.300  1041  1762 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7646 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:51:22.302  1041  1762 I ActivityManager: Killing 6751:com.lge.drmservice/u0a62 (adj 15): empty #17
08-03 19:51:22.360  1041  1961 W libprocessgroup: failed to open /acct/uid_10062/pid_6751/cgroup.procs: No such file or directory
,08-03 19:51:22.529  7500  7536 D UEI.SmartControl: Internal timer expired: 1
08-03 19:51:22.529  7500  7536 D UEI.SmartControl: unbind internal service
,08-03 19:51:22.531  7500  7500 D UEI.SmartControl: Service.onUnbind: IControl
08-03 19:51:22.531  7500  7500 D UEI.SmartControl: Service.onDestroy
08-03 19:51:22.532  7500  7500 D UEI.SmartControl: Lock is in USE false
08-03 19:51:22.532  7500  7500 D UEI.SmartControl: unbind internal service
08-03 19:51:22.532  7500  7500 D serial_port: close(fd = 25)
08-03 19:51:22.535  7500  7500 I UEI.SmartControl: Serial port is closed.
08-03 19:51:22.536  7500  7500 I UEI.SmartControl: Serial port is closed.
08-03 19:51:22.536  7500  7500 D UEI.SmartControl: Blaster closed
08-03 19:51:22.537  7500  7500 D UEI.SmartControl: Shut down QS...
08-03 19:51:22.537  7500  7500 D UEI.SmartControl: Stopping QS lib
08-03 19:51:22.537  7500  7500 D UEI.SmartControl: QS lib stop result = true
08-03 19:51:22.537  7500  7500 D UEI.SmartControl: Stopped QS lib
08-03 19:51:22.538  7500  7500 D UEI.SmartControl: Stopped file observer...
08-03 19:51:22.538  7500  7500 D UEI.SmartControl: QS shutdown complete
08-03 19:51:22.577  7646  7646 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-03 19:51:22.684  7646  7646 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:51:22.684  7646  7646 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:51:22.740  7646  7646 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-03 19:51:22.761  7646  7646 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-03 19:51:22.762  7646  7646 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 19:51:22.786  1041  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=11.7, 0.0, 0.0  rx=9.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1367867554] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:51:22.790  7646  7646 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-03 19:51:22.790  7646  7646 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-03 19:51:22.791  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=11.7, 0.0, 0.0  rx=9.1 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:1367867559] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:51:22.791  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 19:51:22.823  3430  4508 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-03 19:51:22.827  3430  4508 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3c3a0dc0 on behalf of 7646
08-03 19:51:22.831  1041  1997 I ActivityManager: Killing 6808:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-03 19:51:22.892  1041  2027 W libprocessgroup: failed to open /acct/uid_10093/pid_6808/cgroup.procs: No such file or directory
,08-03 19:51:22.909  4534  7690 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-03 19:51:22.911  7646  7646 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-03 19:51:22.951  1041  1058 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7692 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-03 19:51:22.992  7646  7646 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-03 19:51:23.071  7692  7692 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-03 19:51:23.096  7692  7692 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-03 19:51:23.096  7692  7692 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-03 19:51:23.096  7692  7692 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 19:51:23.096  7692  7692 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-03 19:51:23.096  7692  7692 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 19:51:23.096  7692  7692 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-03 19:51:23.121  1041  1058 I ActivityManager: Killing 7370:com.lge.email/u0a23 (adj 15): empty #17
,08-03 19:51:23.203  1041  1888 W libprocessgroup: failed to open /acct/uid_10023/pid_7370/cgroup.procs: No such file or directory
,08-03 19:51:23.348  1041  1925 I art     : Explicit concurrent mark sweep GC freed 28766(1403KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.604ms total 132.412ms
,08-03 19:51:23.465  1041  1058 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:51:23.476  4534  7690 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 567 ms] updated apps [took 567 ms] 
,08-03 19:51:23.953  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-03 19:51:23.963  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
08-03 19:51:24.195  5955  6118 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 798
08-03 19:51:24.195  5955  6118 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 798, name: My test thread name)
,08-03 19:51:24.210  5955  7733 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 799, name: My test thread name)
08-03 19:51:24.210  5955  7733 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 799, thread name: My test thread name)
08-03 19:51:24.210  5955  7733 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 799, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-03 19:51:24.215  5955  6118 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 19:51:24.223  5955  7734 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 803, name: My test thread name)
08-03 19:51:24.224  5955  7734 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 803, thread name: My test thread name): Test exception.
08-03 19:51:24.224  5955  7734 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 803, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-03 19:51:24.227  5955  6118 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
08-03 19:51:24.227  5955  6118 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
08-03 19:51:24.227  5955  6118 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-03 19:51:24.227  5955  6118 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-03 19:51:24.227  5955  6118 D com.test.thalitest.ThaliTestRunner: Total duration: 35939 ms
08-03 19:51:24.230  5955  6118 I jxcore-log: Total number of executed tests:  82
08-03 19:51:24.230  5955  6118 I jxcore-log: 
08-03 19:51:24.231  5955  6118 I jxcore-log: Number of passed tests:  82
08-03 19:51:24.231  5955  6118 I jxcore-log: 
08-03 19:51:24.231  5955  6118 I jxcore-log: Number of failed tests:  0
08-03 19:51:24.231  5955  6118 I jxcore-log: 
08-03 19:51:24.231  5955  6118 I jxcore-log: Number of ignored tests:  0
08-03 19:51:24.231  5955  6118 I jxcore-log: 
08-03 19:51:24.231  5955  6118 I jxcore-log: Total duration:  35939
08-03 19:51:24.231  5955  6118 I jxcore-log: 
08-03 19:51:24.234  5955  6118 I jxcore-log: Unit Test app is loaded
08-03 19:51:24.234  5955  6118 I jxcore-log: 
08-03 19:51:24.255  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.255  5955  6118 I jxcore-log: 
,08-03 19:51:24.272  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.272  5955  6118 I jxcore-log: 
08-03 19:51:24.273  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.273  5955  6118 I jxcore-log: 
08-03 19:51:24.274  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.274  5955  6118 I jxcore-log: 
08-03 19:51:24.275  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.275  5955  6118 I jxcore-log: 
08-03 19:51:24.277  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.277  5955  6118 I jxcore-log: 
,08-03 19:51:24.282  5955  5955 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 19:51:24.285  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.285  5955  6118 I jxcore-log: 
08-03 19:51:24.287  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 19:51:24.287  5955  6118 I jxcore-log: 
08-03 19:51:24.289  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.289  5955  6118 I jxcore-log: 
08-03 19:51:24.289  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.289  5955  6118 I jxcore-log: 
08-03 19:51:24.290  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.290  5955  6118 I jxcore-log: 
08-03 19:51:24.292  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.292  5955  6118 I jxcore-log: 
08-03 19:51:24.293  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.293  5955  6118 I jxcore-log: 
08-03 19:51:24.293  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.293  5955  6118 I jxcore-log: 
08-03 19:51:24.294  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.294  5955  6118 I jxcore-log: 
08-03 19:51:24.295  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.295  5955  6118 I jxcore-log: 
08-03 19:51:24.296  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.296  5955  6118 I jxcore-log: 
08-03 19:51:24.297  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:51:24.297  5955  6118 I jxcore-log: 
08-03 19:51:24.298  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.298  5955  6118 I jxcore-log: 
08-03 19:51:24.299  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:51:24.299  5955  6118 I jxcore-log: 
08-03 19:51:24.300  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:51:24.300  5955  6118 I jxcore-log: 
08-03 19:51:24.301  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:51:24.301  5955  6118 I jxcore-log: 
08-03 19:51:24.302  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:51:24.302  5955  6118 I jxcore-log: 
08,-03 19:51:24.303  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:51:24.303  5955  6118 I jxcore-log: 
08-03 19:51:24.303  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:51:24.303  5955  6118 I jxcore-log: 
08-03 19:51:24.304  5955  6118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:51:24.304  5955  6118 I jxcore-log: 
08-03 19:51:24.307  5955  6118 I jxcore-log: My device name is: LGE-LG-D855
08-03 19:51:24.307  5955  6118 I jxcore-log: 
08-03 19:51:24.308  5955  6118 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 19:51:24.308  5955  6118 I jxcore-log: 
,08-03 19:51:24.314  5955  7644 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 798, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
08-03 19:51:25.810  1041  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1367870578] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:51:25.812  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1367870580] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:51:25.812  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:51:26.780  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 19:51:26.780  5955  6118 I jxcore-log: 
,08-03 19:51:27.431  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 19:51:27.431  5955  6118 I jxcore-log: 
,08-03 19:51:27.453  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 19:51:27.453  5955  6118 I jxcore-log: 
,08-03 19:51:28.783  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 19:51:28.783  5955  6118 I jxcore-log: 
,08-03 19:51:28.836  1041  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1367873604] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:51:28.839  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1367873607] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:51:28.839  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:51:29.005  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-03 19:51:29.005  5955  6118 I jxcore-log: 
,08-03 19:51:29.012  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-03 19:51:29.012  5955  6118 I jxcore-log: 
08-03 19:51:29.015  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-03 19:51:29.015  5955  6118 I jxcore-log: 
08-03 19:51:29.031  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-03 19:51:29.031  5955  6118 I jxcore-log: 
,08-03 19:51:29.035  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-03 19:51:29.035  5955  6118 I jxcore-log: 
08-03 19:51:29.689  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-03 19:51:29.689  5955  6118 I jxcore-log: 
,08-03 19:51:29.703  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-03 19:51:29.703  5955  6118 I jxcore-log: 
,08-03 19:51:29.713  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-03 19:51:29.713  5955  6118 I jxcore-log: 
,08-03 19:51:29.720  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-03 19:51:29.720  5955  6118 I jxcore-log: 
,08-03 19:51:29.767  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-03 19:51:29.767  5955  6118 I jxcore-log: 
,08-03 19:51:29.821  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-03 19:51:29.821  5955  6118 I jxcore-log: 
,08-03 19:51:29.829  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-03 19:51:29.829  5955  6118 I jxcore-log: 
,08-03 19:51:29.992  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-03 19:51:29.992  5955  6118 I jxcore-log: 
,08-03 19:51:30.019  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-03 19:51:30.019  5955  6118 I jxcore-log: 
,08-03 19:51:30.024  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-03 19:51:30.024  5955  6118 I jxcore-log: 
,08-03 19:51:30.030  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-03 19:51:30.030  5955  6118 I jxcore-log: 
,08-03 19:51:30.047  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-03 19:51:30.047  5955  6118 I jxcore-log: 
,08-03 19:51:30.128  5955  6118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-03 19:51:30.128  5955  6118 I jxcore-log: 
,08-03 19:51:30.467  5955  6118 I jxcore-log: ERROR runTests: 
08-03 19:51:30.467  5955  6118 I jxcore-log: 
08-03 19:51:30.469  5955  6118 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliPullReplicationFromNotification'
08-03 19:51:30.469  5955  6118 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-03 19:51:30.470  5955  6118 I jxcore-log: WARN testUtils: logCallback not set!
08-03 19:51:30.470  5955  6118 I jxcore-log: 
,08-03 19:51:30.480  5955  6118 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _functionName: 'loadFile',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _lineNumber: '26',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _columnNumber: '11',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-03 19:51:30.480  5955  6118 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _functionName: '',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _lineNumber: '39',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _columnNumber: '7',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-03 19:51:30.480  5955  6118 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _functionName: '',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _lineNumber: '35',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _columnNumber: '3',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-03 19:51:30.480  5955  6118 I jxcore-log:   { _fileName: 'module.js',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _functionName: '$w.prototype._compile',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _lineNumber: '621',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _columnNumber: '8',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-03 19:51:30.480  5955  6118 I jxcore-log:   { _fileName: 'module.js',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _lineNumber: '651',
08-03 19:51:30.480  5955  6118 I jxcore-log:     _columnNumber: '1',
08-03 19:51:30.480  5955  6118 I jxcore-log:    
,08-03 19:51:30.481  5955  6118 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-03 19:51:30.481  5955  6118 I jxcore-log: 
08-03 19:51:30.481  5955  6118 E jxcore-log: Error: 
08-03 19:51:30.481  5955  6118 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliPullReplicationFromNotification'
08-03 19:51:30.481  5955  6118 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-03 19:51:30.481  5955  6118 E jxcore-log: 
08-03 19:51:31.864  1041  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1367876632] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:51:31.868  1041  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1367876635] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:51:31.868  1041  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:51:32.190  7744  7744 D AndroidRuntime: 
08-03 19:51:32.190  7744  7744 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-03 19:51:32.196  7744  7744 D AndroidRuntime: CheckJNI is OFF
08-03 19:51:32.318  7744  7744 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 19:51:32.328  1041  1106 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-03 19:51:32.329  1041  1106 I ActivityManager: Killing 5955:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-03 19:51:32.366  1041  1679 I WindowState: WIN DEATH: Window{1a28a73f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 19:51:32.370  1041  1529 D WifiService: Client connection lost with reason: 4
08-03 19:51:32.375  1041  1679 D InputDispatcher: Window went away: Window{1a28a73f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 19:51:32.457  1041  1106 I ActivityManager:   Force finishing activity ActivityRecord{3677d3ac u0 com.test.thalitest/.MainActivity t40}
,08-03 19:51:32.472   341   359 E GBMv2   : DFP En is all cleared set to be enabled
,08-03 19:51:32.473  1041  1889 W ActivityManager: Spurious death for ProcessRecord{1b4035f4 5955:com.test.thalitest/u0a118}, curProc for 5955: null
,08-03 19:51:32.473  1041  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-03 19:51:32.475  1041  1125 I ActivityManager:   Force finishing activity ActivityRecord{3677d3ac u0 com.test.thalitest/.MainActivity t40 f}
08-03 19:51:32.475  1041  1125 W ActivityManager: Duplicate finish request for ActivityRecord{3677d3ac u0 com.test.thalitest/.MainActivity t40 f}
,08-03 19:51:32.505  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-03 19:51:32.506  1926  2517 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-03 19:51:32.506  1926  2517 D SplitWindowPolicy: topRunningActivity=ActivityInfo{cd61998 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-03 19:51:32.506  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-03 19:51:32.507  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-03 19:51:32.507  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{168565f1 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-03 19:51:32.511  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-03 19:51:32.511  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-03 19:51:32.511  2017  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-03 19:51:32.517  1041  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 19:51:32.521  4534  4534 I art     : Explicit concurrent mark sweep GC freed 8061(465KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 9.301ms total 41.386ms
,08-03 19:51:32.525  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 19:51:32.526  2707  2707 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-03 19:51:32.526  6965  6965 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-03 19:51:32.526  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-03 19:51:32.539  4411  4411 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-03 19:51:32.539  4411  4411 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-03 19:51:32.539  4411  4411 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-03 19:51:32.539  4411  4411 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-03 19:51:32.539  4411  4411 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:51:32.539  4411  4411 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:51:32.539  4411  4411 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:51:32.539  4411  4411 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:51:32.539  4411  4411 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:51:32.539  4411  4411 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:51:32.539  4411  4411 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:51:32.539  4411  4411 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:51:32.540  3666  3666 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 19:51:32.565  2492  2669 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-03 19:51:32.573  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-03 19:51:32.573  1890  1890 D ActionManagerService: notifyUserLog: 1000003
08-03 19:51:32.575  2707  4434 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-03 19:51:32.579  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-03 19:51:32.587  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-03 19:51:32.589  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-03 19:51:32.597  2146  2146 I ConfigService: onCreate
08-03 19:51:32.597  2146  2146 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-03 19:51:32.607  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-03 19:51:32.614  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-03 19:51:32.622  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-03 19:51:32.629  1587  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 19:51:32.629  1587  1649 D KeyguardModel: createShortcutInfo...
08-03 19:51:32.630  2146  2146 I ConfigService: onBind returning update interface
08-03 19:51:32.634  1890  1890 D ActionManagerService: notifyUserLog: 1000004
08-03 19:51:32.634  2707  4434 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-03 19:51:32.634  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-03 19:51:32.643  2707  2758 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , display: false
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , animation: false }
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , display: false
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , animation: false }
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , create_time: 1469801565454
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , display: false
08-03 19:51:32.645  2017  2017 I GBoardWebViewUtils: , animation: false }
08-03 19:51:32.647  2146  2146 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-03 19:51:32.647  2146  2146 I ConfigService: onBind returning config service
08-03 19:51:32.648  1587  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 19:51:32.648  1587  1649 D KeyguardModel: createShortcutInfo...
,08-03 19:51:32.652  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-03 19:51:32.653  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-03 19:51:32.653  2146  2146 I ConfigService: onDestroy
08-03 19:51:32.656  1041  1997 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:51:32.658  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-03 19:51:32.659  1854  1854 D SplitUIService: removed split : 
,08-03 19:51:32.663  2017  7775 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-03 19:51:32.664  1587  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-03 19:51:32.666  1587  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:51:32.666  1587  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 19:51:32.667  1587  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:51:32.668  1587  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:51:32.668  1587  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 19:51:32.674  1587  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 19:51:32.674  1587  1649 D KeyguardModel: createShortcutInfo...
08-03 19:51:32.674  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-03 19:51:32.675  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-03 19:51:32.678  1587  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 19:51:32.678  1587  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:51:32.682  1587  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:51:32.682  1587  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 19:51:32.685  1041  1041 I art     : Explicit concurrent mark sweep GC freed 16727(1276KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.282ms total 193.703ms
08-03 19:51:32.686  1802  7778 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-03 19:51:32.690  1041  1125 I art     : WaitForGcToComplete blocked for 187.771ms for cause Explicit
08-03 19:51:32.699  1587  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 19:51:32.699  1587  1649 D KeyguardModel: createShortcutInfo...
08-03 19:51:32.705  1587  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:51:32.705  1587  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 19:51:32.705  1587  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 19:51:32.705  1587  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:51:32.706  1587  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:51:32.706  1587  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 19:51:32.708  1041  1925 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:51:32.708  1041  1925 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:51:32.711  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-03 19:51:32.711  1854  1854 I SplitUIService: split app #11
08-03 19:51:32.711  1587  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 19:51:32.711  1587  1649 D KeyguardModel: createShortcutInfo...
,08-03 19:51:32.721  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-03 19:51:32.721  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 19:51:32.741  1587  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 19:51:32.741  1587  1649 D KeyguardModel: createShortcutInfo...
,08-03 19:51:32.744  1587  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 19:51:32.744  1587  1649 D KeyguardModel: createShortcutInfo...
08-03 19:51:32.760  1041  1762 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:51:32.761  6965  6965 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-03 19:51:32.762  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-03 19:51:32.765  1587  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:51:32.765  1587  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 19:51:32.765  1587  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 19:51:32.765  1587  1649 D KeyguardModel: createShortcutInfo...
08-03 19:51:32.767  1041  1041 D administrator: Handling package changes for user 0
08-03 19:51:32.768  1587  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:51:32.768  1587  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 19:51:32.769  1587  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 19:51:32.769  1587  1649 D KeyguardModel: createShortcutInfo...
08-03 19:51:32.770  1587  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:51:32.770  1587  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 19:51:32.772  1587  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 19:51:32.772  1587  1649 D KeyguardModel: createShortcutInfo...
08-03 19:51:32.778  5478  7782 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-03 19:51:32.779  2146  2165 I art     : Explicit concurrent mark sweep GC freed 8465(529KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 577us total 30.689ms
08-03 19:51:32.784  1802  7786 I PeopleContactsSync: CP2 sync disabled
08-03 19:51:32.792  1802  4666 I Icing   : doRemovePackageData com.test.thalitest
,08-03 19:51:32.794  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-03 19:51:32.794  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 19:51:32.802  1802  7785 W GmsApplication: Using Auth Proxy for data requests.
08-03 19:51:32.812  1802  7785 W GmsApplication: Using Auth Proxy for data requests.
,08-03 19:51:32.832  1041  1998 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:51:32.833   333   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 19:51:32.834  3184  7789 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 19:51:32.836  1041  1041 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-03 19:51:32.836  1041  1041 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-03 19:51:32.836  1041  1041 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-03 19:51:32.838  1041  1562 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,08-03 19:51:32.839  7340  7340 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-03 19:51:32.854  2353  7791 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-03 19:51:32.861  1041  1103 W InputMethodInfo: Duplicated subtype definition found: , voice
08-03 19:51:32.875  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-03 19:51:32.879  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:32.883  1041  1058 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7792 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-03 19:51:32.884  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-03 19:51:32.885  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-03 19:51:32.886  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-03 19:51:32.887  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-03 19:51:32.893   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 200us total 10.764ms
08-03 19:51:32.899  1041  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22d489e5 u0 com.lge.launcher2/.Launcher t39} time:197311
08-03 19:51:32.902   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.032ms
,08-03 19:51:32.905  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-03 19:51:32.906  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:32.912   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 8.891ms
08-03 19:51:32.915  2017  2121 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-03 19:51:32.915  2017  2121 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-03 19:51:32.920  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-03 19:51:32.922  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 19:51:32.923  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:32.931  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-03 19:51:32.935  2017  2017 D [Concierge]WidgetView: change position of spinner
08-03 19:51:32.935  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1470246692935
08-03 19:51:32.937  2573  2573 D [Concierge]Service: onStartCommand(). Type : 8
08-03 19:51:32.937  2573  2573 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-03 19:51:32.938  2573  2573 D [Concierge]Service: Update widget ID : 11
08-03 19:51:32.939  2573  2573 D [Concierge]Service: onStartCommand(). Type : 0
08-03 19:51:32.940  7792  7792 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:51:32.941  7792  7792 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:51:32.941  7792  7792 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:51:32.942  7792  7792 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:51:32.959  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 555274030
,08-03 19:51:32.960  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-03 19:51:32.960  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-03 19:51:32.963  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2c5e76b0
08-03 19:51:32.964  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-03 19:51:32.964  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 19:51:32.964  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:32.970  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-03 19:51:32.970  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 19:51:32.971  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470246523249, New one : 1470246692935
08-03 19:51:32.971  2017  2017 D [Concierge]WidgetView: Unregister all receivers
08-03 19:51:32.971  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 19:51:32.971  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-03 19:51:32.971  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 19:51:32.975  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-03 19:51:32.976  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-03 19:51:32.977  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-03 19:51:32.978  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-03 19:51:32.979  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-03 19:51:32.983  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:32.983  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 19:51:32.985  1041  1125 I art     : Explicit concurrent mark sweep GC freed 6795(363KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.611ms total 286.957ms
08-03 19:51:33.017  7792  7792 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 19:51:33.026  7792  7792 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-03 19:51:33.032  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-03 19:51:33.040  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-03 19:51:33.040  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-03 19:51:33.041  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:51:33.056  7792  7792 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 19:51:33.065  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c58df9b time:197476
08-03 19:51:33.076  7792  7792 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:51:33.076  7792  7792 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:51:33.080  7744  7744 D AndroidRuntime: Shutting down VM
,08-03 19:51:33.129  7792  7792 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-03 19:51:33.137  1041  1103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:51:33.140  1041  1997 I ActivityManager: Killing 7447:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-03 19:51:33.142  1041  1103 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-03 19:51:33.170  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-03 19:51:33.204  2017  2890 I GBoardtInterface: onReloaded()
,08-03 19:51:33.206  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-03 19:51:33.209  1980  1980 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 19:51:33.209  1980  1980 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-03 19:51:33.209  1041  1961 W libprocessgroup: failed to open /acct/uid_1000/pid_7447/cgroup.procs: No such file or directory
08-03 19:51:33.211  2707  2723 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:51:33.211  1980  1980 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-03 19:51:33.213  3666  3666 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 19:51:33.214  2707  2763 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:51:33.242  1041  1925 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7817 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 19:51:33.247  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-03 19:51:33.249  2707  4434 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 19:51:33.249  2707  4434 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 19:51:33.251  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-03 19:51:33.253  2707  4434 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 19:51:33.253  2707  4434 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 19:51:33.253  2707  4434 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-03 19:51:33.253  2707  4434 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-03 19:51:33.254  2707  2763 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:51:33.255  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-03 19:51:33.255  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-03 19:51:33.257  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,08-03 19:51:33.257  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 19:51:33.259  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-03 19:51:33.259  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-03 19:51:33.262  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-03 19:51:33.318  1041  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7836 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-03 19:51:33.322  7817  7817 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 19:51:33.322  7817  7817 W LG Account v2.2: No ProfileInfo entries
08-03 19:51:33.323  7817  7817 I LG Account v2.2: isEnabled: false
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Country: EU
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Operator: OPEN
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Ranking support: false
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Comfort support: false
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Accessory: true
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Health device: true
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Extra Pedometer: false
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Blood glucose device: false
08-03 19:51:33.323  7817  7817 I Feature : [Lifetracker]Device Number: 3
08-03 19:51:33.324  7817  7817 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-03 19:51:33.355  1041  1059 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7854 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:51:33.356  1041  1059 I ActivityManager: Killing 7465:com.android.calendar/u0a13 (adj 15): empty #17

```
