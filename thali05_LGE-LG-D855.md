#### Test 79751015a95812e_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 08:01:38.223  5871  5871 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-05 08:01:38.308  5871  5871 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:01:38.308  5871  5871 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 08:01:38.365  5871  5871 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-05 08:01:38.387  5871  5871 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 08:01:38.389  5871  5871 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 08:01:38.405  5871  5871 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 08:01:38.406  5871  5871 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
08-05 08:01:38.416  1027  1942 I ActivityManager: Killing 5353:com.lge.clock/u0a10 (adj 15): empty #17
08-05 08:01:38.474  1027  2317 W libprocessgroup: failed to open /acct/uid_10010/pid_5353/cgroup.procs: No such file or directory
08-05 08:01:38.484  4567  5913 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-05 08:01:38.534  1027  1771 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5914 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 08:01:38.546  3431  3446 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 08:01:38.559  3431  3446 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f938fe1 on behalf of 5871
08-05 08:01:38.592  5871  5871 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-05 08:01:38.615  5871  5871 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-05 08:01:38.689  5914  5914 D DocsApplication: Installing DEX configuration.
08-05 08:01:38.706  5914  5914 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-05 08:01:38.709  5914  5914 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{be392fc com.google.android.apps.docs}
08-05 08:01:38.722  5914  5914 D TAG     : onCreate()
08-05 08:01:38.740  5914  5914 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-05 08:01:38.936  1027  1942 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:01:39.015  4567  5913 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 529 ms] updated apps [took 528 ms] 
08-05 08:01:39.245  5949  5949 D AndroidRuntime: 
08-05 08:01:39.245  5949  5949 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 08:01:39.248  5949  5949 D AndroidRuntime: CheckJNI is OFF
08-05 08:01:39.450  5949  5949 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 08:01:39.457  1027  1043 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 08:01:39.468  1961  1977 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 08:01:39.470  1027  1043 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 08:01:39.471  1027  1043 D ActivityManager: setTaskToReturnTo : TaskRecord{1503397c #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 08:01:39.471  1027  1043 D ActivityManager: setTaskToReturnTo : TaskRecord{1503397c #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 08:01:39.472  1027  1043 D WindowStateEx: AppWindowTokenEx init.. 
08-05 08:01:39.473   329   367 E GBMv2   : DFP En is all cleared set to be enabled
08-05 08:01:39.507  1027  1043 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5967 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 08:01:39.508  5949  5949 D AndroidRuntime: Shutting down VM
08-05 08:01:39.561  1961  1977 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 08:01:39.562  1961  1977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{278cbdaa co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 08:01:39.562  1961  1976 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 08:01:39.563  1961  1976 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1432bd9b co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 08:01:39.615  5967  5967 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 08:01:39.689  5967  5967 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-05 08:01:39.696  5967  5967 I LibraryLoader: Loading: webviewchromium
08-05 08:01:39.699  5967  5967 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3971-3974)
08-05 08:01:39.699  5967  5967 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 08:01:39.716  5967  5967 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2dfcb7a6}
08-05 08:01:39.718  5967  5967 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 08:01:39.718  5967  5967 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 08:01:39.727  5967  5967 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 08:01:39.728  5967  5967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 08:01:39.733  5967  5991 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-05 08:01:39.737  5967  5967 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 08:01:39.738  5967  5967 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 08:01:39.739  5967  5967 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-05 08:01:39.760   312  1378 V AudioPolicyService: registerClient() client 0xb558a380, uid 10118
08-05 08:01:39.761  5967  5967 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 08:01:39.761  5967  5967 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 08:01:39.761  5967  5967 I Adreno-EGL: Build Date: 12/12/14 금
08-05 08:01:39.761  5967  5967 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 08:01:39.761  5967  5967 I Adreno-EGL: Remote Branch: 
08-05 08:01:39.761  5967  5967 I Adreno-EGL: Local Patches: 
08-05 08:01:39.761  5967  5967 I Adreno-EGL: Reconstruct Branch: 
08-05 08:01:39.766  1027  1089 D BluetoothManagerService: Message: 20
08-05 08:01:39.766  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@255b2a26:true
08-05 08:01:39.831  1812  4724 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-05 08:01:39.839  5967  6002 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-05 08:01:39.841  5967  5967 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 08:01:39.857  5967  5967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 08:01:39.861  5967  5967 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 08:01:39.865  5967  5967 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 08:01:39.868  5967  5967 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 08:01:39.868  5967  5967 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 08:01:39.879  1812  4724 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-05 08:01:39.884  5967  5967 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-05 08:01:39.890  5967  5967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 08:01:39.890  5967  5967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 08:01:39.931  5967  6014 D OpenGLRenderer: Render dirty regions requested: true
08-05 08:01:39.931  5967  6014 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 08:01:39.934  5967  6014 D OpenGLRenderer: Enabling debug mode 0
08-05 08:01:39.944  5967  5967 D Atlas   : Validating map...
08-05 08:01:39.947  1027  1942 D SplitWindow: check instance of lgWin Window{125ceb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 08:01:39.964  1812  4724 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-05 08:01:39.975  5967  6012 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:01:39.975  5967  6012 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 08:01:40.042  5914  5914 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:01:40.042  5914  5914 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 08:01:40.048  1027  1090 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +490ms (total +574ms)
08-05 08:01:40.048  1027  1090 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1fcb7205 u0 com.test.thalitest/.MainActivity t40} time:134324
08-05 08:01:40.048  5967  5967 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8be5aad time:134324
08-05 08:01:40.143  5967  5967 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-05 08:01:40.169  5967  5967 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 08:01:40.169  5967  5967 I chromium: 
08-05 08:01:40.186  5967  6012 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 08:01:40.186  5967  6012 I chromium: 
08-05 08:01:40.246  1027  2026 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6036 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-05 08:01:40.257  5914  5914 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-05 08:01:40.270   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 23.760ms
08-05 08:01:40.289   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 349us total 18.630ms
08-05 08:01:40.302  5967  6057 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435135488
08-05 08:01:40.306   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 17.252ms
08-05 08:01:40.309  5967  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 08:01:40.309  5967  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 08:01:40.309  5967  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 08:01:40.309  5967  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 08:01:40.309  5967  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 08:01:40.309  5967  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f938fe1 added. We now have 1 listener(s)
08-05 08:01:40.312  1027  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:40.314  5967  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 08:01:40.315  5967  6057 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:01:40.316  5967  6057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:01:40.316  5967  6057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 08:01:40.320  5967  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38df1df4 added. We now have 1 listener(s)
08-05 08:01:40.320  5967  6057 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:01:40.322  1027  1538 D WifiService: New client listening to asynchronous messages
08-05 08:01:40.325  5967  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:01:40.325  5967  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 08:01:40.325  5967  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 08:01:40.325  5967  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 08:01:40.325  5967  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 08:01:40.327  5967  6057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:40.327  1027  2317 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:40.328  5967  6057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 08:01:40.334  5967  6057 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:40.334  5967  6057 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:40.334  5967  6057 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 08:01:40.335  5967  6057 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:01:40.335  5967  6057 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 08:01:40.336  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:40.340  6036  6036 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-05 08:01:40.354  6036  6036 I LockScreenSettings: New app installed broadcast received ..
08-05 08:01:40.356  6036  6036 I LockScreenSettings: Number of installed packages  1
08-05 08:01:40.367  5967  5967 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-05 08:01:40.389  1027  1905 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6061 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 08:01:40.390  1027  1905 I ActivityManager: Killing 5111:com.lge.bnr/1000 (adj 15): empty #17
08-05 08:01:40.475  1027  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_5111/cgroup.procs: No such file or directory
08-05 08:01:40.496  6061  6061 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 08:01:40.976  1027  2036 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:01:41.001  1027  1960 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 08:01:41.065  2215  2215 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-05 08:01:41.066  2215  2215 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-05 08:01:41.109  1027  2093 I art     : Explicit concurrent mark sweep GC freed 26537(1345KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.340ms total 65.760ms
,08-05 08:01:41.115  6089  6089 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-05 08:01:41.115  6089  6089 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-05 08:01:41.162  1027  1942 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6117 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-05 08:01:41.165  1027  1942 I ActivityManager: Killing 5428:com.google.android.gm/u0a64 (adj 15): empty #17
,08-05 08:01:41.233  5967  6060 W jxcore-log: Initializing JXcore engine
08-05 08:01:41.233  5967  6060 W jxcore-log: JXcore engine is ready
08-05 08:01:41.234  1027  1960 W libprocessgroup: failed to open /acct/uid_10064/pid_5428/cgroup.procs: No such file or directory
08-05 08:01:41.267  6060  6060 W Thread-677: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[10241]" dev="sockfs" ino=10241 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 08:01:41.267  6060  6060 W Thread-677: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 08:01:41.267  6060  6060 W Thread-677: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10402]" dev="sockfs" ino=10402 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 08:01:41.267  6060  6060 W Thread-677: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 08:01:41.267  6060  6060 W Thread-677: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[28434]" dev="sockfs" ino=28434 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-05 08:01:41.290  5967  6060 W jxcore-log: Starting JXcore engine
08-05 08:01:41.302  6117  6117 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-05 08:01:41.325  6117  6117 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 08:01:41.326  1027  1942 I ActivityManager: Killing 5470:com.google.android.talk/u0a72 (adj 15): empty #17
,08-05 08:01:41.364  5967  6060 W jxcore-log: Platform android
08-05 08:01:41.364  5967  6060 W jxcore-log: 
08-05 08:01:41.364  5967  6060 W jxcore-log: Process ARCH arm
08-05 08:01:41.364  5967  6060 W jxcore-log: 
,08-05 08:01:41.408  1027  2026 W libprocessgroup: failed to open /acct/uid_10072/pid_5470/cgroup.procs: No such file or directory
,08-05 08:01:41.454   329   369 E GBMv2   : DFP En is all cleared set to be enabled
08-05 08:01:41.454   329   369 E GBMv2   : Set value is all cleared set the max
08-05 08:01:41.454   329   369 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 08:01:41.581  5967  6060 I jxcore-log: JXcore Cordova bridge is ready!
08-05 08:01:41.581  5967  6060 I jxcore-log: 
08-05 08:01:41.581  5967  6060 W jxcore-log: JXcore engine is started
,08-05 08:01:41.594  5967  6057 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 08:01:41.601  5967  5967 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-05 08:01:43.010  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 08:01:43.010  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 08:01:43.021  1027  1538 D WifiController: battery changed pluggedType: 2
08-05 08:01:43.025  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-05 08:01:43.025  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 08:01:43.025  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:01:43.026  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:01:43.026  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 08:01:43.031  1961  2133 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 08:01:43.032  1961  2133 D LEDHandler: Battery Level Remaining: 100%
08-05 08:01:43.032  1961  2133 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-05 08:01:43.032  3833  3956 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 08:01:43.032  6117  6117 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 08:01:44.139  5914  5914 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-05 08:01:44.147  1027  1925 I ActivityManager: Killing 5254:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-05 08:01:44.163  5231  5231 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 08:01:44.164  5231  5231 W System.err: android.os.DeadObjectException
08-05 08:01:44.164  5231  5231 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 08:01:44.164  5231  5231 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 08:01:44.164  5231  5231 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 08:01:44.164  5231  5231 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 08:01:44.164  5231  5231 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 08:01:44.164  5231  5231 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 08:01:44.164  5231  5231 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 08:01:44.164  5231  5231 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 08:01:44.164  5231  5231 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 08:01:44.164  5231  5231 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 08:01:44.164  5231  5231 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:01:44.165  5231  5231 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 08:01:44.165  5231  5231 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 08:01:44.165  5231  5231 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 08:01:44.165  5231  5231 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 08:01:44.165  5231  5231 W System.err: android.os.DeadObjectException
08-05 08:01:44.165  5231  5231 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 08:01:44.165  5231  5231 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 08:01:44.165  5231  5231 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 08:01:44.165  5231  5231 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 08:01:44.165  5231  5231 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 08:01:44.165  5231  5231 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 08:01:44.165  5231  5231 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 08:01:44.165  5231  5231 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 08:01:44.166  5231  5231 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 08:01:44.166  5231  5231 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 08:01:44.166  5231  5231 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:01:44.166  5231  5231 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 08:01:44.166  5231  5231 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 08:01:44.166  5231  5231 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 08:01:44.166  5231  5231 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 08:01:44.166  5231  5231 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-05 08:01:44.395  1027  1647 W libprocessgroup: failed to open /acct/uid_1000/pid_5254/cgroup.procs: No such file or directory
08-05 08:01:44.396  1027  1647 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-05 08:01:44.403  5231  5231 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 08:01:44.404  5231  5231 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 08:01:44.446  1027  2317 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 08:01:44.446  5231  5231 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 08:01:44.523  6141  6141 D UEI.SmartControl: Quickset Services start...
,08-05 08:01:44.526  6141  6141 I UEI.SmartControl: Manufacture = LGE
08-05 08:01:44.526  6141  6141 D UEI.SmartControl: Id = LGNevo
08-05 08:01:44.527  6141  6141 D UEI.SmartControl: File observer start...
08-05 08:01:44.527  6141  6141 E UEI.SmartControl: IR Port is disabled: false
08-05 08:01:44.528  6141  6141 D UEI.SmartControl: Starting file observer...
08-05 08:01:44.528  6141  6141 D UEI.SmartControl: Extracting JNI libs...
08-05 08:01:44.530  6141  6141 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-05 08:01:44.604  6141  6141 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 08:01:44.604  6141  6141 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 08:01:44.604  6141  6141 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 08:01:44.638  6141  6141 I UEI.SmartControl: --- Selecting new region: 6
,08-05 08:01:44.639  6141  6141 I UEI.SmartControl: Model = LG-D855
08-05 08:01:44.640  6141  6141 D UEI.SmartControl: QS Service created
08-05 08:01:44.651  6141  6141 I UEI.SmartControl: Service initServices...
08-05 08:01:44.654  6141  6141 D UEI.SmartControl: QS start get config
,08-05 08:01:44.692  6141  6141 D UEI.SmartControl: Loading JNI Libs...
,08-05 08:01:44.929  6141  6141 I UEI.SmartControl: Supports setup maps: true
,08-05 08:01:44.933  6141  6141 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 08:01:44.933  6141  6141 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 08:01:44.934  6141  6141 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 08:01:44.934  6141  6141 I UEI.SmartControl: ### init IR Blaster...
08-05 08:01:44.942  6141  6141 D serial_port: Configuring serial port
,08-05 08:01:44.946  6141  6141 E UEI.SmartControl: UEIBLaster setting for 616
08-05 08:01:44.946  6141  6141 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 08:01:44.946  6141  6141 I UEI.SmartControl: configuring settings for MAXQ616
08-05 08:01:44.946  6141  6141 I UEI.SmartControl: Get version...
08-05 08:01:44.962  6141  6174 D UEI.SmartControl: serial port data available: 21
,08-05 08:01:44.989  6141  6141 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 08:01:44.989  6141  6141 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-05 08:01:44.989  6141  6141 I UEI.SmartControl: QS saving settings...
08-05 08:01:44.990  6141  6141 D UEI.SmartControl: IR Blaster version: 25672567
08-05 08:01:45.006  6141  6174 D UEI.SmartControl: serial port data available: 4
,08-05 08:01:45.037  6141  6177 I UEI.SmartControl: Device manager: loading config....
08-05 08:01:45.037  6141  6177 D UEI.SmartControl: ----------- loading internal config...
08-05 08:01:45.038  6141  6141 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 08:01:45.039  6141  6141 E UEI.SmartControl: Services init done
08-05 08:01:45.039  6141  6141 D UEI.SmartControl: QS Service init finished
,08-05 08:01:45.039  6141  6141 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 08:01:45.039  6141  6141 D UEI.SmartControl: QS Service version code: 201091
08-05 08:01:45.042  6141  6141 D UEI.SmartControl: Service requested: Control
08-05 08:01:45.044  6141  6177 E UEI.SmartControl: Loading SETTINGS...
08-05 08:01:45.047  6141  6141 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 08:01:45.050  1027  2026 I ActivityManager: Killing 5231:com.lge.qremote/u0a112 (adj 15): empty #17
08-05 08:01:45.051  5231  5231 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-05 08:01:45.053  6141  6156 I UEI.SmartControl: ------ IControl API: 11
08-05 08:01:45.054  6141  6156 I UEI.SmartControl: Registering callback...
08-05 08:01:45.058  6141  6177 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 08:01:45.076  6141  6176 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 08:01:45.076  6141  6176 D UEI.SmartControl: -----service ready thread exits
,08-05 08:01:45.148  1027  1995 W libprocessgroup: failed to open /acct/uid_10112/pid_5231/cgroup.procs: No such file or directory
08-05 08:01:45.149  6141  6141 D UEI.SmartControl: Internal service binding...
,08-05 08:01:45.175  5914  6028 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-05 08:01:45.969  1027  1371 I ActivityManager: Killing 5156:com.android.calendar/u0a13 (adj 15): empty #17
,08-05 08:01:46.065  1027  2093 W libprocessgroup: failed to open /acct/uid_10013/pid_5156/cgroup.procs: No such file or directory
,08-05 08:01:46.419  1812  5733 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 08:01:46.427   306  6185 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 08:01:46.427  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 08:01:46.428  1812  5733 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-05 08:01:46.429  1812  1812 I ConfigFetchService: fetch service done; releasing wakelock
08-05 08:01:46.429  1812  1812 I ConfigFetchService: stopping self
08-05 08:01:46.432  2233  2233 I ConfigService: onDestroy
,08-05 08:01:50.037  6141  6178 D UEI.SmartControl: Internal timer expired: 1
08-05 08:01:50.038  6141  6178 D UEI.SmartControl: unbind internal service
,08-05 08:01:50.051  6141  6141 D UEI.SmartControl: Service.onUnbind: IControl
,08-05 08:01:50.056  6141  6175 D serial_port: close(fd = 25)
08-05 08:01:50.058  6141  6141 D UEI.SmartControl: Service.onDestroy
08-05 08:01:50.059  6141  6141 D UEI.SmartControl: Lock is in USE false
08-05 08:01:50.059  6141  6141 D UEI.SmartControl: unbind internal service
08-05 08:01:50.059  6141  6141 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@252ca832
08-05 08:01:50.060  6141  6141 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-05 08:01:50.060  6141  6141 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-05 08:01:50.060  6141  6141 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-05 08:01:50.060  6141  6141 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-05 08:01:50.061  6141  6141 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-05 08:01:50.061  6141  6141 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-05 08:01:50.061  6141  6141 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-05 08:01:50.061  6141  6141 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-05 08:01:50.061  6141  6141 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:01:50.061  6141  6141 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 08:01:50.061  6141  6141 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 08:01:50.061  6141  6141 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:01:50.061  6141  6141 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 08:01:50.061  6141  6141 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 08:01:50.062  6141  6141 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 08:01:50.062  6141  6141 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@252ca832
08-05 08:01:50.067  6141  6175 I UEI.SmartControl: Serial port is closed.
,08-05 08:01:50.068  6141  6141 I UEI.SmartControl: Serial port is closed.
08-05 08:01:50.068  6141  6141 I UEI.SmartControl: Serial port is closed.
08-05 08:01:50.068  6141  6141 D UEI.SmartControl: Blaster closed
08-05 08:01:50.068  6141  6141 D UEI.SmartControl: Shut down QS...
08-05 08:01:50.068  6141  6141 D UEI.SmartControl: Stopping QS lib
08-05 08:01:50.069  6141  6141 D UEI.SmartControl: QS lib stop result = true
08-05 08:01:50.069  6141  6141 D UEI.SmartControl: Stopped QS lib
08-05 08:01:50.069  6141  6141 D UEI.SmartControl: Stopped file observer...
08-05 08:01:50.069  6141  6141 D UEI.SmartControl: QS shutdown complete
08-05 08:01:51.493  1027  1085 I ActivityManager: Waited long enough for: ServiceRecord{2f4e2578 u0 com.google.android.gms/.wearable.service.WearableService}
,08-05 08:01:54.619  1027  1380 V AlarmManager: RTC_WAKEUP set : Alarm{30e95c2f type 0 when 1470376913410 com.android.vending} when 1470376913410
,08-05 08:01:54.627   306  6186 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 08:01:54.628  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 08:01:54.654  1027  1960 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:01:54.731  5871  5871 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-05 08:01:58.219  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 08:01:58.219  5967  6060 I jxcore-log: 
,08-05 08:01:58.221  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 08:01:58.221  5967  6060 I jxcore-log: 
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.225  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.228  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.231  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 08:01:58.231  5967  6060 I jxcore-log: 
,08-05 08:01:58.232  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 08:01:58.232  5967  6060 I jxcore-log: 
08-05 08:01:58.565  5967  6060 D ExecuteNativeTests: Running unit tests
,08-05 08:01:58.648  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:01:58.648  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab added. We now have 2 listener(s)
08-05 08:01:58.649  1027  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:58.651  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:01:58.651  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:01:58.651  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:01:58.651  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:01:58.651  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 added. We now have 2 listener(s)
08-05 08:01:58.651  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:01:58.652  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:01:58.654  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.656  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.657  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.657  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:01:58.657  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:01:58.660  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 08:01:58.662  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 08:01:58.662  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 08:01:58.664  5967  6060 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-05 08:01:58.665  5967  6060 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-05 08:01:58.665  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 08:01:58.665  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:01:58.665  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:01:58.666  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.666  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.666  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.667  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.667  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.667  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:01:58.667  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:01:58.667  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab removed from the list
08-05 08:01:58.667  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.667  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 removed from the list
08-05 08:01:58.667  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.667  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.668  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.668  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.669  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.669  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.669  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.669  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.671  5967  6060 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-05 08:01:58.671  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.671  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.671  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.671  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.671  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.672  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.672  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.672  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.672  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.672  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.672  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.672  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.672  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.672  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.672  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.672  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.672  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.672  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
,08-05 08:01:58.676  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 08:01:58.676  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 08:01:58.676  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 08:01:58.676  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 08:01:58.676  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 08:01:58.676  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 08:01:58.677  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 08:01:58.677  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.677  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.677  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.677  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.677  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.677  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.678  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.678  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.678  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.678  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.678  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.678  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.678  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.678  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.679  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.679  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.679  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.679  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.680  5967  6060 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 08:01:58.681  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.683  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.684  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.684  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:01:58.685  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:58.685  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:01:58.686  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:01:58.686  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:01:58.686  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.686  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:01:58.688  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 08:01:58.689  1027  2093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:58.692  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:01:58.696  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:01:58.697  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 08:01:58.698  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:01:58.698  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:01:58.700  5967  6060 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 08:01:58.700  5967  6060 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:01:58.702  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.702  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.702  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.702  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.702  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.702  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:01:58.702  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.702  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.702  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.702  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.702  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.702  5967  6060 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 08:01:58.703  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.705  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.706  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.706  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:01:58.706  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:58.707  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:01:58.707  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:01:58.707  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:01:58.707  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.707  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:01:58.710  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 08:01:58.710  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:01:58.711  5967  6060 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 08:01:58.711  5967  6060 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:01:58.712  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.712  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.712  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.712  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.712  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.712  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:01:58.712  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.712  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.712  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.712  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.712  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.712  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.712  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.713  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.713  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.714  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.714  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.714  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.714  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.714  5967  6060 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 08:01:58.716  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.717  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.718  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.718  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:01:58.719  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:58.719  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:01:58.719  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:01:58.719  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:01:58.719  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.719  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:01:58.722  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:01:58.722  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:01:58.723  5967  6060 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 08:01:58.723  5967  6060 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:01:58.723  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.723  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.723  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.724  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.724  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.724  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.724  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.724  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.724  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:01:58.724  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.724  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.724  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.724  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.724  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.725  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.725  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.725  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.725  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.726  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.726  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.726  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.726  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.726  5967  6060 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 08:01:58.726  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.726  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.726  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.727  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.727  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.727  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.727  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.727  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.727  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.727  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.727  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.727  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.727  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.727  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.728  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.728  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.728  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.728  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.728  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.728  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.729  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 08:01:58.729  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.729  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.729  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.729  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.729  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.729  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.729  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.729  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.729  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.729  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.729  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.729  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.729  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.729  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.730  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.730  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.730  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.730  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.730  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.730  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.731  5967  6060 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 08:01:58.731  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.731  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.731  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.731  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.732  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.732  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.732  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.732  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.732  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.732  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.732  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.732  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.732  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.732  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.732  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.732  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.733  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.733  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.733  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.733  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.733  5967  6060 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 08:01:58.733  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.733  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.733  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.733  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.733  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.734  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.734  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.734  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.734  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.734  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.734  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.734  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.734  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.734  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.735  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.735  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.735  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.735  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.735  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.735  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.735  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 08:01:58.736  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 08:01:58.736  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 08:01:58.736  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:01:58.737  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 08:01:58.737  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 08:01:58.737  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.737  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.737  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.737  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.737  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.737  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.737  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.737  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.737  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.737  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.737  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.737  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.737  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.737  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.738  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.738  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.738  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.738  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.738  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.738  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.739  5967  6060 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:01:58.739  5967  6060 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 08:01:58.739  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 08:01:58.741  5967  6060 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:01:58.741  5967  6060 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 08:01:58.741  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 08:01:58.742  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 08:01:58.742  5967  6060 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 08:01:58.742  5967  6060 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 08:01:58.742  5967  6060 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 08:01:58.742  5967  6060 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:01:58.742  5967  6060 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 08:01:58.742  5967  6060 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 08:01:58.742  5967  6060 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:01:58.742  5967  6060 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 08:01:58.742  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 08:01:58.746  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 08:01:58.747  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 08:01:58.747  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 08:01:58.747  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 08:01:58.748  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 08:01:58.748  5967  6060 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 08:01:58.748  5967  6060 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:01:58.748  5967  6060 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 08:01:58.750  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.750  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.750  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.750  5967  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 741)
08-05 08:01:58.751  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.751  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.751  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.752  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 08:01:58.754  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.754  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.754  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.754  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.754  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.754  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.754  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.754  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.755  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.755  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.756  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.756  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.756  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.756  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.757  5967  6060 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 08:01:58.757  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.757  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.757  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.758  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.758  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.758  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.758  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.758  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.758  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.758  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.758  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.758  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.758  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.758  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.759  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.759  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.760  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.760  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.760  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.760  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.760  5967  6060 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 08:01:58.761  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.761  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.761  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.764  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.764  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.764  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.764  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.764  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.764  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.764  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.764  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.764  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.764  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.764  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.765  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.765  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.765  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.765  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.765  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.765  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.766  5967  6060 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 08:01:58.766  5967  6060 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 08:01:58.766  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 08:01:58.766  5967  6060 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 08:01:58.766  5967  6060 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 08:01:58.766  5967  6060 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 08:01:58.766  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 08:01:58.766  5967  6060 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 08:01:58.766  5967  6060 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 08:01:58.766  5967  6060 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 08:01:58.766  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 08:01:58.766  5967  6060 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 08:01:58.766  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.766  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.766  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.768  5967  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 741
08-05 08:01:58.768  5967  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 741)
08-05 08:01:58.768  5967  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 741)
08-05 08:01:58.771  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.771  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.771  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.771  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.771  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.771  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.771  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.771  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.771  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.771  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.771  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.772  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.772  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.772  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.772  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.772  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.772  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.773  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.773  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.773  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.773  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.773  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.773  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.773  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.773  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.773  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.773  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.773  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.773  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.773  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.773  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.773  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.773  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.773  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.773  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.774  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.774  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.774  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.774  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.774  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.774  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.774  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.774  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.774  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.774  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.774  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.775  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.775  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.775  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.775  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.775  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.775  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.776  5967  6060 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 08:01:58.777  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.777  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 08:01:58.778  5967  6060 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 08:01:58.778  5967  6060 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 08:01:58.778  5967  5967 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 08:01:58.778  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 08:01:58.778  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:01:58.784  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.785  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 08:01:58.785  1027  1647 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:58.785  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 08:01:58.785  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 08:01:58.785  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:01:58.785  5967  6060 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 08:01:58.785  5967  5967 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 08:01:58.785  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.785  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.785  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:01:58.785  5967  6060 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:01:58.785  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:01:58.787  5967  6198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:01:58.787  3833  3851 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-05 08:01:58.788  5967  6198 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 08:01:58.788  5967  6198 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 08:01:58.788  5967  6198 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 08:01:58.789  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:01:58.790  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:01:58.790  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:01:58.790  5967  6060 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:01:58.790  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.790  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.791  5967  6060 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:01:58.791  5967  5967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:01:58.791  5967  5967 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 08:01:58.791  5967  5967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:01:58.791  5967  5967 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:01:58.791  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.791  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.791  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.791  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.792  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.792  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.792  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.792  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.792  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.792  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.792  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.792  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.792  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.792  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.792  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.792  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.792  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.792  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.792  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.793  5967  6060 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 08:01:58.793  5967  6060 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 08:01:58.793  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 08:01:58.794  5967  6060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:01:58.795  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.795  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.795  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.795  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 08:01:58.795  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.795  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.795  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.795  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.795  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.795  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.795  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.795  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.795  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.795  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.796  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.796  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.796  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.796  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.798  1027  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 08:01:58.799  1027  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:58.800  1027  2317 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:58.800  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.800  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.800  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.801  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.801  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.801  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.801  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.801  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 08:01:58.801  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.801  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.801  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.801  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.801  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.801  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.802  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.802  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.802  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.802  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.803  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:01:58.803  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:01:58.803  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:01:58.803  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:01:58.803  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.803  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.803  5967  6060 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21732ab not in the list
08-05 08:01:58.803  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.803  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list
08-05 08:01:58.803  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:01:58.803  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.803  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.803  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:01:58.803  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:01:58.804  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:01:58.804  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:01:58.804  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:01:58.804  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092dd08 not in the list,
08-05 08:01:58.806  5967  6060 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 08:01:58.806  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 08:01:58.806  5967  6060 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 08:01:58.806  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 08:01:58.806  5967  6060 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 08:01:58.806  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 08:01:58.808  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 08:01:58.808  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 08:01:58.808  5967  6060 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 08:01:58.808  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 08:01:58.808  5967  6060 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 08:01:58.808  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 08:01:58.808  5967  6060 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 08:01:58.808  5967  6060 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 08:01:58.809  5967  6060 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-05 08:01:58.809  5967  6060 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 08:01:58.809  5967  6060 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 08:01:58.809  5967  6060 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 08:01:58.810  5967  6060 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 08:01:58.810  5967  6060 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 08:01:58.810  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:01:58.810  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33935ed9 added. We now have 2 listener(s)
08-05 08:01:58.810  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:01:58.812  5967  6060 D BluetoothAdapter: enable(): BT is already enabled..!
,08-05 08:01:58.814  1027  2036 D WifiServiceImplEx: setWifiEnabled: true pid=5967, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-05 08:01:58.815  1027  2036 D WifiService: setWifiEnabled: true pid=5967, uid=10118
08-05 08:01:58.815  1027  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 08:01:58.816  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:01:58.816  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@117bb09e added. We now have 3 listener(s)
08-05 08:01:58.816  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:01:58.818  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:01:58.818  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19ae877f added. We now have 4 listener(s)
08-05 08:01:58.819  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:01:58.821  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:01:58.821  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27d2934c added. We now have 5 listener(s)
08-05 08:01:58.821  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:01:58.823  1027  1995 D WifiServiceImplEx: setWifiEnabled: false pid=5967, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 08:01:58.823  1027  1995 D WifiService: setWifiEnabled: false pid=5967, uid=10118
08-05 08:01:58.823  1027  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:01:58.841  1027  1371 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:01:58.841  1027  1371 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3de7fab1 mBinding = false
08-05 08:01:58.842  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:01:58.842  1027  1533 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-05 08:01:58.842  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 08:01:58.842  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-05 08:01:58.843  1027  1533 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-05 08:01:58.847  1027  1533 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 08:01:58.848  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 08:01:58.849  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 08:01:58.849  1027  1531 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:01:58.849  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-05 08:01:58.849  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:01:58.849  1027  1550 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:01:58.849  1027  1531 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2732cb4
08-05 08:01:58.849  1027  1551 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:01:58.849  1027  1531 D LGWifiP2pService: P2pDisablingState
08-05 08:01:58.849  1027  1531 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:01:58.849  1027  1531 D LGWifiP2pService: p2p socket connection lost
08-05 08:01:58.850  1027  1531 D LGWifiP2pService: P2pDisabledState
08-05 08:01:58.850  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 08:01:58.850  1961  1961 D WfdsService: WifiP2pState is changed : false
08-05 08:01:58.850  1961  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 08:01:58.850  1961  2319 D WfdsService: Set the WFDS Monitor: false
08-05 08:01:58.852  1961  2319 D WfdsMonitor: WFDS Monitor is stopped
08-05 08:01:58.852  1961  2319 D WfdsService: STATE : WfdsDisabledState - enter
08-05 08:01:58.852  1027  1089 D BluetoothManagerService: Message: 2
08-05 08:01:58.852  1961  2320 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 08:01:58.853  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:01:58.853  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 08:01:58.853  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-05 08:01:58.853  1027  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 08:01:58.853  1027  1089 D BluetoothManagerService: Sending off request.
08-05 08:01:58.854  1961  2805 D CtrlSupplicant: Received on exit socket, terminate
08-05 08:01:58.854  1961  2805 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 08:01:58.854  1961  2805 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 08:01:58.854  3833  3852 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 08:01:58.854  1961  2805 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 08:01:58.855  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:01:58.855  3833  3918 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 08:01:58.855  3833  3918 D BluetoothAdapterProperties: Setting state to 13
08-05 08:01:58.855  3833  3918 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 08:01:58.855  1961  2319 W WfdsService: DefaultState - msg [9445378] is not handled
,08-05 08:01:58.856  3833  3918 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 08:01:58.856  3833  3918 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 08:01:58.857  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:01:58.857  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 08:01:58.857  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 08:01:58.860  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 08:01:58.861  3833  3833 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:58.861  3833  3833 D BluetoothMapService: STATE_TURNING_OFF
08-05 08:01:58.861  3833  3833 V BluetoothMapService: Handler(): got msg=4
08-05 08:01:58.861  3833  3833 D BluetoothMapService: MAP Service closeService in
08-05 08:01:58.861  3833  3833 D BluetoothMapMasInstance: MAP Service shutdown
08-05 08:01:58.861  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:58.861  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.861  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 08:01:58.862  3833  4163 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 08:01:58.862  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:01:58.862  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.862  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:01:58.862  3833  3833 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 08:01:58.862  3833  3833 V BluetoothMapService: MAP Service closeService out
08-05 08:01:58.863  3833  3833 V BtOppService: R,eceiver DISABLED_ACTION 
08-05 08:01:58.863  3833  3833 I BtOppRfcommListener: stopping Accept Thread
08-05 08:01:58.863  3833  3833 V BtOppRfcommListener: close mBtServerSocket
08-05 08:01:58.863  3833  3833 V BtOppRfcommListener: waiting for thread to terminate
08-05 08:01:58.863  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:58.863  3833  4190 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:01:58.864  3833  4190 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 08:01:58.864  3833  3833 V BtOppRfcommListener: done waiting for thread to terminate
08-05 08:01:58.866  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.866  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.866  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:01:58.866  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:01:58.869  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:58.871   306   888 D CommandListener: Clearing all IP addresses on wlan0
08-05 08:01:58.882  5967  6196 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-05 08:01:58.882  5967  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 741)
,08-05 08:01:58.912  1027  1085 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6213 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 08:01:58.913  3833  3921 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:01:58.914  3833  3918 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 08:01:58.914  3833  4164 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:01:58.914  3833  3918 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 08:01:58.914  3833  4198 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:01:58.915  1027  1533 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 08:01:58.915  3833  3833 V BtOppService: onDestroy
08-05 08:01:58.915  3833  4201 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:01:58.915  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 08:01:58.915  1027  1533 D WifiNative-p2p0: TERMINATE: returned true
08-05 08:01:58.915  3833  4030 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 08:01:58.915  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:01:58.915  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:01:58.915  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 08:01:58.916  3833  3833 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 08:01:58.918  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 08:01:58.918  3833  4030 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 08:01:58.919  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-05 08:01:58.919  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:01:58.919  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:01:58.919  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 08:01:58.919  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-05 08:01:58.919  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:01:58.919  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:01:58.919  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 08:01:58.920  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 08:01:58.920  1597  159,7 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:01:58.921  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 08:01:58.922  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:01:58.922  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.922  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.923  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:01:58.923  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.925  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:01:58.925  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:01:58.926  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:01:58.926  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:01:58.927  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:58.928  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:01:58.944  1027  1085 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6230 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 08:01:58.944  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 08:01:58.944  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:01:58.944  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-05 08:01:58.960  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 08:01:58.960  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 08:01:58.961  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:01:58.964  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:01:58.973  6213  6213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 08:01:58.973  6213  6213 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-05 08:01:58.973  6213  6213 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 08:01:58.973  6213  6213 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 08:01:58.974  6213  6213 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 08:01:58.974  6213  6213 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 08:01:58.995  2659  2659 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 08:01:58.995  2659  2659 I wpa_supplicant: monitor socket send errors count : 1
08-05 08:01:58.995  2659  2659 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1961-2\x00 that cannot receive messages
,08-05 08:01:58.995  1027  2802 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 08:01:58.995  1027  2802 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 08:01:59.032  2659  2659 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-05 08:01:59.032  2659  2659 W wpa_supplicant: USIM:  scard_deinit function
08-05 08:01:59.033  1027  2802 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 08:01:59.033  1027  2802 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 08:01:59.033  1027  2802 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 08:01:59.034  1027  2802 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 08:01:59.034  1027  2802 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:01:59.034  1027  2802 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:01:59.034  1027  1533 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153297
08-05 08:01:59.034  1027  1533 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153297
08-05 08:01:59.035  1027  1533 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=153297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 08:01:59.035  1027  1533 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=153298  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 08:01:59.035  1027  1089 D Tethering: InitialState.processMessage what=4
08-05 08:01:59.036  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 08:01:59.036  1027  1533 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:01:59.037  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:01:59.038   306  6248 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 08:01:59.038  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 08:01:59.046  6230  6230 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 08:01:59.046  6230  6230 W LG Account v2.2: No ProfileInfo entries
08-05 08:01:59.046  6230  6230 I LG Account v2.2: isEnabled: false
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Country: EU
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Operator: OPEN
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Ranking support: false
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Comfort support: false
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Accessory: true
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Health device: true
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Extra Pedometer: false
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Blood glucose device: false
08-05 08:01:59.047  6230  6230 I Feature : [Lifetracker]Device Number: 3
,08-05 08:01:59.051  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:01:59.082  1027  2026 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6251 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 08:01:59.082  1027  2026 I ActivityManager: Killing 4886:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-05 08:01:59.085  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 08:01:59.125  1027  1905 W libprocessgroup: failed to open /acct/uid_10014/pid_4886/cgroup.procs: No such file or directory
,08-05 08:01:59.131  1027  1089 D BluetoothManagerService: Message: 20
08-05 08:01:59.131  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@221019b3:true
08-05 08:01:59.131  3833  3833 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 08:01:59.132  3833  3833 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:59.132  3833  3833 V BluetoothPbapReceiver: ***********state = 13
08-05 08:01:59.133  3833  3833 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 08:01:59.135  3833  3833 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:59.135  3833  3833 V BluetoothPbapService: state: 13
08-05 08:01:59.135  3833  3833 V BluetoothPbapService: Pbap Service closeService in
08-05 08:01:59.136  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 08:01:59.136  3833  3833 V BluetoothPbapService: successfully stopped pbap service
08-05 08:01:59.136  3833  3833 V BluetoothPbapService: Pbap Service closeService out
08-05 08:01:59.136  3833  3833 V BluetoothPbapService: Pbap Service onDestroy
08-05 08:01:59.136  3833  3833 V BluetoothPbapService: Pbap Service closeService in
,08-05 08:01:59.136  3833  3833 V BluetoothPbapService: Pbap Service closeService out
,08-05 08:01:59.136  3833  3833 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 08:01:59.151  1027  1089 D BluetoothManagerService: Message: 30
,08-05 08:01:59.156  1027  1089 D BluetoothManagerService: Message: 30
08-05 08:01:59.156  2659  2659 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 08:01:59.157  1027  2802 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 08:01:59.157  1027  2802 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 08:01:59.157  1027  2802 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 08:01:59.157  1027  1533 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
08-05 08:01:59.159  6213  6213 D LocalBluetoothProfileManager: Adding local MAP profile
08-05 08:01:59.160  6213  6213 D BluetoothMap: Create BluetoothMap proxy object
08-05 08:01:59.161  1027  1089 D BluetoothManagerService: Message: 30
08-05 08:01:59.165  1027  1089 D BluetoothManagerService: Message: 30
,08-05 08:01:59.167  6213  6213 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-05 08:01:59.167  6213  6213 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-05 08:01:59.170  6251  6251 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 08:01:59.173  6251  6251 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 08:01:59.174  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:01:59.176  1027  1995 I ActivityManager: Killing 2215:com.lge.music/u0a34 (adj 15): empty #17
,08-05 08:01:59.196   312  1377 V AudioFlinger: 2215 died, releasing its sessions
,08-05 08:01:59.196   312  1377 V AudioFlinger:  pid 1870 @ 0
08-05 08:01:59.196   312  1377 V AudioFlinger:  pid 3395 @ 1
08-05 08:01:59.196   312  1377 V AudioFlinger:  pid 3395 @ 2
08-05 08:01:59.206  1027  1043 W libprocessgroup: failed to open /acct/uid_10034/pid_2215/cgroup.procs: No such file or directory
,08-05 08:01:59.207  6213  6213 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-05 08:01:59.210  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-05 08:01:59.217  6213  6213 D DockEventReceiver: finishStartingService: stopping service
,08-05 08:01:59.228  6213  6213 D BluetoothInputDevice: Proxy object connected
,08-05 08:01:59.229  6213  6213 D HidProfile: Bluetooth service connected
,08-05 08:01:59.230  6213  6213 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 08:01:59.231  6213  6213 D PanProfile: Bluetooth service connected
08-05 08:01:59.231  6213  6213 D BluetoothMap: Proxy object connected
08-05 08:01:59.232  6213  6213 D MapProfile: Bluetooth service connected
08-05 08:01:59.232  6213  6213 D BluetoothMap: getConnectedDevices()
08-05 08:01:59.232  6213  6213 D BluetoothMap: Bluetooth is Not enabled
08-05 08:01:59.250  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:01:59.259  1961  1961 D WfdsService: Supplicant Connection state is changed : false
08-05 08:01:59.259  1027  1533 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 08:01:59.260  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:01:59.260  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:01:59.260  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 08:01:59.260  1961  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 08:01:59.260  1961  2319 D WfdsService: Set the WFDS Monitor: false
08-05 08:01:59.260  1961  2319 D WfdsMonitor: WFDS Monitor is stopped
08-05 08:01:59.262  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 08:01:59.262  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:01:59.266  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 08:01:59.266  2452  2452 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 08:01:59.267  1027  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 08:01:59.267  1027  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 08:01:59.268  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:01:59.271  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:01:59.291  5967  5967 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:01:59.300  6213  6213 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:01:59.300  6213  6213 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:01:59.310  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:01:59.312  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 08:01:59.314  6213  6213 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 08:01:59.318  6213  6213 D BluetoothPermissionRequest: onReceive
08-05 08:01:59.320  6213  6213 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 08:01:59.327  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 08:01:59.332  1027  1996 I ActivityManager: Killing 5737:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-05 08:01:59.432  1027  2026 W libprocessgroup: failed to open /acct/uid_10008/pid_5737/cgroup.procs: No such file or directory
,08-05 08:01:59.432  3833  3833 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 08:01:59.433  3833  3833 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 08:01:59.438  3833  3833 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 08:01:59.524  1027  1996 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6282 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-05 08:01:59.525  3833  3833 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:59.525  3833  3833 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 08:01:59.533  3833  3833 V BluetoothFtpService: Ftp Service onStartCommand
08-05 08:01:59.533  3833  3833 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:59.534  3833  3833 V BluetoothFtpService: Ftp Service closeService
08-05 08:01:59.534  3833  3833 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 08:01:59.536  3833  3833 V BluetoothFtpService: successfully stopped ftp service
08-05 08:01:59.536  3833  3833 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:01:59.536  3833  3833 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:01:59.536  3833  3833 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:01:59.536  3833  3833 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:59.536  3833  3833 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 08:01:59.536  3833  3833 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 08:01:59.537  3833  3833 V BluetoothFtpService: Ftp Service onDestroy
08-05 08:01:59.537  3833  3833 V BluetoothFtpService: Ftp Service closeService
,08-05 08:01:59.593  1027  1995 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 08:01:59.594  3833  3833 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:01:59.594  3833  3833 V BluetoothSapService: state: 13
08-05 08:01:59.594  3833  3833 V BluetoothSapService: Stopping SAP server process
08-05 08:01:59.595  3833  3833 V BluetoothSapService: Sap Service closeSapService in
08-05 08:01:59.595  3833  3833 V BluetoothSapService: Close listen Socket : 
08-05 08:01:59.596  3833  3833 V BluetoothSapService: Close rfcomm Socket : 
08-05 08:01:59.596  3833  3833 V BluetoothSapService: Close sapd  Socket : 
08-05 08:01:59.597  3833  3833 V BluetoothSapService: Sap Service closeSapService out
08-05 08:01:59.598  3833  3833 V BluetoothSapService: Sap Service onDestroy
08-05 08:01:59.598  3833  3833 V BluetoothSapService: Sap Service closeSapService in
08-05 08:01:59.598  3833  3833 V BluetoothSapService: Close listen Socket : 
08-05 08:01:59.598  3833  3833 V BluetoothSapService: Close rfcomm Socket : 
08-05 08:01:59.598  3833  3833 V BluetoothSapService: Close sapd  Socket : 
08-05 08:01:59.603  3833  3833 V BluetoothSapService: Sap Service closeSapService out
,08-05 08:01:59.632  6282  6282 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 08:01:59.652  6299  6299 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 08:01:59.659  6282  6282 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-05 08:01:59.669  1027  2317 I ActivityManager: Killing 5770:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 08:01:59.699  6282  6282 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-05 08:01:59.700  6282  6282 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 08:01:59.700  6282  6282 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 08:01:59.701  6282  6282 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 08:01:59.701  6282  6282 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 08:01:59.703  6282  6282 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 08:01:59.709  6282  6282 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 08:01:59.736  1027  1647 W libprocessgroup: failed to open /acct/uid_10011/pid_5770/cgroup.procs: No such file or directory
,08-05 08:01:59.753  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 08:01:59.761  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:01:59.796  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 08:01:59.804  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:01:59.816  6251  6251 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 08:01:59.817  6251  6251 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 08:01:59.817  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 08:01:59.825  6282  6282 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 08:01:59.828  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:01:59.833  6282  6282 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-05 08:01:59.840  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:01:59.849  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 08:01:59.849  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:01:59.852  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:01:59.912  1027  1647 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6319 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 08:01:59.920  3833  3921 D bt_hci_bdroid: cleanup
,08-05 08:01:59.920  3833  4032 I bt_lpm  : LPM is already off!!!
08-05 08:01:59.920  3833  4153 I bt_userial_mct: exiting userial_read_thread
08-05 08:01:59.920  3833  4153 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 08:01:59.921  3833  4030 W bt-btif : ag scb idx 1 not allocated
08-05 08:01:59.921  3833  4030 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 08:01:59.921  3833  3921 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:01:59.921  3833  4032 I bt_vendor: hw_epilog_process
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:01:59.921  3833  4030 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:01:59.921  3833  4030 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 08:01:59.921  3833  3921 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 08:01:59.921  3833  3921 D bt_userial_mct: userial_close
08-05 08:01:59.921  3833  3921 E bt_userial_mct: pthread_join() FAILED result:3
08-05 08:01:59.921  3833  3921 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-05 08:02:00.004  3833  3921 D bt_hci_bdroid: set_power 0
,08-05 08:02:00.004  3833  3921 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 08:02:00.004  3833  3921 I bt_vendor: bluetooth satus is on
08-05 08:02:00.004  3833  3921 I bt_vendor: bt-vendor : resetting BT status
08-05 08:02:00.004  3833  3921 I bt_vendor: Starting hciattach daemon
08-05 08:02:00.004  3833  3921 I bt_vendor: try to set false
08-05 08:02:00.007  3833  3921 I bt_vendor: Starting hciattach daemon
08-05 08:02:00.007  3833  3921 I bt_vendor: try to set false
08-05 08:02:00.009  3833  3921 I bt_vendor: cleanup
08-05 08:02:00.010  3833  4030 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 08:02:00.011  3833  3921 I GKI_LINUX: GKI_exit_task 0 done
08-05 08:02:00.011  3833  3921 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 08:02:00.011  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:00.013  3833  3918 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 08:02:00.016  3833  3833 D HeadsetService: Received stop request...Stopping profile...
08-05 08:02:00.018  3833  3833 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-05 08:02:00.019  3833  3833 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-05 08:02:00.019  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f2f5e7
08-05 08:02:00.020  3833  3956 D HeadsetStateMachine: Exit Disconnected: -1
08-05 08:02:00.023  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:00.023  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 08:02:00.023  1870  1870 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:00.023  1870  1870 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:00.024  1870  1870 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:00.025  3833  3833 D A2dpService: Received stop request...Stopping profile...
08-05 08:02:00.025  3833  4016 D A2dpStateMachine: Exit Disconnected: -1
08-05 08:02:00.027  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 08:02:00.028  3833  3833 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 08:02:00.030  3833  3918 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 08:02:00.030  3833  3833 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 08:02:00.030  3833  3833 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 08:02:00.031  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f2f5e7
,08-05 08:02:00.034  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-05 08:02:00.034  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 08:02:00.035  3833  3833 D HidService: Received stop request...Stopping profile...
08-05 08:02:00.035  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f2f5e7
08-05 08:02:00.036  3833  3833 D HealthService: Received stop request...Stopping profile...
08-05 08:02:00.037  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f2f5e7
08-05 08:02:00.038  3833  3833 D HeadsetStateMachine: Unbinding service...
08-05 08:02:00.038  3833  3833 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 08:02:00.038  3833  3833 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 08:02:00.039  3833  3833 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 08:02:00.039  3833  3833 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 08:02:00.039  3833  3833 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 08:02:00.039  3833  3833 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 08:02:00.039  3833  3833 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-05 08:02:00.039  3833  3833 D PanService: Received stop request...Stopping profile...
08-05 08:02:00.040  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f2f5e7
08-05 08:02:00.041  3833  3833 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 08:02:00.041  3833  3833 D BtGatt.GattService: Received stop request...Stopping profile...
,08-05 08:02:00.042  3833  3833 D BtGatt.GattService: stop()
,08-05 08:02:00.042  3833  3833 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 08:02:00.043  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f2f5e7
08-05 08:02:00.044  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 08:02:00.044  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 08:02:00.044  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 08:02:00.044  3833  3833 D BluetoothMapService: Received stop request...Stopping profile...
08-05 08:02:00.044  3833  3833 D BluetoothMapService: stop()
08-05 08:02:00.044  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
08-05 08:02:00.045  3833  3833 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 08:02:00.045  3833  3833 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 08:02:00.045  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f2f5e7
08-05 08:02:00.046  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 08:02:00.046  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:02:00.047  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:02:00.048  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 08:02:00.054  3833  3833 I BluetoothA2dpServiceJni: cleanupNative
08-05 08:02:00.055  3833  4017 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 08:02:00.055  3833  3833 I GKI_LINUX: GKI_exit_task 2 done
,08-05 08:02:00.055  3833  3833 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 08:02:00.055  3833  3833 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 08:02:00.055  3833  3833 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 08:02:00.056  3833  3833 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 08:02:00.056  3833  3833 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 08:02:00.056  3833  3833 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 08:02:00.056  3833  3833 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 08:02:00.056  3833  3833 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 08:02:00.057  3833  3833 V BluetoothMapService: Handler(): got msg=4
08-05 08:02:00.057  3833  3833 D BluetoothMapService: MAP Service closeService in
08-05 08:02:00.057  3833  3833 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 08:02:00.057  3833  3833 V BluetoothMapService: MAP Service closeService out
08-05 08:02:00.057  3833  3918 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 08:02:00.058  3833  3918 D BluetoothAdapterProperties: Setting state to 10
08-05 08:02:00.058  3833  3918 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 08:02:00.058  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:00.058  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:02:00.058  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 08:02:00.058  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-05 08:02:00.058  3833  3918 I BluetoothAdapterState: Entering OffState
08-05 08:02:00.058  1870  1885 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:00.058  3833  3833 D BluetoothMapService: cleanup()
08-05 08:02:00.058  3833  3833 D BluetoothMapService: MAP Service closeService in
08-05 08:02:00.058  3833  3833 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 08:02:00.059  3833  3833 V BluetoothMapService: MAP Service closeService out
08-05 08:02:00.059  6213  6213 D BluetoothInputDevice: Proxy object disconnected
08-05 08:02:00.059  6213  6213 D HidProfile: Bluetooth service disconnected
08-05 08:02:00.064  1870  2639 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:00.066  6213  6228 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 08:02:00.066  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 08:02:00.067  6213  6229 D BluetoothPan: onBluetoothStateChange on: false
08-05 08:02:00.069  6213  6213 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 08:02:00.069  6213  6213 D PanProfile: Bluetooth service disconnected
08-05 08:02:00.070  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:00.070  6213  6213 D BluetoothMap: Proxy object disconnected
08-05 08:02:00.070  1870  1886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:00.070  6213  6229 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 08:02:00.070  6213  6213 D MapProfile: Bluetooth service disconnected
08-05 08:02:00.071  6213  6228 D BluetoothMap: onBluetoothStateChange: up=false
08-05 08:02:00.072  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 08:02:00.072  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-05 08:02:00.077  1027  1089 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 08:02:00.077  1027  1089 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 08:02:00.077  1027  1089 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3de7fab1 mBinding = false
08-05 08:02:00.081  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:00.082  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:00.082  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:00.082  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 08:02:00.083  1027  1089 D BluetoothManagerService: Sending unbind request.
08-05 08:02:00.083  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 08:02:00.083  6319  6339 W FormManager: Network not available. Please check & try again.
08-05 08:02:00.085  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 08:02:00.087  6319  6340 V FormManager: Network unavailable.
08-05 08:02:00.089  6319  6340 V FormManager: Network unavailable.
,08-05 08:02:00.094  3833  3921 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 08:02:00.095  3833  3833 I GKI_LINUX: GKI_exit_task 1 done
08-05 08:02:00.095  3833  3833 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 08:02:00.096  3833  3833 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 08:02:00.097  3833  3833 I art     : --- WEIRD: removing null entry 246
08-05 08:02:00.097  3833  3833 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-05 08:02:00.097  3833  3833 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 08:02:00.098  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:00.098  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 08:02:00.098  3833  3833 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 08:02:00.098  1961  2173 D LGBluetoothAPIService: Message: 2
08-05 08:02:00.099  1961  2173 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@10422538 mBinding = false
08-05 08:02:00.099  1961  2173 D LGBluetoothAPIService: Sending unbind request.
08-05 08:02:00.101  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:00.102  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:00.105  1597  1597 D BluetoothAdapter: 757322079: getState() :  mService = null. Returning STATE_OFF
08-05 08:02:00.105  1597  1597 D BluetoothAdapter: 757322079: getState() :  mService = null. Returning STATE_OFF
,08-05 08:02:00.105  3833  3833 I art     : System.exit called, status: 0
08-05 08:02:00.107  3833  3833 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 08:02:00.112  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:00.112  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 08:02:00.112  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:00.112  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:00.112  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:00.112  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 08:02:00.117  6213  6213 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 08:02:00.118  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 08:02:00.118  6213  6213 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-05 08:02:00.120  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 08:02:00.128  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:00.128  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 08:02:00.130  6213  6213 D DockEventReceiver: finishStartingService: stopping service
08-05 08:02:00.130  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 08:02:00.133  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:00.134  1027  1996 I ActivityManager: Killing 5672:com.android.defcontainer/u0a4 (adj 15): empty #17
08-05 08:02:00.135   312  1378 V AudioFlinger: 3833 died, releasing its sessions
08-05 08:02:00.135  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 08:02:00.135   312  1378 V AudioFlinger:  pid 1870 @ 0
08-05 08:02:00.135   312  1378 V AudioFlinger:  pid 3395 @ 1
08-05 08:02:00.135   312  1378 V AudioFlinger:  pid 3395 @ 2
08-05 08:02:00.229  4270  6351 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 08:02:00.235  1027  2317 I ActivityManager: Process com.android.bluetooth (pid 3833) has died
08-05 08:02:00.235  1027  2317 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-05 08:02:00.245  4270  6353 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:00.245  1027  1960 W libprocessgroup: failed to open /acct/uid_10004/pid_5672/cgroup.procs: No such file or directory
,08-05 08:02:00.250  4270  6353 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 08:02:00.258  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 08:02:00.264  6251  6251 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 08:02:00.264  6251  6251 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 08:02:00.264  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 08:02:00.274  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 08:02:00.284  6319  6355 W FormManager: Network not available. Please check & try again.
08-05 08:02:00.286  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:00.287  6319  6356 V FormManager: Network unavailable.
08-05 08:02:00.290  6213  6213 D BluetoothPermissionRequest: onReceive
,08-05 08:02:00.297  6213  6213 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 08:02:00.297  6319  6356 V FormManager: Network unavailable.
08-05 08:02:00.297  6213  6213 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 08:02:00.300  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 08:02:00.374  1027  1995 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6357 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 08:02:00.408  6282  6282 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-05 08:02:00.409  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 08:02:00.409   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 33.270ms
08-05 08:02:00.410  6282  6282 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-05 08:02:00.431   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 20.249ms
08-05 08:02:00.444  6357  6357 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 08:02:00.444  6357  6357 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 08:02:00.445  6357  6357 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 08:02:00.445  6357  6357 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 08:02:00.449   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.403ms
08-05 08:02:00.452  6282  6282 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:00.453  6282  6282 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 08:02:00.459  6282  6282 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-05 08:02:00.462  6282  6282 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 08:02:00.462  6282  6282 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 08:02:00.462  6282  6282 V SoundPool: doLoad: loading sample sampleID=1
08-05 08:02:00.462  6282  6376 V SoundPool: Start decode
08-05 08:02:00.462  6282  6376 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 08:02:00.463   312  3960 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 08:02:00.463   312  3960 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 08:02:00.463   312  3960 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 08:02:00.463   312  3960 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 08:02:00.463   312  3960 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 08:02:00.463   312  3960 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 08:02:00.463   312  3960 V MediaPlayerService: player type = 3
08-05 08:02:00.463   312  3960 V AwesomePlayer: AwesomePlayer create()
08-05 08:02:00.463  6282  6282 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 08:02:00.463   312  3960 V AwesomePlayer: reset_l() 
08-05 08:02:00.463   312  3960 V AwesomePlayer: cancelPlayerEvents
08-05 08:02:00.463   312  3960 V AwesomePlayer: setAudioSink() 
08-05 08:02:00.463   312  3960 V AwesomePlayer: reset_l() 
08-05 08:02:00.463   312  3960 V AudioCache: notify(0xb0409440, 8, 0, 0)
08-05 08:02:00.463   312  3960 V AudioCache: ignored
08-05 08:02:00.463   312  3960 V AwesomePlayer: cancelPlayerEvents
08-05 08:02:00.464   312  3960 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 08:02:00.464   312  3960 V AwesomePlayer: setDataSource_l dataSource
08-05 08:02:00.464   312  3960 V LGParserOSAL: SniffLGParser start
08-05 08:02:00.464   312  3960 V LGParserOSAL: MainType:5, SubType=0
08-05 08:02:00.464   312  3960 V LGParserOSAL: #### check Mime : application/ogg
08-05 08:02:00.464   312  3960 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 08:02:00.464   312  3960 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 08:02:00.467  6282  6282 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 08:02:00.467  6141  6141 D UEI.SmartControl: QS Service created
08-05 08:02:00.467  6357  6357 D BluetoothAdapterApp: Loading JNI Library
08-05 08:02:00.468  6282  6282 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 08:02:00.468  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 08:02:00.478  6282  6282 V LGMDMManager: Create singleton instance
08-05 08:02:00.481  6141  6141 I UEI.SmartControl: Service initServices...
08-05 08:02:00.481  6141  6141 D UEI.SmartControl: QS start get config
,08-05 08:02:00.505  6357  6357 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@be392fc Instance Count = 1
08-05 08:02:00.509   312  3960 V LGParserOSAL: supported mime: application/ogg
08-05 08:02:00.509   312  3960 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 08:02:00.509   312  3960 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 08:02:00.509   312  3960 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 08:02:00.509   312  3960 V AwesomePlayer: AudioTrack Setting
08-05 08:02:00.509   312  3960 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 08:02:00.509   312  3960 V AwesomePlayer: setAudioSource() 
08-05 08:02:00.509   312  3960 V MediaPlayerService: prepare
08-05 08:02:00.509   312  3960 V AwesomePlayer: prepareAsync_l() 
08-05 08:02:00.509   312  3960 V MediaPlayerService: wait for prepare
08-05 08:02:00.509   312  6377 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 08:02:00.509   312  6377 V AwesomePlayer: initAudioDecoder() 
08-05 08:02:00.509   312  6377 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 08:02:00.509   312  6377 V AudioSystem: isOffloadSupported()
08-05 08:02:00.509   312  6377 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 08:02:00.509   312  6377 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 08:02:00.509   312  6377 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 08:02:00.509   312  6377 V AwesomePlayer: getUseOffload() = 0 
08-05 08:02:00.509   312  6377 V OMXCodec: OMXCodec::Create
08-05 08:02:00.509   312  6377 V OMXCodec: findMatchingCodecs()
08-05 08:02:00.509   312  6377 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 08:02:00.510   312  6377 V OMXCodec: matchingCodecs.size()=1
08-05 08:02:00.510   312  6377 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 08:02:00.510  6357  6357 D BluetoothAdapterApp: onCreate
,08-05 08:02:00.511   312  6377 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 08:02:00.511   312  6377 V LGCodecAdapter: LG Codec Adapter start
08-05 08:02:00.511   312  6377 V OMXCodec: OMXCodec Createtor
08-05 08:02:00.511   312  6377 V OMXCodec: setComponentRole
08-05 08:02:00.511   312  6377 V OMXCodec: configureCodec protected=0
08-05 08:02:00.511   312  6377 V LGCodecAdapter: called getLGCodecSpecificData
08-05 08:02:00.511   312  6377 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 08:02:00.511   312  6377 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 08:02:00.511   312  6377 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 08:02:00.511   312  6377 V LGCodecOSAL: Not support LGCodec
08-05 08:02:00.511   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 08:02:00.511   312  6377 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 08:02:00.511   312  6377 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 08:02:00.511   312  6377 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 08:02:00.511   312  6377 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 08:02:00.511   312  6377 V AudioSystem: isOffloadSupported()
08-05 08:02:00.511   312  6377 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 08:02:00.511   312  6377 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 08:02:00.511   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 08:02:00.511   312  6377 V OMXCodec: init()
08-05 08:02:00.511   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 08:02:00.511   312  6377 V OMXCodec: allocateBuffers
08-05 08:02:00.511   312  6377 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 08:02:00.511   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 08:02:00.511   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-05 08:02:00.511   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-05 08:02:00.512   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-05 08:02:00.512   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-05 08:02:00.512   312  6377 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 08:02:00.512   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 08:02:00.512   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-05 08:02:00.512   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-05 08:02:00.512   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-05 08:02:00.512   312  6377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-05 08:02:00.512   312  6377 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 08:02:00.512   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 08:02:00.512   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 08:02:00.512   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 08:02:00.512   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 08:02:00.512   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 08:02:00.512   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-05 08:02:00.512   312  6377 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 08:02:00.512   312  6377 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 08:02:00.512   312  6377 V AudioCache: notify(0xb0409440, 5, 0, 0)
08-05 08:02:00.512   312  6377 V AudioCache: ignored
08-05 08:02:00.512   312  6377 V AudioCache: notify(0xb0409440, 1, 0, 0)
08-05 08:02:00.512   312  6377 V AudioCache: prepared
08-05 08:02:00.512   312  3960 V AudioCache: wait - success
08-05 08:02:00.512   312  3960 V MediaPlayerService: start
08-05 08:02:00.512   312  3960 V AwesomePlayer: play_l() 
08-05 08:02:00.512   312  3960 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 08:02:00.512   312  3960 V AwesomePlayer: createAudioPlayer_l
08-05 08:02:00.512   312  3960 V AwesomePlayer: seekAudioIfNecessary_l() 
08-05 08:02:00.512   312  3960 V AwesomePlayer: startAudioPlayer_l() 
08-05 08:02:00.512   312  3960 D AudioPlayer: start of Playback, useOffload 0
08-05 08:02:00.512   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 08:02:00.512   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 08:02:00.514   312  6379 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-05 08:02:00.514   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-05 08:02:00.515   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0970 on output port
08-05 08:02:00.515   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-05 08:02:00.515   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 08:02:0,0.515   312  3960 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 08:02:00.524   312  3960 V AudioCache: notify(0xb0409440, 6, 0, 0)
08-05 08:02:00.524   312  3960 V AudioCache: ignored
08-05 08:02:00.524   312  3960 V MediaPlayerService: wait for playback complete
08-05 08:02:00.528   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.528   312  6380 V AudioCache: memcpy(0xac102000, 0xb0404000, 4096)
08-05 08:02:00.529  6357  6357 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 08:02:00.529  6357  6357 D ProfileConfigQcom: Adding HeadsetService
08-05 08:02:00.529  6357  6357 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 08:02:00.529  6357  6357 D ProfileConfigQcom: Adding A2dpService
08-05 08:02:00.529  6357  6357 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 08:02:00.530  6357  6357 D ProfileConfigQcom: Adding HidService
08-05 08:02:00.530   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.530   312  6380 V AudioCache: memcpy(0xac103000, 0xb0404000, 4096)
08-05 08:02:00.530  6357  6357 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 08:02:00.530   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.530   312  6380 V AudioCache: memcpy(0xac104000, 0xb0404000, 4096)
08-05 08:02:00.530   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.530   312  6380 V AudioCache: memcpy(0xac105000, 0xb0404000, 4096)
08-05 08:02:00.530   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.530  6357  6357 D ProfileConfigQcom: Adding HealthService
08-05 08:02:00.530   312  6380 V AudioCache: memcpy(0xac106000, 0xb0404000, 4096)
08-05 08:02:00.530  6357  6357 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 08:02:00.531  6357  6357 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 08:02:00.531   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.531   312  6380 V AudioCache: memcpy(0xac107000, 0xb0404000, 4096)
08-05 08:02:00.531   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.531   312  6380 V AudioCache: memcpy(0xac108000, 0xb0404000, 4096)
08-05 08:02:00.531  6357  6357 D ProfileConfigQcom: Adding PanService
08-05 08:02:00.531   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.531   312  6380 V AudioCache: memcpy(0xac109000, 0xb0404000, 4096)
08-05 08:02:00.531   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.531   312  6380 V AudioCache: memcpy(0xac10a000, 0xb0404000, 4096)
08-05 08:02:00.531  6357  6357 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 08:02:00.531  6357  6357 D ProfileConfigQcom: Adding GattService
08-05 08:02:00.532  6357  6357 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 08:02:00.532  6357  6357 D ProfileConfigQcom: Adding BluetoothMapService
08-05 08:02:00.532  6357  6357 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 08:02:00.532   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.532   312  6380 V AudioCache: memcpy(0xac10b000, 0xb0404000, 4096)
08-05 08:02:00.532   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.532   312  6380 V AudioCache: memcpy(0xac10c000, 0xb0404000, 4096)
08-05 08:02:00.532   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.532   312  6380 V AudioCache: memcpy(0xac10d000, 0xb0404000, 4096)
08-05 08:02:00.532   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.532   312  6380 V AudioCache: memcpy(0xac10e000, 0xb0404000, 4096)
08-05 08:02:00.533   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.533   312  6380 V AudioCache: memcpy(0xac10f000, 0xb0404000, 4096)
08-05 08:02:00.533   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.533   312  6380 V AudioCache: memcpy(0xac110000, 0xb0404000, 4096)
08-05 08:02:00.533  6357  6357 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 08:02:00.534   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.534   312  6380 V AudioCache: memcpy(0xac111000, 0xb0404000, 4096)
08-05 08:02:00.534   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.534   312  6380 V AudioCache: memcpy(0xac112000, 0xb0404000, 4096)
08-05 08:02:00.534   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.534   312  6380 V AudioCache: memcpy(0xac113000, 0xb0404000, 4096)
08-05 08:02:00.535   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.535   312  6380 V AudioCache: memcpy(0xac114000, 0xb0404000, 4096)
08-05 08:02:00.535   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.535   312  6380 V AudioCache: memcpy(0xac115000, 0xb0404000, 4096)
08-05 08:02:00.536   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.536   312  6380 V AudioCache: memcpy(0xac116000, 0xb0404000, 4096)
08-05 08:02:00.536   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.536   312  6380 V AudioCache: memcpy(0xac117000, 0xb0404000, 4096)
08-05 08:02:00.536   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.536   312  6380 V AudioCache: memcpy(0xac118000, 0xb0404000, 4096)
08-05 08:02:00.537   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.537   312  6380 V AudioCache: memcpy(0xac119000, 0xb0404000, 4096)
08-05 08:02:00.537  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 08:02:00.537   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.537   312  6380 V AudioCache: memcpy(0xac11a000, 0xb0404000, 4096)
08-05 08:02:00.537   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.537   312  6380 V AudioCache: memcpy(0xac11b000, 0xb0404000, 4096)
08-05 08:02:00.538   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.538   312  6380 V AudioCache: memcpy(0xac11c000, 0xb0404000, 4096)
08-05 08:02:00.538   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.538   312  6380 V AudioCache: memcpy(0xac11d000, 0xb0404000, 4096)
08-05 08:02:00.539  6357  6357 V LGMDMManagerInternal: Create singleton instance
08-05 08:02:00.539   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.539   312  6380 V AudioCache: memcpy(0xac11e000, 0xb0404000, 4096)
08-05 08:02:00.539   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.539   312  6380 V AudioCache: memcpy(0xac11f000, 0xb0404000, 4096)
08-05 08:02:00.540   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.540   312  6380 V AudioCache: memcpy(0xac120000, 0xb0404000, 4096)
08-05 08:02:00.540   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.540   312  6380 V AudioCache: memcpy(0xac121000, 0xb0404000, 4096)
08-05 08:02:00.541   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.541   312  6380 V AudioCache: memcpy(0xac122000, 0xb0404000, 4096)
08-05 08:02:00.541   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.541   312  6380 V AudioCache: memcpy(0xac123000, 0xb0404000, 4096)
08-05 08:02:00.542   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.542   312  6380 V AudioCache: memcpy(0xac124000, 0xb0404000, 4096)
08-05 08:02:00.542   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.542   312  6380 V AudioCache: memcpy(0xac125000, 0xb0404000, 4096)
08-05 08:02:00.543   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.543   312  6380 V AudioCache: memcpy(0xac126000, 0xb0404000, 4096)
08-05 08:02:00.543   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.543   312  6380 V AudioCache: memcpy(0xac127000, 0xb0404000, 4096)
08-05 08:02:00.543   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.543   312  6380 V AudioCache: memcpy(0xac128000, 0xb0404000, 4096)
08-05 08:02:00.544   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.544   312  6380 V AudioCache: memcpy(0xac129000, 0xb0404000, 4096)
08-05 08:02:00.544  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 08:02:00.544   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.545   312  6380 V AudioCache: memcpy(0xac12a000, 0xb0404000, 4096)
08-05 08:02:00.545   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.545   312  6380 V AudioCache: memcpy(0xac12b000, 0xb0404000, 4096)
08-05 08:02:00.545  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-05 08:02:00.545   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.545   312  6380 V AudioCache: memcpy(0xac12c000, 0xb0404000, 4096)
08-05 08:02:00.546   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.546   312  6380 V AudioCache: memcpy(0xac12d000, 0xb0404000, 4096)
08-05 08:02:00.546   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.546   312  6380 V AudioCache: memcpy(0xac12e000, 0xb0404000, 4096)
08-05 08:02:00.546  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1139
08-05 08:02:00.547   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.547   312  6380 V AudioCache: memcpy(0xac12f000, 0xb0404000, 4096)
08-05 08:02:00.547   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.547   312  6380 V AudioCache: memcpy(0xac130000, 0xb0404000, 4096)
08-05 08:02:00.547   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.547   312  6380 V AudioCache: memcpy(0xac131000, 0xb0404000, 4096)
08-05 08:02:00.548   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.548   312  6380 V AudioCache: memcpy(0xac132000, 0xb0404000, 4096)
08-05 08:02:00.548   312  6380 V AudioCache: write(0xb0404000, 4096)
08-05 08:02:00.548   312  6380 V AudioCache: memcpy(0xac133000, 0xb0404000, 4096)
08-05 08:02:00.548   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 08:02:00.548   312  6380 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 08:02:00.548   312  6380 V AwesomePlayer: postAudioEOS() 
08-05 08:02:00.549   312  6380 V AudioCache: write(0xb0404000, 280)
08-05 08:02:00.549   312  6380 V AudioCache: memcpy(0xac134000, 0xb0404000, 280)
08-05 08:02:00.550   312  6377 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 08:02:00.550   312  6377 V AwesomePlayer: onStreamDone
08-05 08:02:00.550   312  6377 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 08:02:00.550   312  6377 V AudioCache: notify(0xb0409440, 2, 0, 0)
08-05 08:02:00.550   312  6377 V AudioCache: playback complete
08-05 08:02:00.550   312  6377 V AwesomePlayer: pause_l() 
08-05 08:02:00.550   312  3960 V AudioCache: wait - success
08-05 08:02:00.550   312  6377 V AudioCache: notify(0xb0409440, 7, 0, 0)
08-05 08:02:00.550   312  6377 V AudioCache: ignored
08-05 08:02:00.550   312  3960 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 08:02:00.550   312  6377 V AwesomePlayer: cancelPlayerEvents
08-05 08:02:00.550   312  6377 D AudioPlayer: Pause Playback at 1068125
08-05 08:02:00.550   312  3960 V AwesomePlayer: reset_l() 
08-05 08:02:00.550   312  3960 V AudioCache: notify(0xb0409440, 8, 0, 0)
08-05 08:02:00.550   312  3960 V AudioCache: ignored
08-05 08:02:00.550   312  3960 V AwesomePlayer: cancelPlayerEvents
08-05 08:02:00.550   312  3960 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 08:02:00.550   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 08:02:00.550   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 08:02:00.550   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 08:02:00.550   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0970 on port 1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 08:02:00.553   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 08:02:00.553   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 08:02:00.553   312  6379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 08:02:00.553   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 08:02:00.553   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 08:02:00.553   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 08:02:00.554   312  3960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 08:02:00.554   312  3960 D AudioPlayer: AudioPlayer releasing audio source
08-05 08:02:00.554   312  3960 D AudioPlayer: AudioPlayer done releasing audio source
08-05 08:02:00.554   312  3960 V AwesomePlayer: reset_l() 
08-05 08:02:00.554   312  3960 V AwesomePlayer: cancelPlayerEvents
08-05 08:02:00.554   312  3960 V AwesomePlayer: ~AwesomePlayer call
08-05 08:02:00.554   312  3960 V AwesomePlayer: reset_l() 
08-05 08:02:00.554   312  3960 V AwesomePlayer: cancelPlayerEvents
08-05 08:02:00.555  6282  6376 V SoundPool: close(31)
08-05 08:02:00.555  6282  6376 V SoundPool: pointer = 0x9fea4000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 08:02:00.594  6357  6357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:00.597  6357  6357 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:02:00.598  6357  6357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:02:00.598  6357  6357 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:02:00.599  6357  6357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:00.599  6357  6357 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 08:02:00.606  6299  6299 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 08:02:00.745  6141  6141 I UEI.SmartControl: Supports setup maps: true
,08-05 08:02:00.748  6141  6141 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 08:02:00.748  6141  6141 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 08:02:00.748  6141  6141 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 08:02:00.748  6141  6141 I UEI.SmartControl: ### init IR Blaster...
08-05 08:02:00.751  6141  6141 D serial_port: Configuring serial port
08-05 08:02:00.751  6141  6141 E UEI.SmartControl: UEIBLaster setting for 616
08-05 08:02:00.751  6141  6141 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 08:02:00.751  6141  6141 I UEI.SmartControl: configuring settings for MAXQ616
08-05 08:02:00.751  6141  6141 I UEI.SmartControl: Get version...
08-05 08:02:00.770  6141  6383 D UEI.SmartControl: serial port data available: 21
,08-05 08:02:00.796  6141  6141 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 08:02:00.797  6141  6141 I UEI.SmartControl: IR Blaster version: 256702256704300002,
08-05 08:02:00.797  6141  6141 I UEI.SmartControl: QS saving settings...
,08-05 08:02:00.806  6141  6141 D UEI.SmartControl: IR Blaster version: 25672567
08-05 08:02:00.822  6141  6383 D UEI.SmartControl: serial port data available: 4
,08-05 08:02:00.851  6141  6389 I UEI.SmartControl: Device manager: loading config....
,08-05 08:02:00.857  6141  6389 D UEI.SmartControl: ----------- loading internal config...
08-05 08:02:00.858  6141  6141 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 08:02:00.866  6141  6389 E UEI.SmartControl: Loading SETTINGS...
,08-05 08:02:00.872  6141  6141 E UEI.SmartControl: Services init done
08-05 08:02:00.872  6141  6141 D UEI.SmartControl: QS Service init finished
08-05 08:02:00.873  6141  6141 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 08:02:00.873  6141  6141 D UEI.SmartControl: QS Service version code: 201091
08-05 08:02:00.875  6141  6389 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 08:02:00.875  6141  6141 D UEI.SmartControl: Service requested: Control
08-05 08:02:00.878  6282  6282 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 08:02:00.878  6141  6141 D UEI.SmartControl: Internal service binding...
08-05 08:02:00.879  6141  6157 I UEI.SmartControl: ------ IControl API: 11
08-05 08:02:00.879  6141  6157 D UEI.SmartControl: File observer start...
08-05 08:02:00.880  6141  6157 E UEI.SmartControl: IR Port is disabled: false
08-05 08:02:00.880  6141  6157 D UEI.SmartControl: Starting file observer...
08-05 08:02:00.881  6141  6157 I UEI.SmartControl: Registering callback...
08-05 08:02:00.882  6141  6156 I UEI.SmartControl: ------ IControl API: 19
,08-05 08:02:00.885  6141  6156 I UEI.SmartControl: Registering Services Ready callback...
08-05 08:02:00.885  6141  6156 I UEI.SmartControl: Notify client services are ready...
08-05 08:02:00.886  6282  6298 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 08:02:00.887  6282  6374 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 08:02:00.887  6282  6374 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 08:02:00.887  6282  6282 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 08:02:00.888  6282  6282 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 08:02:00.888  6141  6157 I UEI.SmartControl: ------ IControl API: 8
08-05 08:02:00.890  6282  6282 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 08:02:00.890  6282  6282 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 08:02:00.890  6282  6282 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 08:02:00.890  6141  6388 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 08:02:00.891  6282  6282 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 08:02:00.891  6282  6297 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 08:02:00.891  6282  6374 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 08:02:00.891  6141  6388 D UEI.SmartControl: -----service ready thread exits
08-05 08:02:00.892  6282  6374 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 08:02:00.892  6282  6282 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 08:02:00.892  6282  6282 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 08:02:00.894  6282  6282 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-05 08:02:00.897  6282  6282 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-05 08:02:00.898  6282  6282 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 08:02:00.899  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 08:02:00.900  6282  6282 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 08:02:00.900  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 08:02:00.901  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 08:02:00.902  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 08:02:00.902  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 08:02:00.903  6282  6282 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470376920903]
08-05 08:02:00.905  6282  6282 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 08:02:00.908  1027  2036 I ActivityManager: Killing 5824:com.lge.email/u0a23 (adj 15): empty #17
,08-05 08:02:00.931  6282  6394 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 08:02:00.936  1027  2036 I ActivityManager: Killing 5788:com.android.contacts/u0a19 (adj 15): empty #18
,08-05 08:02:01.001  1027  1371 W libprocessgroup: failed to open /acct/uid_10023/pid_5824/cgroup.procs: No such file or directory
,08-05 08:02:01.013  1027  1647 W libprocessgroup: failed to open /acct/uid_10019/pid_5788/cgroup.procs: No such file or directory
08-05 08:02:01.021  6282  6282 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-05 08:02:01.022  6282  6282 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 08:02:01.023  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 08:02:01.023  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 08:02:01.023  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-05 08:02:01.024  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 08:02:01.024  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 08:02:01.035  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 08:02:01.867  1027  1960 D WifiServiceImplEx: setWifiEnabled: true pid=5967, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 08:02:01.869  1027  1960 D WifiService: setWifiEnabled: true pid=5967, uid=10118
08-05 08:02:01.869  1027  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:02:01.900  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:02:01.900  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 08:02:01.900  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-05 08:02:01.902  1027  1533 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 08:02:01.902  1027  1533 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 08:02:01.904  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 08:02:01.904  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 08:02:01.904  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 08:02:01.904  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 08:02:01.905  1027  1533 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 08:02:01.905  1027  1533 E WifiHW  : unknown target_country: EU , set to default
08-05 08:02:01.905  1027  1533 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-05 08:02:01.905  1027  1533 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 08:02:01.905  1027  1533 I WifiUtil: gEnableBmps=1
08-05 08:02:02.502   306   888 D SoftapController: Softap fwReload - Ok
,08-05 08:02:02.506  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 08:02:02.510  1027  1533 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (601ms)
08-05 08:02:02.517   306   888 D CommandListener: Setting iface cfg
08-05 08:02:02.517   306   888 D CommandListener: Trying to bring down wlan0
,08-05 08:02:02.524   306  6406 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 08:02:02.536  1027  1089 D Tethering: InitialState.processMessage what=4
,08-05 08:02:02.540   306   888 D CommandListener: Clearing all IP addresses on wlan0
08-05 08:02:02.541  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 08:02:02.544  1027  1533 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 08:02:02.545  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-05 08:02:02.553  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:02:02.553  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:02:02.553  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 08:02:02.557  6407  6407 W wpa_supplicant: type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 08:02:02.571  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 08:02:02.557  6407  6407 W wpa_supplicant: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:02.575  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:02.587  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:02.595  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:02.595  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 08:02:02.596  1027  1533 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 08:02:02.596  1027  1533 D WifiMonitor: connecting to supplicant
08-05 08:02:02.611  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:02.611  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:02.611  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:02.611  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-05 08:02:02.620  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 08:02:02.622  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:02.622  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 08:02:02.622  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:02.622  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:02.622  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:02.623  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 08:02:02.624  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 08:02:02.627  6407  6407 I wpa_supplicant: Successfully initialized wpa_supplicant
08-05 08:02:02.628  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:02.628  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:02.628  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:02.628  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 08:02:02.629  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 08:02:02.630  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:02.630  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 08:02:02.630  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:02.630  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:02.630  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:02.630  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 08:02:02.638  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 08:02:02.642  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 08:02:02.648  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:02.661  6407  6407 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 08:02:02.662  6407  6407 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-05 08:02:02.662  6319  6427 W FormManager: Network not available. Please check & try again.
,08-05 08:02:02.666  6319  6428 V FormManager: Network unavailable.
08-05 08:02:02.668  6319  6428 V FormManager: Network unavailable.
08-05 08:02:02.827  6407  6407 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 08:02:02.848  6407  6407 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 08:02:02.854  6407  6407 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 08:02:02.855  6407  6407 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 08:02:02.856  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 08:02:02.857  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 08:02:02.857  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 08:02:02.858  1027  1533 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 08:02:02.858  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:02.859  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:02.859  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:02.861  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:02.861  1027  6429 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 08:02:02.861  1027  6429 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 08:02:02.862  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 08:02:02.862  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 08:02:02.862  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 08:02:02.862  1027  1533 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 08:02:02.862  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 08:02:02.862  1027  1533 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-05 08:02:02.863  1027  1533 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-05 08:02:02.864  1027  1533 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 08:02:02.865  1027  1533 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 08:02:02.865  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:02:02.865  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:02:02.865  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 08:02:02.867  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:02.867  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:02.867  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:02.867  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:02.868  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 08:02:02.872  1027  1533 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 08:02:02.872  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 08:02:02.873  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:02.873  1961  1961 D WfdService: Waiting for WifiP2p enabling
08-05 08:02:02.873  1027  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-05 08:02:02.878  1027  1533 D WifiNative-wlan0: SET update_config 1: returned true
08-05 08:02:02.878  1027  1533 D WifiConfigStore: Loading config and enabling all networks 
08-05 08:02:02.878  1027  1533 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 08:02:02.880  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:02.880  1027  1533 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:02.880  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:02.880  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:02.880  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:02.882  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:02.882  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:02.883  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:02.883  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:02.889  1027  1533 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-05 08:02:02.894  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:02.901  1027  1533 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 08:02:02.901  1027  1533 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 08:02:02.900  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 08:02:02.905  1027  1533 D WifiStateMachine: enableVerboseLogging : level 2
08-05 08:02:02.905  1027  1533 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 08:02:02.906  1027  1533 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 08:02:02.906  1027  1533 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-05 08:02:02.906  1027  1533 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 08:02:02.906  1027  1533 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 08:02:02.907  6319  6431 W FormManager: Network not available. Please check & try again.
08-05 08:02:02.907  1027  1533 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 08:02:02.907  1027  1533 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 08:02:02.907  1027  1533 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 08:02:02.908  1027  1533 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 08:02:02.908  1027  1533 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 08:02:02.909  1027  1533 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 08:02:02.909  1027  1533 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 08:02:02.909  1027  1533 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 08:02:02.910  1027  1533 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 08:02:02.910  1027  1533 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 08:02:02.910  1027  1533 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 08:02:02.911  1027  1533 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 08:02:02.911  1961  1961 D WfdsService: Supplicant Connection state is changed : true
08-05 08:02:02.911  1027  1533 D WifiNative-HAL: Setting external_sim to 1
08-05 08:02:02.911  1027  1533 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 08:02:02.911  1961  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 08:02:02.911  1961  2319 D WfdsService: Set the WFDS Monitor: true
08-05 08:02:02.911  1961  2319 D WfdsMonitor: WfdsMonitorThread create
08-05 08:02:02.912  1961  2319 D WfdsMonitor: WFDS Monitor is created and started
08-05 08:02:02.912  1961  2319 D WfdsService: WiFi: Supplicant connection re-established
08-05 08:02:02.912  1027  1533 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 08:02:02.912  1027  1533 I WifiNative-HAL: startHal
08-05 08:02:02.912  1027  1533 D wifi    : setting scan oui 0x9c3a4680
08-05 08:02:02.912  1961  6433 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 08:02:02.912  1027  1533 D WifiStateMachine: Setting OUI to DA-A1-19
,08-05 08:02:02.912  1027  1533 I WifiNative-HAL: startHal
08-05 08:02:02.912  1027  1533 D wifi    : setting scan oui 0x9c3a4680
08-05 08:02:02.913  6319  6432 V FormManager: Network unavailable.
08-05 08:02:02.913  1027  1533 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 08:02:02.913  1961  6433 E CtrlSupplicant: Succeed to open control connection
08-05 08:02:02.913  1961  6433 E CtrlSupplicant: Succeed to open monitor connection
08-05 08:02:02.913  1961  6433 D WfdsMonitor: Supplicant connection established
08-05 08:02:02.913  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:02.914  1027  1533 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 08:02:02.914  1961  2319 D WfdsService: Connected to the supplicant for wfds
08-05 08:02:02.914  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 08:02:02.914  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 08:02:02.914  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 08:02:02.915  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 08:02:02.915  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 08:02:02.915  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 08:02:02.915  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 08:02:02.915  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 08:02:02.916  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 08:02:02.916  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 08:02:02.916  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 08:02:02.916  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 08:02:02.916  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 08:02:02.916  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 08:02:02.917  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-05 08:02:02.918  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 08:02:02.918  6407  6407 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 08:02:02.918  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 08:02:02.918  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 08:02:02.918  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 08:02:02.919  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 08:02:02.919  6319  6432 V FormManager: Network unavailable.
08-05 08:02:02.920  1027  1533 E WifiNative: : [157,182,417 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 08:02:02.920  1027  1533 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 08:02:02.920  1027  1533 D WifiNative-wlan0: RECONNECT: returned true
08-05 08:02:02.920  1027  1533 D WifiNative-wlan0: doString: [STATUS]
08-05 08:02:02.921  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 08:02:02.921  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 08:02:02.921  1027  1533 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 08:02:02.921  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 08:02:02.922  1027  1533 D WifiNative-wlan0: SET ps 1: returned true
08-05 08:02:02.922  1027  1531 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.923  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 08:02:02.923  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-05 08:02:02.923  1027  1550 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.923  1027  1550 I WifiNative-HAL: startHal
08-05 08:02:02.923  1027  1550 D wifi    : getting scan capabilities on interface[1] = 0x9c3a4680
08-05 08:02:02.923  1027  1550 D wifi    : failed to get capabilities : -3
08-05 08:02:02.923  1027  1550 E WifiScanningService: could not get scan capabilities
08-05 08:02:02.923  1027  1551 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.924   306   888 D CommandListener: Setting iface cfg
08-05 08:02:02.924  1027  1533 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 08:02:02.924   306   888 D CommandListener: Trying to bring up p2p0
08-05 08:02:02.924  1027  1531 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 08:02:02.924  1027  1531 D LGWifiP2pService: P2pEnablingState
08-05 08:02:02.925  1027  1531 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.925  1027  1533 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 08:02:02.925  1027  1531 D LGWifiP2pService: P2p socket connection successful
08-05 08:02:02.925  1027  1531 D LGWifiP2pService: P2pEnabledState
08-05 08:02:02.925  1027  1533 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 08:02:02.925  1027  1533 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 08:02:02.926  1027  1533 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 08:02:02.926  1027  1533 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 08:02:02.927  1027  1533 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 08:02:02.927  1027  1533 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 08:02:02.927  6407  6407 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 08:02:02.928  1027  1533 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-05 08:02:02.928  1027  1533 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 08:02:02.928  1027  1531 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 08:02:02.929  1027  1531 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 08:02:02.929  1027  1533 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 08:02:02.929  1027  1533 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 08:02:02.929  6407  6407 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 08:02:02.929  1027  1531 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 08:02:02.929  1027  1531 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 08:02:02.930  1027  1531 D WifiNative-p2p0: SET device_name G3: returned true
08-05 08:02:02.930  1027  1531 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 08:02:02.930  1027  1531 D LGWifiP2pService: before postfix = G3
08-05 08:02:02.930  1027  1531 D WifiServerServiceExt: postfix byte check : 2
08-05 08:02:02.930  1027  1531 D LGWifiP2pService: after postfix = G3
08-05 08:02:02.930  1027  1531 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 08:02:02.930  1027  1531 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 08:02:02.930  1027  1531 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 08:02:02.931  1027  1531 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 08:02:02.931  1027  1531 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 08:02:02.931  1027  1531 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 08:02:02.931  1027  1531 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 08:02:02.932  1027  1531 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 08:02:02.932  1027  1531 D WifiNative-HAL: p2pGetDeviceAddress
08-05 08:02:02.932  1027  1531 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-05 08:02:02.932  1027  1533 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 08:02:02.933  1027  1533 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 08:02:02.933  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 08:02:02.933  1961  1961 D WfdsService: WifiP2pState is changed : true
08-05 08:02:02.933  1027  1533 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 08:02:02.933  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 08:02:02.934  1961  2319 D WfdsService: Receive the WFDS_ENABLE Method
08-05 08:02:02.934  1961  2319 D WfdsService: Set the WFDS Monitor: true
08-05 08:02:02.934  1961  2319 D WfdsService: Connected to the supplicant for wfds
08-05 08:02:02.934  1961  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
,08-05 08:02:02.934  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 08:02:02.934  1027  1531 D LGWifiP2pService: DeviceAddress: 
08-05 08:02:02.934  1961  1961 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 08:02:02.934  1027  1531 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 08:02:02.934  6407  6407 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.935  1961  1961 D WfdsService: isConnected: false
08-05 08:02:02.935  6407  6407 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 08:02:02.935  6407  6407 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 08:02:02.935  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 08:02:02.935  6407  6407 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.935  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.935  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.936  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.936  1027  6429 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.936  1027  6429 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.936  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.936  1961  6433 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.936  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.936  1961  1961 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 08:02:02.936  1961  1961 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 08:02:02.936  1961  1961 D WfdsService: Update P2p Interface State: 3
08-05 08:02:02.936  6407  6407 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.936  1961  6433 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.936  1027  6429 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.936  1027  6429 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.936  1961  2319 D WfdsService: selectPreferredScanChannel [36]
08-05 08:02:02.936  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.936  1961  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 08:02:02.936  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.938  1027  1533 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 08:02:02.938  1027  1531 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 08:02:02.938  1027  1533 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 08:02:02.938  1027  1531 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 08:02:02.939  1027  1533 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 08:02:02.939  1027  1531 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 08:02:02.939  1027  1531 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 08:02:02.939  1027  1533 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 08:02:02.939  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 08:02:02.939  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:02.940  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 08:02:02.940  1,027  1531 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 08:02:02.940  1027  1531 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 08:02:02.940  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 08:02:02.940  6407  6407 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:02.940  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 08:02:02.940  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:02.940  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:02.940  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:02.941  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:02.941  1027  1533 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 08:02:02.942  1027  1533 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 08:02:02.942  1027  1533 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 08:02:02.942  1027  1533 D WifiNative-wlan0: doBoolean: SCAN
,08-05 08:02:02.943  1027  1533 D WifiNative-wlan0: SCAN: returned false
08-05 08:02:02.943  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=157206  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 08:02:02.944  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:02.944  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=157207  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 08:02:02.945  1027  1533 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:02.945  1027  1533 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:02.946  1027  1533 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:02.946  1027  1533 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:02.946  1027  1533 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:02.948  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:02.948  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:02.948  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:02.948  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:02.948  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 08:02:02.948  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:02.949  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 08:02:02.949  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:02.952  6117  6117 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 08:02:02.953  1027  1531 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 08:02:02.953  1027  1531 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 08:02:02.953  1027  1531 D LGWifiP2pService: InactiveState
08-05 08:02:02.953  1027  1531 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.954  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.954  1027  1531 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-05 08:02:02.954  6117  6117 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 08:02:02.954  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 08:02:02.955  6407  6407 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.955  1027  6429 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 08:02:02.955  6407  6407 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 08:02:02.955  1027  6429 E WifiMonitor: WifiMonitor:p2p0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.956  6407  6407 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.956  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.956  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:02.956  4270  6434 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 08:02:02.956  1027  6429 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.956  1027  6429 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.956  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.956  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.956  6407  6407 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.956  1027  6429 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.956  1027  6429 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.957  1027  6429 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.957  1027  6429 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:02.957  1027  1531 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.957  1961  6433 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.957  1961  6433 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.957  1961  6433 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.957  1027  1531 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.958  1027  1531 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.958  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.958  1027  15,31 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.958  1027  1531 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.958  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.958  1027  1531 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:02.958  1027  1027 E WifiServerServiceExt: No p2p device connected
08-05 08:02:02.958  1961  2319 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 08:02:02.961  4270  6436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:02.961  4270  6436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 08:02:02.962  6117  6117 V [BNRBootReceiver]: Boot Receiver Return
08-05 08:02:02.966  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 08:02:02.973  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:02.978  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:02.982  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:02.983  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 08:02:02.984  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:02:03.445  6407  6407 E wpa_supplicant: USIM:  scard_init function
08-05 08:02:03.446  6407  6407 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 08:02:03.457  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 08:02:03.457  1027  6429 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 08:02:03.457  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 08:02:03.457  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: WPS-AP-AVAILABLE 
08-05 08:02:03.457  1027  6429 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 08:02:03.458  1027  1533 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-05 08:02:03.459  1027  1533 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-05 08:02:03.459  1027  1533 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-05 08:02:03.459  1027  1533 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-05 08:02:03.459  1027  1533 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 08:02:03.460  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 08:02:03.460  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 08:02:03.477  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=157740  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 08:02:03.487  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-05 08:02:03.490  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.490  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.490  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 08:02:03.491  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=157754  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 08:02:03.494  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:03.494  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:03.499  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.499  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.499  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 08:02:03.500  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:03.500  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-05 08:02:03.506  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:03.510  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:03.510  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:03.511  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:03.518  6213  6213 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 08:02:03.524  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:03.537  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:03.547  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:03.556  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:03.557  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 08:02:03.560  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:02:03.565  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:03.574  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:03.582  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:03.591  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:03.591  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:03.592  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 08:02:03.609  6407  6407 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 08:02:03.620  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 08:02:03.621  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 08:02:03.621  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 08:02:03.621  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 08:02:03.622  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:03.622  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=157885  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 08:02:03.622  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:03.622  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=157885  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 08:02:03.625  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:03.625  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:03.625  6407  6407 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 08:02:03.626  6407  6407 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 08:02:03.626  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 08:02:03.626  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 08:02:03.626  1027  6429 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 08:02:03.626  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 08:02:03.626  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 08:02:03.626  1027  6429 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 08:02:03.626  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:03.626  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:03.627  1027  1533 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157886
08-05 08:02:03.628  1027  1533 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157891
,08-05 08:02:03.629  1027  1533 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157892
08-05 08:02:03.630  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157892
08-05 08:02:03.630  1027  1533 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157893
08-05 08:02:03.631  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=157894  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 08:02:03.636  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 08:02:03.639  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:03.639  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:03.639  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:03.639  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 08:02:03.640  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 08:02:03.641  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:03.641  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 08:02:03.641  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:03.641  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:03.641  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:03.641  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 08:02:03.642  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 08:02:03.649  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:03.649  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:03.650  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:03.652  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.653  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.653  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-05 08:02:03.656  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:03.656  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=157919  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 08:02:03.660  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.660  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.660  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 08:02:03.661  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=157924  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 08:02:03.661  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:03.661  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 08:02:03.662  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=157925  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 08:02:03.663  1027  1533 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=157926
08-05 08:02:03.663  1027  1533 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=157926
08-05 08:02:03.664  1027  1533 D WifiNative-wlan0: doString: [STATUS]
08-05 08:02:03.664  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:03.664  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:03.664  1027  1533 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 08:02:03.667  1027  1533 I WifiServiceExtension: setVHTCapabilityType  : false
,08-05 08:02:03.668  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:03.673  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:03.674  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:03.675  1027  1533 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 08:02:03.675  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:03.675  1027  1533 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 08:02:03.677  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:03.679  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.679  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.679  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-05 08:02:03.684  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.685  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:03.685  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 08:02:03.696  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:03.697  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 08:02:03.699  1027  1533 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 08:02:03.699  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:03.699  1027  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:02:03.699  1027  1539 D ConnectivityService: Got NetworkAgent Messenger
08-05 08:02:03.699  1027  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 08:02:03.700  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:03.700  1027  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 08:02:03.700  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:03.700  1027  1539 D ConnectivityService: NetworkAgent connected
08-05 08:02:03.700  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:03.701  1027  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 08:02:03.701  1027  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 08:02:03.705  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:03.705  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:03.705  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:03.706  1027  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 08:02:03.706  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:03.706  1027  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:02:03.706  1027  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 08:02:03.706  1027  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 08:02:03.707  1027  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 08:02:03.710  1027  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-05 08:02:03.713   306   888 D CommandListener: Setting iface cfg
08-05 08:02:03.717  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:03.720  1027  1533 E WifiStateMachine: Start Dhcp Watchdog 1
08-05 08:02:03.720  1027  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=157983  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:03.721  1027  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=157984  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:03.721  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=157984  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:03.722  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:03.722  1027  6464 D DhcpStateMachine: StoppedState
08-05 08:02:03.722  1027  6464 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:03.722  1027  6464 D DhcpStateMachine: WaitBeforeStartState
08-05 08:02:03.722  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:03.722  1027  1533 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:03.723  1027  1533 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:03.723  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:03.724  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:03.725  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:03.725  1027  1027 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 08:02:03.725  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:03.725  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-05 08:02:03.726  1027  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=157989  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:03.726  1027  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=157989  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:03.727  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=157989  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:03.727  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:03.728  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1498108496] from screen [on:0 period:1498108496]
08-05 08:02:03.729  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1498108497]
08-05 08:02:03.729  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:02:03.731  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:03.731  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:03.731  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:03.734  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:03.736  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:03.737  1027  1539 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-05 08:02:03.737  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:03.737  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:03.738  1027  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:03.738  1027  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:03.738  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:03.738  1027  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:03.739  1027  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-05 08:02:03.740  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:03.741  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:03.741  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 08:02:03.742  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-05 08:02:03.742  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-05 08:02:03.742  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 08:02:03.742  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 08:02:03.742  1027  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 08:02:03.743  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 08:02:03.743  1027  1533 D WifiNative-wlan0: SET ps 0: returned true
08-05 08:02:03.743  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 08:02:03.743  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 08:02:03.744  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 08:02:03.744  1027  1533 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 08:02:03.744  1027  1533 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 08:02:03.744  1027  1533 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 08:02:03.744  1027  1531 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e361d60 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:03.744  1027  1533 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-05 08:02:03.744  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e361d60 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:03.744  1027  6464 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:03.745  1027  6464 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 08:02:03.745  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:03.745  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 08:02:03.748  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 08:02:03.753  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:03.754  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:03.754  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:03.757  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:03.764  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:03.768  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:03.774  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 08:02:03.775  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:03.775  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:03.850  1027  1531 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:03.850  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:03.850  1027  1531 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 08:02:03.917  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 08:02:03.919  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-05 08:02:03.920  1027  1533 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-05 08:02:03.921  1027  1533 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 08:02:03.922  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 08:02:03.924  1027  1533 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 08:02:03.948  1027  6464 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 08:02:03.950  1027  6464 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 08:02:03.951  1027  6464 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-05 08:02:03.957  6466  6466 W dhcpcd  : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:03.957  6466  6466 W dhcpcd  : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 08:02:03.997  6466  6466 I dhcpcd  : version 5.5.6 starting
,08-05 08:02:04.000  6466  6466 E dhcpcd  : get_duid: m
08-05 08:02:04.000  6466  6466 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 08:02:04.000  6466  6466 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-05 08:02:04.079  6466  6466 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 08:02:04.080  6466  6466 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 08:02:04.080  6466  6466 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-05 08:02:04.083  6466  6466 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 08:02:04.084  6466  6466 D dhcpcd  : wlan0: sending REQUEST (xid 0x54b3c94), next in 3.66 seconds
08-05 08:02:04.096  6466  6466 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-05 08:02:04.104  6466  6466 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 08:02:04.104  6466  6466 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 08:02:04.107  6466  6466 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 08:02:04.108  6466  6466 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-05 08:02:04.108  6466  6466 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 08:02:04.109  6466  6466 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 08:02:04.110  6466  6466 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 08:02:04.110  6466  6466 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 08:02:04.110  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.115  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-05 08:02:04.116  1027  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.117  1027  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.119  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.120  1027  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.121  1027  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-05 08:02:04.563  1027  6464 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-05 08:02:04.575  1027  6464 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 08:02:04.576  1027  6464 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 08:02:04.577  1027  6464 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 08:02:04.577  1027  6464 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 08:02:04.577  1027  6464 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 08:02:04.577  1027  6464 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-05 08:02:04.582  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 08:02:04.583  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-05 08:02:04.587  1027  6464 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 08:02:04.588  1027  6464 D DhcpStateMachine: RunningState
08-05 08:02:04.588  1027  1531 D LGWifiP2pService: InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.588  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.589  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 08:02:04.589  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 08:02:04.590  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 08:02:04.590  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 08:02:04.590  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 08:02:04.591  1027  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 08:02:04.591  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 08:02:04.609  1027  1533 D WifiNative-wlan0: SET ps 1: returned true
08-05 08:02:04.610  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 08:02:04.611  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 08:02:04.611  1027  1533 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-05 08:02:04.617  1027  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-05 08:02:04.617  1027  1539 D ConnectivityService: ignoring duplicate network state non-change
,08-05 08:02:04.638  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:04.639  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:04.645  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.645  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.645  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-05 08:02:04.651  1027  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 08:02:04.653  1027  1539 D ConnectivityService: Adding iface wlan0 to network 100
08-05 08:02:04.664  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.664  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.664  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-05 08:02:04.676  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:04.680  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 08:02:04.682  1027  1533 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 08:02:04.698  1961  1961 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-05 08:02:04.706  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:04.706  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:04.714  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.714  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.714  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-05 08:02:04.718  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 08:02:04.736  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:04.747  1027  1539 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 08:02:04.747  1027  1539 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-05 08:02:04.749  1027  1539 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-05 08:02:04.751  1027  1539 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-05 08:02:04.752  1027  1539 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 08:02:04.752  1027  1539 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-05 08:02:04.752  1027  1539 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-05 08:02:04.753  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.754  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.754  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 08:02:04.754  1027  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 08:02:04.754  1027  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-05 08:02:04.755  1027  1539 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-05 08:02:04.755  1027  6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.755  1027  6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 08:02:04.755  1027  6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.756  1027  6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 08:02:04.759  1027  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-05 08:02:04.760  1027  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:04.760  1027  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:04.760  1027  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 08:02:04.760  1027  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:04.760  1027  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 08:02:04.760  1027  1539 D ConnectivityService: currentScore = 0, newScore = 20
08-05 08:02:04.760  1027  1539 D ConnectivityService:    accepting network in place of null
08-05 08:02:04.760  1027  1539 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:04.773  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 08:02:04.778  1027  1533 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:04.778  1027  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:04.779  1870  1870 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:04.779  1870  1870 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 08:02:04.779  1027  1539 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-05 08:02:04.781   306  6505 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 08:02:04.785  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 08:02:04.785  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:04.788  1027  1539 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 08:02:04.788  1027  1539 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-05 08:02:04.790  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 08:02:04.793  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 08:02:04.796  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 08:02:04.797  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 08:02:04.797  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 08:02:04.797  1027  1027 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
,08-05 08:02:04.805   306  6506 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 08:02:04.806   306  6506 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-05 08:02:04.813   306  6506 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
,08-05 08:02:04.816  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 08:02:04.822  1027  1530 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 08:02:04.823  1027  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:04.824   306  6505 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-05 08:02:04.826  1027  1539 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 08:02:04.826  1027  1539 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 08:02:04.829  1027  1539 D ConnectivityService: validation of new default Network = false
08-05 08:02:04.829  1027  1539 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 08:02:04.829  1027  1539 D DSQN    : enableDataServiceNotify 
08-05 08:02:04.829  1027  1539 D DSQN    : start dsqn bin
08-05 08:02:04.832  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:04.832  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 08:02:04.832  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:04.837   306  6508 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 08:02:04.839   306  6508 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-05 08:02:04.841  1027  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-05 08:02:04.841  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:04.841  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:04.841  1027  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:04.842  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 08:02:04.837  6509  6509 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:04.837  6509  6509 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 08:02:04.855   306  6505 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 08:02:04.869  6509  6509 E DSQN    : DSQN ssw
,08-05 08:02:04.873  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 08:02:04.873  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:04.877  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:04.894   306  6508 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
08-05 08:02:04.899  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 08:02:04.901   306   887 D LGDataListener: argv[0]=dsqncommand
08-05 08:02:04.901   306   887 D LGDataListener: argv[1]=wlan0
08-05 08:02:04.901   306   887 D LGDataListener: argv[2]=1
08-05 08:02:04.901   306   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 08:02:04.902  1027  1087 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 08:02:04.902  1027  1087 D DSQN    : start to monitor internet connection
08-05 08:02:04.905  1027  2317 D WifiServiceImplEx: setWifiEnabled: false pid=5967, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 08:02:04.905  1027  2317 D WifiService: setWifiEnabled: false pid=5967, uid=10118
08-05 08:02:04.905  1027  2317 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:02:04.923  1027  6507 D LocSvc_java: NTP server : europe.pool.ntp.org
08-05 08:02:04.923  1027  6507 D LocSvc_java: NTP server returned: 1470376924670 (Fri Aug 05 08:02:04 GMT+02:00 2016) reference: 159185 certainty: 13 system time offset: -253
08-05 08:02:04.923  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:02:04.923  1027  6507 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-05 08:02:04.923  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-05 08:02:04.923  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-05 08:02:04.925  1027  1533 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 08:02:04.925  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 08:02:04.926  1027  1533 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 08:02:04.927  1027  1533 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 08:02:04.927  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 08:02:04.927  1027  1533 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 08:02:04.927  1027  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:02:04.927  1027  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 08:02:04.928  1027  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 08:02:04.928  1027  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 08:02:04.934  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:04.938  1027  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 08:02:04.938  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 08:02:04.938  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 08:02:04.938  1027  1531 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.938  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.939  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 08:02:04.939  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 08:02:04.939  1027  1533 D WifiNative-wlan0: SET ps 1: returned true
08-05 08:02:04.939   306   888 D CommandListener: Clearing all IP addresses on wlan0
08-05 08:02:04.940  1027  6464 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 08:02:04.952  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:04.957  1027  6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.ConnectException: failed to connect to clients3.google.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-05 08:02:04.964  1027  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 08:02:04.964  1027  1539 D ConnectivityService: ignoring duplicate network state non-change
,08-05 08:02:04.964  1027  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-05 08:02:04.965  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:04.965  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:04.965  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-05 08:02:04.966  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:04.966  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:04.967  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:04.971  1027  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.971  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.972  1027  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.972  1027  1533 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 08:02:04.972  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:04.975  1961  1961 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-05 08:02:04.977  1027  1531 D LGWifiP2pService: InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.977  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.977  1027  1531 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2732cb4
08-05 08:02:04.977  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.978  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.978  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 08:02:04.978  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-05 08:02:04.978  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.978  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:04.978  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 08:02:04.978  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
,08-05 08:02:04.978  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-05 08:02:04.979  1027  1550 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.979  1027  1551 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.981  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:04.981  1027  1531 D LGWifiP2pService: P2pDisablingState
08-05 08:02:04.981  1027  1531 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.981  1027  1531 D LGWifiP2pService: p2p socket connection lost
08-05 08:02:04.981  1027  1531 D LGWifiP2pService: P2pDisabledState
08-05 08:02:04.982  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 08:02:04.982  1961  1961 D WfdsService: WifiP2pState is changed : false
08-05 08:02:04.985  1027  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.985  1961  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 08:02:04.985  1961  2319 D WfdsService: Set the WFDS Monitor: false
08-05 08:02:04.985  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.986  1027  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:04.986  1961  2319 D WfdsMonitor: WFDS Monitor is stopped
08-05 08:02:04.986  1961  2319 D WfdsService: STATE : WfdsDisabledState - enter
08-05 08:02:04.986  1961  6433 D CtrlSupplicant: Received on exit socket, terminate
08-05 08:02:04.986  1961  6433 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 08:02:04.986  1961  6433 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 08:02:04.986  1961  6433 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 08:02:04.986  1961  2320 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 08:02:04.987  1961  2319 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 08:02:04.987  1027  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-05 08:02:04.990  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:04.990  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:04.990  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:04.991  1027  1531 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.991  1027  1531 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:04.991  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 08:02:04.991  6407  6407 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 08:02:04.993  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 08:02:04.993  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 08:02:04.993  1027  1533 D WifiNative-wlan0: SET ps 1: returned true
08-05 08:02:04.997  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:05.000  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 08:02:05.008  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:05.009  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:05.010  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:05.013  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 08:02:05.015   306   888 D CommandListener: Clearing all IP addresses on wlan0
08-05 08:02:05.016  1027  1539 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 08:02:05.016  1027  1539 D DSQN    : disableDataServiceNotify
08-05 08:02:05.016  1027  1539 D DSQN    : stop dsqn bin
08-05 08:02:05.018  1027  1533 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 08:02:05.018  6251  6251 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 08:02:05.018  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-05 08:02:05.018  1027  1533 D WifiNative-p2p0: TERMINATE: returned true
08-05 08:02:05.018  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:02:05.018  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:02:05.018  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 08:02:05.019  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 08:02:05.019  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:05.020  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:05.020  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:05.020  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 08:02:05.020  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:05.021  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 08:02:05.022  1027  1539 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-05 08:02:05.023  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:05.023  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:05.023  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 08:02:05.023  1027  1539 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:05.023  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:05.023  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 08:02:05.023  1027  1539 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 08:02:05.024  1027  6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:05.024  1027  6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:05.024  1027  1539 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 08:02:05.024  1027  ,6463 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 08:02:05.024  1027  1539 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-05 08:02:05.024  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 08:02:05.025  1027  1530 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 08:02:05.025  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 08:02:05.025  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 08:02:05.026  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 08:02:05.026  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 08:02:05.026  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 08:02:05.026  1027  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:05.026  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-05 08:02:05.027  1027  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:05.027  1027  1539 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:05.027  1027  1539 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:05.027  1027  1539 D NetworkManagementService: Removing idletimer
08-05 08:02:05.027  1027  1539 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:05.027  1027  1533 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:05.027  1027  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:05.028  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:02:05.028  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:05.028  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:05.028  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 08:02:05.028  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:05.028  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:05.028  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will ret,urn stored value
08-05 08:02:05.029  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:05.029  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 08:02:05.029  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 08:02:05.029  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 08:02:05.030  1027  1530 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 08:02:05.031  1870  1870 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:05.031  1870  1870 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 08:02:05.035  1027  1538 D WifiService: New client listening to asynchronous messages
08-05 08:02:05.036  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:05.040  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:05.040  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:05.049  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 08:02:05.056  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:05.057  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:05.057  6282  6282 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 08:02:05.058  6282  6282 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 08:02:05.058  6282  6282 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-05 08:02:05.062  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:05.066  6251  6251 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 08:02:05.068  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:05.073  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:05.075  6407  6407 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 08:02:05.075  6407  6407 I wpa_supplicant: monitor socket send errors count : 1
08-05 08:02:05.075  6407  6407 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1961-4\x00 that cannot receive messages
08-05 08:02:05.075  1027  6429 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 08:02:05.076  1027  6429 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 08:02:05.080  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 08:02:05.080  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:05.081  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:05.082  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:05.085  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:05.086  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 08:02:05.086  6282  6282 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 08:02:05.087  6282  6282 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 08:02:05.088  6282  6282 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 08:02:05.091  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:05.094  6251  6251 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 08:02:05.094  6251  6251 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 08:02:05.094  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:05.097  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:05.099  6407  6407 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 08:02:05.099  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 08:02:05.100  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 08:02:05.100  1027  6429 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 08:02:05.100  1027  6429 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 08:02:05.100  6407  6407 W wpa_supplicant: USIM:  scard_deinit function
08-05 08:02:05.101  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:05.101  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:05.101  1027  1089 D Tethering: InitialState.processMessage what=4
08-05 08:02:05.102  1027  1533 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=159365
08-05 08:02:05.102  1027  1533 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=159365
08-05 08:02:05.102  1027  1533 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=159365  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 08:02:05.103  1027  1533 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=159366  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 08:02:05.103  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 08:02:05.103  1027  1533 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:05.104  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:05.105  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 08:02:05.112  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:05.112  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 08:02:05.114  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:02:05.116  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:05.118  6251  6251 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 08:02:05.119  6251  6251 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 08:02:05.119  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:05.120  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 08:02:05.121  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:05.121  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:05.121  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:05.125  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 08:02:05.129  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:05.129  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:05.130  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:02:05.133  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:05.136  6251  6251 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 08:02:05.136  6251  6251 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 08:02:05.136  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:05.139  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:05.144  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:05.148  1027  6464 D DhcpStateMachine: StoppedState
08-05 08:02:05.148  1027  6464 D DhcpStateMachine: StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:05.151  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:05.151  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 08:02:05.152  1027  1533 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 08:02:05.153  1027  1533 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-05 08:02:05.153  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:02:05.159  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:05.162  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 08:02:05.166  6319  6541 W FormManager: Network not available. Please check & try again.
08-05 08:02:05.169  6319  6542 V FormManager: Network unavailable.
08-05 08:02:05.170  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:05.175  6319  6542 V FormManager: Network unavailable.
,08-05 08:02:05.176  6407  6407 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-05 08:02:05.177  1027  6429 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 08:02:05.177  1027  6429 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 08:02:05.177  1027  6429 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 08:02:05.178  1027  1533 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 36 0
08-05 08:02:05.182  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:05.182  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:05.182  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:05.182  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 08:02:05.182  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 08:02:05.184  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:05.184  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 08:02:05.184  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:05.184  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:05.184  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:05.185  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 08:02:05.283  1961  1961 D WfdsService: Supplicant Connection state is changed : false
08-05 08:02:05.283  1961  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 08:02:05.285  1961  2319 D WfdsService: Set the WFDS Monitor: false
08-05 08:02:05.285  1961  2319 D WfdsMonitor: WFDS Monitor is stopped
08-05 08:02:05.287  1027  1533 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 08:02:05.287  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:02:05.287  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:02:05.287  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 08:02:05.289  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:05.289  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 08:02:05.292  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0,
08-05 08:02:05.292  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:05.296  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:05.297  2452  2452 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:05.299  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:05.299  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:05.299  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 08:02:05.300  1027  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 08:02:05.300  1027  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 08:02:05.301  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:05.303  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:05.307  4270  6543 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 08:02:05.310  4270  6544 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:05.310  4270  6544 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 08:02:05.314  6251  6251 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-05 08:02:05.315  6251  6251 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 08:02:05.315  6251  6251 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:05.318  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 08:02:05.320  6319  6546 W FormManager: Network not available. Please check & try again.
08-05 08:02:05.324  6319  6547 V FormManager: Network unavailable.
08-05 08:02:05.326  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 08:02:05.330  6319  6547 V FormManager: Network unavailable.
08-05 08:02:05.547  1027  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=302453300, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-05 08:02:05.554  6282  6282 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-05 08:02:05.555  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1139
08-05 08:02:05.601  2640  2640 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 08:02:05.632  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=302453300 [*alarm*], flags=0x0
,08-05 08:02:05.852  6141  6390 D UEI.SmartControl: Internal timer expired: 2
08-05 08:02:05.852  6141  6390 D UEI.SmartControl: unbind internal service
,08-05 08:02:06.266  6141  6386 D serial_port: close(fd = 24)
,08-05 08:02:06.275  6141  6386 I UEI.SmartControl: Serial port is closed.
08-05 08:02:06.740  1027  1533 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1498111508] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:02:06.742  1027  1533 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1498111510] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:07.827  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:07.841  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-05 08:02:07.855  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:07.858  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:07.861  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:07.866  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 08:02:07.868  3748  3766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 08:02:07.885  5376  5376 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 08:02:07.926  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:07.926  1027  1043 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 08:02:07.945  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:02:07.946  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 08:02:07.946  1027  1027 D Ulp_jni : JNI:system_update. Event-4
,08-05 08:02:07.948  1027  1089 D BluetoothManagerService: Message: 1
08-05 08:02:07.949  1027  1089 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 08:02:07.972  2233  2233 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:08.024  1027  1089 D BluetoothManagerService: Message: 20
08-05 08:02:08.024  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17e7cb8d:true
,08-05 08:02:08.027  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:08.028  6357  6357 D BluetoothAdapterState: make
08-05 08:02:08.042  6357  6357 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 08:02:08.046  6357  6564 I BluetoothAdapterState: Entering OffState
,08-05 08:02:08.047  6357  6357 I bluedroid-qcom: init
08-05 08:02:08.048  1027  1925 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6574 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-05 08:02:08.050  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:08.052  6357  6357 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 08:02:08.055  6357  6357 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 08:02:08.055  6357  6357 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 08:02:08.055  6357  6357 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 08:02:08.055  6357  6357 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 08:02:08.055  6357  6357 I bluedroid-qcom: get_profile_interface socket
08-05 08:02:08.056  6357  6583 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 08:02:08.058  6357  6357 I bluedroid-qcom: get_profile_interface map_client
,08-05 08:02:08.059  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-05 08:02:08.059  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-05 08:02:08.061  6357  6583 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 08:02:08.047  6584  6584 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:08.047  6584  6584 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:08.064  6357  6583 D BluetoothAdapterProperties: Name is: G3
08-05 08:02:08.065  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:08.065  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 08:02:08.065  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 08:02:08.067  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:08.068  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:08.069  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:08.071  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:08.075  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 08:02:08.076  1027  1089 D BluetoothManagerService: Message: 40
08-05 08:02:08.076  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 08:02:08.076  5376  5376 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 08:02:08.076  6584  6584 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 08:02:08.076  6584  6584 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 08:02:08.076  6584  6584 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 08:02:08.078  6357  6373 I bluedroid-qcom: config_hci_snoop_log
08-05 08:02:08.078  6584  6584 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 08:02:08.079  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 08:02:08.079  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 08:02:08.080  5376  5376 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 08:02:08.086  6584  6584 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 08:02:08.086  6584  6584 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 08:02:08.088  6357  6564 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 08:02:08.088  6357  6564 D BluetoothAdapterProperties: Setting state to 11
08-05 08:02:08.088  6357  6564 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 08:02:08.089  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:02:08.089  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 08:02:08.089  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 08:02:08.090  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 08:02:08.092  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:08.093  6357  6564 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 08:02:08.093  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:08.093  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 08:02:08.094  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:08.098  1027  1084 E GpsLocationProvider: No APN found to select.
08-05 08:02:08.098  6357  6357 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 08:02:08.098  6357  6564 D BluetoothBondStateMachine: make
08-05 08:02:08.099  6357  6357 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:08.099  6357  6357 V BluetoothPbapReceiver: ***********state = 11
08-05 08:02:08.100  6357  6564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.100  6357  6564 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 08:02:08.100  6357  6564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.100  6357  6564 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 08:02:08.101  6357  6564 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 08:02:08.102  6357  6600 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 08:02:08.103  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 08:02:08.106  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:08.106  6357  6564 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 08:02:08.115  6357  6564 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:08.116  6357  6357 D HeadsetService: Received start request. Starting profile...
08-05 08:02:08.116  6357  6357 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 08:02:08.116  6213  6213 D BluetoothPermissionRequest: onReceive
08-05 08:02:08.116  6357  6357 D LGBluetoothHfpAdapter: Version 1.6
,08-05 08:02:08.119  6357  6357 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 08:02:08.120  6357  6357 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 08:02:08.120  6357  6357 D HeadsetStateMachine: make
08-05 08:02:08.122  6357  6564 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:08.122  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:08.123  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 08:02:08.127  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:08.127  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:08.128  6357  6564 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:08.132  6357  6564 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 08:02:08.137  6357  6564 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:08.140  6357  6564 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:08.144  6357  6357 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:08.144  6357  6357 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:08.147  6357  6357 D HeadsetStateMachine: max_hf_connections = 1
08-05 08:02:08.147  6357  6357 I bluedroid-qcom: get_profile_interface handsfree
08-05 08:02:08.149  6357  6357 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 08:02:08.149   312  1377 V AudioPolicyService: registerClient() client 0xb14bfbe0, uid 1002
08-05 08:02:08.150   312   312 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 08:02:08.150   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 08:02:08.150   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 08:02:08.150  6357  6357 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 08:02:08.150   312  3959 V AudioFlinger: registerClient() client 0xb55816a0, pid 6357
08-05 08:02:08.150   312  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:08.150   312  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:08.151  1597  3072 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:08.151  6357  6357 V ToneGenerator: Create Track: 0xb4928080
08-05 08:02:08.151  1597  3072 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:08.151  6357  6357 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 08:02:08.151  6357  6357 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 08:02:08.151  1870  2639 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:08.151   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 08:02:08.151  1870  2639 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-05 08:02:08.151   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 08:02:08.151   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 08:02:08.151   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 08:02:08.151  1027  2093 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:08.151  6357  6372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:08.151  1027  2093 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:08.151  6357  6372 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 08:02:08.151  3395  3411 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:08.151  3395  3411 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:08.151   312  1373 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:08.151   312  3959 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 08:02:08.151   312  1373 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:08.151   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 08:02:08.151   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 08:02:08.151   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 08:02:08.151   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 08:02:08.151  6357  6357 V AudioSystem: getLatency() output 2, latency 50
08-05 08:02:08.151  1027  1942 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:08.151  6357  6357 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 08:02:08.151  6357  6357 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 08:02:08.151  1027  1942 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:08.151  1597  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:08.151  1870  4388 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:08.151  1597  1613 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:08.151  1870  4388 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:08.151  3395  3410 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:08.151  6357  6373 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:08.151  3395  3410 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:08.152  6357  6373 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 08:02:08.152   312  3959 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 08:02:08.152   312  3959 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 08:02:08.152   312  3959 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 08:02:08.152   312  3959 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 08:02:08.152   312  3959 V AudioFlinger: createTrack() lSessionId: 22
08-05 08:02:08.152  6357  6357 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 08:02:08.152   312  3959 V AudioFlinger: acquiring 22 from 6357, for 6357
08-05 08:02:08.152   312  3959 V AudioFlinger:  added new entry for 22
08-05 08:02:08.152  6357  6357 V ToneGenerator: ToneGenerator INIT OK, time: 162428
08-05 08:02:08.152  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.153  6357  6601 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 08:02:08.153  6357  6601 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 08:02:08.153  6357  6357 D BluetoothAdapterService: ,getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.154  6357  6601 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 08:02:08.154  6357  6564 V LGMDMManager: Create singleton instance
08-05 08:02:08.155  6357  6601 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 08:02:08.155  6357  6357 D A2dpService: Received start request. Starting profile...
08-05 08:02:08.155  6357  6564 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 08:02:08.155  6574  6574 I AppUp4:AppBoxCP: onCreate
08-05 08:02:08.156  6357  6357 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 08:02:08.156  6574  6574 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-05 08:02:08.157  6357  6357 V Avrcp   : make
08-05 08:02:08.157  6357  6357 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 08:02:08.157  6357  6357 I bluedroid-qcom: get_profile_interface avrcp
08-05 08:02:08.158   312   312 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6357
08-05 08:02:08.159   312   312 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 08:02:08.159   312   312 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 08:02:08.159   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 08:02:08.159   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 08:02:08.159   312   312 V voice   : voice_set_parameters: exit with code(0)
08-05 08:02:08.159   312   312 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 08:02:08.159   312   312 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 08:02:08.159   312   312 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 08:02:08.159   312   312 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 08:02:08.159   312   312 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 08:02:08.159   312   312 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 08:02:08.159  6357  6601 V ToneGenerator: ToneGenerator destructor
08-05 08:02:08.159  6357  6601 V ToneGenerator: stopTone
08-05 08:02:08.159  6357  6601 V ToneGenerator: Delete Track: 0xb4928080
08-05 08:02:08.159   312  3960 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 08:02:08.159   312  3960 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 08:02:08.159   312  3960 V AudioFlinger: PlaybackThread::Track destructor
08-05 08:02:08.159   312  1251 V AudioPolicyService: AudioCommandThread() waking up
08-05 08:02:08.159   312  3960 V AudioFlinger: removeClient_l() pid 6357, calling pid 312
08-05 08:02:08.159   312  1251 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 08:02:08.159   312  1251 V AudioPolicyManager: releaseOutput() 2
08-05 08:02:08.159   312  1251 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 08:02:08.159  6357  6601 V AudioTrack: ~AudioTrack, releasing session id from 6357 on behalf of 6357
08-05 08:02:08.159   312  3959 V AudioFlinger: releasing 22 from 6357 for 6357
,08-05 08:02:08.159   312  3959 V AudioFlinger:  decremented refcount to 0
08-05 08:02:08.159   312  3959 V AudioFlinger: purging stale effects
08-05 08:02:08.161  1027  2093 W Process : Unable to open /proc/6603/status
08-05 08:02:08.163  6574  6574 I AppUp4:DB:  setFingerPrint start
08-05 08:02:08.163  6574  6574 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 08:02:08.165  6357  6357 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 08:02:08.166  6357  6357 E AudioManager: No RCC entry present to update
08-05 08:02:08.166  6357  6357 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-05 08:02:08.169  6357  6357 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 08:02:08.170  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 08:02:08.170  6357  6357 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 08:02:08.173  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 08:02:08.173  6574  6574 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 08:02:08.173  6574  6574 I AppUp4:DB:  SDK version = 21
08-05 08:02:08.173  6574  6574 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 08:02:08.175  6574  6574 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-05 08:02:08.176  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 08:02:08.176  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:08.177  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-05 08:02:08.178  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 08:02:08.216  6574  6574 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 08:02:08.263  1027  1995 V SIM_STK : Menu title from STK is T-Mobile
08-05 08:02:08.263  1027  1995 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:02:08.269  6574  6574 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 08:02:08.270  6574  6574 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 08:02:08.278  6574  6574 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2dfcb7a6
08-05 08:02:08.278  6574  6574 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 08:02:08.278  6574  6574 D AppUp4:CustFacade: isPhone : true
,08-05 08:02:08.280  6574  6574 D AppUp4:CustModeStarterReceiver: begin check event
08-05 08:02:08.282  6574  6574 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 08:02:08.283  6574  6574 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-05 08:02:08.305  6574  6606 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 08:02:08.305  6574  6606 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 08:02:08.305  6574  6606 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-05 08:02:08.311  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:08.311  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-05 08:02:08.313  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:08.316  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:08.325  4270  6608 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 08:02:08.326  4270  6609 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:08.326  4270  6609 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 08:02:08.387  1027  1905 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6610 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-05 08:02:08.389  1027  2026 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 08:02:08.408  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-05 08:02:08.414  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 08:02:08.415  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 08:02:08.415  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 08:02:08.415  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 08:02:08.415  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 08:02:08.415  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 08:02:08.416  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 08:02:08.416  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 08:02:08.416  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 08:02:08.416  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 08:02:08.416  6357  6357 I BluetoothA2dpServiceJni: classInitNative
08-05 08:02:08.416  6357  6357 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 08:02:08.417  6357  6357 D A2dpStateMachine: make
08-05 08:02:08.419  6357  6357 I bluedroid-qcom: get_profile_interface a2dp
08-05 08:02:08.419  6357  6631 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 08:02:08.422  6357  6357 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 08:02:08.422  6357  6357 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 08:02:08.425  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.427  6357  6357 I BluetoothHidServiceJni: classInitNative: succeeds
,08-05 08:02:08.429  6357  6357 D HidService: Received start request. Starting profile...
08-05 08:02:08.429  6357  6357 I bluedroid-qcom: get_profile_interface hidhost
08-05 08:02:08.429  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.430  6357  6630 D A2dpStateMachine: Enter Disconnected: -2
08-05 08:02:08.430  6357  6357 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 08:02:08.432  6357  6357 D HealthService: Received start request. Starting profile...
08-05 08:02:08.435  6357  6357 I bluedroid-qcom: get_profile_interface health
08-05 08:02:08.435  6357  6357 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 08:02:08.435  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.436  6357  6357 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 08:02:08.438  6357  6357 D PanService: Received start request. Starting profile...
08-05 08:02:08.438  6357  6357 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 08:02:08.438  6357  6357 I bluedroid-qcom: get_profile_interface pan
08-05 08:02:08.445  6357  6357 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 08:02:08.445  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.446  6357  6357 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-05 08:02:08.453  6357  6357 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 08:02:08.454  6357  6357 D BtGatt.GattService: Received start request. Starting profile...
08-05 08:02:08.454  6357  6357 D BtGatt.GattService: start()
08-05 08:02:08.454  6357  6357 I bluedroid-qcom: get_profile_interface gatt
08-05 08:02:08.454  6357  6357 D BtGatt.AdvertiseManager: advertise manager created
08-05 08:02:08.460  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
,08-05 08:02:08.461  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.462  6357  6357 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 08:02:08.463  6357  6357 V BluetoothMapService: BluetoothMapBinder()
08-05 08:02:08.464  6357  6357 D BluetoothMapService: Received start request. Starting profile...
08-05 08:02:08.464  6357  6357 D BluetoothMapService: start()
08-05 08:02:08.467  6357  6357 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 08:02:08.467  6357  6357 D BluetoothMapEmailAppObserver: createReceiver()
08-05 08:02:08.468  6357  6357 D BluetoothMapEmailAppObserver: initObservers()
08-05 08:02:08.469  6357  6357 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 08:02:08.470  6610  6610 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 08:02:08.470  6610  6610 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 08:02:08.472  6610  6610 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 08:02:08.472  6610  6610 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 08:02:08.477  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:08.478  6357  6357 D HeadsetStateMachine: Proxy object connected
08-05 08:02:08.478  6357  6357 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 08:02:08.479  6357  6357 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 08:02:08.480  6357  6601 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-05 08:02:08.480  6357  6601 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 08:02:08.481  6357  6601 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 08:02:08.485  6357  6357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:08.488  6357  6357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:08.489  6357  6357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:08.493  6357  6357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 08:02:08.497  6357  6357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:08.497  6357  6357 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 08:02:08.500  6357  6357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:08.503  6357  6357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 08:02:08.503  6357  6357 V BluetoothMapService: Handler(): got msg=1
08-05 08:02:08.504  6357  6357 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:02:08.504  6357  6564 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 08:02:08.504  6357  6357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:02:08.504  6357  6357 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:02:08.504  6357  6564 I bluedroid-qcom: enable
08-05 08:02:08.504  6357  6357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:08.504  6357  6357 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 08:02:08.505  6357  6638 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 08:02:08.505  6357  6638 I bt-btu  : btu_task pending for preload complete event
08-05 08:02:08.505  6357  6564 I bt_hci_bdroid: init
08-05 08:02:08.506  6357  6564 I bt_vendor: bt-vendor : init
08-05 08:02:08.506  6357  6564 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 08:02:08.506  6357  6564 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 08:02:08.506  6357  6564 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 08:02:08.506  6357  6564 D bt_userial_mct: userial_init
,08-05 08:02:08.510  6357  6564 D bt_hci_bdroid: set_power 1
08-05 08:02:08.510  6357  6564 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 08:02:08.510  6357  6564 I bt_vendor: Starting hciattach daemon
08-05 08:02:08.510  6357  6564 I bt_vendor: try to set true
08-05 08:02:08.497  6641  6641 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:08.497  6641  6641 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 08:02:08.545  6642  6642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 08:02:08.580  6610  6610 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 08:02:08.597  6610  6610 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-05 08:02:08.639  6649  6649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-05 08:02:08.650  6650  6650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 08:02:08.674  6652  6652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 08:02:08.689  6653  6653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 08:02:08.701  6654  6654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-05 08:02:08.713  6655  6655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 08:02:08.733  6657  6657 I libmdmdetect: ESOC framework not supported
,08-05 08:02:08.734  6657  6657 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-05 08:02:08.743  6657  6657 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 08:02:08.743  6657  6657 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 08:02:08.743  6657  6657 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 08:02:08.743  6657  6657 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 08:02:08.743  6657  6657 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 08:02:08.743  6657  6657 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 08:02:08.743  6657  6657 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 08:02:08.780  6657  6658 E QC-QMI  : qmi_client [6657] 14: failed to locate client data
,08-05 08:02:08.782   448   448 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 08:02:08.782   448   448 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-05 08:02:08.860  6659  6659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 08:02:08.875  6660  6660 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 08:02:08.894  1027  1771 I art     : Explicit concurrent mark sweep GC freed 128162(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.350ms total 256.274ms
,08-05 08:02:08.906  6610  6610 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 08:02:08.914  6357  6564 I bt_vendor: bluetooth satus is on
08-05 08:02:08.914  6357  6564 D bt_hci_bdroid: preload
08-05 08:02:08.914  6357  6640 D bt_userial_mct: userial_open(port:0)
08-05 08:02:08.914  6357  6640 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 08:02:08.917  6357  6640 I bt_vendor: Done intiailizing UART
08-05 08:02:08.918  6357  6640 I bt_vendor: Done intiailizing UART
08-05 08:02:08.918  6357  6640 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 08:02:08.918  6357  6640 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 08:02:08.918  6357  6662 D bt_userial_mct: Entering userial_read_thread()
08-05 08:02:08.919  6357  6638 I bt-btu  : btu_task received preload complete event
08-05 08:02:08.919  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 08:02:08.919  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 08:02:08.921  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 08:02:08.925  6357  6638 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 08:02:08.926  6357  6638 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 08:02:08.926  6357  6638 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 08:02:08.926  6357  6638 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 08:02:08.926  6357  6638 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 08:02:08.944  6610  6610 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:08.944  6610  6610 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:08.973  6357  6638 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-05 08:02:08.973  6357  6638 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b0061 
08-05 08:02:08.973  6357  6638 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b0061 
08-05 08:02:08.988  6357  6583 E bt-btif : Calling BTA_HhEnable
,08-05 08:02:08.988  6357  6583 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 08:02:08.988  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 08:02:08.988  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 08:02:08.988  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 08:02:08.989  6357  6583 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 08:02:08.989  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 08:02:08.989  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 08:02:08.990  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 08:02:08.990  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 08:02:08.990  6357  6583 D BluetoothAdapterProperties: Name is: G3
08-05 08:02:08.993  6357  6583 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:02:08.993  6357  6583 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:02:08.993  6357  6583 D bt_hci_bdroid: postload
08-05 08:02:08.994  6357  6640 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 08:02:08.994  6357  6638 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 08:02:08.994  6357  6640 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 08:02:08.994  6357  6640 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 08:02:08.994  6357  6583 D bte_conf: Device ID record 1 : primary
08-05 08:02:08.994  6357  6583 D bte_conf:   vendorId            = 00c4
08-05 08:02:08.994  6357  6583 D bte_conf:   vendorIdSource      = 0001
08-05 08:02:08.994  6357  6583 D bte_conf:   product             = 13a1
08-05 08:02:08.994  6357  6583 D bte_conf:   version             = 1000
08-05 08:02:08.987  6670  6670 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:08.987  6670  6670 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:08.994  6357  6583 D bte_conf:   clientExecutableURL = 
08-05 08:02:08.994  6357  6583 D bte_conf:   serviceDescription  = 
08-05 08:02:08.994  6357  6583 D bte_conf:   documentationURL    = 
08-05 08:02:08.994  6357  6583 D bte_conf: bte_load_did_conf no section named DID2.
08-05 08:02:08.997  6357  6640 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 08:02:08.997  6357  6640 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 08:02:08.997  6357  6583 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-05 08:02:08.997  6357  6564 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 08:02:08.998  6357  6564 D BluetoothAdapterProperties: ScanMode =  20
08-05 08:02:08.998  6357  6564 D BluetoothAdapterProperties: State =  11
08-05 08:02:08.998  6357  6564 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 08:02:08.998  6357  6564 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 08:02:08.998  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:08.998  6357  6564 D BluetoothAdapterProperties: Setting state to 12
08-05 08:02:08.998  6357  6564 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 08:02:08.999  6357  6583 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 08:02:08.999  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:02:08.999  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 08:02:08.999  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-05 08:02:09.003  1870  2638 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:02:09.003  6357  6638 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:09.003  6357  6638 W bt-smp  : Plain text(LSB ~ MSB) = 59 dd 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:09.003  6357  6638 W bt-smp  : Encrypted text(LSB ~ MSB) = 60 9b cc 4d cb c3 b2 e5 e7 72 2b 37 78 02 b8 53 
08-05 08:02:09.003  6357  6638 W bt-btm  : Stopping oneshot timer
08-05 08:02:09.003  6357  6640 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 08:02:09.004  6357  6564 I BluetoothAdapterState: Entering On State
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:09.005  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:02:09.006  6357  6662 E bt_mct  : hci lib postload completed
08-05 08:02:09.013  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:09.018  6357  6564 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 08:02:09.018  6357  6564 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 08:02:09.018  6357  6564 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-05 08:02:09.020  6357  6564 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-05 08:02:09.023  1870  2639 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:02:09.023  1870  1870 D BluetoothHeadset: Proxy object connected
08-05 08:02:09.028  6357  6638 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:09.028  6357  6638 W bt-smp  : Plain text(LSB ~ MSB) = 74 28 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:09.028  6357  6638 W bt-smp  : Encrypted text(LSB ~ MSB) = ea 7a 39 18 3a 83 a7 f5 67 61 3d 2d bf ed b6 5d 
08-05 08:02:09.028  6357  6638 W bt-btm  : Stopping oneshot timer
08-05 08:02:09.028  1870  1870 D BluetoothHeadset: Proxy object connected
08-05 08:02:09.029  6213  6229 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 08:02:09.029  6357  6583 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:02:09.030  6357  6583 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 08:02:09.032  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 08:02:09.033  6213  6213 D BluetoothInputDevice: Proxy object connected
08-05 08:02:09.033  6213  6213 D HidProfile: Bluetooth service connected
,08-05 08:02:09.035  6213  6664 D BluetoothPan: onBluetoothStateChange on: true
08-05 08:02:09.035  6213  6664 D BluetoothPan: onBluetoothStateChange call bindService
08-05 08:02:09.036  1027  1027 D BluetoothA2dp: Proxy object connected
08-05 08:02:09.039  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:02:09.039  1870  2638 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:02:09.039  1027  1027 D BluetoothHeadset: Proxy object connected
08-05 08:02:09.041  1870  1870 D BluetoothHeadset: Proxy object connected
08-05 08:02:09.041  6213  6228 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 08:02:09.043  6357  6638 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:09.043  6357  6638 W bt-smp  : Plain text(LSB ~ MSB) = 5e 2c 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:09.043  6357  6638 W bt-smp  : Encrypted text(LSB ~ MSB) = b1 83 b0 d7 fc bb 46 ca a0 6e 5c 5b 19 3e 64 37 
08-05 08:02:09.043  6357  6638 W bt-btm  : Stopping oneshot timer
08-05 08:02:09.043  6213  6664 D BluetoothMap: onBluetoothStateChange: up=true
08-05 08:02:09.050  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 08:02:09.051  1027  1089 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 08:02:09.051  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-05 08:02:09.054  6357  6564 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 08:02:09.057  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:09.057  1961  2173 D LGBluetoothAPIService: Message: 1
08-05 08:02:09.057  1961  2173 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 08:02:09.057  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 08:02:09.063  6357  6638 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:09.063  6357  6638 W bt-smp  : Plain text(LSB ~ MSB) = ba 8d 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:09.063  6357  6638 W bt-smp  : Encrypted text(LSB ~ MSB) = d5 43 c2 db 99 bd cc 1c 01 37 0d 51 90 e7 e4 c0 
08-05 08:02:09.063  6357  6638 W bt-btm  : Stopping oneshot timer
08-05 08:02:09.064  6675  6675 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 08:02:09.064  6213  6213 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 08:02:09.064  6213  6213 D PanProfile: Bluetooth service connected
08-05 08:02:09.069  6357  6357 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:09.069  6357  6357 D BluetoothMapService: STATE_ON
08-05 08:02:09.069  6357  6357 V BluetoothMapService: Handler(): got msg=1
08-05 08:02:09.069  1027  1089 D BluetoothManagerService: Message: 40
08-05 08:02:09.069  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-05 08:02:09.072  5967  5967 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 08:02:09.074  6357  6357 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 08:02:09.074  1961  2173 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-05 08:02:09.076  6357  6678 D BluetoothMapMasInstance: MAS initSocket()
08-05 08:02:09.076  6357  6357 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 08:02:09.076  6357  6678 D BluetoothMapMasInstance:   masId = 00
08-05 08:02:09.076  6357  6678 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 08:02:09.076  6357  6678 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 08:02:09.076  6357  6678 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 08:02:09.077  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:09.078  6357  6357 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 08:02:09.078  6213  6213 D BluetoothMap: Proxy object connected
08-05 08:02:09.078  6213  6213 D MapProfile: Bluetooth service connected
08-05 08:02:09.078  6213  6213 D BluetoothMap: getConnectedDevices()
08-05 08:02:09.078  6357  6638 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:09.079  6357  6638 W bt-smp  : Plain text(LSB ~ MSB) = c9 54 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:09.079  6357  6638 W bt-smp  : Encrypted text(LSB ~ MSB) = 2d 25 75 df 78 07 04 bf 8c 36 4f e7 43 4f 2c e4 
08-05 08:02:09.079  6357  6638 W bt-btm  : Stopping oneshot timer
08-05 08:02:09.079  1961  1961 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 08:02:09.079  1961  2173 D LGBluetoothAPIService: Message: 100
08-05 08:02:09.079  1961  2173 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:09.082  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:02:09.083  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:09.085  6357  6373 V BluetoothMapService: getConnectedDevices()
08-05 08:02:09.085  6357  6678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:09.087  6357  6678 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,08-05 08:02:09.087  6357  6583 D BluetoothAdapterProperties: Scan Mode:21
08-05 08:02:09.088  6357  6583 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 08:02:09.088  6357  6678 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 08:02:09.088  6357  6678 D BluetoothMapMasInstance: Accepting socket connection...
08-05 08:02:09.090  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:09.092  6213  6213 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-05 08:02:09.093  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:09.094  1027  1089 D BluetoothManagerService: Message: 30
,08-05 08:02:09.097  6213  6213 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 08:02:09.100  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:09.100  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:09.101  6357  6357 V BluetoothPbapService: Pbap Service onCreate
08-05 08:02:09.101  6357  6357 V BluetoothPbapService: Starting PBAP service
08-05 08:02:09.102  6357  6357 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 08:02:09.102  6357  6357 V BluetoothPbapService: Pbap Service onBind
08-05 08:02:09.102  1027  1089 D BluetoothManagerService: Message: 30
08-05 08:02:09.104  6357  6357 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:09.104  6357  6357 V BluetoothPbapService: state: 12
08-05 08:02:09.104  6357  6357 V BluetoothPbapService: Handler(): got msg=1
08-05 08:02:09.105  6357  6357 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 08:02:09.106  6357  6684 V BluetoothPbapService: Pbap Service initSocket
08-05 08:02:09.106  1027  2093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 08:02:09.111  6357  6684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:09.112  6357  6684 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 08:02:09.112  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 08:02:09.112  6357  6684 V BluetoothPbapService: Succeed to create listening socket 
08-05 08:02:09.112  6357  6684 V BluetoothPbapService: Accepting socket connection...
08-05 08:02:09.114  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 08:02:09.116  6213  6213 D BluetoothA2dp: Proxy object connected
08-05 08:02:09.117  6213  6213 D A2dpProfile: Bluetooth service connected
08-05 08:02:09.118  6357  6357 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 08:02:09.118  6357  6357 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-05 08:02:09.118  6357  6357 V BluetoothPbapReceiver: ***********state = 12
,08-05 08:02:09.120  6213  6213 D BluetoothPbap: Proxy object connected
08-05 08:02:09.121  6213  6213 D PbapServerProfile: Bluetooth service connected
08-05 08:02:09.121  6213  6213 D BluetoothHeadset: Proxy object connected
08-05 08:02:09.122  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 08:02:09.122  6213  6213 D HeadsetProfile: Bluetooth service connected
08-05 08:02:09.123  2233  2233 D c       : Getting all permits...
08-05 08:02:09.123  2233  2233 D a       : Opening database...
08-05 08:02:09.128  6213  6213 D DockEventReceiver: finishStartingService: stopping service
08-05 08:02:09.130  2233  2233 D a       : Opening database auth.proximity.permit_store...
,08-05 08:02:09.131  2233  2233 D a       : Closing database...
08-05 08:02:09.141  6213  6213 D BluetoothPermissionRequest: onReceive
08-05 08:02:09.143  6213  6213 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-05 08:02:09.145  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 08:02:09.150  6357  6357 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 08:02:09.151  6357  6357 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 08:02:09.158  6357  6357 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 08:02:09.173  6357  6357 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 08:02:09.174  6357  6357 V BtOppService: onCreate
08-05 08:02:09.177  6357  6357 V BluetoothOppNotification: send message
08-05 08:02:09.179  6357  6357 V BtOppService: Starting RfcommListener
08-05 08:02:09.180  6610  6610 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 08:02:09.184  6357  6357 D BluetoothOppPreference: Dumping Names:  
08-05 08:02:09.184  6357  6357 D BluetoothOppPreference: {}
08-05 08:02:09.184  6357  6357 D BluetoothOppPreference: Dumping Channels:  
08-05 08:02:09.184  6357  6357 D BluetoothOppPreference: {}
08-05 08:02:09.184  6357  6357 V BtOppService: onStartCommand
08-05 08:02:09.187  6357  6692 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 08:02:09.188  6357  6357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:09.188  6357  6357 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 08:02:09.191  6357  6692 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-05 08:02:09.193  6357  6357 V BluetoothOppNotification: new notify threadi!
08-05 08:02:09.193  6357  6689 V BtOppService: Deleted complete outbound shares, number =  0
08-05 08:02:09.193  6357  6357 V BluetoothOppNotification: send delay message
08-05 08:02:09.194  6357  6357 V BtOppService: start RfcommListener
08-05 08:02:09.195  6357  6693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 08:02:09.196  6357  6692 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3233fb89 on behalf of 
08-05 08:02:09.197  6357  6689 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 08:02:09.197  6357  6689 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 08:02:09.198  6357  6693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bbc078e on behalf of 
08-05 08:02:09.198  6357  6689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f30abaf on behalf of 
08-05 08:02:09.199  6357  6692 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 08:02:09.201  6357  6693 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 08:02:09.201  6357  6357 V BtOppService: RfcommListener started
08-05 08:02:09.202  6357  6694 V BtOppRfcommListener: Starting RFCOMM listener....
,08-05 08:02:09.203  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:09.203  6357  6693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 08:02:09.205  6357  6694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:09.206  6357  6693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24629bbc on behalf of 
08-05 08:02:09.207  6357  6693 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 08:02:09.208  6357  6694 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-05 08:02:09.208  6357  6694 V BtOppRfcommListener: Started RFCOMM listener....
08-05 08:02:09.208  6357  6694 I BtOppRfcommListener: Accept thread started.
08-05 08:02:09.208  6357  6694 V BtOppRfcommListener: Accepting connection...
08-05 08:02:09.210  6357  6693 V BluetoothOppNotification: outbound notification was removed.
08-05 08:02:09.210  6357  6693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 08:02:09.211  6357  6693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38d7c745 on behalf of 
08-05 08:02:09.212  6357  6693 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 08:02:09.214  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 08:02:09.214  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:09.216  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 08:02:09.216  3395  3395 D PhoneState: setPdpRejectCasuse : false
08-05 08:02:09.217  6357  6693 V BluetoothOppNotification: inbound notification was removed.
08-05 08:02:09.217  6357  6693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 08:02:09.218  6357  6693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16f50e9a on behalf of 
08-05 08:02:09.222  6610  6610 I HubEmail: JNI_OnLoad()
08-05 08:02:09.222  6610  6610 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 08:02:09.222  6610  6610 I HubEmail: registerNatives()
08-05 08:02:09.222  6610  6610 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 08:02:09.222  6610  6610 I HubEmail: registerNativeMethods()
08-05 08:02:09.222  6610  6610 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 08:02:09.223  6610  6610 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 08:02:09.223  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:09.224  6357  6357 V BluetoothFtpService: Ftp Service onCreate
08-05 08:02:09.224  6357  6357 I BluetoothFtpService: Ftp Service onCreate
08-05 08:02:09.224  6357  6357 V BluetoothFtpService: Ftp Service onStartCommand
08-05 08:02:09.224  6357  6357 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:09.224  6357  6357 V BluetoothFtpService: Starting Listening on sockets
08-05 08:02:09.225  6357  6357 V BtOppService: ContentObserver received notification
08-05 08:02:09.225  6357  6357 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:02:09.225  6357  6357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:02:09.225  6357  6357 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:02:09.225  6357  6357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:09.225  6357  6357 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 08:02:09.225  6357  6357 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 08:02:09.226  6357  6700 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-05 08:02:09.226  6357  6700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 08:02:09.227  6357  6700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a9bb7a8 on behalf of 
08-05 08:02:09.227  6357  6700 V BluetoothOppNotification: update too frequent, put in queue
08-05 08:02:09.228  6357  6700 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 08:02:09.254  1027  2317 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6701 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 08:02:09.258  6357  6357 V BtOppService: ContentObserver received notification
08-05 08:02:09.258  6357  6357 V BluetoothFtpService: Handler(): got msg=1
08-05 08:02:09.258  6357  6357 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 08:02:09.259  6357  6357 V BluetoothFtpService: Ftp Service initSocket
08-05 08:02:09.261  1027  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:09.262  6610  6699 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:09.265  6357  6711 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 08:02:09.265  6357  6711 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 08:02:09.265  6357  6357 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:09.266  6319  6697 W FormManager: Network not available. Please check & try again.
08-05 08:02:09.266  6357  6711 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a3292c1 on behalf of 
08-05 08:02:09.267  6357  6357 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-05 08:02:09.267  6357  6357 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 08:02:09.267  6357  6711 V BluetoothOppNotification: update too frequent, put in queue
,08-05 08:02:09.273  6357  6713 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 08:02:09.276  6357  6711 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 08:02:09.278  6319  6698 V FormManager: Network unavailable.
08-05 08:02:09.281  6319  6698 V FormManager: Network unavailable.
08-05 08:02:09.282  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
,08-05 08:02:09.282  6357  6357 V BluetoothSapService: Sap Service onCreate
08-05 08:02:09.292  6357  6357 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:09.292  6357  6357 V BluetoothSapService: state: 12
08-05 08:02:09.292  6357  6357 V BluetoothSapService: Starting SAP server process
08-05 08:02:09.293  6357  6357 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 08:02:09.294  6357  6721 V BluetoothSapService: Sap Service initRfcommSocket
,08-05 08:02:09.287  6720  6720 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:09.295  1027  2317 I ActivityManager: Killing 5850:com.android.gallery3d/u0a27 (adj 15): empty #17
08-05 08:02:09.287  6720  6720 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:09.305  6720  6720 V BT_SAP  : Event pipe created
08-05 08:02:09.305  6720  6720 V BT_SAP  : create_server_socket qcom.sap.server
08-05 08:02:09.305  6720  6720 V BT_SAP  : created socket fd 6
08-05 08:02:09.314  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:09.314  1027  1925 W libprocessgroup: failed to open /acct/uid_10027/pid_5850/cgroup.procs: No such file or directory
08-05 08:02:09.315  6357  6721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:02:09.319  6357  6721 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-05 08:02:09.319  6357  6721 V BluetoothSapService: Succeed to create listening socket 
08-05 08:02:09.319  6357  6721 V BluetoothSapService: Accepting socket connection...
08-05 08:02:09.380  6701  6701 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:09.380  6701  6701 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 08:02:09.383  6701  6701 D PhoneMonitor: Register our PhoneStateListener
,08-05 08:02:09.407  6701  6701 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 08:02:09.412  6701  6701 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 08:02:09.442  6701  6701 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-05 08:02:09.447  6701  6701 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 08:02:09.448  6701  6701 D TelephonyAutoProfiling: [parse] Load xml
08-05 08:02:09.451  6701  6701 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 08:02:09.451  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 08:02:09.452  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 08:02:09.452  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 08:02:09.452  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 08:02:09.452  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 08:02:09.452  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 08:02:09.452  6701  6701 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 08:02:09.452  6701  6701 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-05 08:02:09.467  6701  6701 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 08:02:09.478  1027  2036 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6725 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 08:02:09.479  1027  2036 I ActivityManager: Killing 5914:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-05 08:02:09.529  1027  1942 W libprocessgroup: failed to open /acct/uid_10061/pid_5914/cgroup.procs: No such file or directory
,08-05 08:02:09.936  1027  1942 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6752 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-05 08:02:09.939  1027  1942 I ActivityManager: Killing 6036:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-05 08:02:09.985  1027  1531 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:09.985  1027  1531 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 08:02:09.999  1027  1925 W libprocessgroup: failed to open /acct/uid_10080/pid_6036/cgroup.procs: No such file or directory
,08-05 08:02:10.022  1027  1533 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-05 08:02:10.022  1027  1533 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 08:02:10.030  6752  6752 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
08-05 08:02:10.032  6752  6752 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-05 08:02:10.063  6752  6752 V DrmService: Service onCreate
08-05 08:02:10.064  6752  6752 D DrmService: Received new request = 2
,08-05 08:02:10.074  6752  6779 I DrmSntpClient: Start Sync process
08-05 08:02:10.074  6752  6779 D DrmSntpClient: Server : 0
08-05 08:02:10.080  1027  1942 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6781 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 08:02:10.083  6752  6779 D DrmSntpClient: Automatic sync but WiFi isn't enabled
,08-05 08:02:10.085  6752  6752 D DrmService: Completed !! request = 2
,08-05 08:02:10.085  6752  6752 D DrmService: Request count = 0
08-05 08:02:10.086  6752  6752 V DrmService: Service onDestroy
08-05 08:02:10.087  1027  1995 I ActivityManager: Killing 6089:com.lge.eula/1000 (adj 15): empty #17
08-05 08:02:10.167  1027  1960 W libprocessgroup: failed to open /acct/uid_1000/pid_6089/cgroup.procs: No such file or directory
,08-05 08:02:10.195  6357  6357 V BluetoothOppNotification: new notify threadi!
,08-05 08:02:10.195  6357  6357 V BluetoothOppNotification: send delay message
08-05 08:02:10.197  6357  6805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 08:02:10.199  6357  6805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@291499fd on behalf of 
08-05 08:02:10.200  6357  6805 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 08:02:10.201  6357  6805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 08:02:10.202  6357  6805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b5ed6f2 on behalf of 
08-05 08:02:10.203  6357  6805 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 08:02:10.204  6357  6805 V BluetoothOppNotification: outbound notification was removed.
08-05 08:02:10.205  6357  6805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 08:02:10.206  6357  6805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e0b7143 on behalf of 
08-05 08:02:10.207  6357  6805 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-05 08:02:10.208  6357  6805 V BluetoothOppNotification: inbound notification was removed.
08-05 08:02:10.208  6357  6805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 08:02:10.210  6357  6805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@433d3c0 on behalf of 
08-05 08:02:10.224  6781  6781 I art     : Almond Protected OAT
,08-05 08:02:10.281  6781  6781 D WeatherApplication: removeAccount
,08-05 08:02:10.283  6781  6781 D WeatherApplication: Account.length = 0
,08-05 08:02:10.284  6781  6781 E WeatherApplication: OPERATOR:OPEN
08-05 08:02:10.289  6781  6781 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:10
08-05 08:02:10.293  6781  6781 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 08:02:10.293  6781  6781 D Weather.Utils: 2 : All the weather widget is gone.
08-05 08:02:10.295  6781  6781 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-05 08:02:10.297  6781  6781 D WeatherAncestor: connectivity changed - connection : true
08-05 08:02:10.298  6781  6781 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-05 08:02:10.310  6781  6781 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 08:02:10.311  6781  6781 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 08:02:10.311  6781  6781 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-05 08:02:10.346  6781  6781 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 08:02:10.346  6781  6781 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:10
,08-05 08:02:10.383  1027  1925 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6810 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 08:02:10.384  1027  1925 I ActivityManager: Killing 6061:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-05 08:02:10.438  1027  1960 W libprocessgroup: failed to open /acct/uid_10097/pid_6061/cgroup.procs: No such file or directory
,08-05 08:02:10.555   278   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 08:02:10.556   278   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 08:02:10.556   278   454 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 08:02:10.559  6810  6828 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 08:02:10.562   278   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 08:02:10.562   278   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 08:02:10.562   278   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 08:02:10.562  6810  6828 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 08:02:10.569   278   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 08:02:10.569   278   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 08:02:10.569   278   454 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 08:02:10.573  6810  6830 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 08:02:10.575   278   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 08:02:10.576   278   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 08:02:10.576   278   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 08:02:10.576  6810  6830 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 08:02:10.848  6810  6810 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 08:02:10.861  6810  6810 I LibraryLoader: Loading: webviewchromium
,08-05 08:02:10.865  6810  6810 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5136-5141)
08-05 08:02:10.866  6810  6810 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 08:02:10.876  6810  6810 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27f55973}
,08-05 08:02:10.879  6810  6810 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 08:02:10.880  6810  6810 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 08:02:10.907  6810  6810 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 08:02:10.909  6810  6810 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 08:02:10.927  6810  6810 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-05 08:02:10.929  6810  6810 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 08:02:10.929  6810  6810 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 08:02:10.945   312   312 V AudioPolicyService: registerClient() client 0xb57d6d60, uid 10093
,08-05 08:02:10.949  6810  6852 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 08:02:10.952  1027  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:10.952  1027  1942 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@22848f0d mBinding = false
08-05 08:02:10.970  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:02:10.970  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-05 08:02:10.970  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-05 08:02:10.970  1027  1089 D BluetoothManagerService: Message: 2
08-05 08:02:10.971  1027  1089 D BluetoothManagerService: Sending off request.
08-05 08:02:10.972  6357  6372 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 08:02:10.973  6357  6564 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 08:02:10.973  6357  6564 D BluetoothAdapterProperties: Setting state to 13
08-05 08:02:10.973  6357  6564 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 08:02:10.973  6357  6564 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 08:02:10.974  6357  6564 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-05 08:02:10.975  6357  6583 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:02:10.976  6357  6564 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 08:02:10.977  6357  6564 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 08:02:10.977  6357  6684 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:02:10.977  6357  6713 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:02:10.978  6357  6721 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:02:10.978  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 08:02:10.979  6357  6694 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:02:10.979  6357  6638 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 08:02:10.979  6357  6678 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 08:02:10.982  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:10.982  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:10.983  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:10.983  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:10.986  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor: upda,teConnectivityInfo: State changed:
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:10.986  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:10.986  5967  5967 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:02:10.986  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:10.987  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:02:10.987  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 08:02:10.987  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 08:02:10.989  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:10.989  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 08:02:10.992  6357  6357 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:10.992  6357  6357 D BluetoothMapService: STATE_TURNING_OFF
08-05 08:02:10.992  6357  6357 V BtOppService: Receiver DISABLED_ACTION 
,08-05 08:02:10.992  6357  6357 V BluetoothMapService: Handler(): got msg=4
08-05 08:02:10.993  6357  6357 D BluetoothMapService: MAP Service closeService in
08-05 08:02:10.993  6357  6357 D BluetoothMapMasInstance: MAP Service shutdown
08-05 08:02:10.993  6357  6357 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 08:02:10.993  6357  6357 V BluetoothMapService: MAP Service closeService out
08-05 08:02:10.993  6357  6357 I BtOppRfcommListener: stopping Accept Thread
08-05 08:02:10.993  6357  6357 V BtOppRfcommListener: close mBtServerSocket
08-05 08:02:10.995  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-05 08:02:10.995  6357  6357 V BtOppRfcommListener: waiting for thread to terminate
08-05 08:02:10.995  6357  6694 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 08:02:10.996  6357  6357 V BtOppRfcommListener: done waiting for thread to terminate
08-05 08:02:10.998  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:10.999  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 08:02:11.002  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 08:02:11.002  6357  6638 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 08:02:11.003  6357  6357 V BtOppService: onDestroy
08-05 08:02:11.003  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 08:02:11.004  6810  6810 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 08:02:11.004  6810  6810 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 08:02:11.004  6810  6810 I Adreno-EGL: Build Date: 12/12/14 금
08-05 08:02:11.004  6810  6810 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 08:02:11.004  6810  6810 I Adreno-EGL: Remote Branch: 
08-05 08:02:11.004  6810  6810 I Adreno-EGL: Local Patches: 
08-05 08:02:11.004  6810  6810 I Adreno-EGL: Reconstruct Branch: 
,08-05 08:02:11.008  6357  6357 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 08:02:11.012  6357  6357 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 08:02:11.012  6357  6357 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:11.012  6357  6357 V BluetoothPbapReceiver: ***********state = 13
08-05 08:02:11.014  6213  6213 D DockEventReceiver: finishStartingService: stopping service
08-05 08:02:11.015  6357  6357 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 08:02:11.017  6357  6357 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:11.017  6357  6357 V BluetoothPbapService: state: 13
08-05 08:02:11.017  6357  6357 V BluetoothPbapService: Pbap Service closeService in
08-05 08:02:11.020  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:02:11.023  6213  6213 D BluetoothPbap: Proxy object disconnected
,08-05 08:02:11.023  6213  6213 D PbapServerProfile: Bluetooth service disconnected
08-05 08:02:11.024  6357  6357 V BluetoothPbapService: successfully stopped pbap service
08-05 08:02:11.025  6357  6357 V BluetoothPbapService: Pbap Service closeService out
08-05 08:02:11.025  6357  6357 V BluetoothPbapService: Pbap Service onDestroy
08-05 08:02:11.025  6357  6357 V BluetoothPbapService: Pbap Service closeService in
08-05 08:02:11.025  6357  6357 V BluetoothPbapService: Pbap Service closeService out
08-05 08:02:11.025  6357  6357 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 08:02:11.034  6213  6213 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 08:02:11.040  6213  6213 D BluetoothPermissionRequest: onReceive
08-05 08:02:11.040  6213  6213 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 08:02:11.056  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 08:02:11.062  6357  6357 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 08:02:11.062  6357  6357 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 08:02:11.063  6357  6357 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 08:02:11.069  6357  6357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 08:02:11.069  6357  6357 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 08:02:11.071  6357  6357 V BluetoothFtpService: Ftp Service onStartCommand
08-05 08:02:11.072  6357  6357 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:11.072  6357  6357 V BluetoothFtpService: Ftp Service closeService
08-05 08:02:11.072  6357  6357 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 08:02:11.074  6357  6357 V BluetoothFtpService: successfully stopped ftp service
08-05 08:02:11.074  6357  6357 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:02:11.074  6357  6357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:02:11.074  6357  6357 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:02:11.074  6357  6357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:11.074  6357  6357 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 08:02:11.074  6357  6357 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 08:02:11.076  6357  6357 V BluetoothFtpService: Ftp Service onDestroy
08-05 08:02:11.076  6357  6357 V BluetoothFtpService: Ftp Service closeService
08-05 08:02:11.081  6357  6357 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:11.081  6357  6357 V BluetoothSapService: state: 13
08-05 08:02:11.082  6357  6357 V BluetoothSapService: Stopping SAP server process
08-05 08:02:11.082  6357  6357 V BluetoothSapService: Sap Service closeSapService in
08-05 08:02:11.082  6357  6357 V BluetoothSapService: Close listen Socket : 
08-05 08:02:11.083  6357  6357 V BluetoothSapService: Close rfcomm Socket : 
08-05 08:02:11.083  6357  6357 V BluetoothSapService: Close sapd  Socket : 
,08-05 08:02:11.092  6357  6357 V BluetoothSapService: Sap Service closeSapService out
08-05 08:02:11.093  6357  6357 V BluetoothSapService: Sap Service onDestroy
08-05 08:02:11.093  6357  6357 V BluetoothSapService: Sap Service closeSapService in
08-05 08:02:11.093  6357  6357 V BluetoothSapService: Close listen Socket : 
08-05 08:02:11.093  6357  6357 V BluetoothSapService: Close rfcomm Socket : 
08-05 08:02:11.093  6357  6357 V BluetoothSapService: Close sapd  Socket : 
08-05 08:02:11.096  6357  6357 V BluetoothSapService: Sap Service closeSapService out
08-05 08:02:11.113  6810  6810 I NSApplication: Starting up...
,08-05 08:02:11.174  1027  1647 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6873 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 08:02:11.175  1027  1647 I ActivityManager: Killing 5871:com.android.vending/u0a44 (adj 15): empty #17
,08-05 08:02:11.244  1027  1371 W libprocessgroup: failed to open /acct/uid_10044/pid_5871/cgroup.procs: No such file or directory
,08-05 08:02:11.285  6873  6873 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 08:02:11.569  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 08:02:11.573  3748  3766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 08:02:11.591  2233  2233 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:11.604  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 08:02:11.604  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:11.605  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 08:02:11.605  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-05 08:02:11.607  6574  6574 I AppUp4:CustModeStarterReceiver: onReceive
08-05 08:02:11.611  6574  6574 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2dfcb7a6
08-05 08:02:11.611  6574  6574 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 08:02:11.611  6574  6574 D AppUp4:CustFacade: isPhone : true
08-05 08:02:11.611  6574  6574 D AppUp4:CustModeStarterReceiver: begin check event
08-05 08:02:11.612  6574  6574 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 08:02:11.615  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:11.615  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 08:02:11.617  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:11.620  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:11.628  6610  6610 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 08:02:11.632  4270  6905 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 08:02:11.642  4270  6906 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:11.642  4270  6906 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 08:02:11.656  6610  6912 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 08:02:11.664  6319  6918 W FormManager: Network not available. Please check & try again.
08-05 08:02:11.672  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 08:02:11.673  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:11.673  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-05 08:02:11.678  6701  6701 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 08:02:11.679  6701  6701 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 08:02:11.684  6319  6919 V FormManager: Network unavailable.
08-05 08:02:11.690  6319  6919 V FormManager: Network unavailable.
,08-05 08:02:11.696  6781  6781 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:11
08-05 08:02:11.697  6781  6781 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 08:02:11.698  6781  6781 D Weather.Utils: 2 : All the weather widget is gone.
08-05 08:02:11.698  6781  6781 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 08:02:11.698  6781  6781 D WeatherAncestor: connectivity changed - connection : true
08-05 08:02:11.698  6781  6781 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a094594
08-05 08:02:11.700  6781  6781 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 08:02:11.700  6781  6781 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 08:02:11.700  6781  6781 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 08:02:11.700  6781  6781 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 08:02:11.700  6781  6781 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:11
08-05 08:02:11.724  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 08:02:11.725  3748  3766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 08:02:11.744  2233  2233 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:11.757  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 08:02:11.757  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:11.757  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 08:02:11.757  6574  6574 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 08:02:11.759  6574  6574 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 08:02:11.763  6574  6574 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2dfcb7a6
08-05 08:02:11.763  6574  6574 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 08:02:11.763  6574  6574 D AppUp4:CustFacade: isPhone : true
08-05 08:02:11.763  6574  6574 D AppUp4:CustModeStarterReceiver: begin check event
08-05 08:02:11.763  6574  6574 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 08:02:11.767  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:11.767  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 08:02:11.769  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:11.772  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 08:02:11.780  6610  6610 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 08:02:11.780  4270  6926 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 08:02:11.792  4270  6927 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:11.792  4270  6927 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 08:02:11.802  6610  6928 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:11.805  6319  6930 W FormManager: Network not available. Please check & try again.
,08-05 08:02:11.811  6319  6931 V FormManager: Network unavailable.
08-05 08:02:11.823  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 08:02:11.823  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:11.823  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-05 08:02:11.827  6701  6701 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 08:02:11.827  6701  6701 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 08:02:11.829  6319  6931 V FormManager: Network unavailable.
08-05 08:02:11.853  6781  6781 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:11
,08-05 08:02:11.856  6781  6781 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 08:02:11.856  6781  6781 D Weather.Utils: 2 : All the weather widget is gone.
08-05 08:02:11.857  6781  6781 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 08:02:11.857  6781  6781 D WeatherAncestor: connectivity changed - connection : true
08-05 08:02:11.857  6781  6781 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a094594
08-05 08:02:11.858  6781  6781 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 08:02:11.858  6781  6781 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 08:02:11.858  6781  6781 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 08:02:11.858  6781  6781 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 08:02:11.859  6781  6781 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:11
08-05 08:02:11.950  6357  6638 W bt-btif : ag scb idx 1 not allocated
08-05 08:02:11.950  6357  6583 D bt_hci_bdroid: cleanup
08-05 08:02:11.950  6357  6640 I bt_lpm  : LPM is already off!!!
08-05 08:02:11.950  6357  6638 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:02:11.950  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-05 08:02:11.951  6357  6638 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:02:11.951  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 08:02:11.951  6357  6662 I bt_userial_mct: exiting userial_read_thread
08-05 08:02:11.951  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:02:11.951  6357  6662 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 08:02:11.951  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 08:02:11.951  6357  6638 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:02:11.951  6357  6638 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 08:02:11.951  6357  6638 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 08:02:11.951  6357  6638 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 08:02:11.951  6357  6583 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 08:02:11.951  6357  6640 I bt_vendor: hw_epilog_process
08-05 08:02:11.952  6357  6583 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 08:02:11.952  6357  6583 D bt_userial_mct: userial_close
08-05 08:02:11.952  6357  6583 E bt_userial_mct: pthread_join() FAILED result:3
08-05 08:02:11.953  6357  6583 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-05 08:02:11.984  6357  6583 D bt_hci_bdroid: set_power 0
08-05 08:02:11.984  6357  6583 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 08:02:11.984  6357  6583 I bt_vendor: bluetooth satus is on
08-05 08:02:11.984  6357  6583 I bt_vendor: bt-vendor : resetting BT status
08-05 08:02:11.984  6357  6583 I bt_vendor: Starting hciattach daemon
08-05 08:02:11.985  6357  6583 I bt_vendor: try to set false
08-05 08:02:11.986  6357  6583 I bt_vendor: Starting hciattach daemon
08-05 08:02:11.986  6357  6583 I bt_vendor: try to set false
,08-05 08:02:11.987  6357  6583 I bt_vendor: cleanup
08-05 08:02:11.989  6357  6638 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 08:02:11.990  6357  6583 I GKI_LINUX: GKI_exit_task 0 done
08-05 08:02:11.990  6357  6583 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-05 08:02:11.993  6357  6564 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 08:02:12.000  6357  6357 D HeadsetService: Received stop request...Stopping profile...
08-05 08:02:12.002  6357  6357 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 08:02:12.002  6357  6357 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 08:02:12.003  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
,08-05 08:02:12.003  6357  6601 D HeadsetStateMachine: Exit Disconnected: -1
08-05 08:02:12.007  6213  6213 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:12.008  6213  6213 D HeadsetProfile: Bluetooth service disconnected
08-05 08:02:12.008  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:12.008  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 08:02:12.009  1870  1870 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:12.009  1870  1870 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:12.009  1870  1870 D BluetoothHeadset: Proxy object disconnected
08-05 08:02:12.010  6357  6357 D A2dpService: Received stop request...Stopping profile...
08-05 08:02:12.010  6357  6564 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 08:02:12.011  6357  6630 D A2dpStateMachine: Exit Disconnected: -1
08-05 08:02:12.012  6357  6357 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 08:02:12.014  6357  6357 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 08:02:12.014  6357  6357 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 08:02:12.015  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:12.016  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-05 08:02:12.016  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 08:02:12.016  6213  6213 D BluetoothA2dp: Proxy object disconnected
08-05 08:02:12.016  6213  6213 D A2dpProfile: Bluetooth service disconnected
,08-05 08:02:12.019  6357  6357 D HidService: Received stop request...Stopping profile...
08-05 08:02:12.019  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:12.020  6213  6213 D BluetoothInputDevice: Proxy object disconnected
08-05 08:02:12.020  6213  6213 D HidProfile: Bluetooth service disconnected
,08-05 08:02:12.022  6357  6357 D HealthService: Received stop request...Stopping profile...
08-05 08:02:12.023  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:12.026  6357  6357 D HeadsetStateMachine: Unbinding service...
08-05 08:02:12.026  6357  6357 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 08:02:12.026  6357  6357 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 08:02:12.026  6357  6357 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 08:02:12.027  6357  6357 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 08:02:12.027  6357  6357 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 08:02:12.027  6357  6357 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 08:02:12.027  6357  6357 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 08:02:12.028  6357  6357 D PanService: Received stop request...Stopping profile...
08-05 08:02:12.028  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:12.029  6213  6213 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 08:02:12.029  6213  6213 D PanProfile: Bluetooth service disconnected
08-05 08:02:12.030  6357  6357 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 08:02:12.031  6357  6357 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 08:02:12.031  6357  6357 D BtGatt.GattService: stop()
08-05 08:02:12.031  6357  6357 D BtGatt.AdvertiseManager: advertise clients cleared
,08-05 08:02:12.034  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
,08-05 08:02:12.035  6357  6357 D BluetoothMapService: Received stop request...Stopping profile...
08-05 08:02:12.035  6357  6357 D BluetoothMapService: stop()
08-05 08:02:12.036  6357  6357 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 08:02:12.036  6357  6357 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 08:02:12.037  6357  6357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:12.038  6357  6357 I BluetoothA2dpServiceJni: cleanupNative
08-05 08:02:12.038  6357  6631 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 08:02:12.038  6213  6213 D BluetoothMap: Proxy object disconnected
08-05 08:02:12.038  6213  6213 D MapProfile: Bluetooth service disconnected
08-05 08:02:12.039  6357  6357 I GKI_LINUX: GKI_exit_task 2 done
08-05 08:02:12.039  6357  6357 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-05 08:02:12.040  6357  6357 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 08:02:12.040  6357  6357 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 08:02:12.040  6357  6357 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 08:02:12.040  6357  6357 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 08:02:12.041  6357  6357 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 08:02:12.041  6357  6357 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 08:02:12.041  6357  6357 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 08:02:12.043  6357  6357 V BluetoothMapService: Handler(): got msg=4
08-05 08:02:12.043  6357  6357 D BluetoothMapService: MAP Service closeService in
08-05 08:02:12.043  6357  6357 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 08:02:12.044  6357  6357 V BluetoothMapService: MAP Service closeService out
08-05 08:02:12.044  6357  6564 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 08:02:12.045  6357  6564 D BluetoothAdapterProperties: Setting state to 10
08-05 08:02:12.045  6357  6564 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 08:02:12.046  6357  6564 I BluetoothAdapterState: Entering OffState
08-05 08:02:12.046  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:02:12.046  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 08:02:12.046  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-05 08:02:12.047  6357  6357 D BluetoothMapService: cleanup()
08-05 08:02:12.047  6357  6357 D BluetoothMapService: MAP Service closeService in
08-05 08:02:12.048  6213  6664 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 08:02:12.048  6357  6357 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 08:02:12.048  6357  6357 V BluetoothMapService: MAP Service closeService out
08-05 08:02:12.048  1870  1886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:12.049  1870  1885 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 08:02:12.050  6213  6229 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-05 08:02:12.051  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 08:02:12.051  6213  6228 D BluetoothPan: onBluetoothStateChange on: false
08-05 08:02:12.052  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:12.052  1870  4388 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:12.053  6213  6664 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:02:12.053  6213  6229 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 08:02:12.054  6213  6228 D BluetoothMap: onBluetoothStateChange: up=false
08-05 08:02:12.056  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 08:02:12.056  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 08:02:12.059  1027  1089 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 08:02:12.059  1027  1089 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 08:02:12.059  1027  1089 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@22848f0d mBinding = false
08-05 08:02:12.060  1027  1089 D BluetoothManagerService: Sending unbind request.
08-05 08:02:12.062  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 08:02:12.064  6357  6583 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 08:02:12.065  6357  6357 I GKI_LINUX: GKI_exit_task 1 done
08-05 08:02:12.065  6357  6357 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 08:02:12.065  6357  6357 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 08:02:12.066  6357  6357 I art     : --- WEIRD: removing null entry 248
08-05 08:02:12.066  6357  6357 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-05 08:02:12.066  6357  6357 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 08:02:12.069  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:12.070  1961  2173 D LGBluetoothAPIService: Message: 2
08-05 08:02:12.070  1961  2173 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@14d11911 mBinding = false
08-05 08:02:12.070  1961  2173 D LGBluetoothAPIService: Sending unbind request.
08-05 08:02:12.071  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 08:02:12.072  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 08:02:12.072  6213  6213 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 08:02:12.075  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:12.077  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:12.079  1597  1597 D BluetoothAdapter: 757322079: getState() :  mService = null. Returning STATE_OFF
08-05 08:02:12.079  1597  1597 D BluetoothAdapter: 757322079: getState() :  mService = null. Returning STATE_OFF
,08-05 08:02:12.082  6357  6357 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 08:02:12.086  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 08:02:12.088  6357  6357 I art     : System.exit called, status: 0
08-05 08:02:12.088  6357  6357 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 08:02:12.095  6213  6213 D DockEventReceiver: finishStartingService: stopping service
,08-05 08:02:12.117   312   312 V AudioFlinger: 6357 died, releasing its sessions
08-05 08:02:12.117   312   312 V AudioFlinger:  pid 1870 @ 0
,08-05 08:02:12.117   312   312 V AudioFlinger:  pid 3395 @ 1
08-05 08:02:12.117   312   312 V AudioFlinger:  pid 3395 @ 2
08-05 08:02:12.118  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 08:02:12.134  1027  2026 I ActivityManager: Process com.android.bluetooth (pid 6357) has died
,08-05 08:02:12.134  1027  2026 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-05 08:02:12.138  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 08:02:12.154  6213  6213 D BluetoothPermissionRequest: onReceive
,08-05 08:02:12.157  6213  6213 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 08:02:12.157  6213  6213 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 08:02:12.162  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 08:02:12.239  1027  1995 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6937 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 08:02:12.332  6937  6937 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-05 08:02:12.332  6937  6937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 08:02:12.333  6937  6937 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 08:02:12.334  6937  6937 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 08:02:12.358  6937  6937 D BluetoothAdapterApp: Loading JNI Library
,08-05 08:02:12.409  6937  6937 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@be392fc Instance Count = 1
,08-05 08:02:12.415  6937  6937 D BluetoothAdapterApp: onCreate
08-05 08:02:12.442  6937  6937 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 08:02:12.443  6937  6937 D ProfileConfigQcom: Adding HeadsetService
08-05 08:02:12.443  6937  6937 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 08:02:12.445  6937  6937 D ProfileConfigQcom: Adding A2dpService
,08-05 08:02:12.445  6937  6937 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 08:02:12.446  6937  6937 D ProfileConfigQcom: Adding HidService
08-05 08:02:12.450  6937  6937 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 08:02:12.450  6937  6937 D ProfileConfigQcom: Adding HealthService
08-05 08:02:12.451  6937  6937 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 08:02:12.453  6937  6937 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 08:02:12.453  6937  6937 D ProfileConfigQcom: Adding PanService
08-05 08:02:12.457  6937  6937 D ProfileConfigQcom: [BTUI] GattService is supported
,08-05 08:02:12.461  6937  6937 D ProfileConfigQcom: Adding GattService
08-05 08:02:12.464  6937  6937 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 08:02:12.464  6937  6937 D ProfileConfigQcom: Adding BluetoothMapService
08-05 08:02:12.465  6937  6937 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 08:02:12.467  6937  6937 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 08:02:12.474  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-05 08:02:12.477  6937  6937 V LGMDMManagerInternal: Create singleton instance
,08-05 08:02:12.594  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 08:02:12.601  6937  6937 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:02:12.601  6937  6937 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:02:12.602  6937  6937 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:02:12.603  6937  6937 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:12.603  6937  6937 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 08:02:12.609  6299  6299 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-05 08:02:12.616  1027  1996 I ActivityManager: Killing 6117:com.lge.bnr/1000 (adj 15): empty #17
,08-05 08:02:12.706  1027  1371 W libprocessgroup: failed to open /acct/uid_1000/pid_6117/cgroup.procs: No such file or directory
,08-05 08:02:13.973  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 08:02:13.981  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:15.034  1027  1539 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-05 08:02:15.597  6810  6831 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-05 08:02:16.592  1027  1995 I ActivityManager: Killing 6251:com.lge.sync/1000 (adj 15): empty #17
,08-05 08:02:16.615  1027  1538 D WifiService: Client connection lost with reason: 4
,08-05 08:02:16.625  1027  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_6251/cgroup.procs: No such file or directory
,08-05 08:02:16.993  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:16.993  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3b9838 added. We now have 6 listener(s)
08-05 08:02:16.993  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 08:02:17.006  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:17.006  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b111011 added. We now have 7 listener(s)
08-05 08:02:17.006  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:17.007  5967  6060 I System.out: IsBluetoothEnabled
08-05 08:02:17.008  1027  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:17.008  1027  1996 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-05 08:02:17.008  1027  1089 D BluetoothManagerService: Message: 2
08-05 08:02:17.013  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:17.015  1027  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:17.015  1027  1905 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 08:02:17.033  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:02:17.034  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 08:02:17.034  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-05 08:02:17.035  1027  1089 D BluetoothManagerService: Message: 1
08-05 08:02:17.035  1027  1089 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-05 08:02:17.191  1027  1771 I art     : Explicit concurrent mark sweep GC freed 36493(1736KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.235ms total 124.332ms
,08-05 08:02:17.193  1027  1089 D BluetoothManagerService: Message: 20
08-05 08:02:17.194  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6fc9e70:true
08-05 08:02:17.195  6937  6937 D BluetoothAdapterState: make
08-05 08:02:17.200  6937  6937 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 08:02:17.200  6937  6937 I bluedroid-qcom: init
08-05 08:02:17.201  6937  6937 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 08:02:17.201  6937  6937 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 08:02:17.201  6937  6937 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 08:02:17.201  6937  6937 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 08:02:17.201  6937  6937 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 08:02:17.203  6937  6937 I bluedroid-qcom: get_profile_interface socket
08-05 08:02:17.203  6937  6937 I bluedroid-qcom: get_profile_interface map_client
,08-05 08:02:17.197  6972  6972 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:17.209  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 08:02:17.209  1027  1089 D BluetoothManagerService: Message: 40
08-05 08:02:17.209  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 08:02:17.209  6937  6952 I bluedroid-qcom: config_hci_snoop_log
08-05 08:02:17.197  6972  6972 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:17.214  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 08:02:17.214  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 08:02:17.218  6972  6972 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 08:02:17.218  6972  6972 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 08:02:17.218  6972  6972 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-05 08:02:17.223  6937  6969 I BluetoothAdapterState: Entering OffState
08-05 08:02:17.223  6937  6969 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 08:02:17.223  6937  6969 D BluetoothAdapterProperties: Setting state to 11
08-05 08:02:17.223  6937  6969 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 08:02:17.223  6972  6972 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 08:02:17.225  6937  6973 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 08:02:17.227  6937  6973 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 08:02:17.230  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:02:17.230  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 08:02:17.230  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-05 08:02:17.236  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:17.237  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 08:02:17.241  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:17.242  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-05 08:02:17.246  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 08:02:17.246  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 08:02:17.247  6972  6972 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 08:02:17.247  6972  6972 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 08:02:17.250  6937  6937 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 08:02:17.251  6937  6937 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:17.251  6937  6937 V BluetoothPbapReceiver: ***********state = 11
08-05 08:02:17.254  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:02:17.265  6213  6213 D BluetoothPermissionRequest: onReceive
08-05 08:02:17.268  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 08:02:17.273  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:17.275  6937  6937 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:02:17.275  6937  6937 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:02:17.275  6937  6937 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:02:17.275  6937  6937 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:17.275  6937  6937 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 08:02:17.278  6937  6973 D BluetoothAdapterProperties: Name is: G3
08-05 08:02:17.280  6937  6969 I LGBluetoothServiceJni: classInitNative: succeeds
,08-05 08:02:17.291  6937  6969 D BluetoothBondStateMachine: make
08-05 08:02:17.300  6937  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.301  6937  6969 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 08:02:17.301  6937  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
,08-05 08:02:17.301  6937  6969 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-05 08:02:17.302  6937  6969 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 08:02:17.303  6937  6979 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 08:02:17.308  6937  6969 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 08:02:17.315  6937  6937 D HeadsetService: Received start request. Starting profile...
08-05 08:02:17.316  6937  6937 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 08:02:17.316  6937  6937 D LGBluetoothHfpAdapter: Version 1.6
,08-05 08:02:17.319  6937  6937 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 08:02:17.320  6937  6937 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 08:02:17.321  6937  6937 D HeadsetStateMachine: make
08-05 08:02:17.324  6937  6969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:17.347  6937  6969 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 08:02:17.360  6937  6937 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:17.360  6937  6937 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:17.367  6937  6937 D HeadsetStateMachine: max_hf_connections = 1
08-05 08:02:17.368  6937  6937 I bluedroid-qcom: get_profile_interface handsfree
08-05 08:02:17.368  6937  6969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:17.373  6937  6937 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 08:02:17.374   312  1377 V AudioPolicyService: registerClient() client 0xb57d6ba0, uid 1002
08-05 08:02:17.376   312   312 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 08:02:17.376   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-05 08:02:17.376   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 08:02:17.377  6937  6937 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 08:02:17.377   312  3959 V AudioFlinger: registerClient() client 0xb55817d8, pid 6937
08-05 08:02:17.378   312  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:17.378   312  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:17.378  6937  6953 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:17.378  6937  6953 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 08:02:17.378  3395  3410 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:17.378  3395  3410 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:17.378   312  1373 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:17.378   312  1373 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:17.378  1027  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:17.378  1027  1995 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:17.379  1027  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:17.379  1027  1995 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:17.379  6937  6952 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:17.379  3395  3411 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:17.379  3395  3411 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:17.379  6937  6952 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 08:02:17.379  1597  1616 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:17.379  1597  1616 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:17.379  1597  1616 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:17.379  1597  1616 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:17.379  6937  6937 V ToneGenerator: Create Track: 0xb4928080
08-05 08:02:17.379  1870  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 08:02:17.379  1870  1886 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 08:02:17.379  6937  6937 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 08:02:17.379  1870  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 08:02:17.379  6937  6937 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 08:02:17.379  1870  1886 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 08:02:17.379   312  1377 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,08-05 08:02:17.379   312  1377 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 08:02:17.379   312  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 08:02:17.379   312  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 08:02:17.380  6937  6969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:17.383   312   312 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 08:02:17.384   312  3959 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 08:02:17.384   312  3959 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 08:02:17.384   312  3959 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 08:02:17.384   312  3959 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 08:02:17.384  6937  6937 V AudioSystem: getLatency() output 2, latency 50
08-05 08:02:17.385  6937  6937 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 08:02:17.385  6937  6937 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 08:02:17.385   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 08:02:17.385   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 08:02:17.385   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 08:02:17.385   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 08:02:17.385   312  1378 V AudioFlinger: createTrack() lSessionId: 23
08-05 08:02:17.388  6937  6969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:17.389  6937  6937 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 08:02:17.390   312  1378 V AudioFlinger: acquiring 23 from 6937, for 6937
08-05 08:02:17.390   312  1378 V AudioFlinger:  added new entry for 23
08-05 08:02:17.390  6937  6937 V ToneGenerator: ToneGenerator INIT OK, time: 171666
08-05 08:02:17.390  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.391  6937  6985 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 08:02:17.391  6937  6985 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 08:02:17.391  6937  6985 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 08:02:17.392  6937  6985 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 08:02:17.392   312  3960 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6937
08-05 08:02:17.392   312  3960 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
,08-05 08:02:17.392   312  3960 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 08:02:17.392   312  3960 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 08:02:17.392   312  3960 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 08:02:17.392   312  3960 V voice   : voice_set_parameters: exit with code(0)
08-05 08:02:17.393   312  3960 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 08:02:17.393   312  3960 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 08:02:17.393   312  3960 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 08:02:17.393   312  3960 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 08:02:17.393   312  3960 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 08:02:17.393   312  3960 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 08:02:17.393  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.397  6937  6985 V ToneGenerator: ToneGenerator destructor
08-05 08:02:17.397  6937  6985 V ToneGenerator: stopTone
08-05 08:02:17.397  6937  6985 V ToneGenerator: Delete Track: 0xb4928080
,08-05 08:02:17.397  6937  6985 V AudioTrack: ~AudioTrack, releasing session id from 6937 on behalf of 6937
08-05 08:02:17.398   312  3959 V AudioFlinger: releasing 23 from 6937 for 6937
08-05 08:02:17.398   312  3959 V AudioFlinger:  decremented refcount to 0
08-05 08:02:17.398   312  3959 V AudioFlinger: purging stale effects
08-05 08:02:17.398   312  3959 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 08:02:17.398   312  3959 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 08:02:17.398   312  3959 V AudioFlinger: PlaybackThread::Track destructor
08-05 08:02:17.398   312  3959 V AudioFlinger: removeClient_l() pid 6937, calling pid 312
08-05 08:02:17.398   312  1251 V AudioPolicyService: AudioCommandThread() waking up
08-05 08:02:17.398   312  1251 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 08:02:17.398   312  1251 V AudioPolicyManager: releaseOutput() 2
08-05 08:02:17.398   312  1251 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 08:02:17.398  6937  6937 D A2dpService: Received start request. Starting profile...
08-05 08:02:17.399  6937  6969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 08:02:17.400  6937  6937 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 08:02:17.402  6937  6937 V Avrcp   : make
08-05 08:02:17.403  6937  6937 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 08:02:17.403  6937  6937 I bluedroid-qcom: get_profile_interface avrcp
08-05 08:02:17.419  6937  6937 V AudioManager: registerRemoteController: size of Media player list: 0
,08-05 08:02:17.421  6937  6969 V LGMDMManager: Create singleton instance,
08-05 08:02:17.424  6937  6937 E AudioManager: No RCC entry present to update
08-05 08:02:17.424  6937  6937 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 08:02:17.429  6937  6969 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 08:02:17.430  6937  6937 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 08:02:17.432  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 08:02:17.432  6937  6937 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-05 08:02:17.439  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 08:02:17.602  1027  1996 V SIM_STK : Menu title from STK is T-Mobile
08-05 08:02:17.603  1027  1996 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:02:17.769  1027  2036 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 08:02:17.783  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-05 08:02:17.790  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 08:02:17.791  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 08:02:17.791  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 08:02:17.791  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 08:02:17.792  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 08:02:17.792  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 08:02:17.792  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 08:02:17.792  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 08:02:17.792  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 08:02:17.792  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 08:02:17.793  6937  6937 I BluetoothA2dpServiceJni: classInitNative
08-05 08:02:17.793  6937  6937 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 08:02:17.793  6937  6937 D A2dpStateMachine: make
08-05 08:02:17.796  6937  6937 I bluedroid-qcom: get_profile_interface a2dp
,08-05 08:02:17.797  6937  7002 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 08:02:17.800  6937  6937 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 08:02:17.800  6937  6937 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 08:02:17.801  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.802  6937  6937 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 08:02:17.803  6937  7001 D A2dpStateMachine: Enter Disconnected: -2
08-05 08:02:17.805  6937  6937 D HidService: Received start request. Starting profile...
08-05 08:02:17.805  6937  6937 I bluedroid-qcom: get_profile_interface hidhost
08-05 08:02:17.805  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.805  6937  6937 D HeadsetStateMachine: Proxy object connected
08-05 08:02:17.806  6937  6937 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 08:02:17.806  6937  6937 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 08:02:17.808  6937  6937 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 08:02:17.810  6937  6937 D HealthService: Received start request. Starting profile...
,08-05 08:02:17.812  6937  6937 I bluedroid-qcom: get_profile_interface health
08-05 08:02:17.813  6937  6937 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 08:02:17.813  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.814  6937  6937 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 08:02:17.816  6937  6937 D PanService: Received start request. Starting profile...
08-05 08:02:17.817  6937  6937 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 08:02:17.817  6937  6937 I bluedroid-qcom: get_profile_interface pan
08-05 08:02:17.827  6937  6937 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-05 08:02:17.827  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.831  6937  6937 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 08:02:17.845  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:17.847  6937  6937 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 08:02:17.849  6937  6937 D BtGatt.GattService: Received start request. Starting profile...
08-05 08:02:17.849  6937  6937 D BtGatt.GattService: start()
08-05 08:02:17.850  6937  6937 I bluedroid-qcom: get_profile_interface gatt
08-05 08:02:17.850  6937  6937 D BtGatt.AdvertiseManager: advertise manager created
08-05 08:02:17.856  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.857  6937  6985 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 08:02:17.858  6937  6985 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 08:02:17.858  6937  6985 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 08:02:17.860  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.860  6937  6937 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 08:02:17.861  6937  6937 V BluetoothMapService: BluetoothMapBinder()
,08-05 08:02:17.862  6937  6937 D BluetoothMapService: Received start request. Starting profile...
08-05 08:02:17.862  6937  6937 D BluetoothMapService: start()
08-05 08:02:17.866  6937  6937 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 08:02:17.866  6937  6937 D BluetoothMapEmailAppObserver: createReceiver()
08-05 08:02:17.867  6937  6937 D BluetoothMapEmailAppObserver: initObservers()
08-05 08:02:17.867  6937  6937 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-05 08:02:17.877  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:17.881  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:17.883  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:17.886  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:17.887  6937  6937 V PanService: [BTUI] SIM Extra State :ABSENT
,08-05 08:02:17.890  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 08:02:17.893  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 08:02:17.893  6937  6937 V BluetoothMapService: Handler(): got msg=1
08-05 08:02:17.894  6937  6969 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 08:02:17.895  6937  6969 I bluedroid-qcom: enable
08-05 08:02:17.895  6937  7009 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 08:02:17.895  6937  6969 I bt_hci_bdroid: init
08-05 08:02:17.896  6937  7009 I bt-btu  : btu_task pending for preload complete event
08-05 08:02:17.897  6937  6969 I bt_vendor: bt-vendor : init
08-05 08:02:17.897  6937  6969 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 08:02:17.897  6937  6969 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 08:02:17.897  6937  6969 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 08:02:17.897  6937  6969 D bt_userial_mct: userial_init
08-05 08:02:17.897  6937  6969 D bt_hci_bdroid: set_power 1
08-05 08:02:17.897  6937  6969 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 08:02:17.897  6937  6969 I bt_vendor: Starting hciattach daemon
08-05 08:02:17.897  6937  6969 I bt_vendor: try to set true
08-05 08:02:17.887  7012  7012 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 08:02:17.897  7012  7012 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:17.931  7013  7013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 08:02:18.009  7019  7019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 08:02:18.023  7020  7020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 08:02:18.049  7022  7022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 08:02:18.062  7023  7023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-05 08:02:18.085  7024  7024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 08:02:18.099  7025  7025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-05 08:02:18.125  7027  7027 I libmdmdetect: ESOC framework not supported
08-05 08:02:18.126  7027  7027 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 08:02:18.136  7027  7027 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 08:02:18.136  7027  7027 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 08:02:18.136  7027  7027 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 08:02:18.136  7027  7027 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 08:02:18.136  7027  7027 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 08:02:18.136  7027  7027 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 08:02:18.136  7027  7027 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 08:02:18.171  7027  7028 E QC-QMI  : qmi_client [7027] 15: failed to locate client data
,08-05 08:02:18.173   448   448 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 08:02:18.173   448   448 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-05 08:02:18.197  7029  7029 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 08:02:18.212  7030  7030 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 08:02:18.250  6937  6969 I bt_vendor: bluetooth satus is on
,08-05 08:02:18.250  6937  6969 D bt_hci_bdroid: preload
,08-05 08:02:18.250  6937  7011 D bt_userial_mct: userial_open(port:0)
08-05 08:02:18.250  6937  7011 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 08:02:18.254  6937  7011 I bt_vendor: Done intiailizing UART
08-05 08:02:18.256  6937  7011 I bt_vendor: Done intiailizing UART
08-05 08:02:18.256  6937  7011 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 08:02:18.257  6937  7011 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 08:02:18.257  6937  7009 I bt-btu  : btu_task received preload complete event
08-05 08:02:18.258  6937  7032 D bt_userial_mct: Entering userial_read_thread()
08-05 08:02:18.264  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 08:02:18.264  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 08:02:18.266  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 08:02:18.271  6937  7009 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 08:02:18.323  6937  7009 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 08:02:18.323  6937  7009 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b0061 
08-05 08:02:18.323  6937  7009 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b0061 
,08-05 08:02:18.337  6937  6973 E bt-btif : Calling BTA_HhEnable
08-05 08:02:18.337  6937  6973 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 08:02:18.338  6937  6973 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 08:02:18.339  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-05 08:02:18.339  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
,08-05 08:02:18.340  6937  6973 D BluetoothAdapterProperties: Name is: G3
08-05 08:02:18.340  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 08:02:18.340  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 08:02:18.340  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 08:02:18.341  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 08:02:18.341  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 08:02:18.341  6937  6973 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:02:18.341  6937  6973 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:02:18.341  6937  6973 D bt_hci_bdroid: postload
08-05 08:02:18.342  6937  7011 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 08:02:18.342  6937  6973 D bte_conf: Device ID record 1 : primary
08-05 08:02:18.342  6937  6973 D bte_conf:   vendorId            = 00c4
08-05 08:02:18.342  6937  6973 D bte_conf:   vendorIdSource      = 0001
,08-05 08:02:18.342  6937  6973 D bte_conf:   product             = 13a1
08-05 08:02:18.342  6937  6973 D bte_conf:   version             = 1000
08-05 08:02:18.342  6937  6973 D bte_conf:   clientExecutableURL = 
08-05 08:02:18.342  6937  6973 D bte_conf:   serviceDescription  = 
08-05 08:02:18.342  6937  6973 D bte_conf:   documentationURL    = 
08-05 08:02:18.343  6937  6973 D bte_conf: bte_load_did_conf no section named DID2.
08-05 08:02:18.348  6937  6969 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 08:02:18.348  6937  6969 D BluetoothAdapterProperties: ScanMode =  20
08-05 08:02:18.349  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:18.350  6937  6969 D BluetoothAdapterProperties: State =  11
08-05 08:02:18.351  6937  6969 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 08:02:18.351  6937  6969 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 08:02:18.352  6937  6969 D BluetoothAdapterProperties: Setting state to 12
08-05 08:02:18.352  6937  6969 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 08:02:18.337  7034  7034 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:18.337  7034  7034 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 08:02:18.358  6937  7032 E bt_mct  : hci lib postload completed
08-05 08:02:18.359  1027  1089 D BluetoothManagerService: Message: 60
08-05 08:02:18.359  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 08:02:18.359  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-05 08:02:18.359  6937  7009 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 08:02:18.361  6937  6969 I BluetoothAdapterState: Entering On State
08-05 08:02:18.362  6937  6973 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 08:02:18.367  6937  6969 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 08:02:18.367  6937  6969 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 08:02:18.367  6937  6969 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-05 08:02:18.372  6937  6969 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 08:02:18.373  6937  7009 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:18.373  6937  7009 W bt-smp  : Plain text(LSB ~ MSB) = 79 7c 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:18.373  6937  7009 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 0b 9f bd c0 02 f1 a4 59 b3 07 6f e7 14 cd ea 
08-05 08:02:18.373  6937  7009 W bt-btm  : Stopping oneshot timer
08-05 08:02:18.374  6213  6229 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 08:02:18.383  1870  4388 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 08:02:18.391  6937  6973 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:02:18.391  6937  6973 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 08:02:18.391  6937  6973 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 08:02:18.392  1870  1870 D BluetoothHeadset: Proxy object connected
08-05 08:02:18.393  1870  2639 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:02:18.399  1870  1870 D BluetoothHeadset: Proxy object connected
,08-05 08:02:18.403  6213  6228 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 08:02:18.404  6937  7009 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-05 08:02:18.404  6937  7009 W bt-smp  : Plain text(LSB ~ MSB) = e9 23 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:18.404  6937  7009 W bt-smp  : Encrypted text(LSB ~ MSB) = e7 75 62 04 40 f1 18 23 2a 06 a5 c4 1c cd 43 af 
08-05 08:02:18.404  6937  7009 W bt-btm  : Stopping oneshot timer
,08-05 08:02:18.406  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 08:02:18.406  1027  1027 D BluetoothA2dp: Proxy object connected
08-05 08:02:18.412  6937  6969 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 08:02:18.415  6213  6664 D BluetoothPan: onBluetoothStateChange on: true
08-05 08:02:18.415  6213  6664 D BluetoothPan: onBluetoothStateChange call bindService
08-05 08:02:18.416  6213  6213 D BluetoothA2dp: Proxy object connected
08-05 08:02:18.416  6213  6213 D A2dpProfile: Bluetooth service connected
,08-05 08:02:18.421  6213  6213 D BluetoothInputDevice: Proxy object connected
08-05 08:02:18.421  6213  6213 D HidProfile: Bluetooth service connected
08-05 08:02:18.423  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:02:18.425  1870  1885 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:02:18.425  6937  7009 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:18.425  6937  7009 W bt-smp  : Plain text(LSB ~ MSB) = 52 00 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-05 08:02:18.425  6937  7009 W bt-smp  : Encrypted text(LSB ~ MSB) = 4a b4 9c 81 41 28 68 ed 07 a1 f1 9a f4 1f 9b ab 
08-05 08:02:18.425  6937  7009 W bt-btm  : Stopping oneshot timer
08-05 08:02:18.424  1027  1027 D BluetoothHeadset: Proxy object connected
08-05 08:02:18.427  6213  6213 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 08:02:18.427  6213  6213 D PanProfile: Bluetooth service connected
08-05 08:02:18.428  1870  1870 D BluetoothHeadset: Proxy object connected
08-05 08:02:18.429  6213  6229 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 08:02:18.433  6213  6228 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 08:02:18.434  6213  6213 D BluetoothHeadset: Proxy object connected
08-05 08:02:18.434  6213  6213 D HeadsetProfile: Bluetooth service connected
08-05 08:02:18.435  7050  7050 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 08:02:18.436  6213  6664 D BluetoothMap: onBluetoothStateChange: up=true
08-05 08:02:18.438  1027  1089 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 08:02:18.438  6213  6213 D BluetoothMap: Proxy object connected
08-05 08:02:18.439  6213  6213 D MapProfile: Bluetooth service connected
08-05 08:02:18.439  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 08:02:18.439  6213  6213 D BluetoothMap: getConnectedDevices()
08-05 08:02:18.440  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 08:02:18.440  1027  1089 D BluetoothManagerService: Message: 40
08-05 08:02:18.440  1961  1961 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.440  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 08:02:18.441  1961  2173 D LGBluetoothAPIService: Message: 1
08-05 08:02:18.441  1961  2173 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 08:02:18.441  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-05 08:02:18.445  6937  7009 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:18.445  6937  7009 W bt-smp  : Plain text(LSB ~ MSB) = 13 77 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:18.445  6937  7009 W bt-smp  : Encrypted text(LSB ~ MSB) = 93 48 0b 30 ec ce 91 5b 3a 51 3f 2f 5f 7f 0d 27 
08-05 08:02:18.445  6937  7009 W bt-btm  : Stopping oneshot timer
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:18.446  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:18.449  6937  6937 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.450  6937  6937 D BluetoothMapService: STATE_ON
08-05 08:02:18.451  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:18.451  1961  2173 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-05 08:02:18.452  6937  7048 V BluetoothMapService: getConnectedDevices()
,08-05 08:02:18.457  6937  7009 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 08:02:18.457  6937  7009 W bt-smp  : Plain text(LSB ~ MSB) = 0d 15 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 08:02:18.457  6937  7009 W bt-smp  : Encrypted text(LSB ~ MSB) = 0f e4 21 38 b0 5d 47 b2 6b 2b c4 aa 33 fd 48 46 
08-05 08:02:18.457  6937  7009 W bt-btm  : Stopping oneshot timer
08-05 08:02:18.459  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-05 08:02:18.461  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 08:02:18.467  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:18.467  6937  6937 V BluetoothPbapService: Pbap Service onCreate
08-05 08:02:18.467  6937  6937 V BluetoothPbapService: Starting PBAP service
08-05 08:02:18.468  6937  6937 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 08:02:18.469  6937  6937 V BluetoothMapService: Handler(): got msg=1
08-05 08:02:18.469  6937  6937 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 08:02:18.469  6937  6937 V BluetoothPbapService: Pbap Service onBind
08-05 08:02:18.470  6937  7053 D BluetoothMapMasInstance: MAS initSocket()
,08-05 08:02:18.471  6937  6937 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.471  6937  6937 V BluetoothPbapService: state: 12
08-05 08:02:18.471  6213  6213 D DockEventReceiver: finishStartingService: stopping service
,08-05 08:02:18.472  6213  6213 D BluetoothPbap: Proxy object connected
08-05 08:02:18.472  6213  6213 D PbapServerProfile: Bluetooth service connected
08-05 08:02:18.473  6937  6937 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 08:02:18.473  6937  6937 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 08:02:18.473  6937  7053 D BluetoothMapMasInstance:   masId = 00
08-05 08:02:18.473  6937  7053 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 08:02:18.473  6937  7053 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 08:02:18.473  6937  7053 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 08:02:18.476  1027  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:18.476  6937  6937 V BluetoothPbapService: Handler(): got msg=1
08-05 08:02:18.476  1961  1961 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 08:02:18.476  1961  2173 D LGBluetoothAPIService: Message: 100
08-05 08:02:18.476  1961  2173 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 08:02:18.476  6937  6937 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 08:02:18.477  6937  6937 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 08:02:18.477  6937  6937 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.477  6937  6937 V BluetoothPbapReceiver: ***********state = 12
08-05 08:02:18.478  6937  7055 V BluetoothPbapService: Pbap Service initSocket
,08-05 08:02:18.478  1027  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:18.478  6937  7053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:18.479  6937  7055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:18.481  2233  2233 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 08:02:18.481  2233  2233 D c       : Getting all permits...
08-05 08:02:18.481  2233  2233 D a       : Opening database...
08-05 08:02:18.482  6937  7055 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 08:02:18.483  6937  7055 V BluetoothPbapService: Succeed to create listening socket 
08-05 08:02:18.483  6937  7055 V BluetoothPbapService: Accepting socket connection...
08-05 08:02:18.483  6937  6973 D BluetoothAdapterProperties: Scan Mode:21
08-05 08:02:18.483  6937  6973 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 08:02:18.485  2233  2233 D a       : Opening database auth.proximity.permit_store...
08-05 08:02:18.486  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:18.486  6937  7053 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 08:02:18.486  6937  7053 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 08:02:18.486  6937  7053 D BluetoothMapMasInstance: Accepting socket connection...
08-05 08:02:18.486  2233  2233 D a       : Closing database...
,08-05 08:02:18.497  6213  6213 D BluetoothPermissionRequest: onReceive
08-05 08:02:18.498  6213  6213 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-05 08:02:18.500  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 08:02:18.502  6937  6937 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 08:02:18.503  6937  6937 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 08:02:18.509  6937  6937 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-05 08:02:18.529  6937  6937 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 08:02:18.529  6937  6937 V BtOppService: onCreate
,08-05 08:02:18.533  6937  6937 V BluetoothOppNotification: send message
08-05 08:02:18.536  6937  6937 V BtOppService: Starting RfcommListener
08-05 08:02:18.539  6937  6937 D BluetoothOppPreference: Dumping Names:  
08-05 08:02:18.539  6937  6937 D BluetoothOppPreference: {}
08-05 08:02:18.539  6937  6937 D BluetoothOppPreference: Dumping Channels:  
08-05 08:02:18.539  6937  6937 D BluetoothOppPreference: {}
08-05 08:02:18.540  6937  6937 V BtOppService: onStartCommand
08-05 08:02:18.541  6937  7061 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-05 08:02:18.543  6937  7061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 08:02:18.544  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.544  6937  7058 V BtOppService: Deleted complete outbound shares, number =  0
08-05 08:02:18.544  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-05 08:02:18.545  6937  7061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3233fb89 on behalf of 
08-05 08:02:18.547  6937  7061 V BluetoothOppNotification: update too frequent, put in queue
08-05 08:02:18.547  6937  7058 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 08:02:18.547  6937  7058 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 08:02:18.548  6937  6937 V BluetoothOppNotification: new notify threadi!
08-05 08:02:18.548  6937  7061 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 08:02:18.549  6937  7061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 08:02:18.549  6937  7058 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bbc078e on behalf of 
08-05 08:02:18.549  6937  6937 V BluetoothOppNotification: send delay message
08-05 08:02:18.550  6937  7061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f30abaf on behalf of 
08-05 08:02:18.550  6937  6937 V BtOppService: start RfcommListener
08-05 08:02:18.550  6937  7062 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 08:02:18.551  6937  7061 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 08:02:18.552  6937  7062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24629bbc on behalf of 
08-05 08:02:18.553  6937  7062 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 08:02:18.553  6937  6937 V BtOppService: RfcommListener started
08-05 08:02:18.553  6937  6937 V BtOppService: ContentObserver received notification
08-05 08:02:18.554  6937  7063 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 08:02:18.554  6937  6937 V BtOppService: ContentObserver received notification
08-05 08:02:18.555  1027  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:18.555  6937  7062 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-05 08:02:18.556  6937  7063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:18.558  6937  7063 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-05 08:02:18.558  6937  7063 V BtOppRfcommListener: Started RFCOMM listener....
08-05 08:02:18.559  6937  7063 I BtOppRfcommListener: Accept thread started.
08-05 08:02:18.559  6937  7063 V BtOppRfcommListener: Accepting connection...
08-05 08:02:18.559  6937  7064 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 08:02:18.559  6937  7064 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 08:02:18.560  6937  7062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38d7c745 on behalf of 
08-05 08:02:18.561  6937  7064 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16f50e9a on behalf of 
08-05 08:02:18.561  6937  7062 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 08:02:18.561  6937  7064 V BluetoothOppNotification: update too frequent, put in queue
08-05 08:02:18.563  6937  7064 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 08:02:18.563  6937  7062 V BluetoothOppNotification: outbound notification was removed.
08-05 08:02:18.563  6937  7062 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 08:02:18.567  6937  7062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15e653cb on behalf of 
,08-05 08:02:18.568  6937  7062 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 08:02:18.569  6937  7062 V BluetoothOppNotification: inbound notification was removed.
08-05 08:02:18.569  6937  7062 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 08:02:18.571  6937  7062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a9bb7a8 on behalf of 
08-05 08:02:18.575  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:18.575  6937  6937 V BluetoothFtpService: Ftp Service onCreate
08-05 08:02:18.575  6937  6937 I BluetoothFtpService: Ftp Service onCreate
08-05 08:02:18.575  6937  6937 V BluetoothFtpService: Ftp Service onStartCommand
08-05 08:02:18.575  6937  6937 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.576  6937  6937 V BluetoothFtpService: Starting Listening on sockets
,08-05 08:02:18.576  6937  6937 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 08:02:18.576  6937  6937 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 08:02:18.576  6937  6937 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 08:02:18.576  6937  6937 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.576  6937  6937 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 08:02:18.576  6937  6937 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 08:02:18.578  6937  6937 V BluetoothFtpService: Handler(): got msg=1
08-05 08:02:18.579  6937  6937 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 08:02:18.579  6937  6937 V BluetoothFtpService: Ftp Service initSocket
,08-05 08:02:18.584  1027  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 08:02:18.585  6937  6937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:02:18.586  6937  6937 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-05 08:02:18.586  6937  6937 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 08:02:18.588  6937  7065 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-05 08:02:18.605  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a094594
08-05 08:02:18.606  6937  6937 V BluetoothSapService: Sap Service onCreate
,08-05 08:02:18.609  6937  6937 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:02:18.609  6937  6937 V BluetoothSapService: state: 12
08-05 08:02:18.609  6937  6937 V BluetoothSapService: Starting SAP server process
08-05 08:02:18.612  6937  6937 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 08:02:18.597  7066  7066 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:18.597  7066  7066 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:18.616  6937  7067 V BluetoothSapService: Sap Service initRfcommSocket
08-05 08:02:18.617  1027  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:18.618  6937  7067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:02:18.620  6937  7067 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 08:02:18.620  6937  7067 V BluetoothSapService: Succeed to create listening socket 
,08-05 08:02:18.621  6937  7067 V BluetoothSapService: Accepting socket connection...
08-05 08:02:18.628  7066  7066 V BT_SAP  : Event pipe created
08-05 08:02:18.628  7066  7066 V BT_SAP  : create_server_socket qcom.sap.server
08-05 08:02:18.628  7066  7066 V BT_SAP  : created socket fd 6
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:19.072  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:02:19.080  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:19.082  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:19.082  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74f3576 added. We now have 8 listener(s)
08-05 08:02:19.082  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:19.086  1027  2026 D WifiServiceImplEx: setWifiEnabled: false pid=5967, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 08:02:19.086  1027  2026 D WifiService: setWifiEnabled: false pid=5967, uid=10118
08-05 08:02:19.086  1027  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 08:02:19.092  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:02:19.095  1027  1925 D WifiServiceImplEx: setWifiEnabled: true pid=5967, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 08:02:19.096  1027  1925 D WifiService: setWifiEnabled: true pid=5967, uid=10118
08-05 08:02:19.096  1027  1925 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:02:19.121  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 08:02:19.122  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 08:02:19.122  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-05 08:02:19.123  1027  1533 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 08:02:19.123  1027  1533 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 08:02:19.125  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 08:02:19.125  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 08:02:19.125  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 08:02:19.125  1027  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 08:02:19.125  1027  1533 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 08:02:19.125  1027  1533 E WifiHW  : unknown target_country: EU , set to default
08-05 08:02:19.125  1027  1533 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 08:02:19.125  1027  1533 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 08:02:19.125  1027  1533 I WifiUtil: gEnableBmps=1
08-05 08:02:19.551  6937  6937 V BluetoothOppNotification: new notify threadi!
,08-05 08:02:19.554  6937  6937 V BluetoothOppNotification: send delay message
08-05 08:02:19.556  6937  7086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 08:02:19.558  6937  7086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@291499fd on behalf of 
08-05 08:02:19.558  6937  7086 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 08:02:19.560  6937  7086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 08:02:19.560  6937  7086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b5ed6f2 on behalf of 
08-05 08:02:19.561  6937  7086 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 08:02:19.563  6937  7086 V BluetoothOppNotification: outbound notification was removed.
08-05 08:02:19.563  6937  7086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 08:02:19.565  6937  7086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e0b7143 on behalf of 
08-05 08:02:19.565  6937  7086 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-05 08:02:19.569  6937  7086 V BluetoothOppNotification: inbound notification was removed.
08-05 08:02:19.569  6937  7086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 08:02:19.570  6937  7086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@433d3c0 on behalf of 
08-05 08:02:19.715   306   888 D SoftapController: Softap fwReload - Ok
,08-05 08:02:19.754  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 08:02:19.757  1027  1533 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (625ms)
08-05 08:02:19.775   306   888 D CommandListener: Setting iface cfg
08-05 08:02:19.775   306   888 D CommandListener: Trying to bring down wlan0
,08-05 08:02:19.804   306  7088 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-05 08:02:19.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:19.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:19.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:19.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 08:02:19.832   306   888 D CommandListener: Clearing all IP addresses on wlan0
08-05 08:02:19.835  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 08:02:19.837  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:19.838  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 08:02:19.838  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:19.838  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:19.838  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:19.838  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 08:02:19.839  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 08:02:19.839  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 08:02:19.842  1027  1533 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 08:02:19.837  7103  7103 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:19.837  7103  7103 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 08:02:19.872  7103  7103 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 08:02:19.904  7103  7103 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 08:02:19.904  7103  7103 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-05 08:02:19.908  1027  1089 D Tethering: InitialState.processMessage what=4
08-05 08:02:19.914  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 08:02:19.914  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:19.914  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:19.914  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:19.914  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 08:02:19.915  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 08:02:19.915  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:19.915  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 08:02:19.915  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:19.915  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:19.915  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:19.915  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 08:02:19.944  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:02:19.944  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:02:19.944  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 08:02:19.945  1027  1533 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 08:02:19.945  1027  1533 D WifiMonitor: connecting to supplicant
08-05 08:02:19.947  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:19.947  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 08:02:19.953  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:19.956  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 08:02:19.968  7103  7103 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 08:02:19.978  7103  7103 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-05 08:02:19.983  7103  7103 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-05 08:02:19.985  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-05 08:02:19.986  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 08:02:19.986  1027  7111 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 08:02:19.986  1027  7111 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 08:02:19.986  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 08:02:19.987  1027  1533 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 08:02:19.987  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:19.988  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:19.988  1027  1533 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:19.989  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:19.989  1027  1533 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 08:02:19.989  1027  1533 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 08:02:19.990  1027  1533 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 08:02:19.991  1027  1533 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 08:02:19.991  1027  1533 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-05 08:02:20.015  1027  1996 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7112 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 08:02:20.021  1027  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 08:02:20.021  1027  1533 E WifiStateMachine: useWiFiOffloading() : false
08-05 08:02:20.021  1027  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 08:02:20.021  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.021  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.022  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.022  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.022  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 08:02:20.022  1027  1533 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 08:02:20.023  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:20.023  1027  1533 D WifiNative-wlan0: SET update_config 1: returned true
08-05 08:02:20.023  1027  1533 D WifiConfigStore: Loading config and enabling all networks 
08-05 08:02:20.023  1027  1533 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 08:02:20.024  1027  1533 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 08:02:20.026  1961  1961 D WfdService: Waiting for WifiP2p enabling
08-05 08:02:20.027  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 08:02:20.027  1027  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-05 08:02:20.030  1027  1533 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 08:02:20.030  6319  7110 V FormManager: Network unavailable.
08-05 08:02:20.035  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 08:02:20.035  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:20.035  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:02:20.035  7103  7103 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 08:02:20.035  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 08:02:20.035  6319  7109 W FormManager: Network not available. Please check & try again.
08-05 08:02:20.035  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 08:02:20.035  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 08:02:20.035  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 08:02:20.037  6319  7110 V FormManager: Network unavailable.
08-05 08:02:20.037  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:20.040  1027  1533 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 08:02:20.041  1027  1533 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 08:02:20.042  1027  1533 D WifiStateMachine: enableVerboseLogging : level 2
08-05 08:02:20.042  1027  1533 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 08:02:20.042  1027  1533 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 08:02:20.042  1027  1533 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 08:02:20.043  1027  1533 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 08:02:20.043  1027  1533 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 08:02:20.043  1027  1533 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 08:02:20.043  1027  1533 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 08:02:20.043  1027  1533 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 08:02:20.043  1027  1533 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 08:02:20.044  1027  1533 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 08:02:20.044  1027  1533 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 08:02:20.044  1027  1533 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 08:02:20.044  1027  1533 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 08:02:20.045  1027  1533 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 08:02:20.045  1027  1533 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 08:02:20.045  1027  1533 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 08:02:20.047  1027  1533 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 08:02:20.047  1027  1533 D WifiNative-HAL: Setting external_sim to 1
08-05 08:02:20.047  1027  1533 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 08:02:20.047  1027  1533 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 08:02:20.048  1027  1533 I WifiNative-HAL: startHal
08-05 08:02:20.048  1027  1533 D wifi    : setting scan oui 0x9c3a4680
08-05 08:02:20.048  1027  1533 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 08:02:20.048  1961  1961 D WfdsService: Supplicant Connection state is changed : true
08-05 08:02:20.048  1027  1533 I WifiNative-HAL: startHal
08-05 08:02:20.048  1027  1533 D wifi    : setting scan oui 0x9c3a4680
08-05 08:02:20.048  1961  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 08:02:20.048  1961  2319 D WfdsService: Set the WFDS Monitor: true
08-05 08:02:20.048  1961  2319 D WfdsMonitor: WfdsMonitorThread create
08-05 08:02:20.048  1027  1533 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 08:02:20.049  1961  2319 D WfdsMonitor: WFDS Monitor is created and started
08-05 08:02:20.049  1961  2319 D WfdsService: WiFi: Supplicant connection re-established
08-05 08:02:20.049  1027  1533 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 08:02:20.049  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 08:02:20.049  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 08:02:20.049  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 08:02:20.049  1961  7129 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 08:02:20.049  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 08:02:20.050  1961  7129 E CtrlSupplicant: Succeed to open control connection
08-05 08:02:20.050  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 08:02:20.050  1961  7129 E CtrlSupplicant: Succeed to open monitor connection
08-05 08:02:20.050  1961  7129 D WfdsMonitor: Supplicant connection established
08-05 08:02:20.050  1961  2319 D WfdsService: Connected to the supplicant for wfds
08-05 08:02:20.050  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 08:02:20.050  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
,08-05 08:02:20.050  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 08:02:20.050  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 08:02:20.050  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 08:02:20.050  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 08:02:20.051  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 08:02:20.051  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 08:02:20.051  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 08:02:20.051  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 08:02:20.051  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 08:02:20.051  7103  7103 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-05 08:02:20.051  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 08:02:20.051  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 08:02:20.052  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-05 08:02:20.052  1027  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 08:02:20.053  1027  1533 E WifiNative: : [174,315,617 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
,08-05 08:02:20.053  1027  1533 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 08:02:20.053  1027  1533 D WifiNative-wlan0: RECONNECT: returned true
08-05 08:02:20.053  1027  1533 D WifiNative-wlan0: doString: [STATUS]
08-05 08:02:20.054  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 08:02:20.054  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 08:02:20.055  1027  1533 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 08:02:20.055  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 08:02:20.055  1027  1533 D WifiNative-wlan0: SET ps 1: returned true
08-05 08:02:20.055  1027  1531 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.056  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 08:02:20.056  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-05 08:02:20.056  1027  1551 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.056  1027  1550 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.056  1027  1550 I WifiNative-HAL: startHal
08-05 08:02:20.056  1027  1550 D wifi    : getting scan capabilities on interface[1] = 0x9c3a4680
08-05 08:02:20.056  1027  1550 D wifi    : failed to get capabilities : -3
08-05 08:02:20.056  1027  1550 E WifiScanningService: could not get scan capabilities
08-05 08:02:20.056   306   888 D CommandListener: Setting iface cfg
08-05 08:02:20.057   306   888 D CommandListener: Trying to bring up p2p0
08-05 08:02:20.057  1027  1531 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 08:02:20.057  1027  1531 D LGWifiP2pService: P2pEnablingState
08-05 08:02:20.057  1027  1531 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.057  1027  1531 D LGWifiP2pService: P2p socket connection successful
08-05 08:02:20.057  1027  1533 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 08:02:20.057  1027  1531 D LGWifiP2pService: P2pEnabledState
,08-05 08:02:20.057  1027  1531 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 08:02:20.057  1027  1531 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 08:02:20.057  1027  1533 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 08:02:20.058  1027  1533 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 08:02:20.058  1027  1531 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 08:02:20.058  1027  1531 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 08:02:20.058  1027  1533 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 08:02:20.058  1027  1531 D WifiNative-p2p0: SET device_name G3: returned true
08-05 08:02:20.058  1027  1531 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 08:02:20.058  1027  1531 D LGWifiP2pService: before postfix = G3
08-05 08:02:20.058  1027  1531 D WifiServerServiceExt: postfix byte check : 2
08-05 08:02:20.058  1027  1531 D LGWifiP2pService: after postfix = G3
08-05 08:02:20.058  1027  1531 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 08:02:20.058  1027  1533 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 08:02:20.059  1027  1533 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 08:02:20.059  1961  1961 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 08:02:20.059  1961  1961 D WfdsService: WifiP2pState is changed : true
08-05 08:02:20.059  1961  2319 D WfdsService: Receive the WFDS_ENABLE Method
08-05 08:02:20.059  1961  2319 D WfdsService: Set the WFDS Monitor: true
08-05 08:02:20.059  1961  2319 D WfdsService: Connected to the supplicant for wfds
08-05 08:02:20.059  1961  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 08:02:20.059  1027  1533 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 08:02:20.059  1027  1533 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 08:02:20.059  7103  7103 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 08:02:20.059  7103  7103 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 08:02:20.059  1961  2319 D WfdsService: selectPreferredScanChannel [36]
08-05 08:02:20.060  1961  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 08:02:20.060  1027  1531 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 08:02:20.060  1027  1533 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 08:02:20.060  1027  1531 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 08:02:20.060  1027  1531 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 08:02:20.060  1027  1531 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 08:02:20.060  1027  1533 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 08:02:20.060  1961  1961 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 08:02:20.060  1027  1533 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 08:02:20.060  1027  1533 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 08:02:20.060  1961  1961 D WfdsService: isConnected: false
08-05 08:02:20.060  7103  7103 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 08:02:20.061  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=174324  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 08:02:20.061  1027  1531 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 08:02:20.061  1027  1531 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 08:02:20.061  1027  1531 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 08:02:20.061  1027  1531 D WifiNative-HAL: p2pGetDeviceAddress
08-05 08:02:20.061  1027  1531 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 08:02:20.062  1027  1531 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 08:02:20.062  1027  1531 D WifiNative-p2p,0: doBoolean: P2P_FLUSH
08-05 08:02:20.062  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=174325  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 08:02:20.062  1027  1531 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 08:02:20.062  1027  1531 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 08:02:20.062  1027  1531 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 08:02:20.062  1027  1533 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 08:02:20.062  1027  1531 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 08:02:20.062  1027  1531 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 08:02:20.062  1027  1533 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 08:02:20.062  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:20.063  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:20.063  1027  1531 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 08:02:20.063  1027  1533 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 08:02:20.063  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 08:02:20.064  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.064  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.064  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 08:02:20.065  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:20.066  1961  1961 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 08:02:20.066  1961  1961 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 08:02:20.066  1961  1961 D WfdsService: Update P2p Interface State: 3
08-05 08:02:20.077  1027  1531 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 08:02:20.077  1027  1531 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-05 08:02:20.077  1027  1531 D LGWifiP2pService: InactiveState
08-05 08:02:20.078  1027  1531 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.078  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.078  1027  1531 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 08:02:20.078  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 08:02:20.079  7103  7103 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.079  1961  7129 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 08:02:20.079  1027  7111 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 08:02:20.079  1027  7111 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.079  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.079  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.079  7103  7103 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 08:02:20.079  7103  7103 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  1961  7129 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.080  1027  7111 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.080  1027  7111 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  7103  7103 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  1961  7129 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.080  1027  7111 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.080  1027  7111 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.080  1027  1531 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 08:02:20.081  1027  1531 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.081  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.081  1027  1531 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.081  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 08:02:20.081  1027  1531 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.081  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.081  1027  1531 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.082  1027  1531 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.082  7103  7103 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHA,NGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.082  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.082  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 08:02:20.082  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.082  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.082  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 08:02:20.082  7103  7103 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 08:02:20.082  7103  7103 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.082  1961  7129 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.083  1027  7111 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.083  1027  7111 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.083  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.083  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.083  7103  7103 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.083  1961  7129 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.083  1027  7111 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 08:02:20.083  1027  7111 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.084  1961  2319 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 08:02:20.084  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.084  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 08:02:20.084  1027  1533 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 08:02:20.084  1027  1531 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.084  1027  1531 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.084  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.084  1027  1533 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 08:02:20.084  1027  1531 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.085  1027  1027 E WifiServerServiceExt: No p2p device connected
08-05 08:02:20.085  1027  1533 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 08:02:20.085  1027  1531 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.085  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:20.085  1027  1533 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 08:02:20.085  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 08:02:20.085  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 08:02:20.085  7103  7103 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:20.086  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 08:02:20.086  1027  ,7111 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:20.086  1027  7111 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:20.086  1027  7111 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 08:02:20.086  1027  1533 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 08:02:20.086  1027  1533 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 08:02:20.086  1027  1533 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 08:02:20.086  1027  1533 D WifiNative-wlan0: doBoolean: SCAN
08-05 08:02:20.086  1027  1533 D WifiNative-wlan0: SCAN: returned false
08-05 08:02:20.087  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=174350  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 08:02:20.087  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=174350  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 08:02:20.088  1027  1533 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:20.088  1027  1533 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:20.088  1027  1533 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:20.088  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:20.088  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:20.089  1027  1533 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:20.089  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.089  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.089  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 08:02:20.089  1027  1533 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 08:02:20.090  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:20.090  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:20.090  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 08:02:20.091  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:20.091  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 08:02:20.098  7112  7112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:20.100  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 08:02:20.104  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:20.117  7112  7112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 08:02:20.119  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 08:02:20.121  6319  7133 W FormManager: Network not available. Please check & try again.
08-05 08:02:20.123  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:20.123  6319  7134 V FormManager: Network unavailable.
08-05 08:02:20.126  6319  7134 V FormManager: Network unavailable.
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:02:20.133  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:02:20.134  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:02:20.134  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:20.135  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 08:02:20.137  5967  6060 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-05 08:02:20.138  5967  6060 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-05 08:02:20.138  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:20.139  5967  6060 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3efad618 Bundle[{}]
08-05 08:02:20.140  5967  6060 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 08:02:20.140  5967  6060 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 08:02:20.140  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:20.141  5967  6060 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-05 08:02:20.141  5967  6060 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 08:02:20.142  5967  6060 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 08:02:20.142  5967  6060 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 08:02:20.144  4270  7135 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 08:02:20.147  5967  6060 I System.out: Running OutgoingSocketThread
08-05 08:02:20.148  4270  7136 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 08:02:20.148  4270  7136 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 08:02:20.151  5967  7137 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 771)
08-05 08:02:20.154  5967  7137 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35562
08-05 08:02:20.155  5967  7137 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-05 08:02:20.167  1027  1371 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7138 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 08:02:20.178   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 9.981ms
08-05 08:02:20.195   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 16.249ms
,08-05 08:02:20.214   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.190ms
,08-05 08:02:20.230  7138  7138 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 08:02:20.230  7138  7138 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 08:02:20.238  7138  7138 V [BNRBootReceiver]: Boot Receiver Return
08-05 08:02:20.240  7138  7138 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 08:02:20.240  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:20.250  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:20.254  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:20.260  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:20.260  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:20.262  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:02:20.266  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 08:02:20.275  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:20.282  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:20.290  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:20.290  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 08:02:20.293  6282  6282 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 08:02:20.294  1027  1647 I ActivityManager: Killing 6574:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-05 08:02:20.337  1027  1942 W libprocessgroup: failed to open /acct/uid_10011/pid_6574/cgroup.procs: No such file or directory
,08-05 08:02:20.717  7103  7103 E wpa_supplicant: USIM:  scard_init function
08-05 08:02:20.718  7103  7103 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 08:02:20.730  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 08:02:20.730  1027  7111 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 08:02:20.730  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 08:02:20.730  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-05 08:02:20.730  1027  7111 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 08:02:20.730  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 08:02:20.730  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 08:02:20.731  1027  1533 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-05 08:02:20.732  1027  1533 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-05 08:02:20.732  1027  1533 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-05 08:02:20.733  1027  1533 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-05 08:02:20.733  1027  1533 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 08:02:20.759  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=175022  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 08:02:20.767  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:20.767  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:20.770  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:20.771  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.772  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.772  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 08:02:20.775  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=175038  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 08:02:20.778  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:20.778  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 08:02:20.783  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 08:02:20.793  6213  6213 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 08:02:20.798  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 08:02:20.809  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:20.818  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:20.826  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:20.827  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:20.827  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 08:02:20.856  7103  7103 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 08:02:20.865  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 08:02:20.866  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 08:02:20.866  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 08:02:20.866  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 08:02:20.866  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:20.866  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:20.871  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=175134  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 08:02:20.871  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=175134  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 08:02:20.872  1027  1533 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175135
08-05 08:02:20.872  1027  1533 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175135
08-05 08:02:20.873  1027  1533 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175136
,08-05 08:02:20.878  7103  7103 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 08:02:20.878  7103  7103 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 08:02:20.883  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 08:02:20.887  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:20.887  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-05 08:02:20.891  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 08:02:20.892  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 08:02:20.892  1027  7111 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 08:02:20.892  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 08:02:20.892  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 08:02:20.893  1027  7111 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 08:02:20.893  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:20.893  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:20.873  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175136
08-05 08:02:20.897  1027  1533 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175160
08-05 08:02:20.898  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=175161  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 08:02:20.903  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.903  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.903  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-05 08:02:20.909  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:20.909  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:20.911  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:20.921  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.921  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.921  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 08:02:20.922  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=175185  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 08:02:20.923  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:20.923  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 08:02:20.925  1027  1533 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:20.925  1027  1533 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:20.926  1027  1533 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:20.926  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:20.927  1027  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 08:02:20.927  1027  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=175190  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 08:02:20.928  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=175191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 08:02:20.928  1027  1533 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175191
08-05 08:02:20.932  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:20.932  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 08:02:20.937  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:20.939  1027  1533 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175202
08-05 08:02:20.940  1027  1533 D WifiNative-wlan0: doString: [STATUS]
08-05 08:02:20.940  1027  7111 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 08:02:20.940  1027  7111 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 08:02:20.941  1027  1533 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 08:02:20.942  1027  1533 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 08:02:20.945  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 08:02:20.945  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 08:02:20.945  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 08:02:20.945  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-05 08:02:20.949  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 08:02:20.951  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 08:02:20.951  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 08:02:20.951  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 08:02:20.951  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 08:02:20.951  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 08:02:20.951  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 08:02:20.951  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 08:02:20.960  1027  1533 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 08:02:20.960  1027  1533 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-05 08:02:20.969  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:20.969  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:20.972  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.972  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.972  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 08:02:20.981  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:20.987  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:20.993  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 08:02:20.996  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:20.996  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 08:02:21.002  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:21.006  1027  1533 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 08:02:21.006  1027  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:02:21.006  1027  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-05 08:02:21.006  1027  1539 D ConnectivityService: Got NetworkAgent Messenger
08-05 08:02:21.007  1027  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 08:02:21.007  1027  1539 D ConnectivityService: NetworkAgent connected
08-05 08:02:21.007  1027  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 08:02:21.007  1027  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 08:02:21.012  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:21.012  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:21.012  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.014  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.021  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 08:02:21.021  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.021  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:21.023  1027  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 08:02:21.023  1027  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:02:21.023  1027  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 08:02:21.023  1027  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 08:02:21.023  1027  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 08:02:21.030  1027  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 08:02:21.030  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:21.032   306   888 D CommandListener: Setting iface cfg
08-05 08:02:21.042  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:21.042  1027  1533 E WifiStateMachine: Start Dhcp Watchdog 2
08-05 08:02:21.043  1027  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175306  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-05 08:02:21.043  1027  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175306  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:21.044  1027  7180 D DhcpStateMachine: StoppedState
08-05 08:02:21.044  1027  7180 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.044  1027  7180 D DhcpStateMachine: WaitBeforeStartState
08-05 08:02:21.044  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175307  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:21.047  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:21.047  1027  1027 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 08:02:21.048  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:21.048  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 08:02:21.049  1027  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175312  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:21.049  1027  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175312  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:21.050  1027  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175313  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 08:02:21.051  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14308] from screen [on:0 period:1498125819] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:02:21.052  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.052  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1498125820] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:02:21.052  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:02:21.056  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:21.056  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:21.057  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:21.057  1027  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:21.057  1027  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:21.058  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:21.058  1027  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 08:02:21.059  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=11,0,0
08-05 08:02:21.059  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=11,0,0
08-05 08:02:21.059  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 08:02:21.060  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 08:02:21.061  1027  1539 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-05 08:02:21.061  1027  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 08:02:21.062  1027  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 08:02:21.063  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 08:02:21.063  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:21.063  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.064  1027  1533 D WifiNative-wlan0: SET ps 0: returned true
08-05 08:02:21.064  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 08:02:21.064  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 08:02:21.064  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:21.064  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 08:02:21.065  1027  1531 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@234a8784 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.065  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@234a8784 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.065  1027  7180 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.065  1027  1533 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 08:02:21.065  1027  7180 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 08:02:21.065  1027  1533 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 08:02:21.065  1027  1533 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 08:02:21.066   306   888 D CommandListener: Setting iface cfg
08-05 08:02:21.066   306   888 D CommandListener: Trying to bring up wlan0
08-05 08:02:21.067  1027  1533 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-05 08:02:21.072  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:21.076  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 08:02:21.076  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 08:02:21.076  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 08:02:21.076  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 08:02:21.076  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 08:02:21.076  1027  1531 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.077  1027  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.077  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 08:02:21.077  1027  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 08:02:21.077  1027  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 08:02:21.077  7103  7103 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 08:02:21.077  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:21.078  1027  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 08:02:21.078  1027  1533 D WifiNative-wlan0: doBoolean: SET ps 1
,08-05 08:02:21.083  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.088  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:21.089  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.089  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:21.092  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 08:02:21.096  1027  1533 D WifiNative-wlan0: SET ps 1: returned true
08-05 08:02:21.096  1027  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 08:02:21.096  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:21.097  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:21.097  1027  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:21.098  1027  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:21.098  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:21.098  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:21.099  1027  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:21.099  1027  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 08:02:21.099  1027  1533 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 08:02:21.100  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 08:02:21.100  1027  1533 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 08:02:21.100  1027  1539 D ConnectivityService: ignoring duplicate network state non-change
08-05 08:02:21.102  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:21.102  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:21.103  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.103  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.103  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-05 08:02:21.104  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.106  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.108  1027  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 08:02:21.109  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.109  1027  1539 D ConnectivityService: Adding iface wlan0 to network 101
08-05 08:02:21.109  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.109  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-05 08:02:21.112  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 08:02:21.113  1027  1533 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 08:02:21.117  1961  1961 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 08:02:21.117  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.117  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.117  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 08:02:21.118  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-05 08:02:21.121  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.121  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:21.122  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 08:02:21.124  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:21.125  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.125  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:21.125  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:21.126  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 08:02:21.127  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.130  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:21.131  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 08:02:21.131  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 08:02:21.133  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:21.134  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:21.134  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 08:02:21.135  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.145  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 08:02:21.147  1027  1539 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 08:02:21.147  1027  1539 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-05 08:02:21.148  1027  1539 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-05 08:02:21.148   306   888 E Netd    : netlink response contains error (File exists)
08-05 08:02:21.149  1027  1539 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-05 08:02:21.149  5967  6060 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 772)
08-05 08:02:21.149  5967  6060 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 772)
08-05 08:02:21.149  1027  1539 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 08:02:21.149  1027  1539 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-05 08:02:21.150  1027  1539 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-05 08:02:21.150  1027  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 08:02:21.150  1027  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 08:02:21.150  1027  1539 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 08:02:21.151  1027  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 08:02:21.151  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.151  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 08:02:21.151  1027  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:21.151  1027  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:21.151  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:21.151  1027  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 08:02:21.151  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 08:02:21.151  1027  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.151  1027  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 08:02:21.151  1027  1539 D ConnectivityService: currentScore = 0, newScore = 20
08-05 08:02:21.151  1027  1539 D ConnectivityService:    accepting network in place of null
08-05 08:02:21.151  1027  1539 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.151  1027  1533 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.151  1027  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:21.152  5967  6060 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 777)
08-05 08:02:21.153   306  7187 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 08:02:21.153  5967  6060 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 08:02:21.153  5967  6060 I io.jxcore.node.SocketThreadBase: close: Complete (thr,ead ID: 778)
08-05 08:02:21.154  1870  1870 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.154  1870  1870 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 08:02:21.156  1027  1539 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 08:02:21.156  1027  1539 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 08:02:21.156  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 08:02:21.157  1027  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:21.157  1027  1539 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 08:02:21.158  1027  1539 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 08:02:21.159  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 08:02:21.159  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 08:02:21.159  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 08:02:21.159  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 08:02:21.159  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.159  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e47e777 added. We now have 2 listener(s)
08-05 08:02:21.160  1027  2317 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.161  1027  1539 D ConnectivityService: validation of new default Network = false
08-05 08:02:21.161  1027  1539 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 08:02:21.161  1027  1539 D DSQN    : enableDataServiceNotify 
08-05 08:02:21.161  1027  1539 D DSQN    : start dsqn bin
08-05 08:02:21.161   306  7188 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 08:02:21.162   306  7188 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-05 08:02:21.163  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.163  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.163  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.163  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.163  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2dffe4 added. We now have 9 listener(s)
08-05 08:02:21.163  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.164  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:02:21.168  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.170  1027  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 08:02:21.170  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.170  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:21.170  1027  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:21.171  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 08:02:21.157  7189  7189 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:21.157  7189  7189 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:02:21.176  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:02:21.178  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.178  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:02:21.178  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.178  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12f13302 added. We now have 3 listener(s)
08-05 08:02:21.179  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.180  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.182  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.185  1027  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.185  7189  7189 E DSQN    : DSQN ssw
,08-05 08:02:21.188  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.188  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.188  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.188  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.188  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c98413 added. We now have 10 listener(s)
08-05 08:02:21.188  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.188   306  7187 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 08:02:21.189  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:02:21.189  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:02:21.189  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:02:21.189  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.189  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.189  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.189  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.189  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e47e777 removed from the list
08-05 08:02:21.189  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.189  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2dffe4 removed from the list
08-05 08:02:21.189  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:02:21.189  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.190  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.190  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.191  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.191  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.191  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.191  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2dffe4 not in the list
08-05 08:02:21.191  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.191  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.192  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.192  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.192  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.192  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c98413 removed from the list
08-05 08:02:21.192  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.192  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.192  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.192  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.192  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12f13302 removed from the list
08-05 08:02:21.193   306  7188 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-05 08:02:21.194  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:21.194  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.194  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cbd3650 added. We now have 2 listener(s)
08-05 08:02:21.195  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.195  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.195  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:21.195  1812  7191 I CheckinService: active receiver: enabled
08-05 08:02:21.197  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.197  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.197  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.197  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.197  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14fcb049 added. We now have 9 listener(s)
08-05 08:02:21.197  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.204  1812  7191 I CheckinService: Preparing to send checkin request
08-05 08:02:21.205  1812  7191 I EventLogService: Accumulating logs since 1470375191389
08-05 08:02:21.205  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:02:21.208  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.208  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:02:21.212  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:02:21.214  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 08:02:21.215  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.215  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.216  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.216  1027  1530 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 08:02:21.217  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:02:21.217  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.217  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11be4e6f added. We now have 3 listener(s)
08-05 08:02:21.218  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.220  1027  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.220  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.220   306  7187 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 08:02:21.222  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.222  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.222  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.222  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.222  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22c7677c added. We now have 10 listener(s)
08-05 08:02:21.222  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.222  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:02:21.222  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:02:21.222  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:02:21.222  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.222  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:02:21.222  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:21.224  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 08:02:21.225  1027  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.228  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:02:21.229  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:02:21.229  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.231  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:02:21.232  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.233  5967  6060 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 08:02:21.233  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:02:21.233  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:02:21.235  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:02:21.235  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:02:21.235  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:02:21.235  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.235  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.235  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.235  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.235  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cbd3650 removed from the list
08-05 08:02:21.235  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.235  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14fcb049 removed from the list
08-05 08:02:21.235  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:02:21.235  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.237  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:21.237  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.238  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.238  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.238  6282  6282 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 08:02:21.238  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.238  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.238  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.239  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14fcb049 not in the list
08-05 08:02:21.239  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.239  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.239  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.241  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:02:21.241  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:02:21.241  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.241  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.241  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22c7677c removed from the list
08-05 08:02:21.241  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.241  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.241  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.241  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.241  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11be4e6f removed from the list
08-05 08:02:21.242  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:21.242  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.242  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@358b628b added. We now have 2 listener(s)
08-05 08:02:21.242  1027  1371 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.243  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.243  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.243  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.244  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.244  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e17f68 added. We now have 9 listener(s)
08-05 08:02:21.244  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.244  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:02:21.245  7112  7112 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 08:02:21.246  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:02:21.249  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:02:21.250  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.250  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:02:21.250  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.250  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ccde826 added. We now have 3 listener(s)
08-05 08:02:21.250  1027  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.250  7112  7112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:21.254  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.254  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.254  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.254  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.254  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cb9c67 added. We now have 10 listener(s)
08-05 08:02:21.254  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.254  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:02:21.255  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:21.255  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.255  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:02:21.255  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:02:21.255  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:02:21.255  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.255  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:02:21.257  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.257  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 08:02:21.258  1027  2093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.261  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.261  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:02:21.263  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:02:21.264   306   887 D LGDataListener: argv[0]=dsqncommand
08-05 08:02:21.264   306   887 D LGDataListener: argv[1]=wlan0
08-05 08:02:21.264   306   887 D LGDataListener: argv[2]=1
08-05 08:02:21.264   306   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 08:02:21.264  1027  1087 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 08:02:21.264  1027  1087 D DSQN    : start to monitor internet connection
08-05 08:02:21.264  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:02:21.265  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.266  5967  6060 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 08:02:21.266  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:02:21.266  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:02:21.266  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:02:21.267  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.267  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.267  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.267  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.267  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@358b628b removed from the list
08-05 08:02:21.267  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.267  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e17f68 removed from the list
08-05 08:02:21.267  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:02:21.267  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.268  1027  7180 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 08:02:21.268  1027  7180 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 08:02:21.268  1027  7180 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 08:02:21.257  7197  7197 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:21.257  7197  7197 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 08:02:21.271  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.271  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:02:21.272  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:21.272  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.272  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.272  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.272  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e17f68 not in the list
08-05 08:02:21.272  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.272  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.272  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.273  6282  6282 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 08:02:21.273  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.273  6282  6282 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 08:02:21.273  6282  6282 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 08:02:21.273  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:02:21.274  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:02:21.274  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.274  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.274  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cb9c67 removed from the list
08-05 08:02:21.274  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.274  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.274  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.274  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.274  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ccde826 removed from the list
08-05 08:02:21.275  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.275  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2060b2 added. We now have 2 listener(s)
08-05 08:02:21.275  1027  2317 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.277  7197  7197 I dhcpcd  : version 5.5.6 starting
08-05 08:02:21.278  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.278  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.278  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.278  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.278  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15eb9803 added. We now have 9 listener(s)
08-05 08:02:21.278  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.279  7197  7197 E dhcpcd  : get_duid: m
08-05 08:02:21.279  7197  7197 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 08:02:21.279  7197  7197 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-05 08:02:21.279  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:02:21.281  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:02:21.283  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:02:21.285  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.285  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:02:21.285  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.285  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d53db9 added. We now have 3 listener(s)
08-05 08:02:21.285  1027  1647 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.287  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.288  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.288  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.288  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.288  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.288  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.288  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23afd5fe added. We now have 10 listener(s)
08-05 08:02:21.288  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.288  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:02:21.288  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:02:21.288  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:02:21.288  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.288  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:02:21.291  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 08:02:21.291  1027  2317 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.291  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 08:02:21.293  1812  7191 W EventLogAggregator: Unknown tag: snet_gcore
08-05 08:02:21.293  1812  7191 W EventLogAggregator: Unknown tag: snet_launch_service
08-05 08:02:21.295  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:02:21.296  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:02:21.297  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:02:21.297  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.299  5967  6060 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 08:02:21.300  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:02:21.300  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:02:21.300  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:02:21.300  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.300  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.300  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.300  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.300  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2060b2 removed from the list
08-05 08:02:21.300  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.300  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15eb9803 removed from the list
08-05 08:02:21.300  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:02:21.300  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.300  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.300  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.301  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.301  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.301  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.301  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15eb9803 not in the list
08-05 08:02:21.301  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.301  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.302  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.302  5967  6060 D BluetoothLeScanner: could not find callback wrapper
08-05 08:02:21.302  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:02:21.302  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.302  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.302  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23afd5fe removed from the list
08-05 08:02:21.302  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.302  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.302  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.302  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.302  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d53db9 removed from the list
08-05 08:02:21.303  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.303  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82fc75 added. We now have 2 listener(s)
08-05 08:02:21.303  1027  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.304  7112  7112 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 08:02:21.304  7112  7112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 08:02:21.305  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.305  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.305  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.305  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.305  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182f540a added. We now have 9 listener(s)
08-05 08:02:21.305  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.305  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 06:02:21 GMT], X-Android-Received-Millis=[1470376941305], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470376941263]}
08-05 08:02:21.306  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 08:02:21.306  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 08:02:21.306  1027  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 08:02:21.306  1027  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 08:02:21.306  1027  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:21.306  1027  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:21.306  1027  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 08:02:21.306  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:02:21.306  1027  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 08:02:21.307  1027  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 08:02:21.307  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.307  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:21.307  1027  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:21.307  1027  1539 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.307  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 08:02:21.307  1027  1533 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.307  1027  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:21.308  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 08:02:21.309  1870  1870 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:21.309  1870  1870 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-05 08:02:21.316  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:02:21.318  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:02:21.322  5967  6060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:02:21.324  5967  6060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:21.324  5967  6060 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:02:21.324  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:02:21.324  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a279298 added. We now have 3 listener(s)
08-05 08:02:21.325  7197  7197 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 08:02:21.325  7197  7197 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 08:02:21.325  7197  7197 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 08:02:21.326  7197  7197 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 08:02:21.326  7197  7197 D dhcpcd  : wlan0: sending REQUEST (xid 0x1d060376), next in 3.13 seconds
08-05 08:02:21.326  1027  1371 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 08:02:21.327  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.327  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 08:02:21.327  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:02:21.328  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:02:21.328  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:02:21.328  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13eaf1 added. We now have 10 listener(s)
08-05 08:02:21.328  5967  6060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:02:21.328  5967  6060 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:02:21.328  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:02:21.328  5967  6060 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:02:21.328  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.328  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.328  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:02:21.328  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.328  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82fc75 removed from the list
08-05 08:02:21.328  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.328  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182f540a removed from the list
08-05 08:02:21.330  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:02:21.330  5967  6060 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:02:21.330  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.330  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.330  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.331  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.331  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.331  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.331  5967  6060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182f540a not in the list
08-05 08:02:21.331  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.331  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.331  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 08:02:21.332  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:02:21.332  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:02:21.332  5967  6060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:02:21.332  5967  6060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13eaf1 removed from the list
08-05 08:02:21.332  5967  6060 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:02:21.332  5967  6060 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:02:21.332  5967  6060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:02:21.332  5967  6060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:02:21.332  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.332  5967  6060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a279298 removed from the list
08-05 08:02:21.332  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:21.333  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 08:02:21.333  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 08:02:21.333  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 08:02:21.333  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:02:21.333  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:02:21.333  5967  6060 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 08:02:21.334  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 08:02:21.339  6282  6282 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 08:02:21.339  6282  6282 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 08:02:21.340  6282  6282 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 08:02:21.340  6282  6282 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 08:02:21.341  6282  6282 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 08:02:21.342  7197  7197 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 08:02:21.345  5967  7205 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 785, name: My test thread name)
08-05 08:02:21.345  5967  7205 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 785, thread name: My test thread name)
08-05 08:02:21.345  5967  7205 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 785, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 08:02:21.347  5967  7206 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 787, name: My test thread name)
08-05 08:02:21.347  5967  7206 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 787, thread name: My test thread name)
08-05 08:02:21.347  5967  7206 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 787, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 08:02:21.349  5967  6060 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 08:02:21.349  5967  6060 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 08:02:21.349  5967  6060 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 08:02:21.349  5967  6060 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 08:02:21.349  5967  6060 D com.test.thalitest.ThaliTestRunner: Total duration: 22703 ms
08-05 08:02:21.350  5967  6060 I jxcore-log: Total number of executed tests:  80
08-05 08:02:21.350  5967  6060 I jxcore-log: 
08-05 08:02:21.350  5967  6060 I jxcore-log: Number of passed tests:  80
08-05 08:02:21.350  5967  6060 I jxcore-log: 
08-05 08:02:21.350  5967  6060 I jxcore-log: Number of failed tests:  0
08-05 08:02:21.350  5967  6060 I jxcore-log: 
08-05 08:02:21.350  5967  6060 I jxcore-log: Number of ignored tests:  0
08-05 08:02:21.350  5967  6060 I jxcore-log: 
08-05 08:02:21.351  5967  6060 I jxcore-log: Total duration:  22703
08-05 08:02:21.351  5967  6060 I jxcore-log: 
08-05 08:02:21.352  5967  6060 I jxcore-log: Unit Test app is loaded
08-05 08:02:21.352  5967  6060 I jxcore-log: 
,08-05 08:02:21.355  7197  7197 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 08:02:21.355  7197  7197 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 08:02:21.355  7197  7197 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 08:02:21.355  7197  7197 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 08:02:21.355  7197  7197 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 08:02:21.355  7197  7197 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 08:02:21.355  7197  7197 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 08:02:21.355  7197  7197 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 08:02:21.362  1812  7191 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 08:02:21.362  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.362  5967  6060 I jxcore-log: 
08-05 08:02:21.365  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.365  5967  6060 I jxcore-log: 
,08-05 08:02:21.366  1027  1538 D WifiService: New client listening to asynchronous messages
08-05 08:02:21.367  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.367  5967  6060 I jxcore-log: 
08-05 08:02:21.368  5967  5967 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-05 08:02:21.374  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.374  5967  6060 I jxcore-log: 
08-05 08:02:21.375  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.375  5967  6060 I jxcore-log: 
08-05 08:02:21.376  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.376  5967  6060 I jxcore-log: 
08-05 08:02:21.378  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.378  5967  6060 I jxcore-log: 
,08-05 08:02:21.380  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.380  5967  6060 I jxcore-log: 
,08-05 08:02:21.381  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.381  5967  6060 I jxcore-log: 
08-05 08:02:21.382  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:02:21.382  5967  6060 I jxcore-log: 
08-05 08:02:21.383  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.383  5967  6060 I jxcore-log: 
08-05 08:02:21.383  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.383  5967  6060 I jxcore-log: 
08-05 08:02:21.384  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.384  5967  6060 I jxcore-log: 
08-05 08:02:21.385  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.385  5967  6060 I jxcore-log: 
08-05 08:02:21.385  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.385  5967  6060 I jxcore-log: 
08-05 08:02:21.386  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.386  5967  6060 I jxcore-log: 
08-05 08:02:21.387  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.387  5967  6060 I jxcore-log: 
08-05 08:02:21.387  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.387  5967  6060 I jxcore-log: 
08-05 08:02:21.388  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.388  5967  6060 I jxcore-log: 
08-05 08:02:21.388  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:02:21.388  5967  6060 I jxcore-log: 
08-05 08:02:21.389  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.389  5967  6060 I jxcore-log: 
08-05 08:02:21.389  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:02:21.389  5967  6060 I jxcore-log: 
08-05 08:02:21.390  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:02:21.390  5967  6060 I jxcore-log: 
08-05 08:02:21.390  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:02:21.390  5967  6060 I jxcore-log: 
08-05 08:02:21.391  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:02:21.391  5967  6060 I jxcore-log: 
08-05 08:02:21.391  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on,","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:02:21.391  5967  6060 I jxcore-log: 
08-05 08:02:21.391  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:02:21.391  5967  6060 I jxcore-log: 
08-05 08:02:21.393  5967  6060 I jxcore-log: My device name is: LGE-LG-D855
08-05 08:02:21.393  5967  6060 I jxcore-log: 
,08-05 08:02:21.470  1027  1905 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7224 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-05 08:02:21.521  7224  7224 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-05 08:02:21.522  7224  7224 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-05 08:02:21.539  7224  7224 I MultiDex: VM with version 2.1.0 has multidex support
08-05 08:02:21.540  7224  7224 I MultiDex: install
,08-05 08:02:21.540  7224  7224 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-05 08:02:21.549  7224  7224 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-05 08:02:21.559  2233  2233 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-05 08:02:21.570  2233  2233 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-05 08:02:21.571  2233  2233 D c       : Getting all permits...
08-05 08:02:21.571  2233  2233 D a       : Opening database...
08-05 08:02:21.573  2233  2233 D a       : Opening database auth.proximity.permit_store...
08-05 08:02:21.574  2233  2233 D a       : Closing database...
,08-05 08:02:21.585  1027  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3a11d44d type 2 when 175848 com.google.android.gms} when 175848
08-05 08:02:21.618  1812  1812 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-05 08:02:21.625  1812  7248 I ConfigFetchService: running network task: configservice_periodic
08-05 08:02:21.627  1812  7248 I ConfigFetchService: launchTask
08-05 08:02:21.628  2233  2233 I ConfigService: onCreate
08-05 08:02:21.628  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 08:02:21.636  2233  2233 I ConfigService: onBind returning update interface
,08-05 08:02:21.637  1812  1812 I ConfigFetchService: service connected
08-05 08:02:21.637  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 08:02:21.638  2233  2233 I ConfigService: onBind returning config service
08-05 08:02:21.642  7224  7243 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 08:02:21.653   306  7254 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 08:02:21.654   306  7254 D libc-netbsd: res_queryN name = www.googleapis.com, class = 1, type = 1
08-05 08:02:21.671  1027  7180 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-05 08:02:21.672  1027  7180 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 08:02:21.672  1027  7180 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 08:02:21.672  1027  7180 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 08:02:21.672  1027  7180 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 08:02:21.672  1027  7180 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 08:02:21.672  1027  7180 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 08:02:21.672  1027  7180 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 08:02:21.673  1027  7180 D DhcpStateMachine: RunningState
08-05 08:02:21.685   306  7254 D libc-netbsd: res_queryN name = www.googleapis.com succeed
,08-05 08:02:21.689  1812  1812 I art     : Explicit concurrent mark sweep GC freed 19997(1359KB) AllocSpace objects, 14(224KB) LOS objects, 51% free, 29MB/61MB, paused 961us total 48.990ms
08-05 08:02:21.691  1812  1812 I ConfigClient: service connected
08-05 08:02:22.497  7261  7261 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 08:02:22.543  7261  7261 I dex2oat : dex2oat took 45.896ms (threads: 4)
,08-05 08:02:22.551  7224  7243 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 08:02:22.551  7224  7243 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 08:02:22.551  7224  7243 I Adreno-EGL: Build Date: 12/12/14 금
08-05 08:02:22.551  7224  7243 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 08:02:22.551  7224  7243 I Adreno-EGL: Remote Branch: 
08-05 08:02:22.551  7224  7243 I Adreno-EGL: Local Patches: 
08-05 08:02:22.551  7224  7243 I Adreno-EGL: Reconstruct Branch: 
08-05 08:02:22.628  7224  7243 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 08:02:22.628  7224  7243 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 08:02:22.628  7224  7243 I Adreno-EGL: Build Date: 12/12/14 금
08-05 08:02:22.628  7224  7243 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 08:02:22.628  7224  7243 I Adreno-EGL: Remote Branch: 
08-05 08:02:22.628  7224  7243 I Adreno-EGL: Local Patches: 
08-05 08:02:22.628  7224  7243 I Adreno-EGL: Reconstruct Branch: 
,08-05 08:02:22.786  1027  1533 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:22.786  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 08:02:22.787  1027  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:22.787  1027  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:22.787  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:22.788  1027  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 08:02:22.788  1027  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-05 08:02:22.790  1027  1539 D ConnectivityService: identical MTU - not setting
08-05 08:02:22.790  1027  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 08:02:22.790  1027  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 08:02:22.790  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:22.790  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:22.791  1027  1539 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:22.791  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 08:02:23.074  7224  7243 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:23.075  7224  7243 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:23.187  7224  7243 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 08:02:23.187  7224  7243 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 08:02:23.187  7224  7243 I Adreno-EGL: Build Date: 12/12/14 금
08-05 08:02:23.187  7224  7243 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 08:02:23.187  7224  7243 I Adreno-EGL: Remote Branch: 
08-05 08:02:23.187  7224  7243 I Adreno-EGL: Local Patches: 
08-05 08:02:23.187  7224  7243 I Adreno-EGL: Reconstruct Branch: 
,08-05 08:02:23.295   306  7276 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 08:02:23.297   306  7276 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-05 08:02:23.330   306  7276 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 08:02:23.531  1812  7191 I CheckinTask: Sending checkin request (8045 bytes)
,08-05 08:02:23.760  1812  7191 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-05 08:02:23.768  1812  7191 I CheckinService: active receiver: disabled
,08-05 08:02:23.793  2233  2233 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 08:02:23.802  2233  2233 I GCM     : GCM config loaded
08-05 08:02:23.809   306  7280 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 08:02:23.810   306  7280 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-05 08:02:23.819  6701  6701 V SetupWizard: Connected to Gservices successfully
08-05 08:02:23.841   306  7280 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 08:02:24.012  2233  7278 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-05 08:02:24.029  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 08:02:24.029  5967  6060 I jxcore-log: 
,08-05 08:02:24.058  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498128826] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:24.059  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1498128827] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:24.059  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:02:24.063  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 08:02:24.114  1027  1534 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-05 08:02:24.159  1027  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:24.168  1027  1089 D Tethering: MasterInitialState.processMessage what=3
,08-05 08:02:24.169  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 08:02:24.170  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:24.176  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 08:02:24.187  1027  1821 D AlarmManagerService: Setting time of day to sec=1470376943
,08-05 08:02:23.926  1027  1821 W AlarmManagerService: Unable to set rtc to 1470376943: Invalid argument
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:02:23.930  5967  5967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:02:23.932  3748  3766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 08:02:23.932  5967  5967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:02:23.934  2233  7283 D GCM     : Connected
,08-05 08:02:23.943  1597  1597 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-05 08:02:23.945  3717  3717 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
08-05 08:02:23.946  3717  3717 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-05 08:02:23...... Request
08-05 08:02:23.946  3717  3717 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 8, total count : 46, new day : false...... Request
08-05 08:02:23.947  3717  3717 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 46
08-05 08:02:23.947  3717  3717 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 8
08-05 08:02:23.947  3717  3717 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-05 08:02:23
,08-05 08:02:23.952  1961  1961 I SecureClockService: Intent.ACTION_TIME_CHANGED 
08-05 08:02:23.953  1597  1597 I LgeClockWidgetControlView: time changed, timezoneChanged : false
08-05 08:02:23.953  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 08:02:23.959  5376  5376 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-05 08:02:23.963  1027  2093 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
08-05 08:02:23.967  2233  7283 D GCM     : Message class com.google.e.a.a.q
08-05 08:02:23.967  2082  2082 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=5 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
08-05 08:02:23.969  2082  2082 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 5
08-05 08:02:23.979  2082  2082 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 5
08-05 08:02:23.979  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 08:02:24.019  2233  2233 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:24.025  2640  2640 D [Concierge]Service: onStartCommand(). Type : 9
08-05 08:02:24.036  1027  1925 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-05 08:02:24.036  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:24.036  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:24.036  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 08:02:24.036  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 08:02:24.037  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-05 08:02:24.047  1027  1960 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7295 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 08:02:24.080  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 06:02:24 GMT], X-Android-Received-Millis=[1470376944079], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470376944037]}
08-05 08:02:24.080  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 08:02:24.080  1027  7174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 08:02:24.080  1027  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 08:02:24.080  1027  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 08:02:24.080  1027  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 08:02:24.080  1027  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:24.080  1027  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 08:02:24.080  1027  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 08:02:24.080  1027  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 08:02:24.080  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 08:02:24.080  1027  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:24.081  1027  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 08:02:24.081  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-05 08:02:24.089  7295  7295 I AppUp4:AppBoxCP: onCreate
08-05 08:02:24.089  7295  7295 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-05 08:02:24.094  7295  7295 I AppUp4:DB:  setFingerPrint start
08-05 08:02:24.094  7295  7295 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 08:02:24.099  7295  7295 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 08:02:24.099  7295  7295 I AppUp4:DB:  SDK version = 21
08-05 08:02:24.099  7295  7295 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-05 08:02:24.173  1027  1905 I art     : Explicit concurrent mark sweep GC freed 76776(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.463ms total 72.609ms
08-05 08:02:24.173  7295  7295 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-05 08:02:24.174  7295  7295 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 08:02:24.174  7295  7295 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:24.175  7295  7295 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 08:02:24.175  7295  7295 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-05 08:02:24.182  7295  7295 I AppUp4:CustModeStarterReceiver: onReceive
08-05 08:02:24.205  7295  7295 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:24.205  7295  7295 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:24.211  7295  7295 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2dfcb7a6
08-05 08:02:24.211  7295  7295 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 08:02:24.211  7295  7295 D AppUp4:CustFacade: isPhone : true
08-05 08:02:24.212  7295  7295 D AppUp4:CustModeStarterReceiver: begin check event
08-05 08:02:24.212  7295  7295 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 08:02:24.212  7295  7295 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-05 08:02:24.213  7295  7313 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 08:02:24.213  7295  7313 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 08:02:24.213  7295  7313 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-05 08:02:24.213  1027  1995 I ActivityManager: Killing 6610:com.lge.email/u0a23 (adj 15): empty #17
08-05 08:02:24.391  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:02:24.392  4270  4270 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 08:02:24.395  1027  1371 W libprocessgroup: failed to open /acct/uid_10023/pid_6610/cgroup.procs: No such file or directory
08-05 08:02:24.398  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:24.404  4270  4270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 08:02:24.413  4270  7316 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 08:02:24.417  3431  3431 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:24.417  4270  7316 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-05 08:02:24.420  3431  3431 V DownloadManager: DownloadService onCreate
08-05 08:02:24.425  3431  7318 I DownloadManager: in removeSpuriousFiles
,08-05 08:02:24.426  3431  7318 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-05 08:02:24.430  4270  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:24.430  4270  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 08:02:24.432  3431  7318 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@38df1df4 on behalf of 3431
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-05 08:02:24.433  3431  7318 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-05 08:02:24.435  3431  7318 I DownloadManager: in trimDatabase
08-05 08:02:24.435  3431  7318 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-05 08:02:24.436  3431  7318 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@10d8491d on behalf of 3431
08-05 08:02:24.470  1027  2317 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7322 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 08:02:24.474  4270  7316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-05 08:02:24.476  3431  3431 V DownloadManager: DownloadService onStartCommand
08-05 08:02:24.478  4270  4270 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-05 08:02:24.478  3431  7319 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-05 08:02:24.479  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 08:02:24.479  5967  6060 I jxcore-log: 
08-05 08:02:24.480  4270  4270 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-05 08:02:24.481  4270  4270 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-05 08:02:24.481  3431  7319 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@18ca2560 on behalf of 3431
08-05 08:02:24.484  4270  4270 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-05 08:02:24.485  3431  7319 V DownloadManager: processing inserted download 1
08-05 08:02:24.486  3431  7319 V DownloadManager: processing inserted download 4
08-05 08:02:24.488  3431  7319 V DownloadManager: processing inserted download 7
08-05 08:02:24.489  3431  7319 V DownloadManager: processing inserted download 8
,08-05 08:02:24.490  3431  7319 V DownloadManager: processing inserted download 9
08-05 08:02:24.491  3431  7319 V DownloadManager: processing inserted download 10
08-05 08:02:24.492  3431  7319 V DownloadManager: processing inserted download 11
08-05 08:02:24.493  3431  7319 V DownloadManager: processing inserted download 12
08-05 08:02:24.494  3431  7319 V DownloadManager: processing inserted download 13
08-05 08:02:24.495  3431  7319 V DownloadManager: processing inserted download 14
08-05 08:02:24.496  3431  7319 V DownloadManager: processing inserted download 16
,08-05 08:02:24.500  4270  4270 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-05 08:02:24.503  3431  3431 V DownloadManager: DownloadService onDestroy
08-05 08:02:24.504  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 08:02:24.504  5967  6060 I jxcore-log: 
08-05 08:02:24.528  7322  7322 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 08:02:24.529  7322  7322 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 08:02:24.530  7322  7322 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 08:02:24.530  7322  7322 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 08:02:24.593  7322  7322 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 08:02:24.603  7322  7322 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-05 08:02:24.670  7322  7322 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 08:02:24.702  7322  7322 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:24.702  7322  7322 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:24.804  7322  7322 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 08:02:24.827  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 08:02:24.827  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 08:02:24.827  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 08:02:24.827  3395  3395 D PhoneState: setPdpRejectCasuse : false
08-05 08:02:24.829  7322  7322 I HubEmail: JNI_OnLoad()
08-05 08:02:24.829  7322  7322 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 08:02:24.829  7322  7322 I HubEmail: registerNatives()
08-05 08:02:24.829  7322  7322 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 08:02:24.829  7322  7322 I HubEmail: registerNativeMethods()
08-05 08:02:24.829  7322  7322 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 08:02:24.829  7322  7322 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-05 08:02:24.830  6701  6701 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 08:02:24.831  6701  6701 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 08:02:24.838  6781  6781 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:24
08-05 08:02:24.842  6781  6781 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 08:02:24.842  6781  6781 D Weather.Utils: 2 : All the weather widget is gone.
,08-05 08:02:24.843  6781  6781 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 08:02:24.843  6781  6781 D WeatherAncestor: connectivity changed - connection : true
08-05 08:02:24.843  6781  6781 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a094594
08-05 08:02:24.844  7322  7348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:24.844  6781  6781 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 08:02:24.844  6781  6781 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 08:02:24.844  6781  6781 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 08:02:24.844  6781  6781 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 08:02:24.844  6781  6781 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:2:24
08-05 08:02:24.864  3748  3748 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,08-05 08:02:24.893  1812  7357 I CheckinService: active receiver: disabled
08-05 08:02:24.904   306  7360 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 08:02:24.904   306  7360 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-05 08:02:24.937   306  7360 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-05 08:02:24.941  1027  2036 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7362 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-05 08:02:24.998  6319  7350 V FormManager: There are no updated forms. The schedule will be deleted.
,08-05 08:02:25.002  6319  7350 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-05 08:02:25.017  1027  1771 I ActivityManager: Killing 6230:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-05 08:02:25.056   306  7379 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 08:02:25.056   306  7379 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-05 08:02:25.134   306  7379 D libc-netbsd: res_queryN name = www.google.com succeed
,08-05 08:02:25.138  1027  2036 W libprocessgroup: failed to open /acct/uid_10037/pid_6230/cgroup.procs: No such file or directory
,08-05 08:02:25.139   306  7381 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 08:02:25.140   306  7381 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 08:02:25.140   306  7381 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 08:02:25.152  7362  7382 D ALBootInit: ====action==>android.intent.action.TIME_SET
,08-05 08:02:25.161  7362  7382 D ALBootInit: Alarm ALBootInit: TIME_SET
08-05 08:02:25.167  7362  7382 D Alarms  : [setNextAlert] start
,08-05 08:02:25.185  7362  7382 D Alarms  : [setNextAlert] (1)
,08-05 08:02:25.189  7362  7382 D Alarms  :  minTime  = 0
08-05 08:02:25.191  7362  7382 D Alarms  :  -- OK multi -- 0
08-05 08:02:25.192  7362  7382 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-05 08:02:25.192  7362  7382 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
08-05 08:02:25.212  7362  7382 I CommonUtil: BUILD Country: EU
,08-05 08:02:25.214  7362  7382 D Alarms  : broadcastToWidgetProvider : false
08-05 08:02:25.218  7362  7382 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
08-05 08:02:25.229  1027  1905 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,08-05 08:02:25.234  7362  7362 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-05 08:02:25.235  7362  7362 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@4f2f5e7
,08-05 08:02:25.237  7362  7362 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@4f2f5e7
08-05 08:02:25.239  7362  7362 D QuickCoverProvider: onReceiver
08-05 08:02:25.244  1552  1552 I indal   : SmartCoverWidgetContext createApplicationContext
08-05 08:02:25.245  1552  1552 I indal   : SmartCoverWidgetContext createApplicationContext
,08-05 08:02:25.262  6781  6781 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:2:25
,08-05 08:02:25.265  6781  6781 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 08:02:25.265  6781  6781 D Weather.Utils: 2 : All the weather widget is gone.
08-05 08:02:25.265  6781  6781 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 08:02:25.268  6781  6781 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a094594
08-05 08:02:25.269  6781  6781 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 08:02:25.269  6781  6781 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 08:02:25.269  6781  6781 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 08:02:25.271  6781  6781 D Weather_cast: 2 : set auto-update time : 8/5 11:2
08-05 08:02:25.277  6781  6781 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:2:25
,08-05 08:02:25.317  1027  2036 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7390 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 08:02:25.318  1027  2036 I ActivityManager: Killing 6299:com.lge.settings.easy/1000 (adj 15): empty #17
08-05 08:02:25.349  1027  1535 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-05 08:02:25.429  1027  1960 W libprocessgroup: failed to open /acct/uid_1000/pid_6299/cgroup.procs: No such file or directory
,08-05 08:02:25.485  7390  7390 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470376945485
08-05 08:02:25.485  7390  7390 D         : TimeServiceNative: User Time to be set is 1470376945485
08-05 08:02:25.485  7390  7390 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-05 08:02:25.485  7390  7390 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-05 08:02:25.485  7390  7390 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470376945485
08-05 08:02:25.485   358  1026 D QC-time-services: Daemon: Connection accepted:time_genoff
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470376945485
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470376945485, operation = 0
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/15/70 0:30:5
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:Value read from RTC seconds = 3889805000
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:new time 1470376945485 
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon: delta 1466487140485 genoff 1466487140485 
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487140485 to memory
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-05 08:02:25.486   358  7407 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-05 08:02:25.486  7390  7390 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-05 08:02:25.493   358  7407 D QC-time-services: Updating the TOD offset
08-05 08:02:25.493   358  7407 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487140485 to memory
,08-05 08:02:25.493   358  7407 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-05 08:02:25.493   358  7407 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-05 08:02:25.497   358  7407 E QC-time-services: Daemon:Update to modem bit set
08-05 08:02:25.497   358  7407 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-05 08:02:25.497   358  7407 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522340485
08-05 08:02:25.497  7390  7390 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-05 08:02:25.499   358  1024 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-05 08:02:25.500   358  1026 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-05 08:02:25.503  7138  7138 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
08-05 08:02:25.505  7138  7138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-05 08:02:25.507  1597  1597 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-05 08:02:25.507  1597  1597 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-05 08:02:25.507  1597  1597 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-05 08:02:25.511  7138  7138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
08-05 08:02:25.512  7138  7138 V [BNRBootReceiver]: Boot Receiver Return
08-05 08:02:25.567  1027  1647 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7408 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,08-05 08:02:25.570  1027  1647 I ActivityManager: Killing 7112:com.lge.sync/1000 (adj 15): empty #17
,08-05 08:02:25.731  1027  1371 W libprocessgroup: failed to open /acct/uid_1000/pid_7112/cgroup.procs: No such file or directory
,08-05 08:02:25.774  7408  7408 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 08:02:25.805  7408  7408 D CalendarApplication: CalendarApplication.onCreate()
,08-05 08:02:25.816  7408  7408 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
08-05 08:02:25.817  7408  7408 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1616f7da, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@33e8240b, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@54e2e8, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@28b77d01, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2dfcb7a6, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@4f2f5e7, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3a094594, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2d9de83d, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@252ca832, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@37ef0983, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3ff2700, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1b85cb39, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@22f9157e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@260ebadf, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@18afb32c, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@b6ee1f5, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1f8d0b8a, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1f4e25fb, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3efad618, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2c98a871, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@38b85656, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2d4f26d7, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@9d33bc4, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@8be5aad, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@77b81e2, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@27f55973, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@26aa5030, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1012f4a9, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@253da2e, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@37c219cf, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@269c3f5c, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@28fd3265, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@38476b3a, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@21f083eb, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2e5bf548, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3f938fe1, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@30b10106, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3a5173c7, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@38df1df4, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@10d8491d, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Pre,ferenceKey$KeyData@3bcc2792, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@16e7856
08-05 08:02:25.820  7408  7408 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,08-05 08:02:25.829  7408  7408 D Config  : [init]
08-05 08:02:25.830  7408  7408 I Config  : LGCalendar ver.4.40.16
08-05 08:02:25.830  7408  7408 I Config  : start check model
08-05 08:02:25.830  7408  7408 I Config  : start check native_ca
08-05 08:02:25.831  7408  7408 I Config  : Config Operator=OPEN, Country=EU
08-05 08:02:25.831  7408  7408 D Config  : [setDefaultValuesToPref]
08-05 08:02:25.831  7408  7408 D Config  : [parseProfiles]
08-05 08:02:25.835  7408  7408 D ProfilesParser: [debug_displayParseInfos] profile.country = null
08-05 08:02:25.835  7408  7408 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
08-05 08:02:25.835  7408  7408 D Config  : [updateProfiletoCountryInfo]
08-05 08:02:25.836  7408  7408 D GeneralPreference: [checkAndMigrateOldPreference]
,08-05 08:02:25.847  7408  7408 E AgendaWidgetManager: [updateWidgets] 
08-05 08:02:25.850  7408  7427 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
08-05 08:02:25.853  7408  7427 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,08-05 08:02:25.868  7408  7427 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,08-05 08:02:25.874  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
08-05 08:02:25.877  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
08-05 08:02:25.880  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,08-05 08:02:25.886  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
08-05 08:02:25.889  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
08-05 08:02:25.890  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 08:02:25.890  5967  6060 I jxcore-log: 
08-05 08:02:25.893  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,08-05 08:02:25.898  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
08-05 08:02:25.901  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
08-05 08:02:25.904  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,08-05 08:02:25.910  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
08-05 08:02:25.913  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
08-05 08:02:25.917  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,08-05 08:02:25.922  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
08-05 08:02:25.925  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
08-05 08:02:25.929  7408  7427 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
08-05 08:02:25.929  7408  7427 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,08-05 08:02:25.933  7408  7427 I AlertUtils: set default noti to content://media/internal/audio/media/41
08-05 08:02:25.939  7408  7427 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
08-05 08:02:25.973  7408  7430 W HolidayIntentService: onHandleIntent
,08-05 08:02:25.975  7408  7430 D HolidayDataLoader: readJsonAsset : holiday.json
08-05 08:02:25.983  7408  7408 D MonthWidgetProvider: [onReceive]
08-05 08:02:25.983  7408  7408 D CalendarWidgetProvider: [onReceive]
08-05 08:02:25.983  7408  7408 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
08-05 08:02:25.985  7408  7408 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-05 08:02:25.989  7408  7408 D WeekWidgetProvider: [onReceive]
08-05 08:02:25.989  7408  7408 D CalendarWidgetProvider: [onReceive]
08-05 08:02:25.989  7408  7408 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
08-05 08:02:25.990  7408  7408 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-05 08:02:25.993  2233  2233 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 08:02:26.008  7362  7362 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,08-05 08:02:26.011  6781  6781 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:2:26
08-05 08:02:26.012  6781  6781 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 08:02:26.013  6781  6781 D Weather.Utils: 2 : All the weather widget is gone.
08-05 08:02:26.013  6781  6781 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 08:02:26.014  6781  6781 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
08-05 08:02:26.014  6781  6781 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:2:26
08-05 08:02:26.017  2082  2082 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-05 08:02:26.019  2082  2810 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-05 08:02:26.019  2082  2810 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-05 08:02:26.019  2082  2810 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-05 08:02:26.020  2082  2810 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-05 08:02:26.020  2082  2810 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-05 08:02:26.021  7138  7138 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
08-05 08:02:26.021  7138  7138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-05 08:02:26.023  1597  1597 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-05 08:02:26.023  1597  1597 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-05 08:02:26.023  1597  1597 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-05 08:02:26.025  7138  7138 V [BNRBootReceiver]: Boot Receiver Return
08-05 08:02:26.025  7408  7430 E HolidayIntentService: onHandleIntent:holiday data empty
,08-05 08:02:26.028  2082  2082 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,08-05 08:02:26.029  2082  5401 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-05 08:02:26.029  2082  5401 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-05 08:02:26.030  2082  5401 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-05 08:02:26.030  1027  1942 I ActivityManager: Killing 6141:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-05 08:02:26.034  2082  5401 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
,08-05 08:02:26.034  2082  5401 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-05 08:02:26.045  6282  6282 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 08:02:26.045  6282  6282 W System.err: android.os.DeadObjectException
08-05 08:02:26.045  6282  6282 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 08:02:26.045  6282  6282 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-05 08:02:26.045  6282  6282 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 08:02:26.045  6282  6282 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 08:02:26.045  6282  6282 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 08:02:26.045  6282  6282 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 08:02:26.045  6282  6282 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 08:02:26.045  6282  6282 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 08:02:26.045  6282  6282 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 08:02:26.045  6282  6282 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 08:02:26.045  6282  6282 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:02:26.046  6282  6282 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 08:02:26.046  6282  6282 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 08:02:26.046  6282  6282 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 08:02:26.046  6282  6282 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 08:02:26.046  6282  6282 W System.err: android.os.DeadObjectException
08-05 08:02:26.046  6282  6282 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 08:02:26.046  6282  6282 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 08:02:26.046  6282  6282 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 08:02:26.046  6282  6282 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 08:02:26.046  6282  6282 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 08:02:26.046  6282  6282 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,08-05 08:02:26.046  6282  6282 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 08:02:26.046  6282  6282 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 08:02:26.047  6282  6282 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 08:02:26.047  6282  6282 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 08:02:26.047  6282  6282 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:02:26.047  6282  6282 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 08:02:26.047  6282  6282 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 08:02:26.047  6282  6282 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 08:02:26.047  6282  6282 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 08:02:26.047  6282  6282 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 08:02:26.178  1027  2036 W libprocessgroup: failed to open /acct/uid_1000/pid_6141/cgroup.procs: No such file or directory
08-05 08:02:26.178  1027  2036 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-05 08:02:26.182  6282  6282 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 08:02:26.182  6282  6282 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 08:02:26.198  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 08:02:26.198  5967  6060 I jxcore-log: 
,08-05 08:02:26.207  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 08:02:26.207  5967  6060 I jxcore-log: 
08-05 08:02:26.239  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 08:02:26.239  5967  6060 I jxcore-log: 
,08-05 08:02:26.247  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 08:02:26.247  5967  6060 I jxcore-log: 
,08-05 08:02:26.265  1027  2026 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7439 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 08:02:26.272  6282  6282 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 08:02:26.372  7439  7439 D UEI.SmartControl: Quickset Services start...
08-05 08:02:26.374  7439  7439 I UEI.SmartControl: Manufacture = LGE
08-05 08:02:26.375  7439  7439 D UEI.SmartControl: Id = LGNevo
08-05 08:02:26.378  7439  7439 D UEI.SmartControl: File observer start...
,08-05 08:02:26.380  7439  7439 E UEI.SmartControl: IR Port is disabled: false
,08-05 08:02:26.381  7439  7439 D UEI.SmartControl: Starting file observer...
08-05 08:02:26.381  7439  7439 D UEI.SmartControl: Extracting JNI libs...
,08-05 08:02:26.382  7439  7439 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-05 08:02:26.472  7439  7439 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 08:02:26.472  7439  7439 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 08:02:26.472  7439  7439 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 08:02:26.511  7439  7439 I UEI.SmartControl: --- Selecting new region: 6
,08-05 08:02:26.517  7439  7439 I UEI.SmartControl: Model = LG-D855
08-05 08:02:26.518  7439  7439 D UEI.SmartControl: QS Service created
,08-05 08:02:26.536  7439  7439 I UEI.SmartControl: Service initServices...
,08-05 08:02:26.549  7439  7439 D UEI.SmartControl: QS start get config
08-05 08:02:26.599  7439  7439 D UEI.SmartControl: Loading JNI Libs...
,08-05 08:02:26.800  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=35.8, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:2735] from screen [on:0 period:1498131568] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 08:02:26.800  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=35.8, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1498131568] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:26.800  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:02:26.851  7439  7439 I UEI.SmartControl: Supports setup maps: true
08-05 08:02:26.854  7439  7439 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 08:02:26.854  7439  7439 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 08:02:26.854  7439  7439 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 08:02:26.854  7439  7439 I UEI.SmartControl: ### init IR Blaster...
,08-05 08:02:26.859  7439  7439 D serial_port: Configuring serial port
08-05 08:02:26.862  7439  7439 E UEI.SmartControl: UEIBLaster setting for 616
08-05 08:02:26.862  7439  7439 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 08:02:26.862  7439  7439 I UEI.SmartControl: configuring settings for MAXQ616
08-05 08:02:26.862  7439  7439 I UEI.SmartControl: Get version...
08-05 08:02:26.879  7439  7463 D UEI.SmartControl: serial port data available: 21
,08-05 08:02:26.907  7439  7439 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 08:02:26.907  7439  7439 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 08:02:26.907  7439  7439 I UEI.SmartControl: QS saving settings...
08-05 08:02:26.908  7439  7439 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 08:02:26.925  7439  7463 D UEI.SmartControl: serial port data available: 4
,08-05 08:02:26.958  7439  7439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 08:02:26.969  7439  7466 I UEI.SmartControl: Device manager: loading config....
08-05 08:02:26.970  7439  7466 D UEI.SmartControl: ----------- loading internal config...
08-05 08:02:26.979  7439  7439 E UEI.SmartControl: Services init done
08-05 08:02:26.979  7439  7439 D UEI.SmartControl: QS Service init finished
08-05 08:02:26.982  7439  7439 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 08:02:26.982  7439  7439 D UEI.SmartControl: QS Service version code: 201091
08-05 08:02:26.983  7439  7439 D UEI.SmartControl: Service requested: Control
,08-05 08:02:26.987  7439  7466 E UEI.SmartControl: Loading SETTINGS...
08-05 08:02:26.988  7439  7439 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 08:02:26.991  1027  2317 I ActivityManager: Killing 6213:com.android.settings/1000 (adj 15): empty #17
08-05 08:02:26.995  6282  6282 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 08:02:26.995  7439  7454 I UEI.SmartControl: ------ IControl API: 11
08-05 08:02:26.996  7439  7454 I UEI.SmartControl: Registering callback...
08-05 08:02:27.001  7439  7466 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 08:02:27.006  7439  7455 I UEI.SmartControl: ------ IControl API: 19
08-05 08:02:27.008  7439  7455 I UEI.SmartControl: Registering Services Ready callback...
08-05 08:02:27.008  7439  7455 I UEI.SmartControl: Notify client services are ready...
,08-05 08:02:27.012  6282  6663 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 08:02:27.012  6282  6374 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 08:02:27.013  6282  6374 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 08:02:27.013  6282  6282 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 08:02:27.013  6282  6282 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 08:02:27.013  7439  7454 I UEI.SmartControl: ------ IControl API: 8
08-05 08:02:27.014  6282  6282 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 08:02:27.014  6282  6282 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 08:02:27.014  6282  6282 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 08:02:27.015  6282  6282 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 08:02:27.015  6282  6282 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 08:02:27.016  6282  6282 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 08:02:27.018  7439  7465 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 08:02:27.018  7439  7465 D UEI.SmartControl: -----service ready thread exits
08-05 08:02:27.018  6282  6298 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 08:02:27.024  6282  6374 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 08:02:27.024  6282  6374 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-05 08:02:27.063  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 08:02:27.063  5967  6060 I jxcore-log: 
,08-05 08:02:27.077  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-05 08:02:27.077  5967  6060 I jxcore-log: 
,08-05 08:02:27.087  1027  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_6213/cgroup.procs: No such file or directory
08-05 08:02:27.091  6282  6282 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-05 08:02:27.093  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 08:02:27.093  5967  6060 I jxcore-log: 
08-05 08:02:27.093  7439  7439 D UEI.SmartControl: Internal service binding...
08-05 08:02:27.094  6282  6282 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-05 08:02:27.094  6282  6282 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 08:02:27.095  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 08:02:27.095  6282  6282 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 08:02:27.095  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 08:02:27.097  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 08:02:27.097  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 08:02:27.097  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 08:02:27.097  6282  6282 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470376947097]
08-05 08:02:27.101  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 08:02:27.101  5967  6060 I jxcore-log: 
08-05 08:02:27.119  6282  7478 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 08:02:27.121  6282  6282 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-05 08:02:27.122  6282  6282 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 08:02:27.122  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 08:02:27.123  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 08:02:27.123  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 08:02:27.123  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-05 08:02:27.123  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 08:02:27.124  6282  6282 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-05 08:02:27.181  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 08:02:27.181  5967  6060 I jxcore-log: 
,08-05 08:02:27.250  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
08-05 08:02:27.250  5967  6060 I jxcore-log: 
,08-05 08:02:27.259  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 08:02:27.259  5967  6060 I jxcore-log: 
,08-05 08:02:27.545  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 08:02:27.545  5967  6060 I jxcore-log: 
,08-05 08:02:27.596  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 08:02:27.596  5967  6060 I jxcore-log: 
,08-05 08:02:27.608  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 08:02:27.608  5967  6060 I jxcore-log: 
08-05 08:02:27.615  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 08:02:27.615  5967  6060 I jxcore-log: 
08-05 08:02:27.642  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 08:02:27.642  5967  6060 I jxcore-log: 
,08-05 08:02:27.746  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 08:02:27.746  5967  6060 I jxcore-log: 
,08-05 08:02:27.764  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 08:02:27.764  5967  6060 I jxcore-log: 
,08-05 08:02:27.794  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 08:02:27.794  5967  6060 I jxcore-log: 
,08-05 08:02:27.825  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 08:02:27.825  5967  6060 I jxcore-log: 
,08-05 08:02:27.860  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 08:02:27.860  5967  6060 I jxcore-log: 
,08-05 08:02:27.926  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 08:02:27.926  5967  6060 I jxcore-log: 
,08-05 08:02:27.936  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 08:02:27.936  5967  6060 I jxcore-log: 
,08-05 08:02:27.990  1027  1960 I ActivityManager: Killing 7295:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 08:02:28.086  1027  1996 W libprocessgroup: failed to open /acct/uid_10011/pid_7295/cgroup.procs: No such file or directory
,08-05 08:02:28.176  5967  6060 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 08:02:28.176  5967  6060 I jxcore-log: 
,08-05 08:02:28.184  5967  6060 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-05 08:02:28.185  5967  6060 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 08:02:28.185  5967  6060 I jxcore-log: 
08-05 08:02:28.241  5967  6060 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:02:28.241  5967  6060 I jxcore-log: 
,08-05 08:02:29.810  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=28.4, 0.0, 0.0  rx=27.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1498134578] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 08:02:29.813  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=28.4, 0.0, 0.0  rx=27.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498134581] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:29.813  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:02:30.983  1597  1597 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 08:02:31.005  1027  1450 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 08:02:31.010  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-05 08:02:31.058  1027  1027 D administrator: Handling package changes for user 0
,08-05 08:02:31.131  1027  1085 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7511 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 08:02:31.149  1597  1597 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 08:02:31.150  1597  1597 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 08:02:31.161  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 08:02:31.197  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 08:02:31.197  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 08:02:31.206  7511  7511 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 08:02:31.252  1027  1084 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 08:02:31.258  1027  1084 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 08:02:31.263  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-05 08:02:31.264  7511  7511 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:31.264  7511  7511 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 08:02:31.266  2452  2452 V GmsNetworkLocationProvi: DISABLE
,08-05 08:02:31.303  1027  1084 D LocationProviderProxy: applying state to connected service
,08-05 08:02:31.305  2452  2452 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-05 08:02:31.362  7511  7542 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 08:02:31.363  7511  7542 I Babel   : MmsConfig.loadMmsSettings
08-05 08:02:31.371  7511  7542 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 08:02:31.372  7511  7542 I Babel   : MmsConfig.loadFromDatabase
,08-05 08:02:31.389  7511  7542 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 08:02:31.389  7511  7542 I Babel   : MmsConfig.loadFromResources
08-05 08:02:31.391  7511  7542 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 08:02:31.392  7511  7542 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 08:02:31.394  1027  1044 V SIM_STK : Menu title from STK is T-Mobile
08-05 08:02:31.407  1812  7250 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 08:02:31.408  7511  7511 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 08:02:31.410   306  7545 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 08:02:31.410   306  7545 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-05 08:02:31.410   306  7545 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 08:02:31.428  7511  7541 W AudioCapabilities: Unsupported mime audio/evrc
08-05 08:02:31.432  7511  7541 W AudioCapabilities: Unsupported mime audio/qcelp
,08-05 08:02:31.434  1812  7546 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 08:02:31.434  1812  7546 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 08:02:31.436  7511  7541 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 08:02:31.451  7511  7541 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-05 08:02:31.453  7511  7541 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 08:02:31.457  7511  7541 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 08:02:31.473  7511  7541 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-05 08:02:31.475  7511  7541 W VideoCapabilities: Unsupported mime video/divx
08-05 08:02:31.477  7511  7541 W VideoCapabilities: Unsupported mime video/divx311
08-05 08:02:31.480  1027  2093 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7550 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 08:02:31.485  1027  2093 I ActivityManager: Killing 6319:com.lge.formmanager/u0a26 (adj 15): empty #17
08-05 08:02:31.485  7511  7541 W VideoCapabilities: Unsupported mime video/divx4
08-05 08:02:31.492  7511  7541 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-05 08:02:31.517  7511  7541 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 08:02:31.520  7511  7541 W AudioCapabilities: Unsupported mime audio/eac3
,08-05 08:02:31.520  7511  7541 W AudioCapabilities: Unsupported mime audio/ac3
08-05 08:02:31.521  7511  7541 W AudioCapabilities: Unsupported mime audio/g726
08-05 08:02:31.522  7511  7541 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 08:02:31.522  7511  7541 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 08:02:31.523  7511  7541 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 08:02:31.524  7511  7541 W VideoCapabilities: Unsupported mime video/theora
08-05 08:02:31.525  7511  7541 W VideoCapabilities: Unsupported mime video/mjpg
,08-05 08:02:31.581  1027  1960 W libprocessgroup: failed to open /acct/uid_10026/pid_6319/cgroup.procs: No such file or directory
08-05 08:02:31.589  1812  4724 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-05 08:02:31.604  7550  7550 I AppUp4:AppBoxCP: onCreate
,08-05 08:02:31.605  7550  7550 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-05 08:02:31.611  7550  7550 I AppUp4:DB:  setFingerPrint start
08-05 08:02:31.611  7550  7550 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 08:02:31.617  7550  7550 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 08:02:31.617  7550  7550 I AppUp4:DB:  SDK version = 21
08-05 08:02:31.617  7550  7550 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-05 08:02:31.618  7550  7550 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-05 08:02:31.622  7550  7550 I AppUp4:CustModeStarterReceiver: onReceive
08-05 08:02:31.624  1812  7250 W ConfigFetchTask: bad response from server: 401 Unauthorized
08-05 08:02:31.626  1812  1812 I ConfigFetchService: fetch service done; releasing wakelock
08-05 08:02:31.627  1812  1812 I ConfigFetchService: stopping self
08-05 08:02:31.643  7550  7550 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:31.643  7550  7550 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:31.655  2233  2233 I ConfigService: onDestroy
08-05 08:02:31.658  7550  7550 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33e8240b
08-05 08:02:31.658  7550  7550 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 08:02:31.658  7550  7550 D AppUp4:CustFacade: isPhone : true
08-05 08:02:31.658  7550  7550 D AppUp4:CustModeStarterReceiver: begin check event
08-05 08:02:31.659  7550  7550 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 08:02:31.706  1027  1044 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7571 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-05 08:02:31.707  1027  1044 I ActivityManager: Killing 6725:com.android.chrome/u0a57 (adj 15): empty #17
,08-05 08:02:31.787  1027  1647 W libprocessgroup: failed to open /acct/uid_10057/pid_6725/cgroup.procs: No such file or directory
,08-05 08:02:31.837  7571  7571 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 08:02:31.838  7571  7571 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 08:02:31.839  7571  7571 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 08:02:31.842  7571  7571 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 08:02:31.843  7571  7571 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 08:02:31.951  7571  7571 I SystemConfig: BUILD Country: EU
08-05 08:02:31.951  7571  7571 I SystemConfig: BUILD Operator: OPEN
,08-05 08:02:31.956  7439  7467 D UEI.SmartControl: Internal timer expired: 1
,08-05 08:02:31.956  7439  7467 D UEI.SmartControl: unbind internal service
08-05 08:02:32.042  1027  1960 I ActivityManager: Killing 6752:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-05 08:02:32.079  1027  1043 W libprocessgroup: failed to open /acct/uid_10062/pid_6752/cgroup.procs: No such file or directory
,08-05 08:02:32.084  7439  7464 D serial_port: close(fd = 25)
08-05 08:02:32.090  7439  7464 I UEI.SmartControl: Serial port is closed.
08-05 08:02:32.132  1027  1960 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7596 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 08:02:32.156   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 26.508ms
,08-05 08:02:32.179   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 21.156ms
,08-05 08:02:32.188  7571  7594 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-05 08:02:32.189  7571  7594 I SystemConfig: existFile = false
08-05 08:02:32.189  7571  7594 I SystemConfig: canReadFile = false
08-05 08:02:32.189  7571  7594 I SystemConfig: systemFeature RCS result false
08-05 08:02:32.189  7571  7594 D SystemConfig: refreshRcsSupport() :false
08-05 08:02:32.198   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.595ms
,08-05 08:02:32.205  7596  7596 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 08:02:32.205  7596  7596 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 08:02:32.205  7596  7596 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-05 08:02:32.206  7596  7596 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 08:02:32.424  1027  1942 I art     : Explicit concurrent mark sweep GC freed 25663(1300KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.959ms total 116.372ms
,08-05 08:02:32.431  7596  7596 I AppConfig: Total System Memory = 2995761152
08-05 08:02:32.437  7596  7596 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-05 08:02:32.537  1027  1044 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7620 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 08:02:32.541  1027  1044 I ActivityManager: Killing 6810:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-05 08:02:32.753  1027  1647 W libprocessgroup: failed to open /acct/uid_10093/pid_6810/cgroup.procs: No such file or directory
,08-05 08:02:32.830  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=15.2, 0.0, 0.0  rx=14.9 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1498137598] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:32.832  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=15.2, 0.0, 0.0  rx=14.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1498137600] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:32.832  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:02:32.945  7620  7620 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 08:02:33.058  7620  7620 D LgDataFeature: LgDataFeature() Constructor: none
08-05 08:02:33.058  7620  7620 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 08:02:33.109  7620  7620 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 08:02:33.134  7620  7620 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 08:02:33.141  7620  7620 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 08:02:33.161  7620  7620 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 08:02:33.161  7620  7620 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-05 08:02:33.185  1027  2026 I ActivityManager: Killing 6873:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-05 08:02:33.249  1027  1905 W libprocessgroup: failed to open /acct/uid_10097/pid_6873/cgroup.procs: No such file or directory
,08-05 08:02:33.255  3431  4455 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 08:02:33.255  4567  7670 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-05 08:02:33.256  3431  4455 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@12ade on behalf of 7620
08-05 08:02:33.312  1027  1996 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7672 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 08:02:33.335  7620  7620 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 08:02:33.372  7620  7620 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-05 08:02:33.421  7672  7672 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 08:02:33.449  7672  7672 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 08:02:33.449  7672  7672 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 08:02:33.449  7672  7672 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 08:02:33.449  7672  7672 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 08:02:33.449  7672  7672 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 08:02:33.449  7672  7672 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 08:02:33.510  1027  1905 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7693 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-05 08:02:33.512  1027  1905 I ActivityManager: Killing 7322:com.lge.email/u0a23 (adj 15): empty #17
08-05 08:02:33.558  1027  1960 W libprocessgroup: failed to open /acct/uid_10023/pid_7322/cgroup.procs: No such file or directory
,08-05 08:02:33.606  7693  7693 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 08:02:33.726  1027  2093 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:02:33.751  4567  7670 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 495 ms] updated apps [took 495 ms] 
,08-05 08:02:33.803  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 08:02:33.803  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 08:02:33.813  1027  1538 D WifiController: battery changed pluggedType: 2
08-05 08:02:33.815  1961  2133 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 08:02:33.815  1961  2133 D LEDHandler: Battery Level Remaining: 100%
08-05 08:02:33.815  1961  2133 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
,08-05 08:02:33.817  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
,08-05 08:02:33.817  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 08:02:33.819  6937  6985 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 08:02:33.820  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 08:02:33.822  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:33.822  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:02:33.823  7138  7138 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 08:02:33.944  2233  2342 I art     : Explicit concurrent mark sweep GC freed 9142(577KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.650ms total 52.109ms
,08-05 08:02:35.851  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=14.1, 0.0, 0.0  rx=12.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498140619] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 08:02:35.861  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=14.1, 0.0, 0.0  rx=12.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498140622] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 08:02:35.862  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:02:38.881  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1498143649] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:38.884  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498143652] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:38.885  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:02:38.950  1027  1371 I ActivityManager: Killing 3748:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-05 08:02:38.988  1027  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_3748/cgroup.procs: No such file or directory
,08-05 08:02:39.282  1027  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{20bd758c type 2 when 192566 com.google.android.gms} when 192566
,08-05 08:02:39.301   306  7733 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 08:02:39.304   306  7733 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 08:02:39.304   306  7733 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 08:02:39.636  2233  7734 D GCM     : Connected
,08-05 08:02:39.674  2233  7734 D GCM     : Message class com.google.e.a.a.q
,08-05 08:02:41.905  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498146673] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:41.916  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1498146684] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:41.916  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:02:43.455  1027  1533 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-05 08:02:43.464  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-05 08:02:43.466  1027  1533 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 08:02:43.468  1027  1533 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 08:02:43.469  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 08:02:43.470  1027  1533 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 08:02:44.940  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498149708] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:44.943  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498149711] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:02:44.943  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:02:47.963  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498152731] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:47.973  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1498152741] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:47.974  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:02:50.995  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498155763] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:51.008  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1498155776] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:51.012  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:02:54.030  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1498158798] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:54.033  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498158801] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:02:54.033  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:02:57.057  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498161825] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:02:57.060  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498161828] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:02:57.061  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:02:59.770  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 08:02:59.770  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 08:02:59.770  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 08:02:59.771  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-05 08:02:59.784  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 08:02:59.785  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:02:59.788  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:02:59.793  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 08:03:00.057  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 08:03:00.057  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 08:03:00.058  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 08:03:00.058  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-05 08:03:00.072  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 08:03:00.072  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:03:00.074  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:03:00.078  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 08:03:00.084  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1498164852] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:00.085  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1498164853] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:00.085  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:03:00.777  1027  1533 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 08:03:00.779  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 08:03:00.780  1027  1533 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 08:03:00.781  1027  1533 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 08:03:00.782  1027  1533 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 08:03:00.783  1027  1533 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-05 08:03:03.101  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498167869] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:03.104  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498167872] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:03.104  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:06.130  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498170898] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:06.133  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498170901] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:06.134  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:09.157  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498173924] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:09.160  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498173927] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:09.160  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:09.686  1027  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=302453300, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-05 08:03:09.696  1027  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{20c3e4d5 type 2 when 224216 com.google.android.gms} when 224216
08-05 08:03:09.738  2640  2640 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 08:03:09.766  1812  1812 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-05 08:03:09.771  2233  2233 I ConfigService: onCreate
08-05 08:03:09.772  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 08:03:09.786  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=302453300 [*alarm*], flags=0x0
,08-05 08:03:09.793  1812  7735 I ConfigFetchService: running network task: configservice_periodic
08-05 08:03:09.797  1812  7735 I ConfigFetchService: launchTask
08-05 08:03:09.801  2233  2233 I ConfigService: onBind returning update interface
,08-05 08:03:09.805  1812  1812 I ConfigFetchService: service connected
08-05 08:03:09.805  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 08:03:09.805  2233  2233 I ConfigService: onBind returning config service
08-05 08:03:09.807  1812  1812 I ConfigClient: service connected
08-05 08:03:09.878  1027  1925 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:03:09.891  1812  2355 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 08:03:09.894   306  7751 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 08:03:09.895   306  7751 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-05 08:03:09.934   306  7751 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 08:03:10.378  1812  2355 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-05 08:03:10.389  1812  1812 I ConfigFetchService: fetch service done; releasing wakelock
08-05 08:03:10.393  1812  1812 I ConfigFetchService: stopping self
08-05 08:03:10.432  2233  2233 I ConfigService: onDestroy
,08-05 08:03:12.183  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498176951] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:12.193  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498176954] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:12.193  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:03:15.212  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=7.4, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498179980] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:03:15.215  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=7.4, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498179983] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 08:03:15.215  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:18.239  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498183007] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:18.242  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498183010] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:18.242  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:21.267  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498186035] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:21.270  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498186038] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:21.271  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:24.298  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498189066] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
08-05 08:03:24.301  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498189069] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:24.301  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:27.325  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498192092] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:27.336  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1498192104] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:27.336  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:03:30.358  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498195126] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:30.361  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498195129] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:30.361  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:33.387  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498198155] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:33.390  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498198158] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:33.390  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:36.417  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498201184] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:36.420  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498201187] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:36.420  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:39.444  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498204212] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:39.455  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1498204222] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:39.455  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:03:42.476  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498207243] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:42.488  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1498207256] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:42.488  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:03:45.512  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1498210280] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:45.515  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498210283] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:45.515  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:48.543  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1498213311] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:48.553  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498213314] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:48.554  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:03:51.572  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498216340] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:51.575  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498216343] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:51.575  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:54.600  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498219368] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:54.603  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498219371] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:54.603  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:57.623  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498222390] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:03:57.626  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498222393] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:03:57.626  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:03:59.091  1027  1380 V AlarmManager: RTC_WAKEUP set : Alarm{224f59bc type 0 when 1470376991485 com.google.android.gms} when 1470376991485
08-05 08:03:59.092  1027  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2c88ad45 type 2 when 253179 android} when 253179
,08-05 08:03:59.118  1812  2371 I EventLogService: Aggregate from 1470376941293 (log), 1470375191389 (data)
,08-05 08:04:00.055  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 08:04:00.055  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 08:04:00.055  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 08:04:00.056  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-05 08:04:00.071  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 08:04:00.071  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
,08-05 08:04:00.073  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
,08-05 08:04:00.075  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 08:04:00.655  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498225422] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:00.667  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1498225435] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:00.668  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:03.689  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498228457] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:03.692  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498228460] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:03.693  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:06.714  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498231482] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:06.725  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1498231493] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:06.726  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:09.748  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498234515] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:09.750  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498234518] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:09.751  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:10.404  1027  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=302453300, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-05 08:04:10.418  1027  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3fd0a9cb type 2 when 284932 com.google.android.gms} when 284932
08-05 08:04:10.474  2640  2640 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 08:04:10.507  1812  1812 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-05 08:04:10.524  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=302453300 [*alarm*], flags=0x0
,08-05 08:04:10.530  2233  2233 I ConfigService: onCreate
08-05 08:04:10.531  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 08:04:10.533  1812  7764 I ConfigFetchService: running network task: configservice_periodic
08-05 08:04:10.539  1812  7764 I ConfigFetchService: launchTask
,08-05 08:04:10.545  2233  2233 I ConfigService: onBind returning update interface
08-05 08:04:10.547  1812  1812 I ConfigFetchService: service connected
08-05 08:04:10.547  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 08:04:10.547  2233  2233 I ConfigService: onBind returning config service
08-05 08:04:10.548  1812  1812 I ConfigClient: service connected
08-05 08:04:10.615  1027  1371 V SIM_STK : Menu title from STK is T-Mobile
,08-05 08:04:10.638  1812  3970 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 08:04:10.642   306  7782 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 08:04:10.642   306  7782 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-05 08:04:10.643   306  7782 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-05 08:04:10.888  1812  3970 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-05 08:04:10.891  1812  1812 I ConfigFetchService: fetch service done; releasing wakelock
,08-05 08:04:10.894  1812  1812 I ConfigFetchService: stopping self
08-05 08:04:10.933  2233  2233 I ConfigService: onDestroy
,08-05 08:04:12.776  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498237544] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:12.779  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498237547] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:12.780  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:15.804  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498240571] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:15.814  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1498240581] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:15.814  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:04:18.837  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1498243605] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:18.840  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498243608] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:18.840  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:21.865  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498246633] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:21.876  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1498246643] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:21.876  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:04:24.898  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498249666] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:24.901  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498249669] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:24.901  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:27.927  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498252695] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:27.930  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498252698] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:27.930  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:30.958  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498255725] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:30.961  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498255728] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:30.961  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:33.988  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498258755] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:33.991  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498258758] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:33.991  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:34.139  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 08:04:34.140  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 08:04:34.164  1027  1538 D WifiController: battery changed pluggedType: 2
,08-05 08:04:34.168  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-05 08:04:34.168  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 08:04:34.170  1961  2133 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 08:04:34.170  1961  2133 D LEDHandler: Battery Level Remaining: 100%
08-05 08:04:34.170  1961  2133 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
08-05 08:04:34.172  6937  6985 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 08:04:34.174  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 08:04:34.175  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 08:04:34.176  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:04:34.177  7138  7138 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 08:04:37.017  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498261785] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:37.021  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498261788] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:37.021  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:40.047  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498264814] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:40.050  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1498264818] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:40.050  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:43.077  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498267845] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:43.080  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498267848] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:43.080  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:46.107  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498270875] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:46.110  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498270878] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:46.110  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:49.138  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498273906] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:49.139  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1498273907] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:49.139  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:52.150  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:1498276918] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:52.154  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498276921] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:52.154  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:55.180  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498279948] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:55.183  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498279951] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:55.183  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:04:58.202  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498282969] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:04:58.205  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498282972] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:04:58.205  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:00.054  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 08:05:00.054  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 08:05:00.054  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 08:05:00.055  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-05 08:05:00.069  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 08:05:00.069  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
,08-05 08:05:00.071  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:05:00.073  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 08:05:00.229  1027  3489 I LocationManagerService: remove 14ade682
,08-05 08:05:00.241  1027  3489 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-05 08:05:00.241  1027  3489 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-05 08:05:00.244  1027  3489 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-05 08:05:00.248  1027  3489 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,08-05 08:05:00.256  1027  3489 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-05 08:05:01.228  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498285995] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 08:05:01.240  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1498286007] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 08:05:01.240  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:04.256  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498289023] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:04.268  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1498289036] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:04.268  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:07.287  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498292055] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:07.291  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498292058] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:07.291  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:10.315  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498295083] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:10.325  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1498295093] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:10.325  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:11.020  1027  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=302453300, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-05 08:05:11.070  2640  2640 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 08:05:11.102  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=302453300 [*alarm*], flags=0x0
,08-05 08:05:13.347  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498298115] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:13.350  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498298118] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:13.350  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:16.378  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498301146] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:16.382  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498301149] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:16.382  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:19.405  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498304172] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:19.414  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1498304182] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:19.415  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:22.435  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498307203] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:22.447  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1498307215] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:22.447  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:25.460  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498310227] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:25.463  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1498310231] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:25.463  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:28.484  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498313252] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:28.495  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1498313263] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:28.495  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:31.519  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1498316286] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:31.531  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1498316299] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:31.532  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:34.548  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498319316] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:34.551  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498319319] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:34.551  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:37.577  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498322345] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:37.580  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498322348] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:37.580  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:40.605  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498325373] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:40.620  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1498325387] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:40.620  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:43.639  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498328407] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:43.642  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498328410] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:43.642  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:46.670  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498331437] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:46.673  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498331440] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:46.673  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:49.698  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1498334465] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:49.701  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498334468] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:49.701  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:52.724  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1498337492] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:52.735  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1498337503] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:52.735  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:05:55.757  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498340524] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:55.760  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1498340527] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:05:55.760  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:05:58.784  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1498343552] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:58.794  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1498343561] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 08:05:58.794  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 08:06:00.054  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 08:06:00.054  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 08:06:00.054  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 08:06:00.055  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-05 08:06:00.069  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 08:06:00.069  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:06:00.071  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-05 08:06:00.073  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 08:06:00.365  5967  6060 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-05 08:06:00.365  5967  6060 I jxcore-log: 
,08-05 08:06:00.678  7808  7808 D AndroidRuntime: 
08-05 08:06:00.678  7808  7808 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 08:06:00.685  7808  7808 D AndroidRuntime: CheckJNI is OFF
08-05 08:06:00.817  7808  7808 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 08:06:00.837  1027  1085 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-05 08:06:00.837  1027  1085 I ActivityManager: Killing 5967:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-05 08:06:00.904  1027  1771 I WindowState: WIN DEATH: Window{125ceb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 08:06:00.905  1027  1538 D WifiService: Client connection lost with reason: 4
,08-05 08:06:00.914  1027  1771 D InputDispatcher: Window went away: Window{125ceb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 08:06:01.054  1027  1085 I ActivityManager:   Force finishing activity ActivityRecord{1fcb7205 u0 com.test.thalitest/.MainActivity t40}
,08-05 08:06:01.095   329   367 E GBMv2   : DFP En is all cleared set to be enabled
,08-05 08:06:01.100  1961  3935 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-05 08:06:01.100  1961  3935 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2a905ce4 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 08:06:01.102  1961  1976 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 08:06:01.102  1961  1976 D SplitWindowPolicy: topRunningActivity=ActivityInfo{181d354d co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 08:06:01.103  1027  1996 W ActivityManager: Spurious death for ProcessRecord{2f3bc04a 5967:com.test.thalitest/u0a118}, curProc for 5967: null
,08-05 08:06:01.118  1027  1110 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-05 08:06:01.119  2082  2082 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 08:06:01.121  2082  2082 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-05 08:06:01.144  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-05 08:06:01.144  2082  2169 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-05 08:06:01.146  1597  1597 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 08:06:01.154  1027  1450 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 08:06:01.167  2452  2579 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 08:06:01.169  3717  3717 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-05 08:06:01.169  2024  2024 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 08:06:01.174  6937  6937 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 08:06:01.174  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 08:06:01.213  4567  4567 I art     : Explicit concurrent mark sweep GC freed 8118(468KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 540us total 86.582ms
,08-05 08:06:01.230  4456  4456 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 08:06:01.230  4456  4456 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 08:06:01.230  4456  4456 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 08:06:01.230  4456  4456 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-05 08:06:01.230  4456  4456 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 08:06:01.230  4456  4456 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 08:06:01.230  4456  4456 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 08:06:01.230  4456  4456 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 08:06:01.230  4456  4456 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:06:01.230  4456  4456 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 08:06:01.230  4456  4456 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 08:06:01.230  4456  4456 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-05 08:06:01.262  1888  1888 D SplitUIManager: split_name #11 / not available #0
08-05 08:06:01.262  1888  1888 D SplitUIService: removed split : 
,08-05 08:06:01.264  1027  1085 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7839 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 08:06:01.267  2082  2082 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 08:06:01.268  2082  2082 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-05 08:06:01.270  1923  1923 D ActionManagerService: notifyUserLog: 1000003
08-05 08:06:01.270  3717  4445 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-05 08:06:01.273  2082  2082 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-05 08:06:01.273  1027  2026 V SIM_STK : Menu title from STK is T-Mobile
08-05 08:06:01.274  1597  1597 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-05 08:06:01.275  1597  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 08:06:01.275  1597  1649 D KeyguardModel: createShortcutInfo...
,08-05 08:06:01.277  2082  2082 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-05 08:06:01.278  1597  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 08:06:01.278  1597  1649 D KeyguardModel: createShortcutInfo...
08-05 08:06:01.281  1923  1923 D ActionManagerService: notifyUserLog: 1000004
08-05 08:06:01.281  2082  2082 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 08:06:01.281  3717  4445 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-05 08:06:01.282  1597  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 08:06:01.283  1597  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 08:06:01.283  1597  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 08:06:01.284  1597  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 08:06:01.287  1597  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 08:06:01.287  1597  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-05 08:06:01.289  3717  3732 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 08:06:01.289  1597  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 08:06:01.289  1597  1649 D KeyguardModel: createShortcutInfo...
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , expire_time: 0
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , display: false
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , animation: false }
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , expire_time: 0
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , display: false
08-05 08:06:01.291  2082  2082 I GBoardWebViewUtils: , animation: false }
08-05 08:06:01.292  2082  2082 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-05 08:06:01.292  2082  2082 I GBoardWebViewUtils: , create_time: 1469801565454
08-05 08:06:01.292  2082  2082 I GBoardWebViewUtils: , expire_time: 0
08-05 08:06:01.292  2082  2082 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 08:06:01.292  2082  2082 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 08:06:01.292  2082  2082 I GBoardWebViewUtils: , display: false
08-05 08:06:01.292  2082  2082 I GBoardWebViewUtils: , animation: false }
08-05 08:06:01.293  1597  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 08:06:01.293  1597  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 08:06:01.294  1597  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 08:06:01.294  1597  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 08:06:01.304  1597  1597 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 08:06:01.304  1597  1597 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-05 08:06:01.305  1597  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 08:06:01.305  1597  1649 D KeyguardModel: createShortcutInfo...
,08-05 08:06:01.310  1597  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 08:06:01.310  1597  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 08:06:01.310  1597  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 08:06:01.310  1597  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 08:06:01.311  1597  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 08:06:01.311  1597  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 08:06:01.312  1597  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 08:06:01.312  1597  1649 D KeyguardModel: createShortcutInfo...
08-05 08:06:01.317  2082  7852 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-05 08:06:01.325  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 08:06:01.325  2082  2082 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 08:06:01.329  1597  1597 D KeyguardModel: handleShortcutListChanged...
08-05 08:06:01.329  1597  1597 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-05 08:06:01.333  1597  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 08:06:01.333  1597  1649 D KeyguardModel: createShortcutInfo...
08-05 08:06:01.335  1027  1044 V SIM_STK : Menu title from STK is T-Mobile
08-05 08:06:01.335  1027  1044 V SIM_STK : Menu title from STK is T-Mobile
08-05 08:06:01.335  1888  1888 D SplitUIManager: split_name #11 / not available #0
08-05 08:06:01.335  1888  1888 I SplitUIService: split app #11
08-05 08:06:01.336  1597  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 08:06:01.336  1597  1649 D KeyguardModel: createShortcutInfo...
08-05 08:06:01.337  1597  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 08:06:01.337  1597  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 08:06:01.338  1597  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 08:06:01.338  1597  1649 D KeyguardModel: createShortcutInfo...
08-05 08:06:01.340  1597  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 08:06:01.340  1597  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-05 08:06:01.346  1597  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 08:06:01.346  1597  1649 D KeyguardModel: createShortcutInfo...
08-05 08:06:01.349  1597  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 08:06:01.349  1597  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 08:06:01.351  1597  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 08:06:01.351  1597  1649 D KeyguardModel: createShortcutInfo...
,08-05 08:06:01.395  1027  1905 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 08:06:01.397  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 08:06:01.397  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 08:06:01.397  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 08:06:01.397  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 08:06:01.397  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 08:06:01.397  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 08:06:01.398  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 08:06:01.398  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 08:06:01.398  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 08:06:01.398  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 08:06:01.398  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 08:06:01.417  1597  1597 D KeyguardModel: handleShortcutListChanged...
08-05 08:06:01.417  1597  1597 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 08:06:01.418  2082  2082 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-05 08:06:01.427  7839  7839 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 08:06:01.448  1027  1371 V SIM_STK : Menu title from STK is T-Mobile
08-05 08:06:01.448  2082  2098 I art     : Background partial concurrent mark sweep GC freed 6961(315KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 5.591ms total 39.121ms
,08-05 08:06:01.450  1027  1027 I art     : Explicit concurrent mark sweep GC freed 87036(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.987ms total 306.431ms
08-05 08:06:01.450  1027  1110 I art     : WaitForGcToComplete blocked for 181.305ms for cause Explicit
08-05 08:06:01.457  1027  1084 W InputMethodInfo: Duplicated subtype definition found: , voice
08-05 08:06:01.459  7839  7839 D PluginManager: init()
,08-05 08:06:01.477  1027  1027 D administrator: Handling package changes for user 0
08-05 08:06:01.511  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-05 08:06:01.514  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 08:06:01.516  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 08:06:01.518  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-05 08:06:01.519  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-05 08:06:01.520  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-05 08:06:01.540  1027  1090 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39247e9d u0 com.lge.launcher2/.Launcher t39} time:396084
08-05 08:06:01.547  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 08:06:01.547  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 08:06:01.556  2082  2289 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-05 08:06:01.556  2082  2289 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-05 08:06:01.572  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-05 08:06:01.572  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 08:06:01.573  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 08:06:01.573  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 08:06:01.573  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 08:06:01.573  1027  1027 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 08:06:01.574  1027  1572 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-05 08:06:01.580  2082  2082 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-05 08:06:01.581  2640  2640 D [Concierge]Service: onStartCommand(). Type : 8
08-05 08:06:01.581  2640  2640 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 08:06:01.584  2640  2640 D [Concierge]Service: Update widget ID : 11
08-05 08:06:01.584  2082  2082 D [Concierge]WidgetView: change position of spinner
08-05 08:06:01.585  2640  2640 D [Concierge]Service: onStartCommand(). Type : 0
08-05 08:06:01.585  2082  2082 I [Concierge]WidgetView: initWebView(). Time : 1470377161585
08-05 08:06:01.602  1027  1110 I art     : Explicit concurrent mark sweep GC freed 7895(480KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.919ms total 151.611ms
,08-05 08:06:01.604  2082  2082 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 163181701
08-05 08:06:01.604  2082  2082 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 08:06:01.604  2082  2082 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 08:06:01.607  2082  2082 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@181dd049
08-05 08:06:01.607  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-05 08:06:01.608  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 08:06:01.608  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 08:06:01.612  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-05 08:06:01.613  2082  2082 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 08:06:01.613  2082  2082 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 08:06:01.613  2082  2082 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470376793764, New one : 1470377161585
08-05 08:06:01.613  2082  2082 D [Concierge]WidgetView: Unregister all receivers
08-05 08:06:01.613  2082  2082 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-05 08:06:01.614   323   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 08:06:01.615  3142  7862 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-05 08:06:01.616  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 08:06:01.617  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 08:06:01.618  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-05 08:06:01.619  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 08:06:01.620  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 08:06:01.621  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-05 08:06:01.625  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 08:06:01.625  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 08:06:01.663  2082  2082 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-05 08:06:01.672  2082  2082 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 08:06:01.672  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-05 08:06:01.677  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 08:06:01.693  1027  1084 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 08:06:01.696  1027  1084 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 08:06:01.700  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 08:06:01.703  2082  2082 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11574916 time:396247
08-05 08:06:01.706  7808  7808 D AndroidRuntime: Shutting down VM
08-05 08:06:01.735  1027  1110 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7863 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 08:06:01.770  7839  7839 W ExternalStrings: load override strings
08-05 08:06:01.770  7839  7839 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 08:06:01.770  7839  7839 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 08:06:01.771  7839  7839 D StatusProvider: onCreate
,08-05 08:06:01.775  1027  1044 I ActivityManager: Killing 7390:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-05 08:06:01.814  1027  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1498346582] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:06:01.814  1027  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1498346582] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 08:06:01.814  1027  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 08:06:01.821  2082  2082 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-05 08:06:01.855  2082  2864 I GBoardtInterface: onReloaded()
,08-05 08:06:01.856  1027  1371 W libprocessgroup: failed to open /acct/uid_1000/pid_7390/cgroup.procs: No such file or directory
08-05 08:06:01.857  2082  2082 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-05 08:06:01.858  3717  3732 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 08:06:01.860  3717  3733 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 08:06:01.865  1923  1923 D ActionManagerService: notifyUserLog: 1000001
08-05 08:06:01.865  3717  4445 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 08:06:01.866  3717  4445 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 08:06:01.868  1923  1923 D ActionManagerService: notifyUserLog: 1000001
,08-05 08:06:01.869  3717  4445 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 08:06:01.869  3717  4445 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 08:06:01.869  3717  4445 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-05 08:06:01.869  3717  4445 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 08:06:01.870  3717  3732 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 08:06:01.872  2082  2082 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 08:06:01.872  2082  2082 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 08:06:01.873  2082  2082 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 08:06:01.873  2082  2082 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 08:06:01.875  2082  2082 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 08:06:01.875  2082  2082 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 08:06:01.895  7839  7839 V Signer  : override build config not found
,08-05 08:06:01.895  7839  7839 D Signer  : value of property debug is false
08-05 08:06:01.916  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-05 08:06:01.916  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-05 08:06:01.917  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-05 08:06:01.917  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-05 08:06:01.917  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-05 08:06:01.917  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-05 08:06:01.917  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-05 08:06:01.917  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-05 08:06:01.918  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-05 08:06:01.918  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-05 08:06:01.918  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-05 08:06:01.918  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-05 08:06:01.918  7839  7839 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-05 08:06:01.925  7839  7839 V LGMDMManager: Create singleton instance
08-05 08:06:01.959  7839  7839 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-05 08:06:01.992  7839  7839 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 08:06:01.993  1027  2093 I ActivityManager: Killing 7408:com.android.calendar/u0a13 (adj 15): empty #17

```
