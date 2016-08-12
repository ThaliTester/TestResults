#### Test 80912877664003a_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 09:20:47.390  6735  6735 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
08-12 09:20:47.438  1027  1769 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6767 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-12 09:20:47.439  1027  1769 I ActivityManager: Killing 6255:com.android.vending/u0a44 (adj 15): empty #17
08-12 09:20:47.492  1027  1988 W libprocessgroup: failed to open /acct/uid_10044/pid_6255/cgroup.procs: No such file or directory
08-12 09:20:47.525  6767  6767 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:20:47.526  6767  6767 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 09:20:47.526  6767  6767 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 09:20:47.526  6767  6767 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 09:20:47.629  6767  6767 I AppConfig: Total System Memory = 2995761152
08-12 09:20:47.640  6767  6767 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-12 09:20:47.683  1027  1728 I ActivityManager: Killing 6304:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-12 09:20:47.742  1027  1930 W libprocessgroup: failed to open /acct/uid_10080/pid_6304/cgroup.procs: No such file or directory
08-12 09:20:47.745  1987  1987 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-12 09:20:47.745  1987  1987 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 09:20:47.747  1987  1987 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 09:20:47.778  6621  6621 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-12 09:20:47.784  6621  6621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-12 09:20:47.843  1027  1991 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6790 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-12 09:20:48.078  6790  6790 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-12 09:20:48.196  6790  6790 D LgDataFeature: LgDataFeature() Constructor: none
08-12 09:20:48.197  6790  6790 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 09:20:48.268  6790  6790 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-12 09:20:48.288  6790  6790 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-12 09:20:48.291  6790  6790 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-12 09:20:48.309  6790  6790 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-12 09:20:48.309  6790  6790 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-12 09:20:48.322  1027  2024 I ActivityManager: Killing 6054:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-12 09:20:48.481  6823  6823 D AndroidRuntime: 
08-12 09:20:48.481  6823  6823 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 09:20:48.486  6823  6823 D AndroidRuntime: CheckJNI is OFF
08-12 09:20:48.527  1027  1769 W libprocessgroup: failed to open /acct/uid_10097/pid_6054/cgroup.procs: No such file or directory
08-12 09:20:48.533  5080  6838 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 09:20:48.578  1027  1930 V SIM_STK : Menu title from STK is T-Mobile
08-12 09:20:48.578  1027  2024 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6850 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-12 09:20:48.583  3224  4225 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-12 09:20:48.590  3224  4225 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@c71ab32 on behalf of 6790
08-12 09:20:48.607  6790  6790 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-12 09:20:48.623  6790  6790 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-12 09:20:48.637  6823  6823 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 09:20:48.641  1027  1959 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 09:20:48.653  1931  1947 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 09:20:48.656  1027  1959 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 09:20:48.657  1027  1959 D ActivityManager: setTaskToReturnTo : TaskRecord{be50ce5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 09:20:48.657  1027  1959 D ActivityManager: setTaskToReturnTo : TaskRecord{be50ce5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 09:20:48.658  1027  1959 D WindowStateEx: AppWindowTokenEx init.. 
08-12 09:20:48.658   336   355 E GBMv2   : DFP En is all cleared set to be enabled
08-12 09:20:48.712  1027  1959 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6874 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 09:20:48.716  6823  6823 D AndroidRuntime: Shutting down VM
08-12 09:20:48.740  5080  6838 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
08-12 09:20:48.784  1931  1947 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 09:20:48.784  1931  1947 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d830ec0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 09:20:48.785  1931  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 09:20:48.786  1931  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{27cbf7f9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 09:20:48.829  6850  6850 D DocsApplication: Installing DEX configuration.
08-12 09:20:48.830  6874  6874 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 09:20:48.846  6850  6850 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-12 09:20:48.849  6850  6850 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{13ed3604 com.google.android.apps.docs}
08-12 09:20:48.864  6850  6850 D TAG     : onCreate()
08-12 09:20:48.878  6850  6850 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-12 09:20:48.900  6874  6874 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-12 09:20:48.907  6874  6874 I LibraryLoader: Loading: webviewchromium
08-12 09:20:48.909  6874  6874 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5126-5129)
08-12 09:20:48.910  6874  6874 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 09:20:48.928  6874  6874 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38a4026e}
,08-12 09:20:48.930  6874  6874 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 09:20:48.931  6874  6874 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 09:20:48.940  6874  6874 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 09:20:48.941  6874  6874 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:20:48.949  6874  6874 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 09:20:48.949  6874  6874 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 09:20:48.950  6874  6874 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 09:20:48.961   307  2144 V AudioPolicyService: registerClient() client 0xb1427160, uid 10118
,08-12 09:20:48.969  1027  1090 D BluetoothManagerService: Message: 20
08-12 09:20:48.969  1027  1090 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c10b1e0:true
08-12 09:20:48.972  6874  6874 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 09:20:48.972  6874  6874 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 09:20:48.972  6874  6874 I Adreno-EGL: Build Date: 12/12/14 금
08-12 09:20:48.972  6874  6874 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 09:20:48.972  6874  6874 I Adreno-EGL: Remote Branch: 
08-12 09:20:48.972  6874  6874 I Adreno-EGL: Local Patches: 
08-12 09:20:48.972  6874  6874 I Adreno-EGL: Reconstruct Branch: 
,08-12 09:20:49.071  6874  6904 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 09:20:49.073  6874  6874 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 09:20:49.088  6874  6874 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:20:49.091  6874  6874 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 09:20:49.094  6874  6874 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 09:20:49.097  6874  6874 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 09:20:49.097  6874  6874 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 09:20:49.108  6874  6874 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 09:20:49.114  6874  6874 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:20:49.114  6874  6874 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 09:20:49.147  6874  6919 D OpenGLRenderer: Render dirty regions requested: true
08-12 09:20:49.147  6874  6919 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 09:20:49.151  6874  6919 D OpenGLRenderer: Enabling debug mode 0
08-12 09:20:49.166  6874  6874 D Atlas   : Validating map...
,08-12 09:20:49.173  1027  1633 D SplitWindow: check instance of lgWin Window{206e571a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 09:20:49.204  6874  6917 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 09:20:49.205  6874  6917 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 09:20:49.302  1027  1091 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +519ms (total +642ms)
08-12 09:20:49.302  1027  1091 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{389273ba u0 com.test.thalitest/.MainActivity t6} time:105522
,08-12 09:20:49.303  6874  6874 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e9bc415 time:105523
08-12 09:20:49.422  6874  6874 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 09:20:49.422  6874  6874 I chromium: 
,08-12 09:20:49.443  6874  6874 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 09:20:49.538  6874  6917 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 09:20:49.538  6874  6917 I chromium: 
,08-12 09:20:49.664  6874  6929 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-12 09:20:49.675  6874  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 09:20:49.675  6874  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 09:20:49.675  6874  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 09:20:49.675  6874  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 09:20:49.675  6874  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 09:20:49.675  6874  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22703cc9 added. We now have 1 listener(s)
08-12 09:20:49.680  1027  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 09:20:49.683  6874  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 09:20:49.684  6874  6929 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-12 09:20:49.686  6874  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 09:20:49.686  6874  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 09:20:49.695  6874  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b27bdfc added. We now have 1 listener(s)
,08-12 09:20:49.696  6874  6929 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 09:20:49.699  1027  1535 D WifiService: New client listening to asynchronous messages
08-12 09:20:49.704  6874  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 09:20:49.704  6874  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 09:20:49.704  6874  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 09:20:49.705  6874  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 09:20:49.705  6874  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 09:20:49.708  6874  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 09:20:49.709  1027  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 09:20:49.710  6874  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 09:20:49.717  6874  6929 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:20:49.718  6874  6929 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 09:20:49.718  6874  6929 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 09:20:49.718  6874  6929 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 09:20:49.719  6874  6929 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 09:20:49.720  6874  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 09:20:49.722  6874  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 09:20:49.751  6874  6874 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-12 09:20:49.760  1808  5161 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-12 09:20:49.814  1808  5161 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-12 09:20:49.887  1808  5161 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-12 09:20:50.122  6850  6850 D LgDataFeature: LgDataFeature() Constructor: none
08-12 09:20:50.123  6850  6850 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 09:20:50.352  6874  6932 W jxcore-log: Initializing JXcore engine
08-12 09:20:50.352  6874  6932 W jxcore-log: JXcore engine is ready
,08-12 09:20:50.388  1027  1969 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6947 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-12 09:20:50.389  1027  1969 I ActivityManager: Killing 5676:com.lge.bnr/1000 (adj 15): empty #17
08-12 09:20:50.441  6932  6932 W Thread-816: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9361]" dev="sockfs" ino=9361 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 09:20:50.441  6932  6932 W Thread-816: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 09:20:50.441  6932  6932 W Thread-816: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8388]" dev="sockfs" ino=8388 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 09:20:50.441  6932  6932 W Thread-816: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 09:20:50.441  6932  6932 W Thread-816: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32996]" dev="sockfs" ino=32996 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-12 09:20:50.472  6874  6932 W jxcore-log: Starting JXcore engine
,08-12 09:20:50.477  1027  1988 W libprocessgroup: failed to open /acct/uid_1000/pid_5676/cgroup.procs: No such file or directory
,08-12 09:20:50.497  6850  6850 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-12 09:20:50.507   336   357 E GBMv2   : DFP En is all cleared set to be enabled
08-12 09:20:50.507   336   357 E GBMv2   : Set value is all cleared set the max
08-12 09:20:50.507   336   357 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 09:20:50.528  6947  6947 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-12 09:20:50.550  6947  6947 I LockScreenSettings: New app installed broadcast received ..
,08-12 09:20:50.557  6947  6947 I LockScreenSettings: Number of installed packages  1
08-12 09:20:50.583  6874  6932 W jxcore-log: Platform android
08-12 09:20:50.583  6874  6932 W jxcore-log: 
08-12 09:20:50.583  6874  6932 W jxcore-log: Process ARCH arm
08-12 09:20:50.583  6874  6932 W jxcore-log: 
,08-12 09:20:50.637  1027  1949 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6974 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-12 09:20:50.753  6874  6932 I jxcore-log: JXcore Cordova bridge is ready!
08-12 09:20:50.753  6874  6932 I jxcore-log: 
08-12 09:20:50.753  6874  6932 W jxcore-log: JXcore engine is started
,08-12 09:20:50.761  6874  6929 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 09:20:50.764  6874  6874 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 09:20:50.823  1027  1959 I art     : Explicit concurrent mark sweep GC freed 24553(1242KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.927ms total 125.124ms
,08-12 09:20:50.825  1027  1040 I art     : WaitForGcToComplete blocked for 93.372ms for cause HeapTrim
08-12 09:20:50.855  6974  6974 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 09:20:51.179  1027  1042 V SIM_STK : Menu title from STK is T-Mobile
,08-12 09:20:51.226  1027  1769 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-12 09:20:51.317  7006  7006 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-12 09:20:51.317  7006  7006 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-12 09:20:51.362  1027  1633 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7028 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-12 09:20:51.364  1027  1633 I ActivityManager: Killing 6094:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-12 09:20:51.421  1027  2024 W libprocessgroup: failed to open /acct/uid_10046/pid_6094/cgroup.procs: No such file or directory
,08-12 09:20:51.498  7028  7028 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-12 09:20:51.527  7028  7028 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-12 09:20:51.529  6621  6621 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-12 09:20:51.556  1027  1959 I ActivityManager: Killing 6326:com.google.android.gm/u0a64 (adj 15): empty #17
,08-12 09:20:51.744  1027  1991 W libprocessgroup: failed to open /acct/uid_10064/pid_6326/cgroup.procs: No such file or directory
,08-12 09:20:54.281  6850  6850 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-12 09:20:54.287  1027  1567 I ActivityManager: Killing 6150:com.google.android.talk/u0a72 (adj 15): empty #17
08-12 09:20:54.316  2783  2783 I MusicWidget: mDelayedStopHandler : unbind
,08-12 09:20:54.353  1027  1769 W libprocessgroup: failed to open /acct/uid_10072/pid_6150/cgroup.procs: No such file or directory
,08-12 09:20:54.368  2113  2113 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-12 09:20:54.369  2113  2113 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-12 09:20:54.369  2113  2113 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,08-12 09:20:54.374  2113  2113 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-12 09:20:54.374  2113  2113 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-12 09:20:54.374  2113  2113 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-12 09:20:54.376  2113  2113 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-12 09:20:54.376  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-12 09:20:54.377  1027  1633 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1c3707ffcom.lge.music.MediaPlaybackService$5@361849cc
08-12 09:20:54.378  2113  2113 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-12 09:20:54.378  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.379  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.379  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.380  2113  2113 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@911d77a
08-12 09:20:54.380  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.381  2113  2113 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-12 09:20:54.381  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.382  2113  2113 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-12 09:20:54.382  2113  2113 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-12 09:20:54.382  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.383  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-12 09:20:54.386  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.386  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.387  2113  2113 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-12 09:20:54.388  2113  2113 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-12 09:20:54.389  2113  2113 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-12 09:20:54.389  2113  2113 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-12 09:20:54.389  2113  2113 V MediaPlayer[Native]: reset
08-12 09:20:54.396  2113  2113 V MediaPlayer[Native]: setListener
08-12 09:20:54.396  2113  2113 V MediaPlayer[Native]: disconnect
08-12 09:20:54.396  2113  2113 V MediaPlayer[Native]: destructor
08-12 09:20:54.396   307   307 V AudioFlinger: releasing 18 from 2113 for -1
08-12 09:20:54.396   307   307 V AudioFlinger:  decremented refcount to 0
08-12 09:20:54.396   307   307 V AudioFlinger: purging stale effects
08-12 09:20:54.396  2113  2113 V MediaPlayer[Native]: disconnect
,08-12 09:20:54.401  2113  2113 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-12 09:20:54.402  2113  2113 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-12 09:20:54.402  2113  2113 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-12 09:20:54.403  2113  2113 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-12 09:20:54.404  2113  2113 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-12 09:20:54.404  2113  2113 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-12 09:20:54.404  2113  2113 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 245089301
,08-12 09:20:54.404  2113  2113 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 245089301
08-12 09:20:54.419  2113  2113 I SmartShareClient: [SmartShareManagerClient] terminate service: 2113/MediaPlaybackService/319401584
,08-12 09:20:54.425  2113  2113 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-12 09:20:54.426  2113  2113 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@2b4f132a
08-12 09:20:54.428  2113  2113 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-12 09:20:54.428  2113  2113 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-12 09:20:54.429  2113  2113 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-12 09:20:54.429  2113  2113 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-12 09:20:54.432  1027  2024 I ActivityManager: Killing 5808:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-12 09:20:54.440  2113  2113 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
,08-12 09:20:54.447  5776  5776 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-12 09:20:54.447  5776  5776 W System.err: android.os.DeadObjectException
08-12 09:20:54.448  5776  5776 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-12 09:20:54.448  5776  5776 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-12 09:20:54.448  5776  5776 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-12 09:20:54.448  5776  5776 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-12 09:20:54.448  5776  5776 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-12 09:20:54.448  5776  5776 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-12 09:20:54.448  5776  5776 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 09:20:54.448  5776  5776 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 09:20:54.448  5776  5776 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:20:54.448  5776  5776 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 09:20:54.448  5776  5776 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:20:54.448  5776  5776 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:20:54.448  5776  5776 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 09:20:54.448  5776  5776 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 09:20:54.448  5776  5776 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-12 09:20:54.448  5776  5776 W System.err: android.os.DeadObjectException
08-12 09:20:54.449  5776  5776 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-12 09:20:54.449  5776  5776 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-12 09:20:54.449  5776  5776 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-12 09:20:54.449  5776  5776 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-12 09:20:54.449  5776  5776 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-12 09:20:54.449  5776  5776 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-12 09:20:54.449  5776  5776 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 09:20:54.449  5776  5776 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 09:20:54.449  5776  5776 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:20:54.449  5776  5776 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 09:20:54.449  5776  5776 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:20:54.449  5776  5776 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:20:54.449  5776  5776 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 09:20:54.449  5776  5776 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 09:20:54.449  5776  5776 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-12 09:20:54.450  5776  5776 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-12 09:20:54.650  1027  2024 E libprocessgroup: failed to kill 1 processes for processgroup 5808
,08-12 09:20:54.881  1027  1948 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-12 09:20:54.905  5776  5776 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-12 09:20:54.905  5776  5776 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-12 09:20:54.946  1027  1959 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7063 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-12 09:20:54.951  5776  5776 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-12 09:20:55.042  7063  7063 D UEI.SmartControl: Quickset Services start...
08-12 09:20:55.044  7063  7063 I UEI.SmartControl: Manufacture = LGE
08-12 09:20:55.044  7063  7063 D UEI.SmartControl: Id = LGNevo
08-12 09:20:55.048  7063  7063 D UEI.SmartControl: File observer start...
,08-12 09:20:55.049  7063  7063 E UEI.SmartControl: IR Port is disabled: false
08-12 09:20:55.050  7063  7063 D UEI.SmartControl: Starting file observer...
08-12 09:20:55.050  7063  7063 D UEI.SmartControl: Extracting JNI libs...
08-12 09:20:55.051  7063  7063 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-12 09:20:55.134  7063  7063 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-12 09:20:55.134  7063  7063 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-12 09:20:55.134  7063  7063 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-12 09:20:55.163  7063  7063 I UEI.SmartControl: --- Selecting new region: 6
,08-12 09:20:55.164  7063  7063 I UEI.SmartControl: Model = LG-D855
08-12 09:20:55.165  7063  7063 D UEI.SmartControl: QS Service created
08-12 09:20:55.177  7063  7063 I UEI.SmartControl: Service initServices...
,08-12 09:20:55.180  7063  7063 D UEI.SmartControl: QS start get config
08-12 09:20:55.203  6850  6938 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-12 09:20:55.213  7063  7063 D UEI.SmartControl: Loading JNI Libs...
08-12 09:20:55.439  7063  7063 I UEI.SmartControl: Supports setup maps: true
,08-12 09:20:55.442  7063  7063 D UEI.SmartControl: QS start statue = true Error code = 0
,08-12 09:20:55.442  7063  7063 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-12 09:20:55.442  7063  7063 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-12 09:20:55.442  7063  7063 I UEI.SmartControl: ### init IR Blaster...
,08-12 09:20:55.447  7063  7063 D serial_port: Configuring serial port
,08-12 09:20:55.451  7063  7063 E UEI.SmartControl: UEIBLaster setting for 616
,08-12 09:20:55.451  7063  7063 I UEI.SmartControl: Setting serial record hearder size = 2
08-12 09:20:55.451  7063  7063 I UEI.SmartControl: configuring settings for MAXQ616
08-12 09:20:55.451  7063  7063 I UEI.SmartControl: Get version...
,08-12 09:20:55.469  7063  7095 D UEI.SmartControl: serial port data available: 21
,08-12 09:20:55.500  7063  7063 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-12 09:20:55.500  7063  7063 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-12 09:20:55.501  7063  7063 I UEI.SmartControl: QS saving settings...
08-12 09:20:55.502  7063  7063 D UEI.SmartControl: IR Blaster version: 25672567
,08-12 09:20:55.519  7063  7095 D UEI.SmartControl: serial port data available: 4
,08-12 09:20:55.552  7063  7101 I UEI.SmartControl: Device manager: loading config....
08-12 09:20:55.553  7063  7101 D UEI.SmartControl: ----------- loading internal config...
,08-12 09:20:55.555  7063  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-12 09:20:55.557  7063  7063 E UEI.SmartControl: Services init done
08-12 09:20:55.557  7063  7063 D UEI.SmartControl: QS Service init finished
08-12 09:20:55.559  7063  7063 D UEI.SmartControl: QS Service version name: 2.1.91
08-12 09:20:55.560  7063  7063 D UEI.SmartControl: QS Service version code: 201091
08-12 09:20:55.561  7063  7063 D UEI.SmartControl: Service requested: Control
08-12 09:20:55.562  7063  7101 E UEI.SmartControl: Loading SETTINGS...
08-12 09:20:55.567  7063  7063 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-12 09:20:55.567  7063  7101 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-12 09:20:55.569  5776  5776 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-12 09:20:55.570  7063  7084 I UEI.SmartControl: ------ IControl API: 11
08-12 09:20:55.572  7063  7100 I UEI.SmartControl: Notify AllClients services are ready: 0
08-12 09:20:55.572  7063  7100 D UEI.SmartControl: -----service ready thread exits
08-12 09:20:55.575  7063  7084 I UEI.SmartControl: Registering callback...
08-12 09:20:55.576  7063  7082 I UEI.SmartControl: ------ IControl API: 19
08-12 09:20:55.576  1027  1948 I ActivityManager: Killing 5776:com.lge.qremote/u0a112 (adj 15): empty #17
08-12 09:20:55.578  7063  7082 I UEI.SmartControl: Registering Services Ready callback...
08-12 09:20:55.578  7063  7082 I UEI.SmartControl: Notify client services are ready...
08-12 09:20:55.683  1027  2042 W libprocessgroup: failed to open /acct/uid_10112/pid_5776/cgroup.procs: No such file or directory
,08-12 09:20:55.684  7063  7063 D UEI.SmartControl: Internal service binding...
08-12 09:20:56.153  1027  2042 I ActivityManager: Killing 5715:com.android.calendar/u0a13 (adj 15): empty #17
,08-12 09:20:56.259  1027  1930 W libprocessgroup: failed to open /acct/uid_10013/pid_5715/cgroup.procs: No such file or directory
,08-12 09:21:00.001  1027  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=756868111, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-12 09:21:00.034  2578  2578 D [Concierge]Service: onStartCommand(). Type : 9
,08-12 09:21:00.047  1595  1595 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 09:21:00.047  1595  1595 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 09:21:00.047  1595  1595 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 09:21:00.047  1595  1595 I [SystemUI]Clock: called onTimeUpdated()
,08-12 09:21:00.049  1595  1595 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 09:21:00.049  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
08-12 09:21:00.050  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
08-12 09:21:00.052  1595  1595 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 09:21:00.096  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=756868111 [*alarm*], flags=0x0
,08-12 09:21:00.134  4962  7107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-12 09:21:00.561  7063  7102 D UEI.SmartControl: Internal timer expired: 1
,08-12 09:21:00.600  7063  7102 D UEI.SmartControl: unbind internal service
,08-12 09:21:00.620  7063  7099 D serial_port: close(fd = 25)
,08-12 09:21:00.653  7063  7063 D UEI.SmartControl: Service.onUnbind: IControl
,08-12 09:21:00.669  7063  7063 D UEI.SmartControl: Service.onDestroy
08-12 09:21:00.669  7063  7063 D UEI.SmartControl: Lock is in USE false
08-12 09:21:00.669  7063  7063 D UEI.SmartControl: unbind internal service
08-12 09:21:00.669  7063  7063 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@911d77a
,08-12 09:21:00.702  7063  7063 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-12 09:21:00.702  7063  7063 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-12 09:21:00.702  7063  7063 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:21:00.702  7063  7063 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 09:21:00.702  7063  7063 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:21:00.702  7063  7063 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:21:00.702  7063  7063 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 09:21:00.702  7063  7063 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 09:21:00.702  7063  7063 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@911d77a
,08-12 09:21:00.738  7063  7099 I UEI.SmartControl: Serial port is closed.
,08-12 09:21:00.741  7063  7063 I UEI.SmartControl: Serial port is closed.
08-12 09:21:00.741  7063  7063 I UEI.SmartControl: Serial port is closed.
08-12 09:21:00.741  7063  7063 D UEI.SmartControl: Blaster closed
08-12 09:21:00.742  7063  7063 D UEI.SmartControl: Shut down QS...
,08-12 09:21:00.742  7063  7063 D UEI.SmartControl: Stopping QS lib
08-12 09:21:00.742  7063  7063 D UEI.SmartControl: QS lib stop result = true
08-12 09:21:00.742  7063  7063 D UEI.SmartControl: Stopped QS lib
08-12 09:21:00.743  7063  7063 D UEI.SmartControl: Stopped file observer...
08-12 09:21:00.743  7063  7063 D UEI.SmartControl: QS shutdown complete
08-12 09:21:01.182  6874  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 09:21:01.182  6874  6932 I jxcore-log: 
08-12 09:21:01.186  6874  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 09:21:01.186  6874  6932 I jxcore-log: 
,08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:21:01.196  6874  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 09:21:01.199  6874  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 09:21:01.203  6874  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 09:21:01.203  6874  6932 I jxcore-log: 
08-12 09:21:01.206  6874  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 09:21:01.206  6874  6932 I jxcore-log: 
,08-12 09:21:01.661  1027  1083 I ActivityManager: Waited long enough for: ServiceRecord{1e49bc4d u0 com.google.android.gms/.wearable.service.WearableService}
,08-12 09:21:01.851  6874  6932 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 09:21:01.851  6874  6932 I jxcore-log: Failed to execute UT.
08-12 09:21:01.851  6874  6932 I jxcore-log: 
08-12 09:21:01.851  6874  6932 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 09:21:01.851  6874  6932 I jxcore-log: 
,08-12 09:21:01.865  6874  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 09:21:01.865  6874  6932 I jxcore-log: 
,08-12 09:21:01.873  6874  6874 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 09:21:02.203  7150  7150 D AndroidRuntime: 
08-12 09:21:02.203  7150  7150 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 09:21:02.207  7150  7150 D AndroidRuntime: CheckJNI is OFF
,08-12 09:21:02.411  7150  7150 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 09:21:02.432  1027  1083 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-12 09:21:02.434  1027  1083 I ActivityManager: Killing 6874:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-12 09:21:02.484  1027  1042 I WindowState: WIN DEATH: Window{206e571a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 09:21:02.485  1027  1535 D WifiService: Client connection lost with reason: 4
,08-12 09:21:02.493  1027  1042 D InputDispatcher: Window went away: Window{206e571a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 09:21:02.655  1027  1083 I ActivityManager:   Force finishing activity ActivityRecord{389273ba u0 com.test.thalitest/.MainActivity t6}
,08-12 09:21:02.695   336   355 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 09:21:02.697  1027  1728 W ActivityManager: Spurious death for ProcessRecord{3563dc9c 6874:com.test.thalitest/u0a118}, curProc for 6874: null
08-12 09:21:02.698  1027  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 09:21:02.702  1027  1115 I ActivityManager:   Force finishing activity ActivityRecord{389273ba u0 com.test.thalitest/.MainActivity t6 f}
08-12 09:21:02.702  1027  1115 W ActivityManager: Duplicate finish request for ActivityRecord{389273ba u0 com.test.thalitest/.MainActivity t6 f}
,08-12 09:21:02.762  5080  5080 I art     : Explicit concurrent mark sweep GC freed 556(35KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 596us total 44.135ms
,08-12 09:21:02.764  2025  2025 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 09:21:02.764  1931  2740 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 09:21:02.765  1931  2740 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1afca33e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 09:21:02.767  2025  2025 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 09:21:02.769  1931  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 09:21:02.769  1931  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3742959f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 09:21:02.770  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 09:21:02.771  2025  2128 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-12 09:21:02.778  1895  1895 D ActionManagerService: notifyUserLog: 1000003
08-12 09:21:02.779  3761  4987 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 09:21:02.779  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-12 09:21:02.782  2025  2025 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 09:21:02.787  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 09:21:02.793  1027  1446 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 09:21:02.806  4326  4326 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 09:21:02.806  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 09:21:02.806  1987  1987 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 09:21:02.807  3761  3761 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-12 09:21:02.811  2496  2668 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 09:21:02.813  1027  1567 V SIM_STK : Menu title from STK is T-Mobile
08-12 09:21:02.818  1027  1082 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 09:21:02.853  4962  4962 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 09:21:02.853  4962  4962 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 09:21:02.853  4962  4962 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 09:21:02.853  4962  4962 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 09:21:02.853  4962  4962 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 09:21:02.854  4962  4962 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 09:21:02.854  4962  4962 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:21:02.854  4962  4962 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 09:21:02.854  4962  4962 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:21:02.854  4962  4962 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:21:02.854  4962  4962 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 09:21:02.854  4962  4962 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 09:21:02.858  2025  2025 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 09:21:02.859  6621  6621 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 09:21:02.867  2025  2025 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 09:21:02.869  1595  1595 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 09:21:02.876  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 09:21:02.877  1027  1027 I art     : Explicit concurrent mark sweep GC freed 15688(1134KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.206ms total 141.606ms
08-12 09:21:02.880  1895  1895 D ActionManagerService: notifyUserLog: 1000004
08-12 09:21:02.883  3761  3777 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-12 09:21:02.885  3761  4987 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , display: false
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , animation: false }
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , display: false
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , animation: false }
08-12 09:21:02.886  1808  1808 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , create_time: 1470393743569
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , display: false
08-12 09:21:02.886  2025  2025 I GBoardWebViewUtils: , animation: false }
08-12 09:21:02.887  1595  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 09:21:02.887  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.894  1595  1595 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 09:21:02.894  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-12 09:21:02.902  1595  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 09:21:02.902  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.907  1595  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 09:21:02.907  1595  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:21:02.908  1595  1644 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 09:21:02.908  1595  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 09:21:02.909  1595  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-12 09:21:02.909  1595  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 09:21:02.910  1861  1861 D SplitUIManager: split_name #11 / not available #0
,08-12 09:21:02.910  1595  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 09:21:02.910  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.910  1861  1861 D SplitUIService: removed split : 
08-12 09:21:02.916  1595  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 09:21:02.916  1595  1644 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 09:21:02.917  1595  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:02.917  1595  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 09:21:02.919  1595  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 09:21:02.919  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.925  1595  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:21:02.926  1595  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 09:21:02.926  1595  1644 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 09:21:02.926  1595  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 09:21:02.927  1595  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-12 09:21:02.927  1595  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-12 09:21:02.935  2183  2183 I ConfigService: onCreate
08-12 09:21:02.936  2183  2183 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 09:21:02.936  1595  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 09:21:02.936  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.937  2025  7183 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 09:21:02.941  1027  1043 V SIM_STK : Menu title from STK is T-Mobile
08-12 09:21:02.941  1027  1043 V SIM_STK : Menu title from STK is T-Mobile
,08-12 09:21:02.945  2183  2183 I ConfigService: onBind returning update interface
08-12 09:21:02.950  1861  1861 D SplitUIManager: split_name #11 / not available #0
08-12 09:21:02.950  1861  1861 I SplitUIService: split app #11
08-12 09:21:02.950  1595  1595 D KeyguardModel: handleShortcutListChanged...
08-12 09:21:02.950  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 09:21:02.951  1027  1027 D administrator: Handling package changes for user 0
08-12 09:21:02.951  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 09:21:02.972  2183  2183 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 09:21:02.972  2183  2183 I ConfigService: onBind returning config service
,08-12 09:21:02.973  1595  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 09:21:02.973  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.973  1808  1808 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 09:21:02.981  1595  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 09:21:02.981  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.982  1595  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:02.982  1595  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 09:21:02.982  1595  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-12 09:21:02.982  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.983  1595  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:02.983  1595  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 09:21:02.984  1595  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 09:21:02.984  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:02.985  1595  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:02.985  1595  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 09:21:02.986  1595  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 09:21:02.986  1595  1644 D KeyguardModel: createShortcutInfo...
08-12 09:21:03.013  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 09:21:03.022  2025  2025 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 09:21:03.026  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 09:21:03.026  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 09:21:03.026  1027  1027 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 09:21:03.030  1027  1569 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 09:21:03.034  1027  1043 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 09:21:03.034  4326  4326 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 09:21:03.038  1027  2042 V SIM_STK : Menu title from STK is T-Mobile
,08-12 09:21:03.044  1595  1595 D KeyguardModel: handleShortcutListChanged...
08-12 09:21:03.044  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 09:21:03.067  1808  1808 I ConfigFetchService: service connected
08-12 09:21:03.067  1808  1808 I ConfigClient: service connected
,08-12 09:21:03.074  2183  2183 I ConfigService: onDestroy
08-12 09:21:03.074  1808  7186 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 09:21:03.088  1027  1115 I art     : Explicit concurrent mark sweep GC freed 10539(773KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.880ms total 199.717ms
,08-12 09:21:03.099  5890  7192 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-12 09:21:03.103  6712  6712 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 09:21:03.106  1808  7193 I PeopleContactsSync: CP2 sync disabled
08-12 09:21:03.113  1808  5161 I Icing   : doRemovePackageData com.test.thalitest
,08-12 09:21:03.134  6735  6735 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 09:21:03.137  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 09:21:03.139  2326  7194 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 09:21:03.142  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:21:03.144  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 09:21:03.145  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 09:21:03.146  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-12 09:21:03.147  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 09:21:03.156  1808  7191 W GmsApplication: Using Auth Proxy for data requests.
08-12 09:21:03.163  1808  7191 W GmsApplication: Using Auth Proxy for data requests.
08-12 09:21:03.163  1027  1091 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3bfda995 u0 com.lge.launcher2/.Launcher t5} time:119383
08-12 09:21:03.164  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 09:21:03.164  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 09:21:03.167  1987  1987 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 09:21:03.167  1987  1987 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 09:21:03.169  1987  1987 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 09:21:03.171  2025  2159 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 09:21:03.171  2025  2159 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 09:21:03.177  6621  6621 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 09:21:03.179  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 09:21:03.180  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 09:21:03.180  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:21:03.188  2025  2025 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-12 09:21:03.210  1027  1567 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7200 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 09:21:03.212  2578  2578 D [Concierge]Service: onStartCommand(). Type : 8
08-12 09:21:03.212  2578  2578 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 09:21:03.213  2578  2578 D [Concierge]Service: Update widget ID : 11
08-12 09:21:03.215  2025  2025 D [Concierge]WidgetView: change position of spinner
08-12 09:21:03.216  2025  2025 I [Concierge]WidgetView: initWebView(). Time : 1470986463216
08-12 09:21:03.216  2578  2578 D [Concierge]Service: onStartCommand(). Type : 0
08-12 09:21:03.218   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 12.353ms
08-12 09:21:03.220  7150  7150 D AndroidRuntime: Shutting down VM
08-12 09:21:03.231   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 12.343ms
,08-12 09:21:03.235  2025  2025 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 963866349
08-12 09:21:03.235  2025  2025 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 09:21:03.235  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 09:21:03.238  2025  2025 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@18ea5a84
08-12 09:21:03.238  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 09:21:03.239  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 09:21:03.239  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:21:03.241   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 8.859ms
08-12 09:21:03.244  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 09:21:03.245  2025  2025 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 09:21:03.245  2025  2025 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 09:21:03.245  2025  2025 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470986370874, New one : 1470986463216
08-12 09:21:03.245  2025  2025 D [Concierge]WidgetView: Unregister all receivers
08-12 09:21:03.246  2025  2025 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-12 09:21:03.246  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:21:03.248  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 09:21:03.249  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 09:21:03.250  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 09:21:03.251  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 09:21:03.252  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 09:21:03.256  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:21:03.256  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:21:03.294  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 09:21:03.303  2025  2025 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 09:21:03.303  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 09:21:03.304  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:21:03.322  7200  7200 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 09:21:03.322  1027  1082 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:21:03.322  7200  7200 W LG Account v2.2: No ProfileInfo entries
08-12 09:21:03.322  7200  7200 I LG Account v2.2: isEnabled: false
,08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Country: EU
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Operator: OPEN
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Ranking support: false
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Comfort support: false
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Accessory: true
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Health device: true
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Extra Pedometer: false
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Blood glucose device: false
08-12 09:21:03.322  7200  7200 I Feature : [Lifetracker]Device Number: 3
08-12 09:21:03.323  7200  7200 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 09:21:03.324  2025  2025 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@928ddde time:119543
08-12 09:21:03.330  1027  1082 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 09:21:03.361  1027  2042 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7220 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-12 09:21:03.366  1027  2042 I ActivityManager: Killing 6393:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-12 09:21:03.436  2025  2025 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 09:21:03.453  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 09:21:03.455  1027  1969 W libprocessgroup: failed to open /acct/uid_10014/pid_6393/cgroup.procs: No such file or directory
08-12 09:21:03.478  2025  2915 I GBoardtInterface: onReloaded()
,08-12 09:21:03.481  2025  2025 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-12 09:21:03.482  3761  4982 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 09:21:03.485  3761  3777 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 09:21:03.490  7220  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:21:03.490  7220  7220 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 09:21:03.490  7220  7220 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 09:21:03.491  7220  7220 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 09:21:03.491  7220  7220 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 09:21:03.492  7220  7220 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 09:21:03.493  1895  1895 D ActionManagerService: notifyUserLog: 1000001
,08-12 09:21:03.495  3761  4987 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 09:21:03.495  3761  4987 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 09:21:03.500  1895  1895 D ActionManagerService: notifyUserLog: 1000001
08-12 09:21:03.502  3761  4987 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 09:21:03.502  3761  4987 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 09:21:03.502  3761  4987 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 09:21:03.502  3761  4987 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 09:21:03.504  3761  4982 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-12 09:21:03.506  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 09:21:03.506  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 09:21:03.509  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 09:21:03.509  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 09:21:03.511  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 09:21:03.511  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: Failed to open database '/data/data/com.android.settings/databases/wificalling.db'.
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at com.android.settings.wifi.WifiCallingBaseDBHelperProvider.onCreate(WifiCallingBaseDBHelperProvider.java:122)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.app,.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 09:21:03.533  7220  7220 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 09:21:03.534  7220  7220 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-12 09:21:03.534  7220  7220 E AndroidRuntime: FATAL EXCEPTION: main
08-12 09:21:03.534  7220  7220 E AndroidRuntime: Process: com.android.settings, PID: 7220
08-12 09:21:03.534  7220  7220 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.settings.wifi.WifiCallingBaseDBHelperProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at com.android.settings.wifi.WifiCallingBaseDBHelperProvider.onCreate(WifiCallingBaseDBHelperProvider.java:122)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-12 09:21:03.534  7220  7220 E AndroidRuntime: 	... 11 more
,08-12 09:21:03.542  7220  7220 I Process : Sending signal. PID: 7220 SIG: 9
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: Can't write: system_app_crash
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 09:21:03.543  1027  7240 E DropBoxManagerService: 	... 5 more
08-12 09:21:03.622   279   775 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
