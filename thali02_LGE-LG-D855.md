#### Test 81418577b3d8250_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 11:20:08.217  6456  6456 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
08-26 11:20:08.278  1034  1887 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6492 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-26 11:20:08.281  1034  1887 I ActivityManager: Killing 5979:com.android.vending/u0a44 (adj 15): empty #17
08-26 11:20:08.340  1034  1889 W libprocessgroup: failed to open /acct/uid_10044/pid_5979/cgroup.procs: No such file or directory
08-26 11:20:08.378  6492  6492 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 11:20:08.379  6492  6492 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 11:20:08.379  6492  6492 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 11:20:08.380  6492  6492 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 11:20:08.508  6492  6492 I AppConfig: Total System Memory = 2995761152
08-26 11:20:08.540  6492  6492 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-26 11:20:08.573  1034  1050 I ActivityManager: Killing 6022:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 11:20:08.604  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-26 11:20:08.604  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-26 11:20:08.607  1034  2034 W libprocessgroup: failed to open /acct/uid_10080/pid_6022/cgroup.procs: No such file or directory
08-26 11:20:08.611  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-26 11:20:08.634  6344  6344 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 11:20:08.641  6344  6344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:08.684  1034  1887 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6515 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 11:20:08.913  6515  6515 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-26 11:20:08.997  6515  6515 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:08.998  6515  6515 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:09.040  6515  6515 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-26 11:20:09.062  6515  6515 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 11:20:09.063  6515  6515 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 11:20:09.080  6515  6515 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 11:20:09.080  6515  6515 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 11:20:09.101  1034  1993 I ActivityManager: Killing 5414:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 11:20:09.188  1034  1785 W libprocessgroup: failed to open /acct/uid_10085/pid_5414/cgroup.procs: No such file or directory
08-26 11:20:09.213  5033  6565 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 11:20:09.258  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:09.267  1034  1968 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6566 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 11:20:09.278  3482  5898 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 11:20:09.282  3482  5898 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@311d6fde on behalf of 6515
08-26 11:20:09.305  6515  6515 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 11:20:09.332  6515  6515 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-26 11:20:09.356  5033  6565 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 143 ms] updated apps [took 143 ms] 
08-26 11:20:09.363  6561  6561 D AndroidRuntime: 
08-26 11:20:09.363  6561  6561 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 11:20:09.367  6561  6561 D AndroidRuntime: CheckJNI is OFF
08-26 11:20:09.417  6566  6566 D DocsApplication: Installing DEX configuration.
08-26 11:20:09.443  6566  6566 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 11:20:09.448  6566  6566 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3cf966d0 com.google.android.apps.docs}
08-26 11:20:09.463  6566  6566 D TAG     : onCreate()
08-26 11:20:09.484  6566  6566 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 11:20:09.498  6561  6561 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 11:20:09.504  1034  1889 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 11:20:09.513  1943  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 11:20:09.516  1034  1889 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 11:20:09.517  1034  1889 D ActivityManager: setTaskToReturnTo : TaskRecord{2ffca720 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 11:20:09.517  1034  1889 D ActivityManager: setTaskToReturnTo : TaskRecord{2ffca720 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 11:20:09.518  1034  1889 D WindowStateEx: AppWindowTokenEx init.. 
08-26 11:20:09.519   350   366 E GBMv2   : DFP En is all cleared set to be enabled
08-26 11:20:09.567  1034  1889 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6606 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 11:20:09.570  6561  6561 D AndroidRuntime: Shutting down VM
08-26 11:20:09.620  1943  2529 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 11:20:09.621  1943  2529 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32499d4c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 11:20:09.622  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 11:20:09.622  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c0d5195 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 11:20:09.694  6606  6606 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-26 11:20:09.791  6606  6606 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 11:20:09.800  6606  6606 I LibraryLoader: Loading: webviewchromium
08-26 11:20:09.803  6606  6606 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3894-3897)
,08-26 11:20:09.804  6606  6606 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 11:20:09.818  6606  6606 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d64ccda}
,08-26 11:20:09.819  6606  6606 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 11:20:09.819  6606  6606 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 11:20:09.828  6606  6606 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 11:20:09.829  6606  6606 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 11:20:09.839  6606  6606 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 11:20:09.839   333  2154 V AudioPolicyService: registerClient() client 0xb1025c60, uid 10118
,08-26 11:20:09.840  6606  6606 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 11:20:09.840  6606  6606 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 11:20:09.844  1034  1116 D BluetoothManagerService: Message: 20
08-26 11:20:09.844  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b298aaa:true
08-26 11:20:09.851  6606  6606 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 11:20:09.851  6606  6606 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 11:20:09.851  6606  6606 I Adreno-EGL: Build Date: 12/12/14 금
08-26 11:20:09.851  6606  6606 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 11:20:09.851  6606  6606 I Adreno-EGL: Remote Branch: 
08-26 11:20:09.851  6606  6606 I Adreno-EGL: Local Patches: 
08-26 11:20:09.851  6606  6606 I Adreno-EGL: Reconstruct Branch: 
,08-26 11:20:09.910  6606  6638 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 11:20:09.914  6606  6606 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 11:20:09.925  6606  6606 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 11:20:09.929  6606  6606 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 11:20:09.931  6606  6606 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 11:20:09.933  6606  6606 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 11:20:09.933  6606  6606 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 11:20:09.943  6606  6606 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-26 11:20:09.947  6606  6606 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 11:20:09.947  6606  6606 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 11:20:09.969  6606  6650 D OpenGLRenderer: Render dirty regions requested: true
08-26 11:20:09.969  6606  6650 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 11:20:09.972  6606  6650 D OpenGLRenderer: Enabling debug mode 0
08-26 11:20:09.978  6606  6606 D Atlas   : Validating map...
,08-26 11:20:09.980  1034  1889 D SplitWindow: check instance of lgWin Window{2e486c14 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 11:20:10.036  6606  6648 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:10.037  6606  6648 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:10.064  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +445ms (total +545ms)
08-26 11:20:10.064  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c3f18d9 u0 com.test.thalitest/.MainActivity t6} time:104158
,08-26 11:20:10.065  6606  6606 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24a48171 time:104159
08-26 11:20:10.154  6606  6606 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 11:20:10.188  6606  6606 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 11:20:10.188  6606  6606 I chromium: 
,08-26 11:20:10.268  6606  6661 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-26 11:20:10.280  6606  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 11:20:10.280  6606  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 11:20:10.280  6606  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 11:20:10.280  6606  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 11:20:10.280  6606  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 11:20:10.281  6606  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16f1bb65 added. We now have 1 listener(s)
,08-26 11:20:10.285  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:10.288  6606  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 11:20:10.290  6606  6661 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:10.291  6606  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:10.291  6606  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 11:20:10.298  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 11:20:10.299  6606  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25dcd248 added. We now have 1 listener(s)
08-26 11:20:10.299  6606  6661 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:10.302  1034  1544 D WifiService: New client listening to asynchronous messages
08-26 11:20:10.305  6606  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:10.305  6606  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 11:20:10.307  6606  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 11:20:10.307  6606  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 11:20:10.307  6606  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 11:20:10.311  6606  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:10.311  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:10.312  6606  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-26 11:20:10.320  6606  6661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:10.320  6606  6661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:10.320  6606  6661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 11:20:10.320  6606  6661 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:10.321  6606  6661 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 11:20:10.322  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:10.324  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:10.363  6606  6648 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 11:20:10.363  6606  6648 I chromium: 
,08-26 11:20:10.364  1818  5179 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-26 11:20:10.448  6606  6606 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 11:20:10.474  1818  5179 I art     : Explicit concurrent mark sweep GC freed 31474(1982KB) AllocSpace objects, 14(224KB) LOS objects, 51% free, 29MB/61MB, paused 2.561ms total 76.023ms
,08-26 11:20:10.495  1818  5179 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-26 11:20:10.522  1818  5179 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-26 11:20:10.843  6566  6566 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:10.844  6566  6566 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:10.847   350   368 E GBMv2   : DFP En is all cleared set to be enabled
08-26 11:20:10.847   350   368 E GBMv2   : Set value is all cleared set the max
08-26 11:20:10.847   350   368 I GBMv2   : DFP Enabled. Ignore VFP set
08-26 11:20:11.069  1034  1993 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6679 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-26 11:20:11.070  1034  1993 I ActivityManager: Killing 6048:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-26 11:20:11.172  1034  2029 W libprocessgroup: failed to open /acct/uid_10097/pid_6048/cgroup.procs: No such file or directory
,08-26 11:20:11.198  6566  6566 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 11:20:11.210  6606  6664 W jxcore-log: Initializing JXcore engine
08-26 11:20:11.210  6606  6664 W jxcore-log: JXcore engine is ready
,08-26 11:20:11.249  6679  6679 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 11:20:11.263  6679  6679 I LockScreenSettings: New app installed broadcast received ..
,08-26 11:20:11.265  6679  6679 I LockScreenSettings: Number of installed packages  1
08-26 11:20:11.274  6664  6664 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7539]" dev="sockfs" ino=7539 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 11:20:11.274  6664  6664 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 11:20:11.274  6664  6664 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9834]" dev="sockfs" ino=9834 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 11:20:11.274  6664  6664 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 11:20:11.274  6664  6664 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29615]" dev="sockfs" ino=29615 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-26 11:20:11.288  6606  6664 W jxcore-log: Starting JXcore engine
,08-26 11:20:11.302  1034  1576 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6706 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 11:20:11.374  6606  6664 W jxcore-log: Platform android
08-26 11:20:11.374  6606  6664 W jxcore-log: 
,08-26 11:20:11.374  6606  6664 W jxcore-log: Process ARCH arm
08-26 11:20:11.374  6606  6664 W jxcore-log: 
08-26 11:20:11.375  6706  6706 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 11:20:11.560  6606  6664 I jxcore-log: JXcore Cordova bridge is ready!
08-26 11:20:11.560  6606  6664 I jxcore-log: 
08-26 11:20:11.560  6606  6664 W jxcore-log: JXcore engine is started
,08-26 11:20:11.569  6606  6661 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 11:20:11.576  6606  6606 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 11:20:11.609  1034  1887 I art     : Explicit concurrent mark sweep GC freed 27002(1336KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.998ms total 143.005ms
,08-26 11:20:11.811  1034  1889 V SIM_STK : Menu title from STK is T-Mobile
,08-26 11:20:11.886  1034  1935 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6736 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 11:20:11.909   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 482us total 19.660ms
,08-26 11:20:11.928   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 18.566ms
,08-26 11:20:11.947   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.855ms
,08-26 11:20:11.970  6736  6736 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
,08-26 11:20:11.970  6736  6736 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-26 11:20:11.972  5540  5540 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-26 11:20:11.989  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-26 11:20:12.013  1034  1050 I ActivityManager: Killing 6080:com.google.android.gm/u0a64 (adj 15): empty #17
,08-26 11:20:12.188  1034  1889 W libprocessgroup: failed to open /acct/uid_10064/pid_6080/cgroup.procs: No such file or directory
,08-26 11:20:12.320  1034  1112 W ProcessCpuTracker: Skipping unknown process pid 6552
08-26 11:20:12.321  1034  1112 W ProcessCpuTracker: Skipping unknown process pid 6555
,08-26 11:20:14.952  6566  6566 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 11:20:14.963  1034  1958 I ActivityManager: Killing 5874:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 11:20:15.128  1034  2029 W libprocessgroup: failed to open /acct/uid_10072/pid_5874/cgroup.procs: No such file or directory
,08-26 11:20:15.891  6566  6674 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 11:20:16.800  1034  1923 I ActivityManager: Killing 5659:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 11:20:16.825  5638  5638 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 11:20:16.825  5638  5638 W System.err: android.os.DeadObjectException
08-26 11:20:16.825  5638  5638 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 11:20:16.825  5638  5638 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 11:20:16.825  5638  5638 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 11:20:16.825  5638  5638 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 11:20:16.825  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-26 11:20:16.826  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 11:20:16.826  5638  5638 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 11:20:16.826  5638  5638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 11:20:16.827  5638  5638 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:16.827  5638  5638 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:16.827  5638  5638 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-26 11:20:16.827  5638  5638 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:16.827  5638  5638 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:16.827  5638  5638 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:16.828  5638  5638 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 11:20:16.828  5638  5638 W System.err: android.os.DeadObjectException
08-26 11:20:16.829  5638  5638 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 11:20:16.829  5638  5638 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 11:20:16.829  5638  5638 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 11:20:16.829  5638  5638 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-26 11:20:16.829  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 11:20:16.829  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 11:20:16.829  5638  5638 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 11:20:16.830  5638  5638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 11:20:16.830  5638  5638 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:16.830  5638  5638 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:16.830  5638  5638 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:16.830  5638  5638 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:16.830  5638  5638 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:16.830  5638  5638 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:16.831  5638  5638 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 11:20:16.832  5638  5638 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 11:20:17.053  1034  1785 W libprocessgroup: failed to open /acct/uid_1000/pid_5659/cgroup.procs: No such file or directory
08-26 11:20:17.054  1034  1785 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 11:20:17.064  5638  5638 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 11:20:17.064  5638  5638 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 11:20:17.111  1034  1889 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6764 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 11:20:17.112  5638  5638 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 11:20:17.189  6764  6764 D UEI.SmartControl: Quickset Services start...
08-26 11:20:17.191  6764  6764 I UEI.SmartControl: Manufacture = LGE
08-26 11:20:17.191  6764  6764 D UEI.SmartControl: Id = LGNevo
08-26 11:20:17.192  6764  6764 D UEI.SmartControl: File observer start...
08-26 11:20:17.193  6764  6764 E UEI.SmartControl: IR Port is disabled: false
08-26 11:20:17.193  6764  6764 D UEI.SmartControl: Starting file observer...
08-26 11:20:17.193  6764  6764 D UEI.SmartControl: Extracting JNI libs...
08-26 11:20:17.193  6764  6764 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-26 11:20:17.274  6764  6764 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-26 11:20:17.274  6764  6764 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 11:20:17.274  6764  6764 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-26 11:20:17.313  6764  6764 I UEI.SmartControl: --- Selecting new region: 6
,08-26 11:20:17.316  6764  6764 I UEI.SmartControl: Model = LG-D855
08-26 11:20:17.318  6764  6764 D UEI.SmartControl: QS Service created
08-26 11:20:17.332  1818  6377 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 11:20:17.338   329  6786 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-26 11:20:17.339   329  6786 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-26 11:20:17.339   329  6786 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-26 11:20:17.345  6764  6764 I UEI.SmartControl: Service initServices...
,08-26 11:20:17.350  6764  6764 D UEI.SmartControl: QS start get config
08-26 11:20:17.405  6764  6764 D UEI.SmartControl: Loading JNI Libs...
,08-26 11:20:17.602  1818  1818 I ConfigFetchService: fetch service done; releasing wakelock
,08-26 11:20:17.603  1818  1818 I ConfigFetchService: stopping self
08-26 11:20:17.609  2080  2080 I ConfigService: onDestroy
08-26 11:20:17.767  6764  6764 I UEI.SmartControl: Supports setup maps: true
08-26 11:20:17.772  6764  6764 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 11:20:17.772  6764  6764 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 11:20:17.772  6764  6764 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 11:20:17.773  6764  6764 I UEI.SmartControl: ### init IR Blaster...
,08-26 11:20:17.781  6764  6764 D serial_port: Configuring serial port
,08-26 11:20:17.792  6764  6764 E UEI.SmartControl: UEIBLaster setting for 616
08-26 11:20:17.792  6764  6764 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 11:20:17.794  6764  6764 I UEI.SmartControl: configuring settings for MAXQ616
08-26 11:20:17.794  6764  6764 I UEI.SmartControl: Get version...
,08-26 11:20:17.811  6764  6787 D UEI.SmartControl: serial port data available: 21
,08-26 11:20:17.838  6764  6764 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 11:20:17.838  6764  6764 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 11:20:17.839  6764  6764 I UEI.SmartControl: QS saving settings...
08-26 11:20:17.839  6764  6764 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 11:20:17.858  6764  6787 D UEI.SmartControl: serial port data available: 4
,08-26 11:20:17.895  6764  6790 I UEI.SmartControl: Device manager: loading config....
,08-26 11:20:17.896  6764  6790 D UEI.SmartControl: ----------- loading internal config...
08-26 11:20:17.899  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 11:20:17.902  6764  6764 E UEI.SmartControl: Services init done
08-26 11:20:17.902  6764  6764 D UEI.SmartControl: QS Service init finished
08-26 11:20:17.904  6764  6764 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 11:20:17.904  6764  6764 D UEI.SmartControl: QS Service version code: 201091
08-26 11:20:17.907  6764  6764 D UEI.SmartControl: Service requested: Control
08-26 11:20:17.914  6764  6790 E UEI.SmartControl: Loading SETTINGS...
,08-26 11:20:17.919  6764  6764 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 11:20:17.923  1034  1889 I ActivityManager: Killing 5638:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 11:20:17.938  6764  6790 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 11:20:17.954  6764  6789 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 11:20:17.954  6764  6789 D UEI.SmartControl: -----service ready thread exits
08-26 11:20:18.059  1034  1993 W libprocessgroup: failed to open /acct/uid_10112/pid_5638/cgroup.procs: No such file or directory
,08-26 11:20:18.063  6764  6764 D UEI.SmartControl: Internal service binding...
08-26 11:20:18.427  2781  2781 I MusicWidget: mDelayedStopHandler : unbind
,08-26 11:20:18.448  2155  2155 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,08-26 11:20:18.466  2155  2155 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 11:20:18.466  2155  2155 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,08-26 11:20:18.477  2155  2155 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 11:20:18.478  2155  2155 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 11:20:18.478  2155  2155 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-26 11:20:18.536  2155  2155 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 11:20:18.536  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-26 11:20:18.556  1034  2029 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@cda7318com.lge.music.MediaPlaybackService$5@24a48171
,08-26 11:20:18.557  2155  2155 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 11:20:18.557  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.558  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.559  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.560  2155  2155 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@4d2dca6
08-26 11:20:18.560  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.561  2155  2155 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 11:20:18.561  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.562  2155  2155 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 11:20:18.562  2155  2155 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 11:20:18.562  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.563  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.564  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.564  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.566  2155  2155 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 11:20:18.567  2155  2155 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-26 11:20:18.571  2155  2155 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 11:20:18.571  2155  2155 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 11:20:18.571  2155  2155 V MediaPlayer[Native]: reset
08-26 11:20:18.578  2155  2155 V MediaPlayer[Native]: setListener
08-26 11:20:18.578  2155  2155 V MediaPlayer[Native]: disconnect
08-26 11:20:18.578  2155  2155 V MediaPlayer[Native]: destructor
08-26 11:20:18.578   333   333 V AudioFlinger: releasing 18 from 2155 for -1
08-26 11:20:18.578   333   333 V AudioFlinger:  decremented refcount to 0
08-26 11:20:18.578   333   333 V AudioFlinger: purging stale effects
08-26 11:20:18.578  2155  2155 V MediaPlayer[Native]: disconnect
08-26 11:20:18.587  2155  2155 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-26 11:20:18.589  2155  2155 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 11:20:18.590  2155  2155 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 11:20:18.591  2155  2155 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 11:20:18.591  2155  2155 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 11:20:18.592  2155  2155 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 11:20:18.592  2155  2155 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 132234070
08-26 11:20:18.592  2155  2155 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 132234070
08-26 11:20:18.605  2155  2155 I SmartShareClient: [SmartShareManagerClient] terminate service: 2155/MediaPlaybackService/634789884
,08-26 11:20:18.610  2155  2155 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 11:20:18.611  2155  2155 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1cb527d7
08-26 11:20:18.613  2155  2155 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 11:20:18.613  2155  2155 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 11:20:18.614  2155  2155 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 11:20:18.615  2155  2155 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 11:20:18.617  1034  1889 I ActivityManager: Killing 5579:com.android.calendar/u0a13 (adj 15): empty #17
,08-26 11:20:18.626  2155  2155 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
,08-26 11:20:18.769  1034  1993 W libprocessgroup: failed to open /acct/uid_10013/pid_5579/cgroup.procs: No such file or directory
,08-26 11:20:22.419  1034  1112 I ActivityManager: Waited long enough for: ServiceRecord{794e845 u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 11:20:22.899  6764  6791 D UEI.SmartControl: Internal timer expired: 1
,08-26 11:20:22.899  6764  6791 D UEI.SmartControl: unbind internal service
,08-26 11:20:22.906  6764  6764 D UEI.SmartControl: Service.onUnbind: IControl
08-26 11:20:22.908  6764  6764 D UEI.SmartControl: Service.onDestroy
08-26 11:20:22.908  6764  6764 D UEI.SmartControl: Lock is in USE false
08-26 11:20:22.908  6764  6764 D UEI.SmartControl: unbind internal service
08-26 11:20:22.909  6764  6764 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@4d2dca6
08-26 11:20:22.910  6764  6764 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 11:20:22.910  6764  6764 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 11:20:22.910  6764  6764 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 11:20:22.910  6764  6764 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 11:20:22.910  6764  6764 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 11:20:22.910  6764  6764 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 11:20:22.910  6764  6764 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 11:20:22.910  6764  6764 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 11:20:22.911  6764  6764 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:22.911  6764  6764 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:22.911  6764  6764 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:22.911  6764  6764 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:22.911  6764  6764 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:22.911  6764  6764 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:22.911  6764  6764 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:22.911  6764  6764 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@4d2dca6
08-26 11:20:22.916  6764  6764 D serial_port: close(fd = 25)
,08-26 11:20:22.922  6764  6764 I UEI.SmartControl: Serial port is closed.
,08-26 11:20:22.922  6764  6764 I UEI.SmartControl: Serial port is closed.
,08-26 11:20:22.922  6764  6764 D UEI.SmartControl: Blaster closed
,08-26 11:20:22.922  6764  6764 D UEI.SmartControl: Shut down QS...
08-26 11:20:22.922  6764  6764 D UEI.SmartControl: Stopping QS lib
08-26 11:20:22.923  6764  6764 D UEI.SmartControl: QS lib stop result = true
08-26 11:20:22.923  6764  6764 D UEI.SmartControl: Stopped QS lib
08-26 11:20:22.924  6764  6764 D UEI.SmartControl: Stopped file observer...
08-26 11:20:22.924  6764  6764 D UEI.SmartControl: QS shutdown complete
08-26 11:20:23.425  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 11:20:23.425  6606  6664 I jxcore-log: 
08-26 11:20:23.428  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 11:20:23.428  6606  6664 I jxcore-log: 
,08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:23.431  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:23.434  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-26 11:20:23.437  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-26 11:20:23.437  6606  6664 I jxcore-log: 
,08-26 11:20:23.439  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 11:20:23.439  6606  6664 I jxcore-log: 
,08-26 11:20:23.941  6606  6664 D executeNativeTests: Running unit tests
,08-26 11:20:24.025  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 11:20:24.025  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 added. We now have 2 listener(s)
,08-26 11:20:24.026  1034  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 11:20:24.028  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 11:20:24.028  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 11:20:24.028  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 11:20:24.028  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:24.028  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a added. We now have 2 listener(s)
,08-26 11:20:24.028  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:24.029  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:24.031  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:24.033  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:24.034  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-26 11:20:24.034  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:24.035  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.036  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:24.039  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 11:20:24.039  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 11:20:24.039  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 11:20:24.040  6606  6664 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 11:20:24.041  6606  6664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 11:20:24.041  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 11:20:24.041  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 11:20:24.041  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 11:20:24.042  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.042  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.042  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.043  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.043  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.043  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:24.043  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:24.043  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 removed from the list
08-26 11:20:24.043  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.043  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a removed from the list
08-26 11:20:24.043  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.043  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.044  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.044  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.045  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.045  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.045  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.045  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.046  6606  6664 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 11:20:24.046  6606  6664 I io.jxcore.node.Connect,ionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.046  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.046  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.047  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.047  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.047  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.047  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
,08-26 11:20:24.047  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.047  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.047  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.047  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.047  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.047  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.047  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.047  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.047  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.047  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.047  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 11:20:24.051  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 11:20:24.052  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:24.052  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:24.052  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.052  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.052  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.052  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.052  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
,08-26 11:20:24.052  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.052  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
,08-26 11:20:24.052  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.052  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.052  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.052  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.052  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.053  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.053  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.053  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.053  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.054  6606  6664 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 11:20:24.055  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:24.058  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:24.058  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:24.059  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:24.060  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.061  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.062  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:24.062  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 11:20:24.063  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:24.063  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:24.063  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:24.066  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 11:20:24.066  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:24.070  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 11:20:24.074  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-26 11:20:24.075  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 11:20:24.076  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:24.076  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:24.078  6606  6664 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 11:20:24.078  6606  6664 I io.jxcore.node.ConnectionHelper: start: OK
08-26 11:20:24.080  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.080  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.080  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.080  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.080  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.080  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:24.080  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.080  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.080  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
,08-26 11:20:24.080  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.080  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.081  6606  6664 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 11:20:24.082  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:24.084  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:24.085  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.085  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:24.086  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.087  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.087  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:24.087  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:24.087  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:24.087  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:24.087  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:24.090  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:24.091  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:24.091  6606  6664 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 11:20:24.091  6606  6664 I io.jxcore.node.ConnectionHelper: start: OK
08-26 11:20:24.093  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.093  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.093  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.093  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.093  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.093  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:24.093  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.093  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.093  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.093  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.093  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:24.093  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.093  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.094  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 11:20:24.094  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.095  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.095  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.095  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.095  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.095  6606  6664 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 11:20:24.097  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:24.099  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:24.099  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.100  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:24.101  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.101  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:24.102  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:24.102  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:24.102  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 11:20:24.102  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:24.102  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:24.104  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:24.105  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:24.105  6606  6664 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 11:20:24.106  6606  6664 I io.jxcore.node.ConnectionHelper: start: OK
08-26 11:20:24.106  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.106  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 11:20:24.106  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.106  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.107  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:24.107  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.107  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.107  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.107  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:24.107  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.107  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.107  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
,08-26 11:20:24.107  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.107  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.107  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.107  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:24.108  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.108  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.108  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.108  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-26 11:20:24.108  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.108  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.109  6606  6664 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 11:20:24.109  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.109  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.109  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:24.109  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.109  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.109  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.109  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list,
08-26 11:20:24.109  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.109  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.109  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:24.109  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.109  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.109  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.109  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.110  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.110  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:24.110  6606  6664 D BluetoothLeScanner: could not find callback wrapper,
08-26 11:20:24.110  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.110  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.110  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.111  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 11:20:24.111  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:24.111  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.111  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.112  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-26 11:20:24.112  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.112  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.112  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
,08-26 11:20:24.112  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.112  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list,
08-26 11:20:24.112  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.112  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 11:20:24.112  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.112  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.112  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.113  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.113  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.113  6606  6664 D BluetoothLeScanner: could not find callback wrapper,
08-26 11:20:24.113  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-26 11:20:24.113  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.113  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.113  6606  6664 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 11:20:24.114  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 11:20:24.114  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.114  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.114  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.114  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.114  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.114  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list,
08-26 11:20:24.114  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.114  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.114  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:24.114  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.114  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.114  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.114  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:24.115  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.115  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.115  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.115  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.115  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.115  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.116  6606  6664 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 11:20:24.116  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.116  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:24.116  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.116  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.116  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.116  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.116  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
,08-26 11:20:24.116  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.116  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.116  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.116  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.116  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:24.116  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.116  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.117  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.117  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:24.117  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.117  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.117  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.118  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.118  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 11:20:24.119  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 11:20:24.119  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 11:20:24.119  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 11:20:24.119  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 11:20:24.119  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 11:20:24.119  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.119  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.119  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.119  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.120  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.120  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.120  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.120  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.120  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.120  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:24.120  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.120  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.120  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.120  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.120  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.120  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:24.121  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.121  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.121  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.121  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.121  6606  6664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 11:20:24.121  6606  6664 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 11:20:24.121  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 11:20:24.123  6606  6664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 11:20:24.123  6606  6664 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 11:20:24.123  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 11:20:24.124  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-26 11:20:24.124  6606  6664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 11:20:24.124  6606  6664 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 11:20:24.124  6606  6664 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd,
08-26 11:20:24.124  6606  6664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 11:20:24.124  6606  6664 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 11:20:24.124  6606  6664 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 11:20:24.124  6606  6664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 11:20:24.124  6606  6664 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 11:20:24.124  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 11:20:24.126  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 11:20:24.127  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-26 11:20:24.127  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 11:20:24.128  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 11:20:24.128  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-26 11:20:24.128  6606  6664 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 11:20:24.128  6606  6664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 11:20:24.128  6606  6664 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-26 11:20:24.128  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.128  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.128  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 11:20:24.129  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.129  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.129  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:24.129  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 11:20:24.129  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.129  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.129  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.129  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.129  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.129  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.129  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.129  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.130  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.130  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.130  6606  6831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-26 11:20:24.130  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.130  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.130  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.130  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.131  6606  6664 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-26 11:20:24.131  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.131  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.131  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.132  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.132  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.132  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.132  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.132  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.132  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.132  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.132  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.132  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.132  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.132  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.132  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.132  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.133  6606  6664 D BluetoothLeScanner: could not find callback wrapper
,08-26 11:20:24.133  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.133  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.133  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.133  6606  6664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 11:20:24.134  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.134  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.134  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.135  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:24.135  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.135  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.135  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.135  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.136  6606  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
08-26 11:20:24.136  6606  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
08-26 11:20:24.136  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.137  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:24.137  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.137  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.137  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.137  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.138  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.138  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.138  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.138  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 11:20:24.138  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.138  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.138  6606  6664 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 11:20:24.139  6606  6664 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 11:20:24.139  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 11:20:24.139  6606  6664 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 11:20:24.139  6606  6664 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 11:20:24.139  6606  6664 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 11:20:24.139  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 11:20:24.139  6606  6664 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 11:20:24.139  6606  6664 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 11:20:24.139  6606  6664 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 11:20:24.139  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 11:20:24.139  6606  6664 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 11:20:24.139  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.139  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.139  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.140  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:24.140  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.140  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.140  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.140  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.140  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.140  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.140  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.140  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.140  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.140  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.142  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.142  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.142  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.142  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.142  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.142  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.143  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:24.143  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.143  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.143  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.143  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.143  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.143  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.143  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.143  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.143  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.143  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.143  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.143  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.143  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.143  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.143  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.143  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.143  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:24.144  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.144  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.144  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.144  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.144  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.144  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.144  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.144  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.144  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.144  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.144  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.145  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.145  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.145  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.145  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.145  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:24.145  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.147  6606  6664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 11:20:24.147  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:24.148  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 11:20:24.149  6606  6664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 11:20:24.149  6606  6664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 11:20:24.149  6606  6606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 11:20:24.149  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 11:20:24.149  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 11:20:24.150  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.151  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 11:20:24.152  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 11:20:24.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 11:20:24.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 11:20:24.152  6606  6606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 11:20:24.152  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
,08-26 11:20:24.152  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.152  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 11:20:24.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 11:20:24.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 11:20:24.153  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 11:20:24.153  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:24.153  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:24.153  6606  6664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 11:20:24.153  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.153  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.154  6606  6664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:24.154  6606  6606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:24.154  6606  6606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:24.154  6606  6606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:24.154  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.155  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.155  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.155  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.155  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.155  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.155  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.155  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.155  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.155  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.155  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.155  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.155  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.155  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.155  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.156  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.156  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.156  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.156  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.158  6606  6832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 11:20:24.158  6606  6832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 11:20:24.159  6606  6606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 11:20:24.159  6606  6664 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 11:20:24.160  6606  6664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 11:20:24.160  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 11:20:24.161  6606  6664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 11:20:24.161  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.161  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.161  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.161  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:24.161  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.161  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.161  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.161  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.161  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.161  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.161  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.161  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.161  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:24.161  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.162  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.162  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.162  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.162  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.164  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:24.164  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:24.165  1034  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:24.165  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.165  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:24.165  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.165  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.165  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.165  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.165  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.165  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.165  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.166  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.166  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.166  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:24.166  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.166  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.166  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.166  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.166  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.166  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.167  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:24.167  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:24.167  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:24.168  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:24.168  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.168  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.168  6606  6664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff6ef5 not in the list
08-26 11:20:24.168  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.168  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.168  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:24.168  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.168  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.168  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:24.168  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:24.168  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:24.168  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:24.169  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:24.169  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f148a not in the list
08-26 11:20:24.170  6606  6664 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 11:20:24.170  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 11:20:24.170  6606  6664 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 11:20:24.170  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 11:20:24.170  6606  6664 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 11:20:24.170  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 11:20:24.171  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 11:20:24.171  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 11:20:24.172  6606  6664 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 11:20:24.172  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 11:20:24.172  6606  6664 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 11:20:24.172  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 11:20:24.173  6606  6664 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 11:20:24.173  6606  6664 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 11:20:24.173  6606  6664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 11:20:24.173  6606  6664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 11:20:24.174  6606  6664 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 11:20:24.174  6606  6664 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 11:20:24.174  6606  6664 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 11:20:24.174  6606  6664 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 11:20:24.174  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:24.174  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1916ce73 added. We now have 2 listener(s)
08-26 11:20:24.174  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:24.176  6606  6664 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 11:20:24.177  1034  1923 D WifiServiceImplEx: setWifiEnabled: true pid=6606, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 11:20:24.178  1034  1923 D WifiService: setWifiEnabled: true pid=6606, uid=10118
08-26 11:20:24.178  1034  1923 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 11:20:24.178  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:24.179  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18f2130 added. We now have 3 listener(s)
08-26 11:20:24.179  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:24.181  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:24.181  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@212df1a9 added. We now have 4 listener(s)
08-26 11:20:24.181  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:24.182  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:24.182  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31e7932e added. We now have 5 listener(s)
08-26 11:20:24.182  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:24.184  1034  2029 D WifiServiceImplEx: setWifiEnabled: false pid=6606, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 11:20:24.184  1034  2029 D WifiService: setWifiEnabled: false pid=6606, uid=10118
08-26 11:20:24.184  1034  2029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:24.205  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:24.206  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:24.206  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 11:20:24.207  1034  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:24.207  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:24.207  1034  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:24.208  1034  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:24.208  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:24.208  1034  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 11:20:24.208  1034  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 11:20:24.208  1034  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 11:20:24.209  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:24.209  1034  1050 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@16c69510 mBinding = false
08-26 11:20:24.209  1034  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 11:20:24.209  1034  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 11:20:24.228  1034  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 11:20:24.229  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 11:20:24.229  1034  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.229  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.229  2768  2768 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-26 11:20:24.229  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 11:20:24.229  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 11:20:24.230  1034  1538 D WifiNative-wlan0: SET ps 1: returned true
08-26 11:20:24.231  1034  2865 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.233   329   892 D CommandListener: Clearing all IP addresses on wlan0
08-26 11:20:24.235  1034  1116 D BluetoothManagerService: Message: 2
08-26 11:20:24.236  1034  1116 D BluetoothManagerService: Sending off request.
08-26 11:20:24.237  4281  4466 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 11:20:24.237  4281  4370 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 11:20:24.237  4281  4370 D BluetoothAdapterProperties: Setting state to 13
08-26 11:20:24.237  4281  4370 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 11:20:24.238  4281  4370 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 11:20:24.238  4281  4370 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 11:20:24.238  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:24.238  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 11:20:24.238  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 11:20:24.241  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 11:20:24.242  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:24.243  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:24.244  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:24.245  4281  4281 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:24.245  4281  4281 D BluetoothMapService: STATE_TURNING_OFF
08-26 11:20:24.245  4281  4281 V BluetoothMapService: Handler(): got msg=4
08-26 11:20:24.245  4281  4281 D BluetoothMapService: MAP Service closeService in
08-26 11:20:24.246  4281  4281 D BluetoothMapMasInstance: MAP Service shutdown
08-26 11:20:24.246  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:24.246  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:24.246  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.247  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 11:20:24.247  4281  4640 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 11:20:24.247  4281  4281 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 11:20:24.248  4281  4281 V BluetoothMapService: MAP Service closeService out
08-26 11:20:24.248  4281  4281 V BtOppService: Receiver DISABLED_ACTION 
08-26 11:20:24.248  4281  4281 I BtOppRfcommListener: stopping Accept Thread
08-26 11:20:24.248  4281  4281 V BtOppRfcommListener: close mBtServerSocket
08-26 11:20:24.248  4281  4674 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:24.249  4281  4674 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 11:20:24.249  4281  4281 V BtOppRfcommListener: waiting for thread to terminate
08-26 11:20:24.249  4281  4281 V BtOppRfcommListener: done waiting for thread to terminate
08-26 11:20:24.250  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 11:20:24.254  1034  1576 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 11:20:24.254  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.255  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.255  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 11:20:24.255  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.255  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 11:20:24.261   329  6847 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 11:20:24.261  1034  1114 D DSQN    : Dns fail occured do internet check.
08-26 11:20:24.261  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-26 11:20:24.261  1034  1034 D DSQN    : try Internet connection check
08-26 11:20:24.266   329  6850 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 11:20:24.266  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 11:20:24.267  1034  1114 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-26 11:20:24.267  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-26 11:20:24.267  1034  6849 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-26 11:20:24.267  1034  6848 D DSQN    : ThreadInternetCheck internet check NOK 
08-26 11:20:24.267  1034  6848 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-26 11:20:24.268  1034  6848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-26 11:20:24.270  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-26 11:20:24.284  1034  1112 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 11:20:24.285  4281  4373 D BluetoothAdapterProperties: Scan Mode:20
08-26 11:20:24.285  4281  4370 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 11:20:24.286  4281  4643 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:24.286  4281  4677 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:24.286  4281  4370 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 11:20:24.287  4281  4696 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:24.289  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 11:20:24.289  4281  4513 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 11:20:24.291  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 11:20:24.291  4281  4513 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 11:20:24.292  4281  4281 V BtOppService: onDestroy
08-26 11:20:24.293  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:24.293  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:24.293  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.293  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:24.317  1034  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 11:20:24.317  1034  1545 D DSQN    : disableDataServiceNotify
08-26 11:20:24.317  1034  1545 D DSQN    : stop dsqn bin
,08-26 11:20:24.321  1034  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 11:20:24.321  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:24.321  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:24.322  1034  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:24.322  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 11:20:24.322  1034  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 11:20:24.322  1034  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 11:20:24.322  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 11:20:24.323  1034  1112 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6873 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 11:20:24.323  1603  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 11:20:24.324  1034  1034 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-26 11:20:24.325  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.325  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.325  1034  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 11:20:24.326  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 11:20:24.327  4281  4281 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 11:20:24.328  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:24.328  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 11:20:24.328  1943  2529 D WifiServiceExtension: isInternetCheckAvailable return false
08-26 11:20:24.328  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:24.329  1034  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:24.329  1034  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:24.329  1034  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 11:20:24.329  1034  1545 D NetworkManagementService: Removing idletimer
08-26 11:20:24.330  1034  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.330  1034  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.330  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.330  1034  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@13167508
08-26 11:20:24.330  1034  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 11:20:24.330  1034  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 11:20:24.331  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:24.331  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 11:20:24.332  1034  1537 D LGWifiP2pService: P2pDisablingState
08-26 11:20:24.332  1034  1537 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.332  1034  1537 D LGWifiP2pService: p2p socket connection lost
08-26 11:20:24.333  1034  1537 D LGWifiP2pService: P2pDisabledState
08-26 11:20:24.333  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 11:20:24.333  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.333  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.333  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 11:20:24.334  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:24.335  1034  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.335  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.335  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.335  1034  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.336  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.336  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.336  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.336  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:24.336  6606 , 6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.336  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.336  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:24.336  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:24.336  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:24.336  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:24.336  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:24.336  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.336  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:24.336  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:24.337  1034  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 11:20:24.337  1034  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.337  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.338  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:24.338  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 11:20:24.338  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 11:20:24.338  1943  1943 D WfdsService: WifiP2pState is changed : false
08-26 11:20:24.338  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 11:20:24.338  1943  2273 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 11:20:24.338  1943  2273 D WfdsService: Set the WFDS Monitor: false
08-26 11:20:24.338  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 11:20:24.338  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.338  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.338  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 11:20:24.338  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 11:20:24.338  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 11:20:24.338  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.339  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 11:20:24.339  1034  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.339  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 11:20:24.339  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 11:20:24.339  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 11:20:24.339  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 11:20:24.339  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 11:20:24.339  1034  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.339  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:24.340  1034  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:24.340  1034  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:24.341  1034  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 11:20:24.341  1034  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.341  1034  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.341  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 11:20:24.341  2768  2768 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 11:20:24.343  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 11:20:24.343  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 11:20:24.343  1034  1538 D WifiNative-wlan0: SET ps 1: returned true
08-26 11:20:24.343   329   892 D CommandListener: Clearing all IP addresses on wlan0
08-26 11:20:24.344  1943  2273 D WfdsMonitor: WFDS Monitor is stopped
08-26 11:20:24.344  1943  2273 D WfdsService: STATE : WfdsDisabledState - enter
08-26 11:20:24.344  1943  2806 D CtrlSupplicant: Received on exit socket, terminate
08-26 11:20:24.344  1943  2806 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 11:20:24.345  1943  2806 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 11:20:24.345  1943  2806 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 11:20:24.345  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 11:20:24.345  1034  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 11:20:24.345  1943  2274 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 11:20:24.345  1943  2273 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 11:20:24.346  1034  1538 D WifiNative-p2p0: TERMINATE: returned true
08-26 11:20:24.346  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:24.346  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:24.346  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 11:20:24.346  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.346  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.346  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 11:20:24.347  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 11:20:24.349  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 11:20:24.349  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:24.349  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:24.350  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:24.350  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 11:20:24.350  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.350  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:24.354  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:24.354  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:24.354  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:24.354  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:24.362  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:24.362  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:24.363  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.367  6853  6853 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 11:20:24.367  6853  6853 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 11:20:24.367  6853  6853 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:24.367  6853  6853 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 11:20:24.368  6853  6853 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 11:20:24.368  6853  6853 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 11:20:24.398  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 11:20:24.398  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.399  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 11:20:24.412  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 11:20:24.412  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.413  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.413  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:24.413  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:24.414  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.415  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 11:20:24.415  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:24.415  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.417  2768  2768 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 11:20:24.417  2768  2768 I wpa_supplicant: monitor socket send errors count : 1
08-26 11:20:24.417  2768  2768 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-26 11:20:24.417  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.417  1034  2780 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 11:20:24.418  1034  2780 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 11:20:24.433  6873  6873 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 11:20:24.434  6873  6873 W LG Account v2.2: No ProfileInfo entries
08-26 11:20:24.434  6873  6873 I LG Account v2.2: isEnabled: false
08-26 11:20:24.434  6873  6873 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 11:20:24.434  6873  6873 I Feature : [Lifetracker]Country: EU
08-26 11:20:24.434  6873  6873 I Feature : [Lifetracker]Operator: OPEN
08-26 11:20:24.434  6873  6873 I Feature : [Lifetracker]Ranking support: false
08-26 11:20:24.434  6873  6873 I Feature : [Lifetracker]Comfort support: false
08-26 11:20:24.434  6873  6873 I Feature : [Lifetracker]Accessory: true
08-26 11:20:24.434  6873  6873 I Feature : [Lifetracker]Health device: true
08-26 11:20:24.435  6873  6873 I Feature : [Lifetracker]Extra Pedometer: false
08-26 11:20:24.435  6873  6873 I Feature : [Lifetracker]Blood glucose device: false
08-26 11:20:24.435  6873  6873 I Feature : [Lifetracker]Device Number: 3
,08-26 11:20:24.441  1034  2865 D DhcpStateMachine: StoppedState
08-26 11:20:24.441  1034  2865 D DhcpStateMachine: StoppedState{ when=-98ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:24.441  1034  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 11:20:24.442  1034  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 11:20:24.443  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:24.454  2768  2768 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 11:20:24.454  2768  2768 W wpa_supplicant: USIM:  scard_deinit function
,08-26 11:20:24.455  1034  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 11:20:24.455  1034  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 11:20:24.455  1034  2780 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 11:20:24.455  1034  2780 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 11:20:24.455  1034  1116 D Tethering: InitialState.processMessage what=4
08-26 11:20:24.455  1034  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:24.455  1034  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:24.455  1034  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118538
08-26 11:20:24.456  1034  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118538
08-26 11:20:24.456  1034  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118539  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 11:20:24.457  1034  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118539  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 11:20:24.475  1034  1935 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6893 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 11:20:24.476  1034  1935 I ActivityManager: Killing 6133:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-26 11:20:24.492  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 11:20:24.507  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 11:20:24.507  1034  1576 W libprocessgroup: failed to open /acct/uid_10014/pid_6133/cgroup.procs: No such file or directory
08-26 11:20:24.507  1034  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:24.508  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:24.515  4281  4281 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 11:20:24.515  4281  4281 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:24.515  4281  4281 V BluetoothPbapReceiver: ***********state = 13
08-26 11:20:24.516  4281  4281 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 11:20:24.516  4281  4281 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:24.517  4281  4281 V BluetoothPbapService: state: 13
08-26 11:20:24.517  4281  4281 V BluetoothPbapService: Pbap Service closeService in
08-26 11:20:24.517  4281  4281 V BluetoothPbapService: successfully stopped pbap service
08-26 11:20:24.517  4281  4281 V BluetoothPbapService: Pbap Service closeService out
08-26 11:20:24.517  4281  4281 V BluetoothPbapService: Pbap Service onDestroy
08-26 11:20:24.517  4281  4281 V BluetoothPbapService: Pbap Service closeService in
08-26 11:20:24.517  4281  4281 V BluetoothPbapService: Pbap Service closeService out
08-26 11:20:24.517  4281  4281 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 11:20:24.518  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:24.519  1034  1116 D BluetoothManagerService: Message: 20
08-26 11:20:24.520  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fae891a:true
08-26 11:20:24.530  2768  2768 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 11:20:24.530  1034  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 11:20:24.530  1034  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 11:20:24.530  1034  2780 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 11:20:24.530  1034  1116 D BluetoothManagerService: Message: 30
08-26 11:20:24.531  1034  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 11:20:24.536  1034  1116 D BluetoothManagerService: Message: 30
08-26 11:20:24.538  6853  6853 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 11:20:24.539  6853  6853 D BluetoothMap: Create BluetoothMap proxy object
08-26 11:20:24.540  1034  1116 D BluetoothManagerService: Message: 30
08-26 11:20:24.542  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 11:20:24.543  1034  1116 D BluetoothManagerService: Message: 30
08-26 11:20:24.545  6853  6853 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 11:20:24.545  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 11:20:24.546  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:24.546  6853  6853 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-26 11:20:24.554  1034  1935 I ActivityManager: Killing 6191:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-26 11:20:24.572  1034  1703 W libprocessgroup: failed to open /acct/uid_10004/pid_6191/cgroup.procs: No such file or directory
,08-26 11:20:24.573  6853  6853 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-26 11:20:24.576  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 11:20:24.590  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:24.609  6853  6853 D BluetoothInputDevice: Proxy object connected
,08-26 11:20:24.611  6853  6853 D HidProfile: Bluetooth service connected
,08-26 11:20:24.613  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 11:20:24.614  6853  6853 D PanProfile: Bluetooth service connected
08-26 11:20:24.616  6853  6853 D BluetoothMap: Proxy object connected
08-26 11:20:24.618  6853  6853 D MapProfile: Bluetooth service connected
08-26 11:20:24.618  6853  6853 D BluetoothMap: getConnectedDevices()
08-26 11:20:24.619  6853  6853 D BluetoothMap: Bluetooth is Not enabled
08-26 11:20:24.633  1034  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 11:20:24.633  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:24.633  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:24.633  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 11:20:24.637  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 11:20:24.637  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:24.638  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 11:20:24.638  1943  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 11:20:24.638  1943  2273 D WfdsService: Set the WFDS Monitor: false
08-26 11:20:24.638  1943  2273 D WfdsMonitor: WFDS Monitor is stopped
08-26 11:20:24.644  2434  2434 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:24.644  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 11:20:24.646  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 11:20:24.646  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 11:20:24.647  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:24.650  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:24.654  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 11:20:24.654  6606  6606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 11:20:24.696  6853  6853 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:24.696  6853  6853 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:24.706  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:24.708  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-26 11:20:24.711  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 11:20:24.716  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 11:20:24.720  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 11:20:24.728  1034  1889 I ActivityManager: Killing 6390:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-26 11:20:24.730  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 11:20:24.787  4281  4281 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 11:20:24.787  4281  4281 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 11:20:24.788  1034  1785 W libprocessgroup: failed to open /acct/uid_10008/pid_6390/cgroup.procs: No such file or directory
08-26 11:20:24.789  4281  4281 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-26 11:20:24.807  4281  4281 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:24.807  4281  4281 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-26 11:20:24.887  1034  1889 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6921 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 11:20:24.895  4281  4281 V BluetoothFtpService: Ftp Service onStartCommand
08-26 11:20:24.895  4281  4281 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:24.896  4281  4281 V BluetoothFtpService: Ftp Service closeService
08-26 11:20:24.896  4281  4281 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 11:20:24.897  4281  4281 V BluetoothFtpService: successfully stopped ftp service
08-26 11:20:24.897  4281  4281 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:24.898  4281  4281 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:24.898  4281  4281 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 11:20:24.898  4281  4281 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:24.898  4281  4281 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 11:20:24.898  4281  4281 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 11:20:24.899  4281  4281 V BluetoothFtpService: Ftp Service onDestroy
08-26 11:20:24.900  4281  4281 V BluetoothFtpService: Ftp Service closeService
,08-26 11:20:24.954  1034  1887 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6941 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 11:20:24.956  4281  4281 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:24.956  4281  4281 V BluetoothSapService: state: 13
08-26 11:20:24.956  4281  4281 V BluetoothSapService: Stopping SAP server process
08-26 11:20:24.957  4281  4281 V BluetoothSapService: Sap Service closeSapService in
08-26 11:20:24.957  4281  4281 V BluetoothSapService: Close listen Socket : 
08-26 11:20:24.958  4281  4281 V BluetoothSapService: Close rfcomm Socket : 
08-26 11:20:24.958  4281  4281 V BluetoothSapService: Close sapd  Socket : 
08-26 11:20:24.961  4281  4281 V BluetoothSapService: Sap Service closeSapService out
08-26 11:20:24.961  4281  4281 V BluetoothSapService: Sap Service onDestroy
08-26 11:20:24.961  4281  4281 V BluetoothSapService: Sap Service closeSapService in
08-26 11:20:24.961  4281  4281 V BluetoothSapService: Close listen Socket : 
08-26 11:20:24.961  4281  4281 V BluetoothSapService: Close rfcomm Socket : 
08-26 11:20:24.961  4281  4281 V BluetoothSapService: Close sapd  Socket : 
08-26 11:20:24.962  4281  4281 V BluetoothSapService: Sap Service closeSapService out
08-26 11:20:24.989  6921  6921 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 11:20:25.026  6941  6941 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 11:20:25.026  6921  6921 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 11:20:25.042  1034  1993 I ActivityManager: Killing 6434:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 11:20:25.067  6921  6921 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 11:20:25.067  6921  6921 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-26 11:20:25.068  6921  6921 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 11:20:25.069  6921  6921 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 11:20:25.069  6921  6921 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-26 11:20:25.071  6921  6921 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 11:20:25.076  6921  6921 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 11:20:25.095  1034  2000 W libprocessgroup: failed to open /acct/uid_10011/pid_6434/cgroup.procs: No such file or directory
,08-26 11:20:25.120  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:25.126  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:25.169  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 11:20:25.175  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:25.180  6921  6921 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-26 11:20:25.184  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 11:20:25.184  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 11:20:25.184  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:25.188  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 11:20:25.190  6921  6921 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-26 11:20:25.199  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:25.211  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:25.212  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 11:20:25.215  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:25.221  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:25.225  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 11:20:25.225  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 11:20:25.225  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:25.233  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:25.244  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:25.254  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:25.254  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 11:20:25.257  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:25.295  4281  4513 W bt-btif : ag scb idx 1 not allocated
08-26 11:20:25.295  4281  4373 D bt_hci_bdroid: cleanup
08-26 11:20:25.296  4281  4513 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 11:20:25.296  4281  4515 I bt_lpm  : LPM is already off!!!
,08-26 11:20:25.298  4281  4598 I bt_userial_mct: exiting userial_read_thread
08-26 11:20:25.298  4281  4598 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 11:20:25.298  4281  4373 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 11:20:25.299  4281  4515 I bt_vendor: hw_epilog_process
08-26 11:20:25.299  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:25.299  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:25.299  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:25.299  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:25.300  4281  4373 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:25.300  4281  4373 D bt_userial_mct: userial_close
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:25.300  4281  4373 E bt_userial_mct: pthread_join() FAILED result:3
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:25.300  4281  4373 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:25.300  4281  4513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:25.300  4281  4513 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 11:20:25.325  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-26 11:20:25.333  1034  1935 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6962 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 11:20:25.386  4281  4373 D bt_hci_bdroid: set_power 0
08-26 11:20:25.386  4281  4373 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 11:20:25.386  4281  4373 I bt_vendor: bluetooth satus is on
08-26 11:20:25.386  4281  4373 I bt_vendor: bt-vendor : resetting BT status
08-26 11:20:25.386  4281  4373 I bt_vendor: Starting hciattach daemon
08-26 11:20:25.387  4281  4373 I bt_vendor: try to set false
08-26 11:20:25.389  4281  4373 I bt_vendor: Starting hciattach daemon
08-26 11:20:25.389  4281  4373 I bt_vendor: try to set false
08-26 11:20:25.389  4281  4373 I bt_vendor: cleanup
08-26 11:20:25.391  4281  4513 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 11:20:25.396  4281  4373 I GKI_LINUX: GKI_exit_task 0 done
08-26 11:20:25.396  4281  4373 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 11:20:25.399  4281  4370 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 11:20:25.404  4281  4281 D HeadsetService: Received stop request...Stopping profile...
08-26 11:20:25.405  4281  4281 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 11:20:25.405  4281  4281 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 11:20:25.405  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f1d50b
08-26 11:20:25.405  4281  4461 D HeadsetStateMachine: Exit Disconnected: -1
08-26 11:20:25.406  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:25.406  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 11:20:25.407  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:25.407  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:25.407  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:25.410  4281  4281 D A2dpService: Received stop request...Stopping profile...
08-26 11:20:25.411  4281  4497 D A2dpStateMachine: Exit Disconnected: -1
08-26 11:20:25.411  4281  4370 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 11:20:25.411  4281  4281 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-26 11:20:25.413  4281  4281 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 11:20:25.413  4281  4281 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 11:20:25.413  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f1d50b
08-26 11:20:25.414  4281  4281 D HeadsetStateMachine: Unbinding service...
08-26 11:20:25.416  4281  4281 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 11:20:25.416  4281  4281 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 11:20:25.416  4281  4281 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 11:20:25.416  4281  4281 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 11:20:25.416  4281  4281 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 11:20:25.416  4281  4281 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 11:20:25.416  4281  4281 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 11:20:25.416  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 11:20:25.416  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 11:20:25.417  4281  4281 D HidService: Received stop request...Stopping profile...
08-26 11:20:25.417  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f1d50b
08-26 11:20:25.418  6853  6853 D BluetoothInputDevice: Proxy object disconnected
08-26 11:20:25.418  4281  4281 D HealthService: Received stop request...Stopping profile...
08-26 11:20:25.418  6853  6853 D HidProfile: Bluetooth service disconnected
08-26 11:20:25.418  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f1d50b
08-26 11:20:25.420  4281  4281 D PanService: Received stop request...Stopping profile...
08-26 11:20:25.420  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f1d50b
08-26 11:20:25.421  4281  4281 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 11:20:25.421  6853  6853 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 11:20:25.421  6853  6853 D PanProfile: Bluetooth service disconnected
08-26 11:20:25.421  4281  4281 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 11:20:25.421  4281  4281 D BtGatt.GattService: stop()
08-26 11:20:25.422  4281  4281 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 11:20:25.423  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f1d50b
08-26 11:20:25.424  4281  4281 D BluetoothMapService: Received stop request...Stopping profile...
08-26 11:20:25.424  4281  4281 D BluetoothMapService: stop()
,08-26 11:20:25.426  4281  4281 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 11:20:25.426  4281  4281 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 11:20:25.427  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4f1d50b
,08-26 11:20:25.428  6853  6853 D BluetoothMap: Proxy object disconnected
08-26 11:20:25.429  4281  4281 I BluetoothA2dpServiceJni: cleanupNative
08-26 11:20:25.429  4281  4498 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 11:20:25.429  4281  4281 I GKI_LINUX: GKI_exit_task 2 done
08-26 11:20:25.429  4281  4281 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 11:20:25.430  4281  4281 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 11:20:25.430  4281  4281 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 11:20:25.430  6853  6853 D MapProfile: Bluetooth service disconnected
08-26 11:20:25.430  4281  4281 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 11:20:25.430  4281  4281 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 11:20:25.430  4281  4281 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 11:20:25.431  4281  4281 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 11:20:25.431  4281  4281 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 11:20:25.432  4281  4281 V BluetoothMapService: Handler(): got msg=4
08-26 11:20:25.432  4281  4281 D BluetoothMapService: MAP Service closeService in
08-26 11:20:25.432  4281  4281 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 11:20:25.432  4281  4281 V BluetoothMapService: MAP Service closeService out
08-26 11:20:25.432  4281  4370 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 11:20:25.432  4281  4370 D BluetoothAdapterProperties: Setting state to 10
08-26 11:20:25.432  4281  4370 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 11:20:25.433  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:25.433  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 11:20:25.433  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 11:20:25.433  4281  4370 I BluetoothAdapterState: Entering OffState
08-26 11:20:25.433  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 11:20:25.434  4281  4281 D BluetoothMapService: cleanup()
08-26 11:20:25.434  4281  4281 D BluetoothMapService: MAP Service closeService in
08-26 11:20:25.434  4281  4281 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 11:20:25.434  4281  4281 V BluetoothMapService: MAP Service closeService out
08-26 11:20:25.434  1853  2599 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:25.435  6853  6870 D BluetoothPan: onBluetoothStateChange on: false
08-26 11:20:25.436  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:25.436  6853  6872 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 11:20:25.437  6853  6870 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 11:20:25.438  6853  6872 D BluetoothMap: onBluetoothStateChange: up=false
08-26 11:20:25.438  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:25.438  1853  3502 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:25.440  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 11:20:25.440  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 11:20:25.442  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 11:20:25.442  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 11:20:25.442  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@16c69510 mBinding = false
08-26 11:20:25.443  1034  1116 D BluetoothManagerService: Sending unbind request.
08-26 11:20:25.444  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 11:20:25.448  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:25.448  6853  6853 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 11:20:25.449  1943  2115 D LGBluetoothAPIService: Message: 2
08-26 11:20:25.449  1943  2115 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1ec552aa mBinding = false
08-26 11:20:25.449  1943  2115 D LGBluetoothAPIService: Sending unbind request.
08-26 11:20:25.449  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 11:20:25.449  6853  6853 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 11:20:25.449  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:25.451  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:25.453  4281  4373 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 11:20:25.453  4281  4281 I GKI_LINUX: GKI_exit_task 1 done
08-26 11:20:25.453  4281  4281 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 11:20:25.454  4281  4281 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 11:20:25.454  4281  4281 I art     : --- WEIRD: removing null entry 246
08-26 11:20:25.454  4281  4281 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 11:20:25.454  4281  4281 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 11:20:25.454  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:25.456  4281  4281 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 11:20:25.457  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 11:20:25.458  4281  4281 I art     : System.exit called, status: 0
08-26 11:20:25.458  4281  4281 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 11:20:25.460  1603  1603 D BluetoothAdapter: 1068271875: getState() :  mService = null. Returning STATE_OFF
08-26 11:20:25.461  1603  1603 D BluetoothAdapter: 1068271875: getState() :  mService = null. Returning STATE_OFF
08-26 11:20:25.464  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:25.478  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:25.482   333  2154 V AudioFlinger: 4281 died, releasing its sessions
08-26 11:20:25.482   333  2154 V AudioFlinger:  pid 1853 @ 0
08-26 11:20:25.482   333  2154 V AudioFlinger:  pid 3346 @ 1
,08-26 11:20:25.482   333  2154 V AudioFlinger:  pid 3346 @ 2
08-26 11:20:25.483  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 11:20:25.489  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:25.489  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 11:20:25.566  1034  1889 I ActivityManager: Process com.android.bluetooth (pid 4281) has died
08-26 11:20:25.567  1034  1889 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 11:20:25.583  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-26 11:20:25.614  6962  6987 W FormManager: Network not available. Please check & try again.
,08-26 11:20:25.619  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 11:20:25.628  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 11:20:25.628  6853  6853 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 11:20:25.630  6962  6988 V FormManager: Network unavailable.
08-26 11:20:25.637  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 11:20:25.640  6962  6988 V FormManager: Network unavailable.
,08-26 11:20:25.719  1034  1889 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6991 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 11:20:25.725  1034  1889 I ActivityManager: Killing 5935:com.android.contacts/u0a19 (adj 15): empty #17
08-26 11:20:25.788  1034  1703 W libprocessgroup: failed to open /acct/uid_10019/pid_5935/cgroup.procs: No such file or directory
,08-26 11:20:25.809  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-26 11:20:25.810  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 11:20:25.810  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 11:20:25.810  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 11:20:25.811  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 11:20:25.823  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 11:20:25.824  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-26 11:20:25.824  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 11:20:25.824  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 11:20:25.824  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 11:20:25.824  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 11:20:25.833  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 11:20:25.834  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:25.837  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:25.837  6991  6991 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 11:20:25.838  6991  6991 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:25.838  6991  6991 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 11:20:25.839  6991  6991 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 11:20:25.841  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:25.853  6893  6893 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 11:20:25.853  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 11:20:25.853  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 11:20:25.860  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 11:20:25.862  4767  7012 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 11:20:25.862  6991  6991 D BluetoothAdapterApp: Loading JNI Library
,08-26 11:20:25.866  4767  7012 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null,
08-26 11:20:25.873  6962  7013 W FormManager: Network not available. Please check & try again.
08-26 11:20:25.874  6962  7015 V FormManager: Network unavailable.
08-26 11:20:25.877  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 11:20:25.881  4767  7010 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:25.881  6962  7015 V FormManager: Network unavailable.
08-26 11:20:25.899  6921  6921 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 11:20:25.900  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 11:20:25.900  6991  6991 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3cf966d0 Instance Count = 1
08-26 11:20:25.901  6921  6921 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 11:20:25.906  6991  6991 D BluetoothAdapterApp: onCreate
08-26 11:20:25.931  6991  6991 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-26 11:20:25.931  6991  6991 D ProfileConfigQcom: Adding HeadsetService
08-26 11:20:25.931  6991  6991 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 11:20:25.932  6991  6991 D ProfileConfigQcom: Adding A2dpService
08-26 11:20:25.932  6991  6991 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 11:20:25.932  6991  6991 D ProfileConfigQcom: Adding HidService
08-26 11:20:25.932  6991  6991 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 11:20:25.932  6991  6991 D ProfileConfigQcom: Adding HealthService
08-26 11:20:25.933  6991  6991 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 11:20:25.934  6991  6991 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 11:20:25.934  6991  6991 D ProfileConfigQcom: Adding PanService
08-26 11:20:25.934  6991  6991 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 11:20:25.935  6991  6991 D ProfileConfigQcom: Adding GattService
08-26 11:20:25.935  6991  6991 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 11:20:25.935  6991  6991 D ProfileConfigQcom: Adding BluetoothMapService
08-26 11:20:25.935  6991  6991 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 11:20:25.937  6991  6991 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 11:20:25.942  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 11:20:25.944  6991  6991 V LGMDMManagerInternal: Create singleton instance
,08-26 11:20:25.948  6921  6921 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:25.948  6921  6921 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 11:20:25.958  6921  6921 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-26 11:20:25.959  6921  6921 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 11:20:25.959  6921  6921 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 11:20:25.959  6921  6921 V SoundPool: doLoad: loading sample sampleID=1
08-26 11:20:25.959  6921  6921 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 11:20:25.964  6921  7019 V SoundPool: Start decode
08-26 11:20:25.964  6921  7019 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 11:20:25.965   333   333 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 11:20:25.965   333   333 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 11:20:25.965   333   333 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 11:20:25.965   333   333 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 11:20:25.965  6764  6764 D UEI.SmartControl: QS Service created
08-26 11:20:25.965   333   333 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 11:20:25.965   333   333 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 11:20:25.965   333   333 V MediaPlayerService: player type = 3
08-26 11:20:25.965   333   333 V AwesomePlayer: AwesomePlayer create()
08-26 11:20:25.965  6921  6921 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 11:20:25.965   333   333 V AwesomePlayer: reset_l() 
08-26 11:20:25.965   333   333 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:25.965   333   333 V AwesomePlayer: setAudioSink() 
08-26 11:20:25.965   333   333 V AwesomePlayer: reset_l() 
08-26 11:20:25.965   333   333 V AudioCache: notify(0xb54747c0, 8, 0, 0)
08-26 11:20:25.966   333   333 V AudioCache: ignored
08-26 11:20:25.966   333   333 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:25.966   333   333 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 11:20:25.966   333   333 V AwesomePlayer: setDataSource_l dataSource
08-26 11:20:25.966   333   333 V LGParserOSAL: SniffLGParser start
08-26 11:20:25.966   333   333 V LGParserOSAL: MainType:5, SubType=0
08-26 11:20:25.966   333   333 V LGParserOSAL: #### check Mime : application/ogg
08-26 11:20:25.966   333   333 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 11:20:25.966   333   333 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 11:20:25.978  6921  6921 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 11:20:25.980  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 11:20:25.981  6764  6764 I UEI.SmartControl: Service initServices...
08-26 11:20:25.981  6764  6764 D UEI.SmartControl: QS start get config
,08-26 11:20:26.013  6921  6921 V LGMDMManager: Create singleton instance
08-26 11:20:26.015   333   333 V LGParserOSAL: supported mime: application/ogg
08-26 11:20:26.015   333   333 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 11:20:26.015   333   333 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 11:20:26.015   333   333 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 11:20:26.015   333   333 V AwesomePlayer: AudioTrack Setting
08-26 11:20:26.015   333   333 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 11:20:26.015   333   333 V AwesomePlayer: setAudioSource() 
08-26 11:20:26.015   333   333 V MediaPlayerService: prepare
08-26 11:20:26.015   333   333 V AwesomePlayer: prepareAsync_l() 
08-26 11:20:26.015   333   333 V MediaPlayerService: wait for prepare
08-26 11:20:26.016   333  7020 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 11:20:26.016   333  7020 V AwesomePlayer: initAudioDecoder() 
08-26 11:20:26.016   333  7020 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 11:20:26.016   333  7020 V AudioSystem: isOffloadSupported()
08-26 11:20:26.016   333  7020 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 11:20:26.016   333  7020 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 11:20:26.016   333  7020 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 11:20:26.016   333  7020 V AwesomePlayer: getUseOffload() = 0 
08-26 11:20:26.016   333  7020 V OMXCodec: OMXCodec::Create
08-26 11:20:26.016   333  7020 V OMXCodec: findMatchingCodecs()
08-26 11:20:26.016   333  7020 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 11:20:26.016   333  7020 V OMXCodec: matchingCodecs.size()=1
08-26 11:20:26.016   333  7020 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 11:20:26.018   333  7020 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 11:20:26.018   333  7020 V LGCodecAdapter: LG Codec Adapter start
08-26 11:20:26.018   333  7020 V OMXCodec: OMXCodec Createtor
08-26 11:20:26.018   333  7020 V OMXCodec: setComponentRole
08-26 11:20:26.018   333  7020 V OMXCodec: configureCodec protected=0
08-26 11:20:26.018   333  7020 V LGCodecAdapter: called getLGCodecSpecificData
08-26 11:20:26.018   333  7020 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 11:20:26.018   333  7020 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 11:20:26.019   333  7020 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 11:20:26.019   333  7020 V LGCodecOSAL: Not support LGCodec
08-26 11:20:26.019   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 11:20:26.019   333  7020 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 11:20:26.019   333  7020 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 11:20:26.019   333  7020 I AwesomePlayer: Could not offload audio decode, try pcm offload
,08-26 11:20:26.019   333  7020 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 11:20:26.019   333  7020 V AudioSystem: isOffloadSupported()
08-26 11:20:26.019   333  7020 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 11:20:26.019   333  7020 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 11:20:26.019   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 11:20:26.019   333  7020 V OMXCodec: init()
08-26 11:20:26.019   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 11:20:26.019   333  7020 V OMXCodec: allocateBuffers
08-26 11:20:26.019   333  7020 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 11:20:26.019   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 11:20:26.019   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-26 11:20:26.019   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-26 11:20:26.019   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-26 11:20:26.020   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-26 11:20:26.020   333  7020 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 11:20:26.020   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 11:20:26.020   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-26 11:20:26.020   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-26 11:20:26.020   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-26 11:20:26.020   333  7020 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-26 11:20:26.020   333  7020 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 11:20:26.020   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 11:20:26.020   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 11:20:26.020   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 11:20:26.020   333  7020 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 11:20:26.020   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 11:20:26.020   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 11:20:26.020   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 11:20:26.020   333  7020 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 11:20:26.020   333  7020 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 11:20:26.020   333  7020 V AudioCache: notify(0xb54747c0, 5, 0, 0)
08-26 11:20:26.020   333  7020 V AudioCache: ignored
08-26 11:20:26.020   333  7020 V AudioCache: notify(0xb54747c0, 1, 0, 0)
08-26 11:20:26.020   333  7020 V AudioCache: prepared
08-26 11:20:26.020   333   333 V AudioCache: wait - success
08-26 11:20:26.020   333   333 V MediaPlayerService: start
08-26 11:20:26.020   333   333 V AwesomePlayer: play_l() 
08-26 11:20:26.020   333   333 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 11:20:26.021   333   333 V AwesomePlayer: createAudioPlayer_l
08-26 11:20:26.021   333   333 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 11:20:26.021   333   333 V AwesomePlayer: startAudioPlayer_l() 
08-26 11:20:26.021   333   333 D AudioPlayer: start of Playback, useOffload 0
08-26 11:20:26.021   333   333 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 11:20:26.021   333   333 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific ,data
08-26 11:20:26.023   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 11:20:26.023   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 11:20:26.023   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 11:20:26.024   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 11:20:26.025   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 11:20:26.025   333  7022 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 11:20:26.025   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 11:20:26.025   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-26 11:20:26.025   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-26 11:20:26.025   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-26 11:20:26.025   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-26 11:20:26.025   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 11:20:26.026   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 11:20:26.028   333   333 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 11:20:26.030   333   333 V AudioCache: notify(0xb54747c0, 6, 0, 0)
08-26 11:20:26.030   333   333 V AudioCache: ignored
08-26 11:20:26.030   333   333 V MediaPlayerService: wait for playback complete
08-26 11:20:26.031   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.031   333  7023 V AudioCache: memcpy(0xaf004000, 0xb1472000, 4096)
,08-26 11:20:26.033   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.033   333  7023 V AudioCache: memcpy(0xaf005000, 0xb1472000, 4096)
08-26 11:20:26.034   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.034   333  7023 V AudioCache: memcpy(0xaf006000, 0xb1472000, 4096)
08-26 11:20:26.035   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.035   333  7023 V AudioCache: memcpy(0xaf007000, 0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: memcpy(0xaf008000, 0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: memcpy(0xaf009000, 0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: memcpy(0xaf00a000, 0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.037   333  7023 V AudioCache: memcpy(0xaf00b000, 0xb1472000, 4096)
08-26 11:20:26.038   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.038   333  7023 V AudioCache: memcpy(0xaf00c000, 0xb1472000, 4096)
08-26 11:20:26.038   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.038   333  7023 V AudioCache: memcpy(0xaf00d000, 0xb1472000, 4096)
08-26 11:20:26.038   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.038   333  7023 V AudioCache: memcpy(0xaf00e000, 0xb1472000, 4096)
08-26 11:20:26.039   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.039   333  7023 V AudioCache: memcpy(0xaf00f000, 0xb1472000, 4096)
08-26 11:20:26.039   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.039   333  7023 V AudioCache: memcpy(0xaf010000, 0xb1472000, 4096)
08-26 11:20:26.039   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.039   333  7023 V AudioCache: memcpy(0xaf011000, 0xb1472000, 4096)
08-26 11:20:26.040   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.040   333  7023 V AudioCache: memcpy(0xaf012000, 0xb1472000, 4096)
08-26 11:20:26.040   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.040   333  7023 V AudioCache: memcpy(0xaf013000, 0xb1472000, 4096)
08-26 11:20:26.040   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.040   333  7023 V AudioCache: memcpy(0xaf014000, 0xb1472000, 4096)
08-26 11:20:26.041   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.041   333  7023 V AudioCache: memcpy(0xaf015000, 0xb1472000, 4096)
08-26 11:20:26.041   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.041   333  7023 V AudioCache: memcpy(0xaf016000, 0xb1472000, 4096)
08-26 11:20:26.042   333  7023 V AudioCache: write(0xb1472000, 4096)
,08-26 11:20:26.044   333  7023 V AudioCache: memcpy(0xaf017000, 0xb1472000, 4096)
08-26 11:20:26.046   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.046   333  7023 V AudioCache: memcpy(0xaf018000, 0xb1472000, 4096)
08-26 11:20:26.046   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.046   333  7023 V AudioCache: memcpy(0xaf019000, 0xb1472000, 4096)
08-26 11:20:26.047   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.047   333  7023 V AudioCache: memcpy(0xaf01a000, 0xb1472000, 4096)
08-26 11:20:26.048   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.048   333  7023 V AudioCache: memcpy(0xaf01b000, 0xb1472000, 4096)
08-26 11:20:26.048   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.048   333  7023 V AudioCache: memcpy(0xaf01c000, 0xb1472000, 4096)
08-26 11:20:26.048   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.048   333  7023 V AudioCache: memcpy(0xaf01d000, 0xb1472000, 4096)
08-26 11:20:26.049   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.050   333  7023 V AudioCache: memcpy(0xaf01e000, 0xb1472000, 4096)
08-26 11:20:26.050   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.050   333  7023 V AudioCache: memcpy(0xaf01f000, 0xb1472000, 4096)
08-26 11:20:26.050   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.050   333  7023 V AudioCache: memcpy(0xaf020000, 0xb1472000, 4096)
08-26 11:20:26.050   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.050   333  7023 V AudioCache: memcpy(0xaf021000, 0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: memcpy(0xaf022000, 0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: memcpy(0xaf023000, 0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: memcpy(0xaf024000, 0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.052   333  7023 V AudioCache: memcpy(0xaf025000, 0xb1472000, 4096)
08-26 11:20:26.053   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.053   333  7023 V AudioCache: memcpy(0xaf026000, 0xb1472000, 4096)
08-26 11:20:26.053   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.053   333  7023 V AudioCache: memcpy(0xaf027000, 0xb1472000, 4096)
08-26 11:20:26.053   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.053   333  7023 V AudioCache: memcpy(0xaf028000, 0xb1472000, 4096)
08-26 11:20:26.054   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.054   333  7023 V AudioCache: memcpy(0xaf029000, 0xb1472000, 4096)
08-26 11:20:26.054   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.054   333  7023 V AudioCache: memcpy(0xaf02a000, 0xb1472000, 4096)
08-26 11:20:26.054   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.054   333  7023 V AudioCache: memcpy(0xaf02b000, 0xb1472000, 4096)
08-26 11:20:26.055   333  7023 V AudioCache: write(0xb1472000, 4096)
,08-26 11:20:26.055   333  7023 V AudioCache: memcpy(0xaf02c000, 0xb1472000, 4096)
08-26 11:20:26.055   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.055   333  7023 V AudioCache: memcpy(0xaf02d000, 0xb1472000, 4096)
08-26 11:20:26.055   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.055   333  7023 V AudioCache: memcpy(0xaf02e000, 0xb1472000, 4096)
08-26 11:20:26.056   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.056   333  7023 V AudioCache: memcpy(0xaf02f000, 0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: memcpy(0xaf030000, 0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: memcpy(0xaf031000, 0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: memcpy(0xaf032000, 0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.057   333  7023 V AudioCache: memcpy(0xaf033000, 0xb1472000, 4096)
08-26 11:20:26.058   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.058   333  7023 V AudioCache: memcpy(0xaf034000, 0xb1472000, 4096)
08-26 11:20:26.058  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:26.058   333  7023 V AudioCache: write(0xb1472000, 4096)
08-26 11:20:26.058   333  7023 V AudioCache: memcpy(0xaf035000, 0xb1472000, 4096)
08-26 11:20:26.058   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 11:20:26.058   333  7023 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 11:20:26.058   333  7023 V AwesomePlayer: postAudioEOS() 
08-26 11:20:26.058   333  7023 V AudioCache: write(0xb1472000, 280)
08-26 11:20:26.058   333  7023 V AudioCache: memcpy(0xaf036000, 0xb1472000, 280)
08-26 11:20:26.060   333  7020 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 11:20:26.060   333  7020 V AwesomePlayer: onStreamDone
08-26 11:20:26.060   333  7020 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 11:20:26.060   333  7020 V AudioCache: notify(0xb54747c0, 2, 0, 0)
08-26 11:20:26.060   333  7020 V AudioCache: playback complete
08-26 11:20:26.060   333  7020 V AwesomePlayer: pause_l() 
08-26 11:20:26.060   333  7020 V AudioCache: notify(0xb54747c0, 7, 0, 0)
08-26 11:20:26.060   333  7020 V AudioCache: ignored
08-26 11:20:26.060   333  7020 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:26.060   333   333 V AudioCache: wait - success
08-26 11:20:26.060   333   333 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 11:20:26.060   333  7020 D AudioPlayer: Pause Playback at 1068125
08-26 11:20:26.061   333   333 V AwesomePlayer: reset_l() 
08-26 11:20:26.061   333   333 V AudioCache: notify(0xb54747c0, 8, 0, 0)
08-26 11:20:26.061   333   333 V AudioCache: ignored
08-26 11:20:26.061   333   333 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:26.061   333   333 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 11:20:26.061   333   333 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 11:20:26.061   333   333 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 11:20:26.061   333   333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 11:20:26.061   333   333 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 11:20:26.061   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 11:20:26.061   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 11:20:26.061   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 11:20:26.061   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-26 11:20:26.061   333  7022 V OMXCodec: [OMX.google.vorb,is.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:26.062   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 11:20:26.062  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:26.063  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:26.063  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 11:20:26.063   333   333 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 11:20:26.063   333   333 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 11:20:26.063   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 11:20:26.063   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 11:20:26.063   333  7022 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 11:20:26.063   333   333 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 11:20:26.063   333   333 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 11:20:26.064   333   333 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 11:20:26.064  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:26.064  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 11:20:26.065   333   333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 11:20:26.065   333   333 D AudioPlayer: AudioPlayer releasing audio source
08-26 11:20:26.065   333   333 D AudioPlayer: AudioPlayer done releasing audio source
08-26 11:20:26.065   333   333 V AwesomePlayer: reset_l() 
08-26 11:20:26.065   333   333 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:26.065   333   333 V AwesomePlayer: ~AwesomePlayer call
08-26 11:20:26.065   333   333 V AwesomePlayer: reset_l() 
08-26 11:20:26.065   333   333 V AwesomePlayer: cancelPlayerEvents
,08-26 11:20:26.066  6921  7019 V SoundPool: close(31)
08-26 11:20:26.066  6921  7019 V SoundPool: pointer = 0xa0021000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 11:20:26.072  6941  6941 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 11:20:26.108  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-26 11:20:26.110  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-26 11:20:26.112  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5239
08-26 11:20:26.291  6764  6764 I UEI.SmartControl: Supports setup maps: true
,08-26 11:20:26.294  6764  6764 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 11:20:26.294  6764  6764 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 11:20:26.294  6764  6764 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 11:20:26.294  6764  6764 I UEI.SmartControl: ### init IR Blaster...
08-26 11:20:26.298  6764  6764 D serial_port: Configuring serial port
08-26 11:20:26.298  6764  6764 E UEI.SmartControl: UEIBLaster setting for 616
08-26 11:20:26.298  6764  6764 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 11:20:26.298  6764  6764 I UEI.SmartControl: configuring settings for MAXQ616
08-26 11:20:26.298  6764  6764 I UEI.SmartControl: Get version...
08-26 11:20:26.317  6764  7025 D UEI.SmartControl: serial port data available: 21
,08-26 11:20:26.344  6764  6764 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 11:20:26.344  6764  6764 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 11:20:26.344  6764  6764 I UEI.SmartControl: QS saving settings...
08-26 11:20:26.347  6764  6764 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 11:20:26.363  6764  7025 D UEI.SmartControl: serial port data available: 4
,08-26 11:20:26.401  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 11:20:26.408  6764  6764 E UEI.SmartControl: Services init done
08-26 11:20:26.408  6764  6764 D UEI.SmartControl: QS Service init finished
08-26 11:20:26.409  6764  6764 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 11:20:26.409  6764  6764 D UEI.SmartControl: QS Service version code: 201091
08-26 11:20:26.409  6764  6764 D UEI.SmartControl: Service requested: Control
08-26 11:20:26.412  6764  6764 D UEI.SmartControl: Internal service binding...
08-26 11:20:26.413  6921  6921 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 11:20:26.415  6764  6779 I UEI.SmartControl: ------ IControl API: 11
08-26 11:20:26.416  6764  6779 D UEI.SmartControl: File observer start...
,08-26 11:20:26.417  6764  6779 E UEI.SmartControl: IR Port is disabled: false
08-26 11:20:26.417  6764  6779 D UEI.SmartControl: Starting file observer...
08-26 11:20:26.419  6764  6779 I UEI.SmartControl: Registering callback...
08-26 11:20:26.419  6764  6792 I UEI.SmartControl: ------ IControl API: 19
08-26 11:20:26.420  6764  6792 I UEI.SmartControl: Registering Services Ready callback...
08-26 11:20:26.421  6764  7034 I UEI.SmartControl: Device manager: loading config....
08-26 11:20:26.421  6764  7034 D UEI.SmartControl: ----------- loading internal config...
08-26 11:20:26.425  6764  7034 E UEI.SmartControl: Loading SETTINGS...
08-26 11:20:26.430  6764  7034 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 11:20:26.438  6764  7033 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 11:20:26.438  6764  7033 D UEI.SmartControl: -----service ready thread exits
08-26 11:20:26.439  6921  6939 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 11:20:26.439  6921  7017 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 11:20:26.440  6921  7017 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 11:20:26.440  6921  6921 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 11:20:26.440  6921  6921 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 11:20:26.441  6764  6780 I UEI.SmartControl: ------ IControl API: 8
08-26 11:20:26.442  6921  6921 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 11:20:26.443  6921  6921 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 11:20:26.443  6921  6921 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 11:20:26.443  6921  6921 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 11:20:26.444  6921  6921 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 11:20:26.444  6921  6921 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 11:20:26.446  6921  6921 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-26 11:20:26.450  6921  6921 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 11:20:26.451  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 11:20:26.452  6921  6921 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 11:20:26.452  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 11:20:26.453  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 11:20:26.454  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 11:20:26.455  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 11:20:26.456  6921  6921 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472203226455]
08-26 11:20:26.457  6921  6921 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 11:20:26.460  1034  1935 I ActivityManager: Killing 6492:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-26 11:20:26.480  6921  7036 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 11:20:26.557  1034  1935 I ActivityManager: Killing 6456:com.lge.email/u0a23 (adj 15): empty #18
,08-26 11:20:26.615  1034  1703 W libprocessgroup: failed to open /acct/uid_10027/pid_6492/cgroup.procs: No such file or directory
,08-26 11:20:26.621  1034  1889 W libprocessgroup: failed to open /acct/uid_10023/pid_6456/cgroup.procs: No such file or directory
,08-26 11:20:26.629  6921  6921 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-26 11:20:26.630  6921  6921 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-26 11:20:26.630  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 11:20:26.631  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 11:20:26.631  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 11:20:26.632  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 11:20:26.633  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 11:20:26.646  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 11:20:27.331  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:27.348  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-26 11:20:27.354  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:27.358  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:27.362  1034  1887 D WifiServiceImplEx: setWifiEnabled: true pid=6606, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 11:20:27.363  1034  1887 D WifiService: setWifiEnabled: true pid=6606, uid=10118
08-26 11:20:27.364  1034  1887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 11:20:27.370  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:27.373  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:27.378  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-26 11:20:27.387  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:27.391  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:27.395  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:27.395  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:27.395  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 11:20:27.396  1034  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 11:20:27.396  1034  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 11:20:27.397  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 11:20:27.397  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 11:20:27.397  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 11:20:27.397  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 11:20:27.397  1034  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 11:20:27.397  1034  1538 E WifiHW  : unknown target_country: EU , set to default
08-26 11:20:27.397  1034  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 11:20:27.397  1034  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 11:20:27.397  1034  1538 I WifiUtil: gEnableBmps=1
,08-26 11:20:27.407  5767  5767 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 11:20:27.407  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 11:20:27.410  6344  6372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 11:20:27.428  5767  5767 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 11:20:27.459  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:27.530  1034  1935 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7055 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 11:20:27.584  7055  7055 I AppUp4:AppBoxCP: onCreate
08-26 11:20:27.585  7055  7055 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 11:20:27.590  7055  7055 I AppUp4:DB:  setFingerPrint start
08-26 11:20:27.590  7055  7055 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 11:20:27.594  7055  7055 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 11:20:27.594  7055  7055 I AppUp4:DB:  SDK version = 21
08-26 11:20:27.594  7055  7055 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-26 11:20:27.595  7055  7055 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-26 11:20:27.596  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 11:20:27.596  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:27.597  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 11:20:27.598  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 11:20:27.600  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:27.601  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:27.601  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:27.602  7055  7055 I AppUp4:CustModeStarterReceiver: onReceive
08-26 11:20:27.623  7055  7055 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:27.623  7055  7055 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:27.629  7055  7055 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d64ccda
08-26 11:20:27.629  7055  7055 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-26 11:20:27.629  7055  7055 D AppUp4:CustFacade: isPhone : true
08-26 11:20:27.630  7055  7055 D AppUp4:CustModeStarterReceiver: begin check event
08-26 11:20:27.630  7055  7055 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 11:20:27.630  7055  7055 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 11:20:27.630  7055  7074 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 11:20:27.631  7055  7074 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 11:20:27.631  7055  7074 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 11:20:27.632  1034  1887 I ActivityManager: Killing 6515:com.android.vending/u0a44 (adj 15): empty #17
08-26 11:20:27.711  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:27.712  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:27.714  1034  2034 W libprocessgroup: failed to open /acct/uid_10044/pid_6515/cgroup.procs: No such file or directory
,08-26 11:20:27.717  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:27.729  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 11:20:27.737  4767  7078 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:27.741  4767  7079 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:27.741  4767  7079 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 11:20:27.809  1034  1785 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7080 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 11:20:27.903  7080  7080 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 11:20:27.904  7080  7080 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:27.906  7080  7080 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 11:20:27.906  7080  7080 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 11:20:28.036  7080  7080 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 11:20:28.063  7080  7080 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 11:20:28.113  7080  7080 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 11:20:28.139  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 11:20:28.145  1034  1116 D Tethering: InitialState.processMessage what=4
08-26 11:20:28.146  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 11:20:28.160   329   892 D SoftapController: Softap fwReload - Ok
08-26 11:20:28.161  1034  1538 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (756ms)
08-26 11:20:28.165   329   892 D CommandListener: Setting iface cfg
,08-26 11:20:28.165   329   892 D CommandListener: Trying to bring down wlan0
08-26 11:20:28.166   329   892 D CommandListener: Clearing all IP addresses on wlan0
,08-26 11:20:28.169  1034  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 11:20:28.164  7108  7108 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:28.164  7108  7108 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:28.178  7080  7080 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:28.178  7080  7080 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:28.199  7108  7108 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 11:20:28.206  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:28.206  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:28.206  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 11:20:28.209  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 11:20:28.210  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:28.217  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 11:20:28.218  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:28.222  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:28.223  1034  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 11:20:28.223  1034  1538 D WifiMonitor: connecting to supplicant
08-26 11:20:28.234  7108  7108 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 11:20:28.234  7108  7108 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 11:20:28.315  7080  7080 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 11:20:28.335  7108  7108 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 11:20:28.355  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 11:20:28.355  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:28.356  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 11:20:28.363  7080  7080 I HubEmail: JNI_OnLoad()
08-26 11:20:28.363  7080  7080 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 11:20:28.363  7080  7080 I HubEmail: registerNatives()
08-26 11:20:28.364  7080  7080 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 11:20:28.364  7080  7080 I HubEmail: registerNativeMethods()
08-26 11:20:28.364  7080  7080 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 11:20:28.364  7080  7080 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 11:20:28.379  7108  7108 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 11:20:28.386  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 11:20:28.386  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 11:20:28.387  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 11:20:28.387  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 11:20:28.387  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 11:20:28.388  1034  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 11:20:28.388  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:28.389  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:28.390  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:28.391  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-26 11:20:28.392  1034  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 11:20:28.392  1034  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 11:20:28.393  1034  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 11:20:28.393  1034  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 11:20:28.393  1034  7122 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 11:20:28.393  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 11:20:28.393  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 11:20:28.393  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 11:20:28.393  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 11:20:28.393  1034  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 11:20:28.393  1034  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 11:20:28.413  1034  1887 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7123 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 11:20:28.417  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:28.417  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:28.417  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 11:20:28.418  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:28.418  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:28.418  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:28.419  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:28.419  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 11:20:28.419  1034  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 11:20:28.421  1034  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-26 11:20:28.421  1034  1538 D WifiConfigStore: Loading config and enabling all networks 
08-26 11:20:28.421  1034  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 11:20:28.422  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:28.423  1034  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 11:20:28.423  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-26 11:20:28.424  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:28.424  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:28.424  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 11:20:28.425  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:28.425  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:28.425  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 11:20:28.426  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:28.426  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:28.426  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:28.426  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:28.426  6606  6606 V io.jxcore.node.Co,nnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:28.426  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:28.426  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:28.426  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:28.426  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:28.426  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:28.426  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:28.436   355   355 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 19.617ms
,08-26 11:20:28.440  1034  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 11:20:28.444  7080  7120 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:28.439  6962  7118 W FormManager: Network not available. Please check & try again.
08-26 11:20:28.450  6962  7119 V FormManager: Network unavailable.
,08-26 11:20:28.454  6962  7119 V FormManager: Network unavailable.
08-26 11:20:28.457  1034  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 11:20:28.458  1034  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 11:20:28.458  1034  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-26 11:20:28.458  1034  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 11:20:28.460   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 16.226ms
08-26 11:20:28.461  1034  1923 I ActivityManager: Killing 6566:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-26 11:20:28.466  1034  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 11:20:28.466  1034  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 11:20:28.467  1034  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 11:20:28.467  1034  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-26 11:20:28.467  1034  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 11:20:28.467  1034  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 11:20:28.467  1034  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 11:20:28.467  1034  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 11:20:28.468  1034  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 11:20:28.468  1034  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 11:20:28.468  1034  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 11:20:28.468  1034  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 11:20:28.469  1034  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 11:20:28.473   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 13.623ms
,08-26 11:20:28.502  1034  2029 W libprocessgroup: failed to open /acct/uid_10061/pid_6566/cgroup.procs: No such file or directory
,08-26 11:20:28.502  1034  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 11:20:28.502  1034  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 11:20:28.503  1034  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 11:20:28.503  1034  1538 D WifiNative-HAL: Setting external_sim to 1
08-26 11:20:28.504  1034  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 11:20:28.504  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 11:20:28.504  1943  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 11:20:28.504  1943  2273 D WfdsService: Set the WFDS Monitor: true
08-26 11:20:28.504  1943  2273 D WfdsMonitor: WfdsMonitorThread create
08-26 11:20:28.505  1943  2273 D WfdsMonitor: WFDS Monitor is created and started
08-26 11:20:28.505  1034  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 11:20:28.505  1943  2273 D WfdsService: WiFi: Supplicant connection re-established
08-26 11:20:28.505  1034  1538 I WifiNative-HAL: startHal
08-26 11:20:28.505  1034  1538 D wifi    : setting scan oui 0xaf63eee0
08-26 11:20:28.505  1943  7141 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 11:20:28.506  1943  7141 E CtrlSupplicant: Succeed to open control connection
08-26 11:20:28.506  1943  7141 E CtrlSupplicant: Succeed to open monitor connection
08-26 11:20:28.506  1034  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 11:20:28.506  1943  7141 D WfdsMonitor: Supplicant connection established
08-26 11:20:28.506  1034  1538 I WifiNative-HAL: startHal
08-26 11:20:28.506  1034  1538 D wifi    : setting scan oui 0xaf63eee0
08-26 11:20:28.506  1943  2273 D WfdsService: Connected to the supplicant for wfds
08-26 11:20:28.507  1034  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 11:20:28.507  1034  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 11:20:28.507  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 11:20:28.507  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 11:20:28.508  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 11:20:28.508  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 11:20:28.508  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 11:20:28.508  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 11:20:28.508  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 11:20:28.508  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 11:20:28.509  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 11:20:28.509  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 11:20:28.509  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 11:20:28.509  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 11:20:28.509  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 11:20:28.509  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 11:20:28.509  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 11:20:28.509  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 11:20:28.509  7108  7108 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 11:20:28.510  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 11:20:28.510  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 11:20:28.510  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 11:20:28.510  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 11:20:28.511  1034  1538 E WifiNative: : [122,593,141 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 11:20:28.511  1034  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 11:20:28.511  1034  1538 D W,ifiNative-wlan0: RECONNECT: returned true
08-26 11:20:28.511  1034  1538 D WifiNative-wlan0: doString: [STATUS]
08-26 11:20:28.512  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 11:20:28.512  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 11:20:28.512  1034  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 11:20:28.512  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 11:20:28.513  1034  1538 D WifiNative-wlan0: SET ps 1: returned true
,08-26 11:20:28.513  1034  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.514  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 11:20:28.514  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 11:20:28.515  1034  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.515  1034  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.515  1034  1556 I WifiNative-HAL: startHal
,08-26 11:20:28.515  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf63eee0
08-26 11:20:28.515  1034  1556 D wifi    : failed to get capabilities : -3
08-26 11:20:28.515  1034  1556 E WifiScanningService: could not get scan capabilities
08-26 11:20:28.516   329   892 D CommandListener: Setting iface cfg
08-26 11:20:28.516   329   892 D CommandListener: Trying to bring up p2p0
08-26 11:20:28.516  1034  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 11:20:28.516  1034  1537 D LGWifiP2pService: P2pEnablingState
08-26 11:20:28.516  1034  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.516  1034  1537 D LGWifiP2pService: P2p socket connection successful
08-26 11:20:28.516  1034  1537 D LGWifiP2pService: P2pEnabledState
08-26 11:20:28.517  1034  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 11:20:28.517  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 11:20:28.517  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 11:20:28.518  1034  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 11:20:28.518  1943  2273 D WfdsService: Receive the WFDS_ENABLE Method
08-26 11:20:28.518  1943  2273 D WfdsService: Set the WFDS Monitor: true
08-26 11:20:28.518  1034  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 11:20:28.518  1943  2273 D WfdsService: Connected to the supplicant for wfds
08-26 11:20:28.518  1943  2273 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 11:20:28.518  1034  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 11:20:28.518  7108  7108 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 11:20:28.519  1034  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 11:20:28.519  1943  2273 D WfdsService: selectPreferredScanChannel [36]
08-26 11:20:28.519  1943  2273 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 11:20:28.519  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 11:20:28.519  1034  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-26 11:20:28.519  1034  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 11:20:28.519  1034  1537 D LGWifiP2pService: before postfix = G3
08-26 11:20:28.519  1034  1537 D WifiServerServiceExt: postfix byte check : 2
08-26 11:20:28.519  1034  1537 D LGWifiP2pService: after postfix = G3
08-26 11:20:28.519  1034  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 11:20:28.520  1943  1943 D WfdsService: isConnected: false
08-26 11:20:28.520  1034  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 11:20:28.520  1034  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 11:20:28.520  1034  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 11:20:28.520  1034  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 11:20:28.520  1034  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 11:20:28.520  1034  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 11:20:28.521  1034  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 11:20:28.521  1034  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 11:20:28.521  1034  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-26 11:20:28.521  1034  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 11:20:28.521  1034  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 11:20:28.521  1034  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 11:20:28.521  1034  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 11:20:28.522  1034  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 11:20:28.522  1034  1537 D WifiNative-p2p0: doBoolean: P2P_SER,VICE_FLUSH
08-26 11:20:28.522  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 11:20:28.522  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 11:20:28.522  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 11:20:28.523  1034  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 11:20:28.523  1034  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 11:20:28.523  1034  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 11:20:28.523  1034  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 11:20:28.523  1034  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 11:20:28.524  1034  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-26 11:20:28.525  1034  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 11:20:28.526  1034  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 11:20:28.527  1034  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 11:20:28.531  7108  7108 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 11:20:28.531  1034  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 11:20:28.531  1034  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 11:20:28.531  1034  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 11:20:28.532  1034  1537 D LGWifiP2pService: InactiveState
08-26 11:20:28.532  1034  1537 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.532  1034  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 11:20:28.532  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.532  1034  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 11:20:28.532  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 11:20:28.532  1034  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 11:20:28.533  1034  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 11:20:28.533  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.533  1943  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 11:20:28.533  1034  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 11:20:28.533  1034  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.533  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.533  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.533  7108  7108 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 11:20:28.534  7108  7108 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 11:20:28.534  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1034  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 11:20:28.534  1943  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.534  1034  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.534  1034  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.534  1034  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.534  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1034  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.534  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1943  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.534  1034  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.534  1034  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1034  1537 D LGWifiP2pService: InactiveSt,ate{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.534  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.534  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.534  1034  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.535  1943  2273 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 11:20:28.535  1034  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.535  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.535  1034  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.535  1034  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.535  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.535  1034  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.535  1034  1034 E WifiServerServiceExt: No p2p device connected
08-26 11:20:28.537  1034  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 11:20:28.538  1034  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
,08-26 11:20:28.538  1034  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 11:20:28.538  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 11:20:28.539  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 11:20:28.540  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.540  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 11:20:28.540  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.540  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.540  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:28.541  7108  7108 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 11:20:28.542  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.542  1943  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.542  1034  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.542  1034  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.542  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.542  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.543  1034  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 11:20:28.543  1034  1537 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.543  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:28.543  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.543  1034  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 11:20:28.543  1943  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.543  1034  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:28.543  1034  7122 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.543  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.543  1034  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 11:20:28.543  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:28.544  1034  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 11:20:28.544  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 11:20:28.544  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 11:20:28.545  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:28.545  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 11:20:28.545  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:28.545  1034  7122 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:28.545  1034  7122 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:28.547  1034  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 11:20:28.547  1034  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 11:20:28.547  1034  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 11:20:28.548,  1034  1538 D WifiNative-wlan0: doBoolean: SCAN
08-26 11:20:28.548  1034  1538 D WifiNative-wlan0: SCAN: returned false
08-26 11:20:28.549  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122632  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-26 11:20:28.552  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:28.552  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:28.553  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:28.554  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:28.554  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:28.554  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 11:20:28.556  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122638  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 11:20:28.557  1034  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:28.558  1034  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:28.559  1034  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:28.559  1034  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:28.560  1034  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:28.561  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:28.561  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-26 11:20:28.566  7123  7123 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:28.566  7123  7123 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 11:20:28.569  7123  7123 D PhoneMonitor: Register our PhoneStateListener
08-26 11:20:28.580  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 11:20:28.582  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 11:20:28.597  7123  7123 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 11:20:28.598  7123  7123 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 11:20:28.598  7123  7123 D TelephonyAutoProfiling: [parse] Load xml
,08-26 11:20:28.601  7123  7123 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 11:20:28.601  7123  7123 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 11:20:28.601  7123  7123 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-26 11:20:28.608  7123  7123 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-26 11:20:28.616  2155  2155 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19999
08-26 11:20:28.650  1034  1935 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7144 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 11:20:28.651  1034  1935 I ActivityManager: Killing 6679:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-26 11:20:28.718  1034  1923 W libprocessgroup: failed to open /acct/uid_10080/pid_6679/cgroup.procs: No such file or directory
,08-26 11:20:28.892  1034  1889 I art     : Explicit concurrent mark sweep GC freed 69022(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.556ms total 181.130ms
,08-26 11:20:29.022  7108  7108 E wpa_supplicant: USIM:  scard_init function
08-26 11:20:29.023  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 11:20:29.023  1034  7122 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 11:20:29.023  7108  7108 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 11:20:29.023  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 11:20:29.023  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 11:20:29.023  1034  7122 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 11:20:29.024  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 11:20:29.024  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-26 11:20:29.027  1034  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 11:20:29.029  1034  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 11:20:29.032  1034  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 11:20:29.034  1034  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 11:20:29.034  1034  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 11:20:29.048  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123131  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 11:20:29.115  1034  1923 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7166 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-26 11:20:29.117  1034  1923 I ActivityManager: Killing 6706:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-26 11:20:29.139  7108  7108 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 11:20:29.142  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 11:20:29.143  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 11:20:29.143  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 11:20:29.143  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 11:20:29.143  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:29.143  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 11:20:29.149  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:29.149  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:29.150  7108  7108 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 11:20:29.150  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 11:20:29.151  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 11:20:29.151  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 11:20:29.151  1034  7122 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 11:20:29.154  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 11:20:29.154  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 11:20:29.155  1034  7122 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 11:20:29.155  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:29.155  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 11:20:29.244  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123327  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 11:20:29.246  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.246  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 11:20:29.250  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123332  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 11:20:29.252  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123334  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 11:20:29.254  1034  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123337
08-26 11:20:29.255  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.256  1034  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123338
08-26 11:20:29.257  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.257  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.257  1034  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123340
08-26 11:20:29.258  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123340
08-26 11:20:29.258  1034  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123341
08-26 11:20:29.259  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123341  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 11:20:29.259  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 11:20:29.257  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-26 11:20:29.263  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.263  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.263  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 11:20:29.266  1034  1576 W libprocessgroup: failed to open /acct/uid_10097/pid_6706/cgroup.procs: No such file or directory
08-26 11:20:29.270  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123353  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 11:20:29.271  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123354  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 11:20:29.272  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123354  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 11:20:29.273  1034  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123355
08-26 11:20:29.273  1034  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123356
08-26 11:20:29.274  1034  1538 D WifiNative-wlan0: doString: [STATUS]
08-26 11:20:29.274  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:29.274  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:29.275  1034  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 11:20:29.277  1034  1538 I WifiServiceExtension: setVHTCapabilityType  : false
,08-26 11:20:29.284  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.284  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:29.285  1034  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 11:20:29.285  1034  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 11:20:29.285  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.296  1034  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-26 11:20:29.297  1034  1545 D ConnectivityService: Got NetworkAgent Messenger
08-26 11:20:29.297  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 11:20:29.297  1034  1545 D ConnectivityService: NetworkAgent connected
08-26 11:20:29.298  1034  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 11:20:29.298  1034  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 11:20:29.298  1034  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 11:20:29.298  1034  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 11:20:29.304  1034  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 11:20:29.304  1034  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 11:20:29.304  1034  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 11:20:29.305  1034  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 11:20:29.305  1034  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 11:20:29.310  1034  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 11:20:29.311   329   892 D CommandListener: Setting iface cfg
08-26 11:20:29.313  1034  1538 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 11:20:29.313  1034  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:29.314  1034  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 11:20:29.314  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123397  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:29.314  1034  7189 D DhcpStateMachine: StoppedState
08-26 11:20:29.314  1034  7189 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.314  1034  7189 D DhcpStateMachine: WaitBeforeStartState
,08-26 11:20:29.328  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.328  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:29.330  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.331  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.331  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.331  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 11:20:29.333  1034  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.333  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.333  1034  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.333  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.333  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.333  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 11:20:29.335  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.335  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.335  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 11:20:29.337  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.337  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.337  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 11:20:29.339  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:29.339  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-26 11:20:29.350  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.350  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:29.351  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 11:20:29.353  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.353  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:29.354  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.355  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.355  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:29.356  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.388  1034  1958 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7191 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 11:20:29.390  1034  1958 I ActivityManager: Killing 6736:com.lge.eula/1000 (adj 15): empty #17
08-26 11:20:29.518  1034  2034 W libprocessgroup: failed to open /acct/uid_1000/pid_6736/cgroup.procs: No such file or directory
,08-26 11:20:29.541  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:29.541  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-26 11:20:29.542  1034  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:29.543  1034  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123626  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:29.545  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123627  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:29.548  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77256] from screen [on:0 period:-970552980] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 11:20:29.551  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-970552977] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 11:20:29.552  1034  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 11:20:29.558  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 11:20:29.561  1034  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 11:20:29.562  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:29.563  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:29.565  1034  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:29.566  7191  7191 I art     : Almond Protected OAT
08-26 11:20:29.566  1034  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:29.567  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:29.568  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:29.569  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 11:20:29.570  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:29.571  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-26 11:20:29.571  1034  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:29.572  1034  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:29.573  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:29.574  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:29.575  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:29.575  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 11:20:29.576  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=120,0,0
08-26 11:20:29.577  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=120,0,0
08-26 11:20:29.577  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 11:20:29.578  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 11:20:29.579  1034  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 11:20:29.579  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 11:20:29.579  1034  1538 D WifiNative-wlan0: SET ps 0: returned true
08-26 11:20:29.580  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 11:20:29.580  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 11:20:29.580  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 11:20:29.581  1034  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f774d63 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.581  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f774d63 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.581  1034  7189 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.581  1034  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 11:20:29.581  1034  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 11:20:29.581  1034  7189 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 11:20:29.582  1034  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-26 11:20:29.584   329   892 D CommandListener: Setting iface cfg
08-26 11:20:29.584   329   892 D CommandListener: Trying to bring up wlan0
08-26 11:20:29.585  1034  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 11:20:29.587  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 11:20:29.587  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 11:20:29.588  1034  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 11:20:29.588  1034  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 11:20:29.589  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 11:20:29.589  1034  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 11:20:29.590  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:29.590  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 11:20:29.590  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 11:20:29.591  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 11:20:29.591  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 11:20:29.591  1034  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.592  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 11:20:29.592  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.592  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 11:20:29.592  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 11:20:29.592  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 11:20:29.593  1034  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 11:20:29.593  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 11:20:29.609  1034  1538 D WifiNative-wlan0: SET ps 1: returned true,
,08-26 11:20:29.610  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 11:20:29.610  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:29.611  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:29.611  1034  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:29.612  1034  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:29.612  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:29.613  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:29.614  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 11:20:29.614  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 11:20:29.615  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 11:20:29.615  1034  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 11:20:29.615  1034  1545 D ConnectivityService: ignoring duplicate network state non-change
08-26 11:20:29.620  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.620  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:29.621  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 11:20:29.626  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.626  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.627  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 11:20:29.627  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 11:20:29.628  7191  7191 D WeatherApplication: removeAccount
08-26 11:20:29.628  1034  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-26 11:20:29.629  7191  7191 D WeatherApplication: Account.length = 0
08-26 11:20:29.629  7191  7191 E WeatherApplication: OPERATOR:OPEN
08-26 11:20:29.636  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.636  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.637  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-26 11:20:29.637  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 11:20:29.639  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 11:20:29.642  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.642  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.642  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 11:20:29.643  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 11:20:29.643  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.643  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:29.644  1034  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 11:20:29.647  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.648  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:29
,08-26 11:20:29.650  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.650  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 11:20:29.651  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.653  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.654  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.654  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:29.654  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 11:20:29.654  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 11:20:29.654  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.654  1034  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 11:20:29.655  1034  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 11:20:29.656  1034  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 11:20:29.656  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 11:20:29.656  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-26 11:20:29.656   329   892 E Netd    : netlink response contains error (File exists)
08-26 11:20:29.657  1034  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 11:20:29.657  1034  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 11:20:29.658  1034  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 11:20:29.658  1034  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 11:20:29.663  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 11:20:29.663  1034  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 11:20:29.663  1034  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 11:20:29.664  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.664  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 11:20:29.664  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:29.664  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 11:20:29.664  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 11:20:29.665  1034  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 11:20:29.666  1034  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:29.667  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-26 11:20:29.668  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 11:20:29.670  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:29.670  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 11:20:29.670  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:29.671  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 11:20:29.671  1034  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-26 11:20:29.671  1034  1545 D ConnectivityService:    accepting network in place of null
08-26 11:20:29.671  1034  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:29.671  1034  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:29.671  1034  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:29.672   329  7214 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 11:20:29.672  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:29.672  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 11:20:29.673  1034  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 11:20:29.674  1034  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 11:20:29.674  1034  1545 D ConnectivitySe,rvice: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 11:20:29.674  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:29.676  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-26 11:20:29.676  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 11:20:29.676  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 11:20:29.676  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 11:20:29.676  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 11:20:29.678  1034  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 11:20:29.679  1034  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 11:20:29.680  1034  1545 D ConnectivityService: validation of new default Network = false
08-26 11:20:29.680  1034  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 11:20:29.680  1034  1545 D DSQN    : enableDataServiceNotify 
08-26 11:20:29.680  1034  1545 D DSQN    : start dsqn bin
08-26 11:20:29.681  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 11:20:29.682  7191  7191 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 11:20:29.689  1034  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 11:20:29.689  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:29.689  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:29.689  1034  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:29.684  7216  7216 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:29.684  7216  7216 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:29.690  1603  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 11:20:29.700  7216  7216 E DSQN    : DSQN ssw
08-26 11:20:29.700  1034  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 11:20:29.713  1818  7218 I CheckinService: active receiver: enabled
08-26 11:20:29.713  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 11:20:29.713  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:29
,08-26 11:20:29.723  1818  7218 I CheckinService: Preparing to send checkin request
08-26 11:20:29.724  1818  7218 I EventLogService: Accumulating logs since 1472203148831
08-26 11:20:29.763  1034  1050 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7222 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 11:20:29.764  1034  1050 I ActivityManager: Killing 5540:com.lge.bnr/1000 (adj 15): empty #17
08-26 11:20:29.784  1034  7189 D DhcpStateMachine: DHCPV4 request on wlan0
,08-26 11:20:29.785  1034  7189 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 11:20:29.785  1034  7189 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 11:20:29.784  7239  7239 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:29.784  7239  7239 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:29.800  7239  7239 I dhcpcd  : version 5.5.6 starting
,08-26 11:20:29.803  7239  7239 E dhcpcd  : get_duid: m
08-26 11:20:29.803  7239  7239 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 11:20:29.803  7239  7239 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 11:20:29.818  1034  1958 W libprocessgroup: failed to open /acct/uid_1000/pid_5540/cgroup.procs: No such file or directory
,08-26 11:20:29.828  1818  7218 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 11:20:29.836  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 11:20:29.838  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:29.839  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 11:20:29.873  7239  7239 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 11:20:29.873  7239  7239 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 11:20:29.873  7239  7239 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 11:20:29.873  7239  7239 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 11:20:29.874  7239  7239 D dhcpcd  : wlan0: sending REQUEST (xid 0xc7cd55d1), next in 4.66 seconds
08-26 11:20:29.931  7239  7239 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 11:20:29.959   279   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 11:20:29.960   279   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 11:20:29.960   279   370 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 11:20:29.962  7222  7253 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 11:20:29.964   279   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 11:20:29.964   279   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 11:20:29.964   279   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 11:20:29.965  7222  7253 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 11:20:29.966  7239  7239 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 11:20:29.966  7239  7239 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 11:20:29.967  7239  7239 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 11:20:29.967  7239  7239 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 11:20:29.968  7239  7239 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 11:20:29.968  1034  1889 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7255 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-26 11:20:29.968  7239  7239 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 11:20:29.968  7239  7239 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 11:20:29.968  7239  7239 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 11:20:29.978   279   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 11:20:29.978   279   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 11:20:29.978   279   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 11:20:29.979  7222  7263 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-26 11:20:29.984   279   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 11:20:29.984   279   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 11:20:29.984   279   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 11:20:29.984  7222  7263 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 11:20:30.043  7255  7255 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 11:20:30.043  7255  7255 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 11:20:30.072  7255  7255 I MultiDex: VM with version 2.1.0 has multidex support
08-26 11:20:30.072  7255  7255 I MultiDex: install
08-26 11:20:30.073  7255  7255 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 11:20:30.082  7255  7255 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 11:20:30.188  1034  7189 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-26 11:20:30.189  1034  7189 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 11:20:30.189  1034  7189 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 11:20:30.189  1034  7189 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 11:20:30.189  1034  7189 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 11:20:30.189  1034  7189 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 11:20:30.189  1034  7189 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 11:20:30.189  1034  7189 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 11:20:30.190  1034  7189 D DhcpStateMachine: RunningState
08-26 11:20:30.220  7222  7222 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 11:20:30.230  7222  7222 I LibraryLoader: Loading: webviewchromium
,08-26 11:20:30.233  7222  7222 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4323-4327)
08-26 11:20:30.234  7222  7222 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 11:20:30.243  7222  7222 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {382ec3ad}
,08-26 11:20:30.245  7222  7222 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 11:20:30.245  7222  7222 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 11:20:30.260  7222  7222 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 11:20:30.261  7222  7222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 11:20:30.284   333  2154 V AudioPolicyService: registerClient() client 0xb1025e00, uid 10093
,08-26 11:20:30.285  7222  7222 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 11:20:30.285  7222  7315 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 11:20:30.287  7222  7222 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 11:20:30.288  7222  7222 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 11:20:30.313  7222  7222 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 11:20:30.313  7222  7222 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 11:20:30.313  7222  7222 I Adreno-EGL: Build Date: 12/12/14 금
08-26 11:20:30.313  7222  7222 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 11:20:30.313  7222  7222 I Adreno-EGL: Remote Branch: 
08-26 11:20:30.313  7222  7222 I Adreno-EGL: Local Patches: 
08-26 11:20:30.313  7222  7222 I Adreno-EGL: Reconstruct Branch: 
,08-26 11:20:30.363  7323  7323 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 11:20:30.368   329  7214 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 11:20:30.405   329  7214 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 11:20:30.414  1034  1887 D WifiServiceImplEx: setWifiEnabled: false pid=6606, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 11:20:30.414  1034  1887 D WifiService: setWifiEnabled: false pid=6606, uid=10118
08-26 11:20:30.414  1034  1887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 11:20:30.422  7222  7222 I NSApplication: Starting up...
,08-26 11:20:30.430  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:30.430  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:30.430  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 11:20:30.431  1034  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:30.432  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:30.432  1034  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:30.433  1034  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,08-26 11:20:30.433  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 11:20:30.433  1034  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 11:20:30.433  1034  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 11:20:30.434  1034  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 11:20:30.434  1034  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 11:20:30.434  7323  7323 I dex2oat : dex2oat took 71.582ms (threads: 4)
08-26 11:20:30.434  1034  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 11:20:30.439  1034  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 11:20:30.439  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 11:20:30.439  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 11:20:30.439  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 11:20:30.440  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 11:20:30.440  1034  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.440  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.440  1034  1538 D WifiNative-wlan0: SET ps 1: returned true
08-26 11:20:30.440  1034  7189 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.440   329   892 D CommandListener: Clearing all IP addresses on wlan0
08-26 11:20:30.452  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.ConnectException: failed to connect to clients3.google.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 11:20:30.452  7255  7276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 11:20:30.452  7255  7276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 11:20:30.452  7255  7276 I Adreno-EGL: Build Date: 12/12/14 금
08-26 11:20:30.452  7255  7276 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 11:20:30.452  7255  7276 I Adreno-EGL: Remote Branch: 
08-26 11:20:30.452  7255  7276 I Adreno-EGL: Local Patches: 
08-26 11:20:30.452  7255  7276 I Adreno-EGL: Reconstruct Branch: 
,08-26 11:20:30.468  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 11:20:30.468  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-26 11:20:30.497  1034  1404 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7337 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 11:20:30.497  1034  1404 V AlarmManager: RTC_WAKEUP set : Alarm{2fc4bef2 type 0 when 1472203224086 com.android.vending} when 1472203224086
08-26 11:20:30.537  1034  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 11:20:30.537  1034  1545 D DSQN    : disableDataServiceNotify
,08-26 11:20:30.537  1034  1545 D DSQN    : stop dsqn bin
08-26 11:20:30.538  1034  1785 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7357 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 11:20:30.539  1034  1785 I ActivityManager: Killing 2155:com.lge.music/u0a34 (adj 15): empty #17
08-26 11:20:30.544  1034  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 11:20:30.544  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:30.544  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:30.545  1034  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:30.545  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 11:20:30.546  1034  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 11:20:30.546  1034  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 11:20:30.546  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.546  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.546  1034  7183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 11:20:30.546  1603  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 11:20:30.546  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 11:20:30.560   333  1381 V AudioFlinger: 2155 died, releasing its sessions
08-26 11:20:30.560   333  1381 V AudioFlinger:  pid 1853 @ 0
08-26 11:20:30.560   333  1381 V AudioFlinger:  pid 3346 @ 1
08-26 11:20:30.560   333  1381 V AudioFlinger:  pid 3346 @ 2
,08-26 11:20:30.574  7255  7276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 11:20:30.574  7255  7276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 11:20:30.574  7255  7276 I Adreno-EGL: Build Date: 12/12/14 금
08-26 11:20:30.574  7255  7276 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 11:20:30.574  7255  7276 I Adreno-EGL: Remote Branch: 
08-26 11:20:30.574  7255  7276 I Adreno-EGL: Local Patches: 
08-26 11:20:30.574  7255  7276 I Adreno-EGL: Reconstruct Branch: 
,08-26 11:20:30.631  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:30.632  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 11:20:30.639  1034  1889 W libprocessgroup: failed to open /acct/uid_10034/pid_2155/cgroup.procs: No such file or directory
,08-26 11:20:30.647  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:30.647  1034  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.647  1034  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:30.647  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.647  1034  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@13167508
08-26 11:20:30.647  1034  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:30.648  1034  1537 D LGWifiP2pService: P2pDisablingState
08-26 11:20:30.648  1034  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.648  1034  1537 D LGWifiP2pService: p2p socket connection lost
08-26 11:20:30.648  1034  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:30.648  1034  1537 D LGWifiP2pService: P2pDisabledState
08-26 11:20:30.648  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:30.648  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:30.649  1034  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:30.649  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:30.650  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:30.650  1034  7189 D DhcpStateMachine: StoppedState
08-26 11:20:30.650  1034  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 11:20:30.650  1034  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:30.650  1034  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:30.651  1034  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 11:20:30.651  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 11:20:30.651  1034  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.651  1034  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.651  7108  7108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-26 11:20:30.653  1034  1545 D NetworkManagementService: Removing idletimer
08-26 11:20:30.653  1034  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.653  1034  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 11:20:30.655  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 11:20:30.655  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 11:20:30.656  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:30.656  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 11:20:30.657  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 11:20:30.657  1034  1538 D WifiNative-wlan0: SET ps 1: returned true
08-26 11:20:30.657  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 11:20:30.657  1034  7189 D DhcpStateMachine: StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.657   329   892 D CommandListener: Clearing all IP addresses on wlan0
,08-26 11:20:30.659  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:30.659  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:30.660  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.663  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.663  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.663  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 11:20:30.664  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 11:20:30.665  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.665  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.665  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-26 11:20:30.665  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 11:20:30.665  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 11:20:30.665  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-26 11:20:30.665  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 11:20:30.666  1034  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 11:20:30.670  1034  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 11:20:30.670  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 11:20:30.670  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 11:20:30.670  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 11:20:30.670  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 11:20:30.673  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 11:20:30.673  1943  1943 D WfdsService: WifiP2pState is changed : false
,08-26 11:20:30.673  1943  2273 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 11:20:30.673  1943  2273 D WfdsService: Set the WFDS Monitor: false
08-26 11:20:30.673  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 11:20:30.673  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 11:20:30.673  1943  2273 D WfdsMonitor: WFDS Monitor is stopped
08-26 11:20:30.673  1943  2273 D WfdsService: STATE : WfdsDisabledState - enter
08-26 11:20:30.673  1943  7141 D CtrlSupplicant: Received on exit socket, terminate
08-26 11:20:30.673  1943  7141 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 11:20:30.673  1943  7141 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 11:20:30.674  1943  7141 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 11:20:30.674  1943  2274 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 11:20:30.674  1943  2273 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 11:20:30.674  1034  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 11:20:30.674  1034  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.675  1034  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:30.675  1034  1538 D WifiNative-p2p0: TERMINATE: returned true
08-26 11:20:30.675  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:30.675  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:30.675  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 11:20:30.676  1034  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-26 11:20:30.676  1034  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 11:20:30.679  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 11:20:30.684  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:30.684  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:30.684  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.685  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.685  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-26 11:20:30.688  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 11:20:30.689  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 11:20:30.689  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:30.689  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 11:20:30.690  1034  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 11:20:30.690  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.692  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:30.692  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:30.692  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:30.692  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:30.692  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:30.692  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:30.693  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:30.706  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 11:20:30.707  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.707  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.720  7357  7357 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 11:20:30.721  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 11:20:30.722  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.723  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.723  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 11:20:30.723  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:30.725  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.726  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:30.777  7108  7108 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 11:20:30.777  7108  7108 I wpa_supplicant: monitor socket send errors count : 1
08-26 11:20:30.777  7108  7108 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-26 11:20:30.778  1034  7122 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 11:20:30.778  1034  7122 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-26 11:20:30.783  7337  7337 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-26 11:20:30.798  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 11:20:30.799  7108  7108 W wpa_supplicant: USIM:  scard_deinit function
08-26 11:20:30.799  1034  1116 D Tethering: InitialState.processMessage what=4
08-26 11:20:30.800  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 11:20:30.800  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 11:20:30.800  1034  7122 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 11:20:30.800  1034  7122 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 11:20:30.801  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:30.801  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:30.801  1034  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124883
08-26 11:20:30.801  1034  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124884
08-26 11:20:30.802  1034  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 11:20:30.802  1034  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 11:20:30.803  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 11:20:30.803  1034  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:30.804  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:30.821  7255  7276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 11:20:30.821  7255  7276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 11:20:30.821  7255  7276 I Adreno-EGL: Build Date: 12/12/14 금
08-26 11:20:30.821  7255  7276 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 11:20:30.821  7255  7276 I Adreno-EGL: Remote Branch: 
08-26 11:20:30.821  7255  7276 I Adreno-EGL: Local Patches: 
08-26 11:20:30.821  7255  7276 I Adreno-EGL: Reconstruct Branch: 
,08-26 11:20:30.844  7337  7337 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:30.845  7337  7337 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:30.878  7337  7337 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 11:20:30.891  7337  7337 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 11:20:30.894  7337  7337 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 11:20:30.908  7337  7337 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 11:20:30.908  7337  7337 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 11:20:30.919  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 11:20:30.920  6344  6372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 11:20:30.941  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:30.944  3482  4029 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 11:20:30.945  3482  4029 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@55275bf on behalf of 7337
08-26 11:20:30.950  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-26 11:20:30.950  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:30.950  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 11:20:30.950  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 11:20:30.951  7055  7055 I AppUp4:CustModeStarterReceiver: onReceive
08-26 11:20:30.954  7055  7055 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d64ccda
08-26 11:20:30.954  7055  7055 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 11:20:30.954  7055  7055 D AppUp4:CustFacade: isPhone : true
08-26 11:20:30.955  7055  7055 D AppUp4:CustModeStarterReceiver: begin check event
08-26 11:20:30.955  7055  7055 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 11:20:30.958  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:30.958  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:30.960  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:30.960  7337  7337 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 11:20:30.961  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:30.967  7108  7108 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 11:20:30.967  1034  7122 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 11:20:30.967  1034  7122 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 11:20:30.967  1034  7122 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 11:20:30.967  1034  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-26 11:20:30.970  4767  7403 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:30.973  4767  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:30.973  4767  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 11:20:30.974  7337  7337 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-26 11:20:30.983  7255  7276 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:30.983  7255  7276 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 11:20:30.985  7080  7080 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 11:20:30.992  7080  7408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:30.993  1034  2029 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:31.005  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 11:20:31.005  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:31.005  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 11:20:31.012  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 11:20:31.012  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 11:20:31.013  6962  7410 W FormManager: Network not available. Please check & try again.
08-26 11:20:31.013  6962  7411 V FormManager: Network unavailable.
08-26 11:20:31.017  6962  7411 V FormManager: Network unavailable.
,08-26 11:20:31.022  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:31
08-26 11:20:31.023  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 11:20:31.023  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-26 11:20:31.024  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 11:20:31.024  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-26 11:20:31.024  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b633fe8
08-26 11:20:31.024  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 11:20:31.024  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 11:20:31.024  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 11:20:31.024  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 11:20:31.025  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:31
08-26 11:20:31.025   329  7417 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 11:20:31.026  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 11:20:31.026  1818  7218 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-26 11:20:31.039  1818  7218 I CheckinService: active receiver: disabled
,08-26 11:20:31.052  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 11:20:31.052  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 11:20:31.052  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 11:20:31.052  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 11:20:31.052  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 11:20:31.054  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 11:20:31.054  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 11:20:31.054  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 11:20:31.054  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 11:20:31.054  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 11:20:31.054  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 11:20:31.060  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 11:20:31.063  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 11:20:31.067  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.070  1034  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 11:20:31.070  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:31.070  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:31.070  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 11:20:31.071  6962  7419 W FormManager: Network not available. Please check & try again.
,08-26 11:20:31.072  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 11:20:31.073  1943  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 11:20:31.073  1943  2273 D WfdsService: Set the WFDS Monitor: false
08-26 11:20:31.073  1943  2273 D WfdsMonitor: WFDS Monitor is stopped
08-26 11:20:31.074  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 11:20:31.075  2434  2434 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:31.075  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:31.076  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 11:20:31.076  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 11:20:31.077  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 11:20:31.081  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:31.081  6962  7420 V FormManager: Network unavailable.
08-26 11:20:31.081  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:31.084  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 11:20:31.085  6962  7420 V FormManager: Network unavailable.
08-26 11:20:31.089  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 11:20:31.091  6962  7421 W FormManager: Network not available. Please check & try again.
08-26 11:20:31.093  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.097  6962  7422 V FormManager: Network unavailable.
,08-26 11:20:31.099  6962  7422 V FormManager: Network unavailable.
08-26 11:20:31.105  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 11:20:31.106  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:31.107  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:31.108  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:31.112  4767  7423 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 11:20:31.112  4767  7424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 11:20:31.112  4767  7424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 11:20:31.154  1034  1889 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7425 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 11:20:31.170  7337  7337 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 11:20:31.172  1034  1968 I ActivityManager: Killing 6873:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 11:20:31.258  1034  1993 W libprocessgroup: failed to open /acct/uid_10037/pid_6873/cgroup.procs: No such file or directory
,08-26 11:20:31.354  7425  7425 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 11:20:31.355  7425  7425 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 11:20:31.369  7425  7425 V [BNRBootReceiver]: Boot Receiver Return
,08-26 11:20:31.370  7425  7425 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 11:20:31.379  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:31.391  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.398  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.401  6764  7035 D UEI.SmartControl: Internal timer expired: 2
08-26 11:20:31.401  6764  7035 D UEI.SmartControl: unbind internal service
08-26 11:20:31.414  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:31.415  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.418  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:31.427  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-26 11:20:31.433  6853  6853 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 11:20:31.441  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:31.455  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.465  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.478  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:31.480  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.485  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:31.499  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:31.504  6764  7029 D serial_port: close(fd = 24)
,08-26 11:20:31.511  6764  7029 I UEI.SmartControl: Serial port is closed.
08-26 11:20:31.517  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.526  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 11:20:31.535  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:31.538  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.539  6921  6921 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:31.544  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.553  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.562  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.570  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:31.571  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.572  6921  6921 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:31.578  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.593  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.600  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.607  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:31.607  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.608  6921  6921 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 11:20:31.612  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.621  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.630  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.638  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:31.638  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.639  6921  6921 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 11:20:31.642  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.650  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.657  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.664  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:31.664  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 11:20:31.664  6921  6921 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:31.674  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.690  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.700  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.709  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:31.709  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 11:20:31.714  6921  6921 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:31.720  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.732  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.740  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.747  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:31.747  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.748  6921  6921 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 11:20:31.755  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.760  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 11:20:31.770  1034  1544 D WifiService: New client listening to asynchronous messages
08-26 11:20:31.771  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:31.775  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.783  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.791  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:31.793  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.794  6921  6921 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 11:20:31.795  6921  6921 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 11:20:31.796  6921  6921 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 11:20:31.802  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.808  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 11:20:31.810  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:31.815  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.821  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.830  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:31.830  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.831  6921  6921 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 11:20:31.832  6921  6921 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-26 11:20:31.832  6921  6921 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 11:20:31.836  1034  1993 I ActivityManager: Killing 6941:com.lge.settings.easy/1000 (adj 15): empty #17
08-26 11:20:31.869  1034  2029 W libprocessgroup: failed to open /acct/uid_1000/pid_6941/cgroup.procs: No such file or directory
,08-26 11:20:31.874  2080  2080 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 11:20:31.899  2080  2080 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 11:20:31.901  2080  2080 D c       : Getting all permits...
08-26 11:20:31.901  2080  2080 D a       : Opening database...
08-26 11:20:31.908  2080  2080 D a       : Opening database auth.proximity.permit_store...
08-26 11:20:31.909  2080  2080 D a       : Closing database...
08-26 11:20:31.927  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:31.938  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 11:20:31.938  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 11:20:31.938  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:31.944  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.951  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.960  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:31.960  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.962  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:31.964  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:31.967  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 11:20:31.967  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 11:20:31.967  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:31.970  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:31.977  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:31.986  4935  7453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-26 11:20:31.987  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:31.987  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:31.991  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 11:20:31.996  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:32.001  6893  6893 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 11:20:32.001  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 11:20:32.001  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:32.019  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:32.035  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:32.041  6921  6921 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:32.042  6921  6921 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:32.044  6921  6921 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:32.060  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 11:20:32.063  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 11:20:32.077  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:32.083  6962  7472 W FormManager: Network not available. Please check & try again.
08-26 11:20:32.094  2080  2080 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 11:20:32.102  6962  7473 V FormManager: Network unavailable.
08-26 11:20:32.108  6962  7473 V FormManager: Network unavailable.
,08-26 11:20:32.116  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 11:20:32.116  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:32.118  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:32.120  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:32.128  4767  7474 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:32.129  6893  6893 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 11:20:32.129  6893  6893 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 11:20:32.129  6893  6893 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:32.130  4767  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 11:20:32.130  4767  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 11:20:32.133  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 11:20:32.140  6962  7478 W FormManager: Network not available. Please check & try again.
08-26 11:20:32.142  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:32.148  6962  7479 V FormManager: Network unavailable.
,08-26 11:20:32.151  6962  7479 V FormManager: Network unavailable.
08-26 11:20:32.335  1034  1404 V AlarmManager: ELAPSED_WAKEUP set : Alarm{397d8bc6 type 2 when 126415 com.google.android.gms} when 126415
,08-26 11:20:32.349  6921  6921 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-26 11:20:32.349  6921  6921 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5239
08-26 11:20:32.350   329  7481 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 11:20:32.351  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 11:20:32.562  1034  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-970549966] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 11:20:32.564  1034  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-970549964] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 11:20:32.681  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:32.697  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-26 11:20:32.706  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:32.710  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:32.713  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:32.717  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 11:20:32.718  6344  6372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 11:20:32.730  5767  5767 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 11:20:32.751  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:32.773  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 11:20:32.773  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:32.773  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 11:20:32.773  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 11:20:32.778  7055  7055 I AppUp4:CustModeStarterReceiver: onReceive
08-26 11:20:32.782  7055  7055 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d64ccda
08-26 11:20:32.782  7055  7055 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 11:20:32.782  7055  7055 D AppUp4:CustFacade: isPhone : true
08-26 11:20:32.782  7055  7055 D AppUp4:CustModeStarterReceiver: begin check event
08-26 11:20:32.782  7055  7055 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 11:20:32.787  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:32.788  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:32.789  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 11:20:32.794  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:32.802  7080  7080 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 11:20:32.832  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 11:20:32.833  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:32.833  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 11:20:32.833  3346  3346 D PhoneState: setPdpRejectCasuse : false
,08-26 11:20:32.843  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 11:20:32.844  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 11:20:32.850  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 11:20:32.852  4767  7493 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:32.858  7080  7492 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:32.863  4767  7507 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:32.863  4767  7507 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 11:20:32.864  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:32
08-26 11:20:32.870  6962  7508 W FormManager: Network not available. Please check & try again.
,08-26 11:20:32.871  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 11:20:32.871  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-26 11:20:32.872  6962  7509 V FormManager: Network unavailable.
08-26 11:20:32.872  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 11:20:32.873  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-26 11:20:32.873  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b633fe8
08-26 11:20:32.874  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 11:20:32.874  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 11:20:32.874  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 11:20:32.874  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 11:20:32.875  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:32
08-26 11:20:32.885  6962  7509 V FormManager: Network unavailable.
,08-26 11:20:33.433  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:33.434  1034  1923 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 11:20:33.455  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:33.455  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:33.455  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 11:20:33.458  1034  1116 D BluetoothManagerService: Message: 1
08-26 11:20:33.459  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 11:20:33.489  1034  1116 D BluetoothManagerService: Message: 20
08-26 11:20:33.489  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17fb859b:true
08-26 11:20:33.490  6991  6991 D BluetoothAdapterState: make
,08-26 11:20:33.497  6991  6991 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 11:20:33.497  6991  6991 I bluedroid-qcom: init
08-26 11:20:33.499  6991  7524 I BluetoothAdapterState: Entering OffState
08-26 11:20:33.500  6991  6991 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 11:20:33.500  6991  6991 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 11:20:33.500  6991  6991 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 11:20:33.500  6991  6991 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 11:20:33.500  6991  6991 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 11:20:33.507  6991  6991 I bluedroid-qcom: get_profile_interface socket
08-26 11:20:33.507  6991  6991 I bluedroid-qcom: get_profile_interface map_client
,08-26 11:20:33.511  6991  7528 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 11:20:33.504  7527  7527 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:33.504  7527  7527 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:33.520  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-26 11:20:33.522  1034  1116 D BluetoothManagerService: Message: 40
08-26 11:20:33.522  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 11:20:33.526  6991  7007 I bluedroid-qcom: config_hci_snoop_log
08-26 11:20:33.529  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 11:20:33.529  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 11:20:33.533  7527  7527 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 11:20:33.533  7527  7527 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 11:20:33.533  7527  7527 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 11:20:33.539  7527  7527 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 11:20:33.549  6991  7524 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-26 11:20:33.551  6991  7524 D BluetoothAdapterProperties: Setting state to 11
08-26 11:20:33.551  6991  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 11:20:33.553  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:33.553  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 11:20:33.553  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 11:20:33.557  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:33.559  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:33.564  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-26 11:20:33.568  7527  7527 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 11:20:33.568  7527  7527 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 11:20:33.572  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:33.575  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:33.581  6991  7524 I LGBluetoothServiceJni: classInitNative: succeeds
,08-26 11:20:33.589  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-26 11:20:33.592  6991  7528 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 11:20:33.595  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:33.595  6991  6991 V BluetoothPbapReceiver: ***********state = 11
,08-26 11:20:33.602  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 11:20:33.602  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 11:20:33.605  6991  7528 D BluetoothAdapterProperties: Name is: G3
08-26 11:20:33.609  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 11:20:33.633  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:33.665  1034  2034 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7545 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 11:20:33.667  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.669  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-26 11:20:33.671  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.673  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-26 11:20:33.677  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:33.678  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:33.684  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 11:20:33.684  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:33.687  6344  6372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 11:20:33.688  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:33.691  6991  7524 D BluetoothBondStateMachine: make
08-26 11:20:33.693  6991  7524 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
,08-26 11:20:33.693  6991  7524 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 11:20:33.693  6991  7524 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:33.693  6991  7524 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 11:20:33.694  6991  7524 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 11:20:33.695  1034  1404 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29bb0d13 type 2 when 127776 com.google.android.gms} when 127776
08-26 11:20:33.695  6991  7562 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 11:20:33.695  5767  5767 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 11:20:33.698  6991  7524 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:33.701  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.702  5767  5767 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 11:20:33.705  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:33.705  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 11:20:33.706  6991  7524 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:33.706  6991  6991 D HeadsetService: Received start request. Starting profile...
08-26 11:20:33.707  6991  6991 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 11:20:33.707  6991  6991 D LGBluetoothHfpAdapter: Version 1.6
08-26 11:20:33.710  6991  6991 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 11:20:33.711  6991  6991 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 11:20:33.711  6991  6991 D HeadsetStateMachine: make
08-26 11:20:33.716  6991  7524 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:33.720  6991  7524 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 11:20:33.724  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.727  6991  7524 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:33.732  6991  7524 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 11:20:33.733  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 11:20:33.733  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.733  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 11:20:33.733  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 11:20:33.735  7055  7055 I AppUp4:CustModeStarterReceiver: onReceive
08-26 11:20:33.739  6991  7524 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:33.740  7055  7055 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d64ccda
08-26 11:20:33.740  7055  7055 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 11:20:33.740  7055  7055 D AppUp4:CustFacade: isPhone : true
08-26 11:20:33.740  7055  7055 D AppUp4:CustModeStarterReceiver: begin check event
08-26 11:20:33.740  7055  7055 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 11:20:33.745  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.745  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 11:20:33.748  6991  6991 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:33.749  6991  6991 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 11:20:33.752  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:33.755  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:33.757  6991  7524 V LGMDMManager: Create singleton instance
,08-26 11:20:33.763  6991  7524 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 11:20:33.860  1034  2034 I art     : Explicit concurrent mark sweep GC freed 119682(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.981ms total 106.049ms
08-26 11:20:33.861  6991  6991 D HeadsetStateMachine: max_hf_connections = 1
08-26 11:20:33.861  6991  6991 I bluedroid-qcom: get_profile_interface handsfree
08-26 11:20:33.862  6991  6991 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-26 11:20:33.864   333   333 V AudioPolicyService: registerClient() client 0xb558a9e0, uid 1002
08-26 11:20:33.865   333  2154 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 11:20:33.865   333  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 11:20:33.865   333  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 11:20:33.865  6991  6991 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 11:20:33.866   333  1382 V AudioFlinger: registerClient() client 0xb1023c28, pid 6991
08-26 11:20:33.867  6991  6991 V ToneGenerator: Create Track: 0xb4928a80
08-26 11:20:33.867   333  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:33.867  6991  6991 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 11:20:33.867  6991  6991 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 11:20:33.867   333  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:33.867   333  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 11:20:33.867   333  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 11:20:33.867   333  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 11:20:33.867   333  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 11:20:33.867  6991  6991 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 11:20:33.868  1603  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:33.868  1603  1624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:33.868  3346  3363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:33.868  3346  3363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:33.868  1853  3502 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:33.868  1853  3502 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:33.868   333  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 11:20:33.869  1034  1889 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:33.869  1034  1889 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:33.869   333  2153 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000,
08-26 11:20:33.869   333  2153 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 11:20:33.869   333  2153 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 11:20:33.869   333  2153 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 11:20:33.869   333  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:33.869   333  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:33.870  6991  7008 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:33.870  6991  7008 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 11:20:33.870  6991  6991 V AudioSystem: getLatency() output 2, latency 50
08-26 11:20:33.870  6991  6991 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 11:20:33.870  6991  6991 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 11:20:33.870  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:33.870  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:33.870  3346  3371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:33.870  3346  3371 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:33.870  6991  7007 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:33.870  6991  7007 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 11:20:33.870   333  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 11:20:33.870   333  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 11:20:33.870   333  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 11:20:33.870   333  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 11:20:33.870   333  1381 V AudioFlinger: createTrack() lSessionId: 22
08-26 11:20:33.870  1034  2029 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:33.870  1034  2029 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:33.871  6991  6991 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 11:20:33.871  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:33.871  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:33.871   333  1382 V AudioFlinger: acquiring 22 from 6991, for 6991
08-26 11:20:33.871   333  1382 V AudioFlinger:  added new entry for 22
08-26 11:20:33.872  6991  6991 V ToneGenerator: ToneGenerator INIT OK, time: 127965
08-26 11:20:33.872  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:33.872  6991  7563 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 11:20:33.872  6991  7563 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 11:20:33.872  6991  7563 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 11:20:33.873  6991  7563 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 11:20:33.874  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:33.874   333  2153 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6991
08-26 11:20:33.875   333  2153 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 11:20:33.875   333  2153 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 11:20:33.875   333  2153 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 11:20:33.875   333  2153 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 11:20:33.875   333  2153 V voice,   : voice_set_parameters: exit with code(0)
08-26 11:20:33.875   333  2153 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 11:20:33.875   333  2153 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 11:20:33.876   333  2153 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 11:20:33.876   333  2153 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 11:20:33.876  6991  6991 D A2dpService: Received start request. Starting profile...
08-26 11:20:33.876   333  2153 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 11:20:33.876   333  2153 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 11:20:33.877  6991  6991 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 11:20:33.877  6991  7563 V ToneGenerator: ToneGenerator destructor
08-26 11:20:33.877  6991  7563 V ToneGenerator: stopTone
08-26 11:20:33.877  6991  7563 V ToneGenerator: Delete Track: 0xb4928a80
08-26 11:20:33.877  6991  6991 V Avrcp   : make
,08-26 11:20:33.878  6991  6991 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-26 11:20:33.878  6991  6991 I bluedroid-qcom: get_profile_interface avrcp
08-26 11:20:33.878  6991  7563 V AudioTrack: ~AudioTrack, releasing session id from 6991 on behalf of 6991
08-26 11:20:33.879  4767  7567 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:33.880   333   333 V AudioFlinger: releasing 22 from 6991 for 6991
08-26 11:20:33.880   333   333 V AudioFlinger:  decremented refcount to 0
08-26 11:20:33.880   333   333 V AudioFlinger: purging stale effects
,08-26 11:20:33.880  1034  1050 W Process : Unable to open /proc/7566/status
08-26 11:20:33.880   333   333 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 11:20:33.880   333   333 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 11:20:33.880   333  1272 V AudioPolicyService: AudioCommandThread() waking up
08-26 11:20:33.880   333   333 V AudioFlinger: PlaybackThread::Track destructor
08-26 11:20:33.880   333  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 11:20:33.880   333  1272 V AudioPolicyManager: releaseOutput() 2
08-26 11:20:33.880   333  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 11:20:33.880   333   333 V AudioFlinger: removeClient_l() pid 6991, calling pid 333
08-26 11:20:33.884  7545  7545 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 11:20:33.885  7545  7545 W LG Account v2.2: No ProfileInfo entries
08-26 11:20:33.885  7545  7545 I LG Account v2.2: isEnabled: false
08-26 11:20:33.886  7545  7545 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 11:20:33.886  7545  7545 I Feature : [Lifetracker]Country: EU
,08-26 11:20:33.886  7545  7545 I Feature : [Lifetracker]Operator: OPEN
08-26 11:20:33.887  7545  7545 I Feature : [Lifetracker]Ranking support: false
08-26 11:20:33.887  4767  7569 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.887  7545  7545 I Feature : [Lifetracker]Comfort support: false
08-26 11:20:33.887  4767  7569 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 11:20:33.887  7545  7545 I Feature : [Lifetracker]Accessory: true
08-26 11:20:33.887  7545  7545 I Feature : [Lifetracker]Health device: true
08-26 11:20:33.887  7545  7545 I Feature : [Lifetracker]Extra Pedometer: false
08-26 11:20:33.887  7545  7545 I Feature : [Lifetracker]Blood glucose device: false
08-26 11:20:33.888  7545  7545 I Feature : [Lifetracker]Device Number: 3
08-26 11:20:33.895  6991  6991 V AudioManager: registerRemoteController: size of Media player list: 0
,08-26 11:20:33.897  6991  6991 E AudioManager: No RCC entry present to update
08-26 11:20:33.897  6991  6991 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 11:20:33.901  7080  7080 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 11:20:33.901  6991  6991 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 11:20:33.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 11:20:33.902  6991  6991 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 11:20:33.910  6853  6853 D BluetoothPermissionRequest: onReceive
,08-26 11:20:33.911  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 11:20:34.001  7080  7572 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 11:20:34.014  6962  7574 W FormManager: Network not available. Please check & try again.
08-26 11:20:34.020  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 11:20:34.036  6962  7575 V FormManager: Network unavailable.
,08-26 11:20:34.041  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 11:20:34.041  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:34.041  1034  2000 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:34.041  1034  2000 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:34.042  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 11:20:34.044  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 11:20:34.045  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 11:20:34.049  6962  7575 V FormManager: Network unavailable.
,08-26 11:20:34.057  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:34
08-26 11:20:34.059  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 11:20:34.059  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-26 11:20:34.060  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 11:20:34.060  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-26 11:20:34.060  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b633fe8
08-26 11:20:34.061  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 11:20:34.061  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 11:20:34.061  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 11:20:34.061  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 11:20:34.061  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:34
,08-26 11:20:34.085  6344  6344 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 11:20:34.089  6344  6372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 11:20:34.102  1034  1968 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 11:20:34.107  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 11:20:34.109  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:34.110  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 11:20:34.111  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 11:20:34.111  6991  6991 I BluetoothA2dpServiceJni: classInitNative
08-26 11:20:34.111  6991  6991 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 11:20:34.111  6991  6991 D A2dpStateMachine: make
08-26 11:20:34.113  6991  6991 I bluedroid-qcom: get_profile_interface a2dp
08-26 11:20:34.113  6991  7579 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 11:20:34.115  6991  6991 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 11:20:34.116  6991  6991 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 11:20:34.117  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.118  6991  6991 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 11:20:34.120  6991  6991 D HidService: Received start request. Starting profile...
,08-26 11:20:34.120  6991  6991 I bluedroid-qcom: get_profile_interface hidhost
08-26 11:20:34.120  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.120  6991  6991 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 11:20:34.121  6991  7578 D A2dpStateMachine: Enter Disconnected: -2
08-26 11:20:34.122  6991  6991 D HealthService: Received start request. Starting profile...
08-26 11:20:34.124  6991  6991 I bluedroid-qcom: get_profile_interface health
08-26 11:20:34.124  6991  6991 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 11:20:34.124  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.124  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 11:20:34.124  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:34.124  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 11:20:34.125  7055  7055 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 11:20:34.125  6991  6991 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 11:20:34.126  6991  6991 D PanService: Received start request. Starting profile...
08-26 11:20:34.126  6991  6991 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 11:20:34.126  6991  6991 I bluedroid-qcom: get_profile_interface pan
08-26 11:20:34.129  7055  7055 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 11:20:34.133  6991  6991 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-26 11:20:34.133  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.135  6991  6991 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 11:20:34.137  7055  7055 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d64ccda
08-26 11:20:34.137  7055  7055 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 11:20:34.137  7055  7055 D AppUp4:CustFacade: isPhone : true
08-26 11:20:34.138  7055  7055 D AppUp4:CustModeStarterReceiver: begin check event
08-26 11:20:34.138  7055  7055 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 11:20:34.141  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:34.141  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:34.143  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:34.143  6991  6991 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 11:20:34.144  6991  6991 D BtGatt.GattService: Received start request. Starting profile...
08-26 11:20:34.144  6991  6991 D BtGatt.GattService: start()
08-26 11:20:34.144  6991  6991 I bluedroid-qcom: get_profile_interface gatt
08-26 11:20:34.144  6991  6991 D BtGatt.AdvertiseManager: advertise manager created
08-26 11:20:34.145  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 11:20:34.153  4767  7585 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:34.153  7080  7080 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 11:20:34.154  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
,08-26 11:20:34.156  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.156  6991  6991 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 11:20:34.157  4767  7587 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:34.157  4767  7587 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 11:20:34.157  6991  6991 V BluetoothMapService: BluetoothMapBinder()
08-26 11:20:34.158  6991  6991 D BluetoothMapService: Received start request. Starting profile...
08-26 11:20:34.158  6991  6991 D BluetoothMapService: start()
,08-26 11:20:34.162  6991  6991 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 11:20:34.162  6991  6991 D BluetoothMapEmailAppObserver: createReceiver()
08-26 11:20:34.164  6991  6991 D BluetoothMapEmailAppObserver: initObservers()
08-26 11:20:34.164  6991  6991 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 11:20:34.172  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.172  6991  6991 D HeadsetStateMachine: Proxy object connected
,08-26 11:20:34.173  6991  6991 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 11:20:34.173  6991  6991 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 11:20:34.177  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 11:20:34.177  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:34.177  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 11:20:34.178  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:34.179  6991  7563 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 11:20:34.179  6991  7563 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 11:20:34.180  6991  7563 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 11:20:34.181  7080  7588 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:34.182  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:34.184  6962  7591 W FormManager: Network not available. Please check & try again.
,08-26 11:20:34.185  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:34.189  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:34.189  6991  6991 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 11:20:34.189  7123  7123 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 11:20:34.189  7123  7123 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 11:20:34.190  6962  7592 V FormManager: Network unavailable.
08-26 11:20:34.192  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:34.195  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 11:20:34.195  6991  6991 V BluetoothMapService: Handler(): got msg=1
,08-26 11:20:34.196  6991  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 11:20:34.196  6991  7524 I bluedroid-qcom: enable
08-26 11:20:34.197  6991  7524 I bt_hci_bdroid: init
08-26 11:20:34.197  6991  7593 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 11:20:34.198  6991  7593 I bt-btu  : btu_task pending for preload complete event
08-26 11:20:34.199  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.199  6991  7524 I bt_vendor: bt-vendor : init
08-26 11:20:34.199  6991  7524 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 11:20:34.199  6991  7524 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 11:20:34.199  6991  7524 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 11:20:34.199  6991  7524 D bt_userial_mct: userial_init
08-26 11:20:34.200  6991  7524 D bt_hci_bdroid: set_power 1
08-26 11:20:34.200  6991  7524 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 11:20:34.200  6991  7524 I bt_vendor: Starting hciattach daemon
08-26 11:20:34.200  6991  7524 I bt_vendor: try to set true
08-26 11:20:34.200  6962  7592 V FormManager: Network unavailable.
08-26 11:20:34.201  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:34.201  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:34.201  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 11:20:34.201  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.201  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 11:20:34.194  7596  7596 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:34.194  7596  7596 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:34.228  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 11:20:34.270  1034  2000 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7600 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 11:20:34.281  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:34
08-26 11:20:34.283  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 11:20:34.284  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-26 11:20:34.285  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 11:20:34.285  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-26 11:20:34.285  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b633fe8
08-26 11:20:34.287  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 11:20:34.287  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 11:20:34.287  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 11:20:34.287  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 11:20:34.287  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:34
,08-26 11:20:34.302  7618  7618 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 11:20:34.312  7621  7621 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 11:20:34.334  7624  7624 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-26 11:20:34.344  7625  7625 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 11:20:34.351  7600  7600 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:34.352  7626  7626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-26 11:20:34.354  1034  1112 W ProcessCpuTracker: Skipping unknown process pid 7622
08-26 11:20:34.359  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 11:20:34.364  1034  1889 I ActivityManager: Killing 7337:com.android.vending/u0a44 (adj 15): empty #17
08-26 11:20:34.377  7629  7629 I libmdmdetect: ESOC framework not supported
08-26 11:20:34.378  7629  7629 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 11:20:34.386  7629  7629 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 11:20:34.386  7629  7629 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 11:20:34.387  7629  7629 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 11:20:34.387  7629  7629 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 11:20:34.387  7629  7629 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 11:20:34.387  7629  7629 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 11:20:34.387  7629  7629 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 11:20:34.412  1034  1993 W libprocessgroup: failed to open /acct/uid_10044/pid_7337/cgroup.procs: No such file or directory
,08-26 11:20:34.422  7629  7630 E QC-QMI  : qmi_client [7629] 14: failed to locate client data
08-26 11:20:34.424   477   477 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 11:20:34.424   477   477 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-26 11:20:34.478  7631  7631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 11:20:34.494  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 11:20:34.553  6991  7524 I bt_vendor: bluetooth satus is on
,08-26 11:20:34.553  6991  7524 D bt_hci_bdroid: preload
08-26 11:20:34.553  6991  7595 D bt_userial_mct: userial_open(port:0)
08-26 11:20:34.553  6991  7595 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 11:20:34.559  6991  7595 I bt_vendor: Done intiailizing UART
08-26 11:20:34.560  6991  7595 I bt_vendor: Done intiailizing UART
08-26 11:20:34.560  6991  7595 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 11:20:34.560  6991  7595 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 11:20:34.560  6991  7593 I bt-btu  : btu_task received preload complete event
08-26 11:20:34.560  6991  7634 D bt_userial_mct: Entering userial_read_thread()
08-26 11:20:34.561  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 11:20:34.561  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 11:20:34.563  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 11:20:34.568  6991  7593 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 11:20:34.626  6991  7593 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 11:20:34.626  6991  7593 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa022f061 
08-26 11:20:34.626  6991  7593 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa022f061 
,08-26 11:20:34.677  6991  7528 E bt-btif : Calling BTA_HhEnable
,08-26 11:20:34.677  6991  7528 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-26 11:20:34.682  6991  7528 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 11:20:34.682  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-26 11:20:34.683  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 11:20:34.683  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 11:20:34.683  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 11:20:34.683  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 11:20:34.685  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 11:20:34.686  6991  7528 D BluetoothAdapterProperties: Name is: G3
08-26 11:20:34.688  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 11:20:34.688  6991  7528 D BluetoothAdapterProperties: Scan Mode:20
,08-26 11:20:34.689  6991  7528 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:34.689  6991  7528 D bt_hci_bdroid: postload
08-26 11:20:34.689  6991  7595 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 11:20:34.690  6991  7595 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 11:20:34.692  6991  7595 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 11:20:34.699  6991  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 11:20:34.699  6991  7528 D bte_conf: Device ID record 1 : primary
08-26 11:20:34.699  6991  7528 D bte_conf:   vendorId            = 00c4
08-26 11:20:34.699  6991  7528 D bte_conf:   vendorIdSource      = 0001
08-26 11:20:34.699  6991  7528 D bte_conf:   product             = 13a1
08-26 11:20:34.699  6991  7528 D bte_conf:   version             = 1000
08-26 11:20:34.699  6991  7528 D bte_conf:   clientExecutableURL = 
08-26 11:20:34.699  6991  7528 D bte_conf:   serviceDescription  = 
08-26 11:20:34.700  6991  7528 D bte_conf:   documentationURL    = 
08-26 11:20:34.700  6991  7528 D bte_conf: bte_load_did_conf no section named DID2.
08-26 11:20:34.701  6991  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:34.701  6991  7593 W bt-smp  : Plain text(LSB ~ MSB) = 3a cb 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:34.701  6991  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 38 d2 4d 06 67 c6 13 30 d4 f0 4d 67 ba 8b 25 
08-26 11:20:34.701  6991  7593 W bt-btm  : Stopping oneshot timer
08-26 11:20:34.701  6991  7595 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 11:20:34.694  7642  7642 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:34.694  7642  7642 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:34.705  6991  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 11:20:34.705  6991  7524 D BluetoothAdapterProperties: ScanMode =  20
08-26 11:20:34.705  6991  7524 D BluetoothAdapterProperties: State =  11
08-26 11:20:34.705  6991  7524 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 11:20:34.706  6991  7634 E bt_mct  : hci lib postload completed
08-26 11:20:34.707  6991  7524 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 11:20:34.707  6991  7524 D BluetoothAdapterProperties: Setting state to 12
08-26 11:20:34.707  6991  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 11:20:34.707  6991  7528 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 11:20:34.708  6991  7528 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 11:20:34.711  6991  7524 I BluetoothAdapterState: Entering On State
08-26 11:20:34.714  6991  7524 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 11:20:34.714  6991  7524 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 11:20:34.714  6991  7524 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 11:20:34.715  6991  7524 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 11:20:34.716  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:34.716  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 11:20:34.716  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 11:20:34.716  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 11:20:34.726  1034  1034 D BluetoothA2dp: Proxy object connected
08-26 11:20:34.728  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:34.730  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:34.735  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:34.743  1853  1853 D BluetoothHeadset: Proxy object connected
,08-26 11:20:34.744  6991  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:34.744  6991  7593 W bt-smp  : Plain text(LSB ~ MSB) = cd 2e 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:34.744  6991  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 d2 df f7 73 bf 4e 9f 5f 8a 89 ab 8d 81 fc b0 
08-26 11:20:34.744  6991  7593 W bt-btm  : Stopping oneshot timer
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:34.746  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:34.747  6991  7528 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:34.747  6991  7528 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 11:20:34.749  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:34.749  6853  6870 D BluetoothPan: onBluetoothStateChange on: true
08-26 11:20:34.749  6853  6870 D BluetoothPan: onBluetoothStateChange call bindService
08-26 11:20:34.753  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:34.756  1853  1853 D BluetoothHeadset: Proxy object connected
,08-26 11:20:34.760  6991  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:34.760  6991  7593 W bt-smp  : Plain text(LSB ~ MSB) = f2 27 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:34.760  6991  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = 8c 69 95 78 60 44 72 6c 21 45 00 0a e4 00 f2 18 
,08-26 11:20:34.760  6853  6870 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 11:20:34.761  6991  7593 W bt-btm  : Stopping oneshot timer
08-26 11:20:34.761  6991  7524 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 11:20:34.762  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 11:20:34.762  6853  6853 D PanProfile: Bluetooth service connected
08-26 11:20:34.765  6853  6872 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 11:20:34.771  6853  6870 D BluetoothMap: onBluetoothStateChange: up=true
08-26 11:20:34.772  6853  6853 D BluetoothInputDevice: Proxy object connected
08-26 11:20:34.772  6853  6853 D HidProfile: Bluetooth service connected
,08-26 11:20:34.773  6991  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:34.773  6991  7593 W bt-smp  : Plain text(LSB ~ MSB) = 18 b7 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:34.773  6991  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = 7f cf cf ab c7 a8 53 5d 03 3b 39 c7 97 84 f3 ce 
08-26 11:20:34.773  6991  7593 W bt-btm  : Stopping oneshot timer
08-26 11:20:34.779  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:34.780  1853  3502 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:34.781  1034  1034 D BluetoothHeadset: Proxy object connected
08-26 11:20:34.782  6853  6853 D BluetoothMap: Proxy object connected
08-26 11:20:34.782  6853  6853 D MapProfile: Bluetooth service connected
08-26 11:20:34.782  6853  6853 D BluetoothMap: getConnectedDevices()
08-26 11:20:34.784  1853  1853 D BluetoothHeadset: Proxy object connected
,08-26 11:20:34.785  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 11:20:34.785  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 11:20:34.786  6991  7007 V BluetoothMapService: getConnectedDevices()
08-26 11:20:34.788  6991  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:34.788  6991  7593 W bt-smp  : Plain text(LSB ~ MSB) = dd 64 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:34.788  6991  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = d9 d0 24 2f c2 46 85 5f 23 7a c9 12 1e 55 30 91 
08-26 11:20:34.788  6991  7593 W bt-btm  : Stopping oneshot timer
08-26 11:20:34.791  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.791  1943  2115 D LGBluetoothAPIService: Message: 1
08-26 11:20:34.791  1943  2115 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 11:20:34.794  6606  6606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 11:20:34.796  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:34.797  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:34.798  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:34.798  7660  7660 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-26 11:20:34.804  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 11:20:34.805  1034  1116 D BluetoothManagerService: Message: 40
08-26 11:20:34.805  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 11:20:34.805  1943  2115 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 11:20:34.808  6991  6991 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.808  6991  6991 D BluetoothMapService: STATE_ON
08-26 11:20:34.810  6991  6991 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 11:20:34.810  6991  6991 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 11:20:34.811  6991  6991 V BluetoothMapService: Handler(): got msg=1
08-26 11:20:34.811  6853  6853 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 11:20:34.812  6991  6991 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 11:20:34.812  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 11:20:34.812  1943  2115 D LGBluetoothAPIService: Message: 100
08-26 11:20:34.812  1943  2115 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 11:20:34.813  6991  7662 D BluetoothMapMasInstance: MAS initSocket()
08-26 11:20:34.814  1034  1116 D BluetoothManagerService: Message: 30
08-26 11:20:34.814  6991  7662 D BluetoothMapMasInstance:   masId = 00
08-26 11:20:34.814  6991  7662 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 11:20:34.814  6991  7662 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 11:20:34.814  6991  7662 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 11:20:34.815  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 11:20:34.816  6853  6853 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 11:20:34.819  6991  7662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:34.823  6991  7662 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 11:20:34.823  6991  7662 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 11:20:34.823  6991  7662 D BluetoothMapMasInstance: Accepting socket connection...
08-26 11:20:34.824  6991  7528 D BluetoothAdapterProperties: Scan Mode:21
08-26 11:20:34.824  6991  7528 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 11:20:34.825  1034  1116 D BluetoothManagerService: Message: 30
08-26 11:20:34.827  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:34.829  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.829  6991  6991 V BluetoothPbapService: Pbap Service onCreate
08-26 11:20:34.829  6991  6991 V BluetoothPbapService: Starting PBAP service
,08-26 11:20:34.831  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:34.832  6991  6991 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 11:20:34.832  6991  6991 V BluetoothPbapService: Pbap Service onBind
08-26 11:20:34.834  6991  6991 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.834  6991  6991 V BluetoothPbapService: state: 12
08-26 11:20:34.834  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 11:20:34.834  6991  6991 V BluetoothPbapService: Handler(): got msg=1
08-26 11:20:34.834  6991  6991 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 11:20:34.835  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 11:20:34.836  6991  7663 V BluetoothPbapService: Pbap Service initSocket
08-26 11:20:34.838  1034  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:34.839  6991  7663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:34.840  6853  6853 D BluetoothA2dp: Proxy object connected
08-26 11:20:34.840  6853  6853 D A2dpProfile: Bluetooth service connected
08-26 11:20:34.841  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 11:20:34.841  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.841  6991  6991 V BluetoothPbapReceiver: ***********state = 12
08-26 11:20:34.842  6991  7663 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 11:20:34.842  6991  7663 V BluetoothPbapService: Succeed to create listening socket 
08-26 11:20:34.842  6991  7663 V BluetoothPbapService: Accepting socket connection...
,08-26 11:20:34.845  6853  6853 D BluetoothHeadset: Proxy object connected
,08-26 11:20:34.847  6853  6853 D HeadsetProfile: Bluetooth service connected
08-26 11:20:34.847  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 11:20:34.847  2080  2080 D c       : Getting all permits...
08-26 11:20:34.847  2080  2080 D a       : Opening database...
08-26 11:20:34.851  2080  2080 D a       : Opening database auth.proximity.permit_store...
08-26 11:20:34.852  2080  2080 D a       : Closing database...
08-26 11:20:34.855  6853  6853 D BluetoothPbap: Proxy object connected
08-26 11:20:34.856  6853  6853 D PbapServerProfile: Bluetooth service connected
,08-26 11:20:34.860  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-26 11:20:34.865  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 11:20:34.867  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 11:20:34.868  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 11:20:34.872  6991  6991 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 11:20:34.873  6991  6991 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 11:20:34.880  6991  6991 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 11:20:34.904  6991  6991 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 11:20:34.904  6991  6991 V BtOppService: onCreate
08-26 11:20:34.909  6991  6991 V BluetoothOppNotification: send message
08-26 11:20:34.913  6991  6991 V BtOppService: Starting RfcommListener
08-26 11:20:34.919  6991  6991 D BluetoothOppPreference: Dumping Names:  
08-26 11:20:34.919  6991  6991 D BluetoothOppPreference: {}
08-26 11:20:34.919  6991  6991 D BluetoothOppPreference: Dumping Channels:  
08-26 11:20:34.919  6991  6991 D BluetoothOppPreference: {}
,08-26 11:20:34.922  6991  6991 V BtOppService: onStartCommand
,08-26 11:20:34.927  6991  7671 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 11:20:34.928  6991  7668 V BtOppService: Deleted complete outbound shares, number =  0
08-26 11:20:34.929  6991  7671 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 11:20:34.930  6991  7668 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 11:20:34.930  6991  7668 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 11:20:34.930  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.930  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 11:20:34.935  6991  7668 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@331b9c8d on behalf of 
08-26 11:20:34.936  6991  7671 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e82ce42 on behalf of 
,08-26 11:20:34.938  6991  6991 V BluetoothOppNotification: new notify threadi!
08-26 11:20:34.939  6991  6991 V BluetoothOppNotification: send delay message
08-26 11:20:34.939  6991  6991 V BtOppService: start RfcommListener
08-26 11:20:34.943  6991  6991 V BtOppService: RfcommListener started
08-26 11:20:34.943  6991  6991 V BtOppService: ContentObserver received notification
08-26 11:20:34.943  6991  6991 V BtOppService: ContentObserver received notification
,08-26 11:20:34.945  6991  7673 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 11:20:34.945  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:34.946  6991  7671 V BluetoothOppNotification: update too frequent, put in queue
08-26 11:20:34.946  6991  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 11:20:34.947  6991  7673 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:34.949  6991  7673 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-26 11:20:34.949  6991  7673 V BtOppRfcommListener: Started RFCOMM listener....
08-26 11:20:34.949  6991  7673 I BtOppRfcommListener: Accept thread started.
08-26 11:20:34.949  6991  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11961e53 on behalf of 
08-26 11:20:34.949  6991  7673 V BtOppRfcommListener: Accepting connection...
08-26 11:20:34.949  6991  7671 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 11:20:34.950  6991  7671 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-26 11:20:34.952  6991  7672 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 11:20:34.954  6991  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 11:20:34.955  6991  7671 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15a6390 on behalf of 
08-26 11:20:34.956  6991  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f327489 on behalf of 
08-26 11:20:34.957  6991  7671 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 11:20:34.958  6991  7672 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 11:20:34.959  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:34.959  6991  6991 V BluetoothFtpService: Ftp Service onCreate
08-26 11:20:34.959  6991  6991 I BluetoothFtpService: Ftp Service onCreate
08-26 11:20:34.959  6991  6991 V BluetoothFtpService: Ftp Service onStartCommand
08-26 11:20:34.959  6991  6991 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.960  6991  6991 V BluetoothFtpService: Starting Listening on sockets
08-26 11:20:34.960  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:34.960  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:34.960  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 11:20:34.960  6991  7672 V BluetoothOppNotification: outbound notification was removed.
08-26 11:20:34.960  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:34.961  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 11:20:34.961  6991  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 11:20:34.961  6991  6991 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 11:20:34.963  6991  6991 V BluetoothFtpService: Handler(): got msg=1
08-26 11:20:34.963  6991  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a5a4caf on behalf of 
08-26 11:20:34.964  6991  6991 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 11:20:34.964  6991  6991 V BluetoothFtpService: Ftp Service initSocket
08-26 11:20:34.965  6991  7672 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 11:20:34.969  6991  7672 V BluetoothOppNotification: inbound notification was removed.
08-26 11:20:34.969  6991  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 11:20:34.969  1034  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:34.970  6991  6991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:34.971  6991  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a2a28bc on behalf of 
08-26 11:20:34.971  6991  6991 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-26 11:20:34.972  6991  6991 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 11:20:34.974  6991  7674 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 11:20:34.980  7222  7258 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-26 11:20:35.002  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
,08-26 11:20:35.002  6991  6991 V BluetoothSapService: Sap Service onCreate
08-26 11:20:35.004  6991  6991 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:35.004  6991  6991 V BluetoothSapService: state: 12
,08-26 11:20:35.004  6991  6991 V BluetoothSapService: Starting SAP server process
08-26 11:20:35.004  7677  7677 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:35.007  6991  6991 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 11:20:35.004  7677  7677 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:35.015  6991  7679 V BluetoothSapService: Sap Service initRfcommSocket
08-26 11:20:35.015  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:35.017  6991  7679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:35.018  6991  7679 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
,08-26 11:20:35.018  6991  7679 V BluetoothSapService: Succeed to create listening socket 
,08-26 11:20:35.018  6991  7679 V BluetoothSapService: Accepting socket connection...
,08-26 11:20:35.021  7677  7677 V BT_SAP  : Event pipe created
,08-26 11:20:35.021  7677  7677 V BT_SAP  : create_server_socket qcom.sap.server,
08-26 11:20:35.021  7677  7677 V BT_SAP  : created socket fd 6
,08-26 11:20:35.652  1034  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:35.653  1034  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 11:20:35.678  1034  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 11:20:35.679  1034  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 11:20:35.938  1034  1935 I ActivityManager: Killing 7425:com.lge.bnr/1000 (adj 15): empty #17
,08-26 11:20:35.947  6991  6991 V BluetoothOppNotification: new notify threadi!
,08-26 11:20:35.948  6991  6991 V BluetoothOppNotification: send delay message
08-26 11:20:35.963  6991  7689 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 11:20:35.972  6991  7689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19cf14a8 on behalf of 
08-26 11:20:35.973  6991  7689 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 11:20:35.974  6991  7689 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 11:20:35.975  6991  7689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37672bc1 on behalf of 
08-26 11:20:35.978  6991  7689 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 11:20:35.983  6991  7689 V BluetoothOppNotification: outbound notification was removed.
08-26 11:20:35.983  6991  7689 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 11:20:35.984  6991  7689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e889f66 on behalf of 
08-26 11:20:35.985  6991  7689 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 11:20:35.987  6991  7689 V BluetoothOppNotification: inbound notification was removed.
08-26 11:20:35.988  6991  7689 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 11:20:35.989  6991  7689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fa122a7 on behalf of 
08-26 11:20:35.992  1034  1923 W libprocessgroup: failed to open /acct/uid_1000/pid_7425/cgroup.procs: No such file or directory
,08-26 11:20:36.004  1034  1703 I ActivityManager: Killing 6893:com.lge.sync/1000 (adj 15): empty #17
,08-26 11:20:36.021  1034  1544 D WifiService: Client connection lost with reason: 4
,08-26 11:20:36.037  1034  1785 W libprocessgroup: failed to open /acct/uid_1000/pid_6893/cgroup.procs: No such file or directory
,08-26 11:20:36.480  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 11:20:36.481  1034  1935 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@204e5604 mBinding = false
,08-26 11:20:36.518  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:36.519  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:36.519  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 11:20:36.522  1034  1116 D BluetoothManagerService: Message: 2
08-26 11:20:36.523  1034  1116 D BluetoothManagerService: Sending off request.
08-26 11:20:36.524  6991  7643 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 11:20:36.526  6991  7524 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 11:20:36.526  6991  7524 D BluetoothAdapterProperties: Setting state to 13
08-26 11:20:36.526  6991  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 11:20:36.527  6991  7524 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 11:20:36.527  6991  7524 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 11:20:36.528  6991  7528 D BluetoothAdapterProperties: Scan Mode:20
08-26 11:20:36.530  6991  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 11:20:36.531  6991  7524 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 11:20:36.534  6991  7663 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:36.535  6991  7673 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:36.536  6991  7674 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:36.536  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 11:20:36.536  6991  7593 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 11:20:36.539  6991  7662 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 11:20:36.543  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 11:20:36.543  6991  7593 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-26 11:20:36.549  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:36.549  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:36.556  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:36.556  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:36.563  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:36.563  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:36.567  6606  6606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:36.567  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:36.567  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:36.567  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 11:20:36.568  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-26 11:20:36.572  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.573  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:36.578  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:36.581  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:36.584  6991  6991 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.584  6991  6991 D BluetoothMapService: STATE_TURNING_OFF
08-26 11:20:36.584  6991  6991 V BluetoothMapService: Handler(): got msg=4
08-26 11:20:36.585  6991  6991 D BluetoothMapService: MAP Service closeService in
08-26 11:20:36.585  6991  6991 D BluetoothMapMasInstance: MAP Service shutdown
08-26 11:20:36.585  6991  6991 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 11:20:36.585  6991  6991 V BluetoothMapService: MAP Service closeService out
08-26 11:20:36.587  6991  6991 V BtOppService: Receiver DISABLED_ACTION 
08-26 11:20:36.587  6991  6991 I BtOppRfcommListener: stopping Accept Thread
08-26 11:20:36.587  6991  6991 V BtOppRfcommListener: close mBtServerSocket
08-26 11:20:36.587  6991  7673 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 11:20:36.588  6991  6991 V BtOppRfcommListener: waiting for thread to terminate
08-26 11:20:36.588  6991  6991 V BtOppRfcommListener: done waiting for thread to terminate
08-26 11:20:36.591  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-26 11:20:36.601  6991  7679 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:36.605  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 11:20:36.607  6991  6991 V BtOppService: onDestroy
08-26 11:20:36.609  6991  6991 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 11:20:36.614  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 11:20:36.614  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.614  6991  6991 V BluetoothPbapReceiver: ***********state = 13
,08-26 11:20:36.618  6991  6991 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 11:20:36.620  6991  6991 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.620  6991  6991 V BluetoothPbapService: state: 13
08-26 11:20:36.620  6991  6991 V BluetoothPbapService: Pbap Service closeService in
08-26 11:20:36.623  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 11:20:36.624  6991  6991 V BluetoothPbapService: successfully stopped pbap service
08-26 11:20:36.624  6991  6991 V BluetoothPbapService: Pbap Service closeService out
08-26 11:20:36.625  6991  6991 V BluetoothPbapService: Pbap Service onDestroy
08-26 11:20:36.625  6991  6991 V BluetoothPbapService: Pbap Service closeService in
08-26 11:20:36.625  6991  6991 V BluetoothPbapService: Pbap Service closeService out
08-26 11:20:36.625  6991  6991 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 11:20:36.649  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:36.653  6853  6853 D BluetoothPbap: Proxy object disconnected
08-26 11:20:36.653  6853  6853 D PbapServerProfile: Bluetooth service disconnected
08-26 11:20:36.658  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 11:20:36.662  6853  6853 D BluetoothPermissionRequest: onReceive
,08-26 11:20:36.662  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 11:20:36.668  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 11:20:36.671  6991  6991 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 11:20:36.672  6991  6991 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 11:20:36.672  6991  6991 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 11:20:36.675  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.676  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 11:20:36.677  6991  6991 V BluetoothFtpService: Ftp Service onStartCommand
08-26 11:20:36.677  6991  6991 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.677  6991  6991 V BluetoothFtpService: Ftp Service closeService
08-26 11:20:36.677  6991  6991 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-26 11:20:36.679  6991  6991 V BluetoothFtpService: successfully stopped ftp service
,08-26 11:20:36.680  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:36.680  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:36.680  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 11:20:36.680  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.680  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 11:20:36.680  6991  6991 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 11:20:36.681  6991  6991 V BluetoothFtpService: Ftp Service onDestroy
08-26 11:20:36.681  6991  6991 V BluetoothFtpService: Ftp Service closeService
08-26 11:20:36.685  6991  6991 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:36.685  6991  6991 V BluetoothSapService: state: 13
08-26 11:20:36.685  6991  6991 V BluetoothSapService: Stopping SAP server process
08-26 11:20:36.687  6991  6991 V BluetoothSapService: Sap Service closeSapService in
08-26 11:20:36.687  6991  6991 V BluetoothSapService: Close listen Socket : 
08-26 11:20:36.687  6991  6991 V BluetoothSapService: Close rfcomm Socket : 
,08-26 11:20:36.687  6991  6991 V BluetoothSapService: Close sapd  Socket : 
08-26 11:20:36.688  6991  6991 V BluetoothSapService: Sap Service closeSapService out
08-26 11:20:36.689  6991  6991 V BluetoothSapService: Sap Service onDestroy
08-26 11:20:36.689  6991  6991 V BluetoothSapService: Sap Service closeSapService in
08-26 11:20:36.689  6991  6991 V BluetoothSapService: Close listen Socket : 
08-26 11:20:36.689  6991  6991 V BluetoothSapService: Close rfcomm Socket : 
08-26 11:20:36.689  6991  6991 V BluetoothSapService: Close sapd  Socket : 
08-26 11:20:36.689  6991  6991 V BluetoothSapService: Sap Service closeSapService out
,08-26 11:20:37.444  6991  7528 D bt_hci_bdroid: cleanup
,08-26 11:20:37.452  6991  7595 I bt_lpm  : LPM is already off!!!
08-26 11:20:37.452  6991  7634 I bt_userial_mct: exiting userial_read_thread
08-26 11:20:37.452  6991  7634 D bt_userial_mct: Leaving userial_evt_read_thread(),
08-26 11:20:37.453  6991  7593 W bt-btif : ag scb idx 1 not allocated
08-26 11:20:37.453  6991  7593 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 11:20:37.453  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:37.453  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 11:20:37.454  6991  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 11:20:37.455  6991  7593 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 11:20:37.457  6991  7528 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 11:20:37.458  6991  7595 I bt_vendor: hw_epilog_process
08-26 11:20:37.458  6991  7528 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 11:20:37.458  6991  7528 D bt_userial_mct: userial_close
08-26 11:20:37.458  6991  7528 E bt_userial_mct: pthread_join() FAILED result:3
08-26 11:20:37.458  6991  7528 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 11:20:37.466  6991  7528 D bt_hci_bdroid: set_power 0
08-26 11:20:37.466  6991  7528 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 11:20:37.467  6991  7528 I bt_vendor: bluetooth satus is on
08-26 11:20:37.467  6991  7528 I bt_vendor: bt-vendor : resetting BT status
08-26 11:20:37.467  6991  7528 I bt_vendor: Starting hciattach daemon
08-26 11:20:37.467  6991  7528 I bt_vendor: try to set false
,08-26 11:20:37.474  6991  7528 I bt_vendor: Starting hciattach daemon
08-26 11:20:37.474  6991  7528 I bt_vendor: try to set false
08-26 11:20:37.475  6991  7528 I bt_vendor: cleanup
08-26 11:20:37.476  6991  7593 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 11:20:37.476  6991  7528 I GKI_LINUX: GKI_exit_task 0 done
08-26 11:20:37.476  6991  7528 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 11:20:37.478  6991  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 11:20:37.482  6991  6991 D HeadsetService: Received stop request...Stopping profile...
,08-26 11:20:37.486  6991  6991 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 11:20:37.486  6991  6991 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 11:20:37.486  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:37.487  6991  7563 D HeadsetStateMachine: Exit Disconnected: -1
08-26 11:20:37.492  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:37.493  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:37.493  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 11:20:37.495  1853  1853 D BluetoothHeadset: Proxy object disconnected
,08-26 11:20:37.500  6991  6991 D A2dpService: Received stop request...Stopping profile...
08-26 11:20:37.500  6991  7578 D A2dpStateMachine: Exit Disconnected: -1
08-26 11:20:37.503  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:37.503  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 11:20:37.504  6991  7524 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 11:20:37.505  6991  6991 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 11:20:37.505  6991  6991 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 11:20:37.505  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:37.508  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 11:20:37.508  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 11:20:37.510  6991  6991 D HidService: Received stop request...Stopping profile...
08-26 11:20:37.510  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:37.512  6991  6991 D HeadsetStateMachine: Unbinding service...
08-26 11:20:37.514  6991  6991 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 11:20:37.514  6991  6991 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 11:20:37.514  6991  6991 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 11:20:37.514  6991  6991 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 11:20:37.514  6991  6991 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 11:20:37.514  6991  6991 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 11:20:37.514  6991  6991 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 11:20:37.515  6991  6991 D HealthService: Received stop request...Stopping profile...
08-26 11:20:37.515  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:37.517  6991  6991 D PanService: Received stop request...Stopping profile...
08-26 11:20:37.518  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:37.519  6991  6991 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 11:20:37.522  6991  6991 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 11:20:37.522  6991  6991 D BtGatt.GattService: stop()
08-26 11:20:37.522  6991  6991 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 11:20:37.524  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:37.526  6991  6991 D BluetoothMapService: Received stop request...Stopping profile...
08-26 11:20:37.526  6991  6991 D BluetoothMapService: stop()
08-26 11:20:37.527  6991  6991 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 11:20:37.527  6991  6991 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 11:20:37.528  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b633fe8
08-26 11:20:37.529  6991  6991 I BluetoothA2dpServiceJni: cleanupNative
08-26 11:20:37.529  6991  7579 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 11:20:37.530  6991  6991 I GKI_LINUX: GKI_exit_task 2 done
08-26 11:20:37.530  6991  6991 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 11:20:37.530  6991  6991 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 11:20:37.530  6991  6991 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 11:20:37.530  6991  6991 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 11:20:37.531  6991  6991 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 11:20:37.531  6991  6991 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 11:20:37.531  6991  6991 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 11:20:37.531  6991  6991 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 11:20:37.535  6991  6991 V BluetoothMapService: Handler(): got msg=4
08-26 11:20:37.535  6991  6991 D BluetoothMapService: MAP Service closeService in
08-26 11:20:37.535  6991  6991 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 11:20:37.535  6991  6991 V BluetoothMapService: MAP Service closeService out
08-26 11:20:37.537  6991  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 11:20:37.538  6991  7524 D BluetoothAdapterProperties: Setting state to 10
08-26 11:20:37.538  6991  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 11:20:37.538  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:37.538  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 11:20:37.538  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 11:20:37.538  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 11:20:37.539  6991  7524 I BluetoothAdapterState: Entering OffState
08-26 11:20:37.542  6991  6991 D BluetoothMapService: cleanup()
08-26 11:20:37.542  6991  6991 D BluetoothMapService: MAP Service closeService in
08-26 11:20:37.542  6991  6991 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 11:20:37.542  6991  6991 V BluetoothMapService: MAP Service closeService out
08-26 11:20:37.544  6853  6870 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:37.548  1853  2599 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:37.549  6853  6870 D BluetoothPan: onBluetoothStateChange on: false
08-26 11:20:37.550  1853  3502 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:37.550  6853  6870 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 11:20:37.551  6853  6870 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 11:20:37.551  6853  6870 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 11:20:37.552  6853  6870 D BluetoothMap: onBluetoothStateChange: up=false
08-26 11:20:37.552  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:37.553  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:37.554  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 11:20:37.554  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 11:20:37.556  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 11:20:37.556  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 11:20:37.556  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@204e5604 mBinding = false
,08-26 11:20:37.559  1034  1116 D BluetoothManagerService: Sending unbind request.
08-26 11:20:37.564  6991  7528 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 11:20:37.565  6991  6991 I GKI_LINUX: GKI_exit_task 1 done
08-26 11:20:37.565  6991  6991 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 11:20:37.565  6991  6991 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 11:20:37.565  6991  6991 I art     : --- WEIRD: removing null entry 248
08-26 11:20:37.565  6991  6991 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 11:20:37.565  6991  6991 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 11:20:37.567  6991  6991 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 11:20:37.568  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-26 11:20:37.572  6991  6991 I art     : System.exit called, status: 0
08-26 11:20:37.572  6991  6991 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 11:20:37.593   333  2153 V AudioFlinger: 6991 died, releasing its sessions
08-26 11:20:37.594   333  2153 V AudioFlinger:  pid 1853 @ 0
08-26 11:20:37.594   333  2153 V AudioFlinger:  pid 3346 @ 1
08-26 11:20:37.594   333  2153 V AudioFlinger:  pid 3346 @ 2
,08-26 11:20:37.604  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 11:20:37.604  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-26 11:20:37.604  1943  2115 D LGBluetoothAPIService: Message: 101
08-26 11:20:37.604  1943  2115 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-26 11:20:37.604  1943  2115 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-26 11:20:37.604  1943  2115 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-26 11:20:37.736  1034  1889 I ActivityManager: Process com.android.bluetooth (pid 6991) has died
08-26 11:20:37.737  1034  1889 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-26 11:20:37.737  1034  1889 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-26 11:20:37.747  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:37.751  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:37.752  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:37.753  1943  2115 D LGBluetoothAPIService: Message: 2
08-26 11:20:37.753  1943  2115 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-26 11:20:37.754  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:37.759  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-26 11:20:37.759  6853  6853 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 11:20:37.759  1603  1603 D BluetoothAdapter: 1068271875: getState() :  mService = null. Returning STATE_OFF
08-26 11:20:37.759  1603  1603 D BluetoothAdapter: 1068271875: getState() :  mService = null. Returning STATE_OFF
08-26 11:20:37.761  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 11:20:37.824  1034  1703 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7738 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-26 11:20:37.826  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:37.853   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 477us total 29.810ms
,08-26 11:20:37.875   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.841ms
,08-26 11:20:37.897   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 20.611ms
,08-26 11:20:37.912  7738  7738 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 11:20:37.913  7738  7738 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:37.913  7738  7738 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 11:20:37.914  7738  7738 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 11:20:37.934  7738  7738 D BluetoothAdapterApp: Loading JNI Library
,08-26 11:20:37.971  7738  7738 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3cf966d0 Instance Count = 1
,08-26 11:20:37.977  7738  7738 D BluetoothAdapterApp: onCreate
,08-26 11:20:38.002  7738  7738 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-26 11:20:38.002  7738  7738 D ProfileConfigQcom: Adding HeadsetService
08-26 11:20:38.003  7738  7738 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-26 11:20:38.003  7738  7738 D ProfileConfigQcom: Adding A2dpService
08-26 11:20:38.003  7738  7738 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 11:20:38.003  7738  7738 D ProfileConfigQcom: Adding HidService
,08-26 11:20:38.003  7738  7738 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 11:20:38.004  7738  7738 D ProfileConfigQcom: Adding HealthService
08-26 11:20:38.004  7738  7738 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-26 11:20:38.005  7738  7738 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 11:20:38.005  7738  7738 D ProfileConfigQcom: Adding PanService
08-26 11:20:38.005  7738  7738 D ProfileConfigQcom: [BTUI] GattService is supported
,08-26 11:20:38.006  7738  7738 D ProfileConfigQcom: Adding GattService
08-26 11:20:38.006  7738  7738 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-26 11:20:38.006  7738  7738 D ProfileConfigQcom: Adding BluetoothMapService
08-26 11:20:38.007  7738  7738 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-26 11:20:38.007  7738  7738 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 11:20:38.009  7738  7738 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:38.009  7738  7738 V BluetoothPbapReceiver: ***********state = 10
08-26 11:20:38.011  7738  7738 V LGMDMManagerInternal: Create singleton instance
08-26 11:20:38.098  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 11:20:38.101  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 11:20:38.103  7738  7738 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 11:20:38.103  7738  7738 D LGBluetoothAPIServer: [BTUI] onBind()
,08-26 11:20:38.108  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 11:20:38.109  1943  2115 D LGBluetoothAPIService: Message: 100
08-26 11:20:38.109  1943  2115 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 11:20:38.121  6853  6853 D BluetoothPermissionRequest: onReceive
,08-26 11:20:38.126  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 11:20:38.126  6853  6853 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 11:20:38.131  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 11:20:38.141  7738  7738 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-26 11:20:38.160  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 11:20:38.169  7738  7738 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:38.170  7738  7738 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:38.171  7738  7738 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 11:20:38.175  7738  7738 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:38.175  7738  7738 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-26 11:20:38.197  7600  7600 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 11:20:39.586  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:39.586  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:39.794  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 11:20:39.812  1034  1467 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 11:20:39.827  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 11:20:39.852  1034  1034 D administrator: Handling package changes for user 0
,08-26 11:20:39.940  1034  1112 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7767 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 11:20:39.946  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 11:20:39.947  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-26 11:20:39.983  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:40.002  7767  7767 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 11:20:40.050  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 11:20:40.051  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 11:20:40.098  7767  7767 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 11:20:40.098  7767  7767 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:40.105  1034  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 11:20:40.112  1034  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 11:20:40.121  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 11:20:40.123  2434  2434 V GmsNetworkLocationProvi: DISABLE
08-26 11:20:40.168  2434  2434 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-26 11:20:40.241  7767  7813 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 11:20:40.241  7767  7813 I Babel   : MmsConfig.loadMmsSettings
08-26 11:20:40.244  7767  7813 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 11:20:40.244  7767  7813 I Babel   : MmsConfig.loadFromDatabase
,08-26 11:20:40.268  7767  7813 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 11:20:40.268  7767  7813 I Babel   : MmsConfig.loadFromResources
08-26 11:20:40.270  7767  7813 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 11:20:40.270  7767  7813 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-26 11:20:40.274  1034  1111 D LocationProviderProxy: applying state to connected service
08-26 11:20:40.282  7767  7767 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 11:20:40.291  7767  7811 W AudioCapabilities: Unsupported mime audio/evrc
08-26 11:20:40.292  7767  7811 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 11:20:40.294  7767  7811 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 11:20:40.305  1818  7815 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 11:20:40.305  1818  7815 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-26 11:20:40.306  7767  7811 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-26 11:20:40.310  7055  7055 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 11:20:40.311  7767  7811 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 11:20:40.319  7055  7055 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d64ccda
08-26 11:20:40.319  7055  7055 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 11:20:40.319  7055  7055 D AppUp4:CustFacade: isPhone : true
08-26 11:20:40.320  7767  7811 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 11:20:40.321  7055  7055 D AppUp4:CustModeStarterReceiver: begin check event
08-26 11:20:40.321  7055  7055 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 11:20:40.322  1818  5179 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 11:20:40.345  7767  7811 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 11:20:40.347  7767  7811 W VideoCapabilities: Unsupported mime video/divx
08-26 11:20:40.351  7767  7811 W VideoCapabilities: Unsupported mime video/divx311
08-26 11:20:40.354  7767  7811 W VideoCapabilities: Unsupported mime video/divx4
,08-26 11:20:40.363  1034  1703 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7818 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-26 11:20:40.366  1034  1993 I ActivityManager: Killing 6764:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 11:20:40.367  7767  7811 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-26 11:20:40.379  6921  6921 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 11:20:40.379  6921  6921 W System.err: android.os.DeadObjectException
08-26 11:20:40.379  6921  6921 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 11:20:40.379  6921  6921 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 11:20:40.379  6921  6921 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 11:20:40.379  6921  6921 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,08-26 11:20:40.379  6921  6921 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-26 11:20:40.379  6921  6921 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 11:20:40.379  6921  6921 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 11:20:40.379  6921  6921 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 11:20:40.379  6921  6921 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:40.379  6921  6921 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:40.379  6921  6921 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:40.379  6921  6921 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:40.379  6921  6921 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:40.379  6921  6921 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:40.380  6921  6921 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 11:20:40.380  6921  6921 W System.err: android.os.DeadObjectException
08-26 11:20:40.380  6921  6921 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 11:20:40.381  6921  6921 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 11:20:40.381  6921  6921 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 11:20:40.381  6921  6921 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 11:20:40.381  6921  6921 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 11:20:40.381  6921  6921 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 11:20:40.381  6921  6921 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 11:20:40.381  6921  6921 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 11:20:40.381  6921  6921 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:40.381  6921  6921 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:40.381  6921  6921 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:40.381  6921  6921 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:40.381  6921  6921 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:40.381  6921  6921 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:40.381  6921  6921 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 11:20:40.381  6921  6921 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 11:20:40.386  7767  7811 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-26 11:20:40.390  7767  7811 W AudioCapabilities: Unsupported mime audio/eac3
08-26 11:20:40.391  7767  7811 W AudioCapabilities: Unsupported mime audio/ac3
08-26 11:20:40.393  7767  7811 W AudioCapabilities: Unsupported mime audio/g726
08-26 11:20:40.394  7767  7811 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-26 11:20:40.395  7767  7811 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 11:20:40.396  7767  7811 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 11:20:40.398  7767  7811 W VideoCapabilities: Unsupported mime video/theora
08-26 11:20:40.399  7767  7811 W VideoCapabilities: Unsupported mime video/mjpg
08-26 11:20:40.690  1034  1785 W libprocessgroup: failed to open /acct/uid_1000/pid_6764/cgroup.procs: No such file or directory
08-26 11:20:40.690  1034  1785 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 11:20:40.706  6921  6921 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 11:20:40.707  6921  6921 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 11:20:40.734  7818  7818 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 11:20:40.735  7818  7818 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:40.735  7818  7818 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-26 11:20:40.747  1034  1703 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7842 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 11:20:40.747  7818  7818 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 11:20:40.747  7818  7818 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 11:20:40.747  6921  6921 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 11:20:40.833  7842  7842 D UEI.SmartControl: Quickset Services start...
08-26 11:20:40.835  7842  7842 I UEI.SmartControl: Manufacture = LGE
08-26 11:20:40.835  7842  7842 D UEI.SmartControl: Id = LGNevo
08-26 11:20:40.846  7842  7842 D UEI.SmartControl: File observer start...
,08-26 11:20:40.847  7842  7842 E UEI.SmartControl: IR Port is disabled: false
08-26 11:20:40.847  7842  7842 D UEI.SmartControl: Starting file observer...
08-26 11:20:40.848  7842  7842 D UEI.SmartControl: Extracting JNI libs...
,08-26 11:20:40.848  7842  7842 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 11:20:40.869  7818  7818 I SystemConfig: BUILD Country: EU
08-26 11:20:40.869  7818  7818 I SystemConfig: BUILD Operator: OPEN
,08-26 11:20:40.919  1034  2000 I ActivityManager: Killing 6921:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 11:20:40.925  7842  7842 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 11:20:40.925  7842  7842 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 11:20:40.925  7842  7842 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 11:20:40.950  7842  7842 I UEI.SmartControl: --- Selecting new region: 6
,08-26 11:20:40.951  7842  7842 I UEI.SmartControl: Model = LG-D855
08-26 11:20:40.952  7842  7842 D UEI.SmartControl: QS Service created
08-26 11:20:41.065  1034  1923 W libprocessgroup: failed to open /acct/uid_10112/pid_6921/cgroup.procs: No such file or directory
,08-26 11:20:41.094  7842  7842 I UEI.SmartControl: Service initServices...
,08-26 11:20:41.100  7842  7842 D UEI.SmartControl: QS start get config
,08-26 11:20:41.119  1034  2000 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7875 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 11:20:41.123  7818  7871 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 11:20:41.123  7818  7871 I SystemConfig: existFile = false
08-26 11:20:41.123  7818  7871 I SystemConfig: canReadFile = false
08-26 11:20:41.123  7818  7871 I SystemConfig: systemFeature RCS result false
08-26 11:20:41.123  7818  7871 D SystemConfig: refreshRcsSupport() :false
,08-26 11:20:41.163  7842  7842 D UEI.SmartControl: Loading JNI Libs...
,08-26 11:20:41.165  7875  7875 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 11:20:41.166  7875  7875 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 11:20:41.166  7875  7875 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 11:20:41.166  7875  7875 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 11:20:41.275  7875  7875 I AppConfig: Total System Memory = 2995761152
,08-26 11:20:41.286  7875  7875 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-26 11:20:41.386  1034  1958 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7894 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 11:20:41.387  1034  1958 I ActivityManager: Killing 7080:com.lge.email/u0a23 (adj 15): empty #17
,08-26 11:20:41.397  7842  7842 I UEI.SmartControl: Supports setup maps: true
08-26 11:20:41.400  7842  7842 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 11:20:41.400  7842  7842 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 11:20:41.400  7842  7842 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 11:20:41.400  7842  7842 I UEI.SmartControl: ### init IR Blaster...
08-26 11:20:41.404  7842  7842 D serial_port: Configuring serial port
,08-26 11:20:41.410  7842  7842 E UEI.SmartControl: UEIBLaster setting for 616
08-26 11:20:41.410  7842  7842 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 11:20:41.411  7842  7842 I UEI.SmartControl: configuring settings for MAXQ616
08-26 11:20:41.412  7842  7842 I UEI.SmartControl: Get version...
08-26 11:20:41.427  1034  1935 W libprocessgroup: failed to open /acct/uid_10023/pid_7080/cgroup.procs: No such file or directory
,08-26 11:20:41.430  7842  7909 D UEI.SmartControl: serial port data available: 21
08-26 11:20:41.460  7842  7842 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 11:20:41.460  7842  7842 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 11:20:41.460  7842  7842 I UEI.SmartControl: QS saving settings...
08-26 11:20:41.462  7842  7842 D UEI.SmartControl: IR Blaster version: 25672567
08-26 11:20:41.479  7842  7909 D UEI.SmartControl: serial port data available: 4
,08-26 11:20:41.514  7842  7915 I UEI.SmartControl: Device manager: loading config....
08-26 11:20:41.514  7842  7915 D UEI.SmartControl: ----------- loading internal config...
,08-26 11:20:41.517  7842  7842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 11:20:41.525  7842  7842 E UEI.SmartControl: Services init done
08-26 11:20:41.525  7842  7842 D UEI.SmartControl: QS Service init finished
08-26 11:20:41.526  7842  7842 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 11:20:41.526  7842  7842 D UEI.SmartControl: QS Service version code: 201091
08-26 11:20:41.528  7842  7842 D UEI.SmartControl: Service requested: Control
08-26 11:20:41.530  7842  7915 E UEI.SmartControl: Loading SETTINGS...
,08-26 11:20:41.533  7842  7842 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 11:20:41.536  7842  7842 D UEI.SmartControl: Service.onUnbind: IControl
08-26 11:20:41.538  7842  7915 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 11:20:41.539  7842  7842 D UEI.SmartControl: Service.onDestroy
08-26 11:20:41.540  7842  7842 D UEI.SmartControl: Lock is in USE false
08-26 11:20:41.540  7842  7842 D UEI.SmartControl: unbind internal service
08-26 11:20:41.542  7842  7842 D serial_port: close(fd = 25)
08-26 11:20:41.547  7842  7842 I UEI.SmartControl: Serial port is closed.
08-26 11:20:41.547  7842  7842 I UEI.SmartControl: Serial port is closed.
08-26 11:20:41.550  7842  7842 D UEI.SmartControl: Blaster closed
,08-26 11:20:41.550  7842  7842 D UEI.SmartControl: Shut down QS...
08-26 11:20:41.551  7842  7842 D UEI.SmartControl: Stopping QS lib
08-26 11:20:41.551  7842  7842 D UEI.SmartControl: QS lib stop result = true
08-26 11:20:41.551  7842  7842 D UEI.SmartControl: Stopped QS lib
08-26 11:20:41.552  7842  7842 D UEI.SmartControl: Stopped file observer...
08-26 11:20:41.553  7842  7842 D UEI.SmartControl: QS shutdown complete
08-26 11:20:41.554  7842  7914 I UEI.SmartControl: Notify AllClients services are ready: 11
08-26 11:20:41.555  7842  7914 D UEI.SmartControl: -----service ready thread exits
08-26 11:20:41.555  7842  7842 D UEI.SmartControl: QS Service created
08-26 11:20:41.578  7842  7842 I UEI.SmartControl: Service initServices...
08-26 11:20:41.579  7842  7842 D UEI.SmartControl: QS start get config
,08-26 11:20:41.618  7894  7894 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 11:20:41.718  7894  7894 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 11:20:41.718  7894  7894 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:41.755  1034  1404 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3bc2d8a7 type 2 when 135835 com.google.android.gms} when 135835
,08-26 11:20:41.793  7894  7894 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 11:20:41.831  7894  7894 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 11:20:41.833  7894  7894 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 11:20:41.857  7894  7894 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 11:20:41.857  7894  7894 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 11:20:41.869  7842  7842 I UEI.SmartControl: Supports setup maps: true
,08-26 11:20:41.873  7842  7842 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 11:20:41.873  7842  7842 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 11:20:41.873  7842  7842 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 11:20:41.873  7842  7842 I UEI.SmartControl: ### init IR Blaster...
08-26 11:20:41.875  1034  2034 I ActivityManager: Killing 6962:com.lge.formmanager/u0a26 (adj 15): empty #17
08-26 11:20:41.888  7842  7842 D serial_port: Configuring serial port
,08-26 11:20:41.891  7842  7842 E UEI.SmartControl: UEIBLaster setting for 616
08-26 11:20:41.891  7842  7842 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 11:20:41.891  7842  7842 I UEI.SmartControl: configuring settings for MAXQ616
08-26 11:20:41.891  7842  7842 I UEI.SmartControl: Get version...
08-26 11:20:41.907  7842  7941 D UEI.SmartControl: serial port data available: 21
,08-26 11:20:41.909  1034  1889 W libprocessgroup: failed to open /acct/uid_10026/pid_6962/cgroup.procs: No such file or directory
08-26 11:20:41.914  3482  4029 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 11:20:41.915  3482  4029 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34b6848c on behalf of 7894
08-26 11:20:41.916  5033  7942 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-26 11:20:41.934  7842  7842 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 11:20:41.934  7842  7842 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 11:20:41.934  7842  7842 I UEI.SmartControl: QS saving settings...
08-26 11:20:41.935  7842  7842 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 11:20:41.948  7842  7941 D UEI.SmartControl: serial port data available: 4
,08-26 11:20:41.956  1034  1935 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7944 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-26 11:20:41.983  7842  7842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 11:20:41.987  7842  7960 I UEI.SmartControl: Device manager: loading config....,
08-26 11:20:41.987  7842  7960 D UEI.SmartControl: ----------- loading internal config...
08-26 11:20:41.993  7842  7960 E UEI.SmartControl: Loading SETTINGS...
08-26 11:20:41.994  7842  7842 E UEI.SmartControl: Services init done
08-26 11:20:41.994  7842  7842 D UEI.SmartControl: QS Service init finished
08-26 11:20:41.995  7842  7842 D UEI.SmartControl: QS Service version name: 2.1.91
,08-26 11:20:41.995  7842  7842 D UEI.SmartControl: QS Service version code: 201091
08-26 11:20:41.996  7842  7842 D UEI.SmartControl: Service requested: Control
08-26 11:20:41.999  1034  1576 I ActivityManager: Killing 6344:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 11:20:42.003  7894  7894 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 11:20:42.009  7842  7960 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 11:20:42.025  7842  7959 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 11:20:42.025  7842  7959 D UEI.SmartControl: -----service ready thread exits
,08-26 11:20:42.040  7842  7842 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@4d2dca6 that was originally bound here
08-26 11:20:42.040  7842  7842 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@4d2dca6 that was originally bound here
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:42.040  7842  7842 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 11:20:42.193  1034  2000 I art     : Explicit concurrent mark sweep GC freed 39806(1900KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.947ms total 147.939ms
,08-26 11:20:42.217  1034  1958 W libprocessgroup: failed to open /acct/uid_1000/pid_6344/cgroup.procs: No such file or directory
,08-26 11:20:42.227  7842  7842 D UEI.SmartControl: Internal service binding...
,08-26 11:20:42.240  7894  7894 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 11:20:42.258  7944  7944 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 11:20:42.282  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-26 11:20:42.282  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 11:20:42.282  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 11:20:42.282  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-26 11:20:42.282  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 11:20:42.282  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-26 11:20:42.296   329  7969 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 11:20:42.297  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 11:20:42.307  1034  1049 I ActivityManager: Killing 7123:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-26 11:20:42.336  1034  2029 W libprocessgroup: failed to open /acct/uid_10046/pid_7123/cgroup.procs: No such file or directory
,08-26 11:20:42.540  7842  7919 D UEI.SmartControl: Internal timer expired: 2
,08-26 11:20:42.553  1034  2029 V SIM_STK : Menu title from STK is T-Mobile
,08-26 11:20:42.583  5033  7942 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 666 ms] updated apps [took 666 ms] 
,08-26 11:20:42.598  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:42.598  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@197d205c added. We now have 6 listener(s)
,08-26 11:20:42.598  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:42.601  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:42.601  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d4aff65 added. We now have 7 listener(s)
08-26 11:20:42.601  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:42.603  6606  6664 I System.out: IsBluetoothEnabled
08-26 11:20:42.604  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:42.604  1034  1958 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 11:20:42.605  1034  1116 D BluetoothManagerService: Message: 2
08-26 11:20:42.612  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:42.612  1034  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:42.613  1034  1889 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 11:20:42.636  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:42.637  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:42.637  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 11:20:42.638  1034  1116 D BluetoothManagerService: Message: 1
08-26 11:20:42.638  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 11:20:42.672  1034  1116 D BluetoothManagerService: Message: 20
08-26 11:20:42.672  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@274c731c:true
,08-26 11:20:42.673  7738  7738 D BluetoothAdapterState: make
08-26 11:20:42.678  7738  7738 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 11:20:42.679  7738  7738 I bluedroid-qcom: init
08-26 11:20:42.679  7738  7976 I BluetoothAdapterState: Entering OffState
08-26 11:20:42.680  7738  7738 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 11:20:42.680  7738  7738 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 11:20:42.680  7738  7738 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 11:20:42.680  7738  7738 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 11:20:42.680  7738  7738 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 11:20:42.674  7979  7979 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:42.682  7738  7738 I bluedroid-qcom: get_profile_interface socket
08-26 11:20:42.682  7738  7738 I bluedroid-qcom: get_profile_interface map_client
08-26 11:20:42.674  7979  7979 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:42.688  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-26 11:20:42.691  7979  7979 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,08-26 11:20:42.691  7979  7979 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 11:20:42.691  7979  7979 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 11:20:42.692  1034  1116 D BluetoothManagerService: Message: 40
08-26 11:20:42.692  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 11:20:42.693  7738  7754 I bluedroid-qcom: config_hci_snoop_log
08-26 11:20:42.694  7738  7980 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 11:20:42.694  7979  7979 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 11:20:42.696  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 11:20:42.696  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 11:20:42.698  7738  7980 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 11:20:42.699  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 11:20:42.700  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 11:20:42.700  7738  7980 D BluetoothAdapterProperties: Name is: G3
,08-26 11:20:42.703  7979  7979 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 11:20:42.703  7979  7979 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 11:20:42.708  7738  7976 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 11:20:42.709  7738  7976 D BluetoothAdapterProperties: Setting state to 11
08-26 11:20:42.709  7738  7976 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 11:20:42.709  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:42.709  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 11:20:42.710  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 11:20:42.710  7738  7976 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 11:20:42.713  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:42.716  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:42.717  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:42.717  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-26 11:20:42.725  7738  7976 D BluetoothBondStateMachine: make
08-26 11:20:42.728  7738  7738 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 11:20:42.728  7738  7738 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:42.728  7738  7976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:42.728  7738  7738 V BluetoothPbapReceiver: ***********state = 11
08-26 11:20:42.728  7738  7976 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 11:20:42.728  7738  7976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:42.728  7738  7976 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 11:20:42.729  7738  7976 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-26 11:20:42.731  7738  7981 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 11:20:42.734  7738  7976 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:42.735  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 11:20:42.749  7738  7976 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 11:20:42.749  7738  7738 D HeadsetService: Received start request. Starting profile...
08-26 11:20:42.750  7738  7738 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 11:20:42.750  7738  7738 D LGBluetoothHfpAdapter: Version 1.6
08-26 11:20:42.755  7738  7738 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 11:20:42.757  7738  7738 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 11:20:42.757  7738  7738 D HeadsetStateMachine: make
08-26 11:20:42.761  7738  7976 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:42.767  7738  7976 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 11:20:42.772  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 11:20:42.787  7738  7976 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:42.787  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 11:20:42.794  7738  7976 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:42.795  7738  7738 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:42.795  7738  7738 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 11:20:42.799  7738  7976 E BluetoothAdapterService: File transfer profiles supported!!
08-26 11:20:42.799  7738  7738 D HeadsetStateMachine: max_hf_connections = 1
08-26 11:20:42.799  7738  7738 I bluedroid-qcom: get_profile_interface handsfree
,08-26 11:20:42.802  7738  7738 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 11:20:42.802   333  1382 V AudioPolicyService: registerClient() client 0xb558a680, uid 1002
08-26 11:20:42.803   333  2154 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 11:20:42.803   333  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 11:20:42.803   333  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 11:20:42.803  7738  7738 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 11:20:42.803   333  2153 V AudioFlinger: registerClient() client 0xb1023b68, pid 7738
08-26 11:20:42.803   333  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:42.803   333  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:42.803  7738  7738 V ToneGenerator: Create Track: 0xb4928080
08-26 11:20:42.803  7738  7738 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 11:20:42.804  7738  7738 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 11:20:42.804   333  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 11:20:42.804   333  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 11:20:42.804   333  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 11:20:42.804   333  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 11:20:42.804  1603  2191 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:42.804  7738  7738 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 11:20:42.804  1603  2191 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:42.804  7738  7754 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:42.804  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:42.804  7738  7754 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 11:20:42.804  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:42.804  1034  2029 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:42.804  1034  2029 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:42.804  3346  3363 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 11:20:42.804  3346  3363 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 11:20:42.804   333  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:42.804   333  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:42.804  1034  1993 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:42.804  1034  1993 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:42.804  1853  3502 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:42.804   333  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 11:20:42.804  1853  3502 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:42.804  3346  3371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:42.804  3346  3371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:42.805   333  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 11:20:42.805   333  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 11:20:42.805   333  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 11:20:42.805   333  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 11:20:42.805  7738  7754 V Audio,System: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:42.805  7738  7738 V AudioSystem: getLatency() output 2, latency 50
08-26 11:20:42.805  7738  7754 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 11:20:42.805  7738  7738 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 11:20:42.805  7738  7738 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 11:20:42.805   333  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 11:20:42.805   333  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 11:20:42.805   333  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 11:20:42.805   333  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 11:20:42.805   333  1382 V AudioFlinger: createTrack() lSessionId: 23
08-26 11:20:42.806  7738  7738 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 11:20:42.806  1603  2191 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 11:20:42.806  1603  2191 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 11:20:42.806   333   333 V AudioFlinger: acquiring 23 from 7738, for 7738
08-26 11:20:42.806   333   333 V AudioFlinger:  added new entry for 23
08-26 11:20:42.806  7738  7738 V ToneGenerator: ToneGenerator INIT OK, time: 136900
08-26 11:20:42.806  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:42.807  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:42.808  7738  7982 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 11:20:42.808  7738  7982 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 11:20:42.808  7738  7982 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 11:20:42.809  7738  7982 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 11:20:42.809  7738  7738 D A2dpService: Received start request. Starting profile...
08-26 11:20:42.809   333  1381 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7738
08-26 11:20:42.809   333  1381 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 11:20:42.809   333  1381 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 11:20:42.809   333  1381 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 11:20:42.809  7738  7738 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 11:20:42.809   333  1381 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 11:20:42.809   333  1381 V voice   : voice_set_parameters: exit with code(0)
08-26 11:20:42.809   333  1381 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 11:20:42.809   333  1381 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 11:20:42.809   333  1381 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 11:20:42.809   333  1381 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 11:20:42.809   333  1381 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 11:20:42.809   333  1381 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 11:20:42.810  7738  7982 V ToneGenerator: ToneGenerator destructor
08-26 11:20:42.810  7738  7982 V ToneGenerator: stopTone
08-26 11:20:42.810  7738  7982 V ToneGenerator: Delete Track: 0xb4928080
08-26 11:20:42.810  7738  7738 V Avrcp   : make
08-26 11:20:42.810  7738  7738 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 11:20:42.810  7738  7738 I bluedroid-qcom: get_profile_interface avrcp
08-26 11:20:42.812   333  2153 V AudioPolicyService: AudioCommandThread() a,dding release output 2
08-26 11:20:42.812   333  2153 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 11:20:42.812   333  1272 V AudioPolicyService: AudioCommandThread() waking up
08-26 11:20:42.812   333  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 11:20:42.812   333  1272 V AudioPolicyManager: releaseOutput() 2
08-26 11:20:42.812   333  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 11:20:42.812   333  2153 V AudioFlinger: PlaybackThread::Track destructor
08-26 11:20:42.812   333  2153 V AudioFlinger: removeClient_l() pid 7738, calling pid 333
08-26 11:20:42.814  7738  7982 V AudioTrack: ~AudioTrack, releasing session id from 7738 on behalf of 7738
08-26 11:20:42.815   333   333 V AudioFlinger: releasing 23 from 7738 for 7738
08-26 11:20:42.815   333   333 V AudioFlinger:  decremented refcount to 0
08-26 11:20:42.815   333   333 V AudioFlinger: purging stale effects
08-26 11:20:42.815  1034  1703 W Process : Unable to open /proc/7992/status
08-26 11:20:42.815  7738  7976 V LGMDMManager: Create singleton instance
08-26 11:20:42.821  7738  7738 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 11:20:42.822  7738  7738 E AudioManager: No RCC entry present to update
08-26 11:20:42.822  7738  7738 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 11:20:42.826  7738  7976 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 11:20:42.826  7738  7738 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-26 11:20:42.827  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 11:20:42.828  7738  7738 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 11:20:42.831  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 11:20:42.981  1034  1889 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:42.981  1034  1889 V SIM_STK : Menu title from STK is T-Mobile
,08-26 11:20:43.115  1034  1993 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 11:20:43.126  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 11:20:43.131  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 11:20:43.132  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 11:20:43.133  7738  7738 I BluetoothA2dpServiceJni: classInitNative
08-26 11:20:43.133  7738  7738 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 11:20:43.133  7738  7738 D A2dpStateMachine: make
08-26 11:20:43.136  7738  7738 I bluedroid-qcom: get_profile_interface a2dp
08-26 11:20:43.137  7738  8001 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 11:20:43.139  7738  7738 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 11:20:43.139  7738  7738 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 11:20:43.140  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:43.140  7738  8000 D A2dpStateMachine: Enter Disconnected: -2
08-26 11:20:43.141  7738  7738 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 11:20:43.145  7738  7738 D HidService: Received start request. Starting profile...
08-26 11:20:43.145  7738  7738 I bluedroid-qcom: get_profile_interface hidhost
08-26 11:20:43.146  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:43.148  7738  7738 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 11:20:43.161  7738  7738 D HealthService: Received start request. Starting profile...
,08-26 11:20:43.169  7738  7738 I bluedroid-qcom: get_profile_interface health
08-26 11:20:43.169  7738  7738 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 11:20:43.170  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:43.173  7738  7738 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 11:20:43.178  7738  7738 D PanService: Received start request. Starting profile...
08-26 11:20:43.179  7738  7738 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 11:20:43.179  7738  7738 I bluedroid-qcom: get_profile_interface pan
08-26 11:20:43.187  7738  7738 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 11:20:43.187  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:43.188  7738  7738 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-26 11:20:43.195  7738  7738 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 11:20:43.195  7738  7738 D BtGatt.GattService: Received start request. Starting profile...
08-26 11:20:43.195  7738  7738 D BtGatt.GattService: start()
08-26 11:20:43.195  7738  7738 I bluedroid-qcom: get_profile_interface gatt
08-26 11:20:43.196  7738  7738 D BtGatt.AdvertiseManager: advertise manager created
08-26 11:20:43.204  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:43.204  7738  7738 D HeadsetStateMachine: Proxy object connected
08-26 11:20:43.205  7738  7738 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 11:20:43.205  7738  7738 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 11:20:43.209  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
,08-26 11:20:43.209  7738  7738 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-26 11:20:43.211  7738  7738 V BluetoothMapService: BluetoothMapBinder()
08-26 11:20:43.211  7738  7738 D BluetoothMapService: Received start request. Starting profile...
,08-26 11:20:43.211  7738  7738 D BluetoothMapService: start()
08-26 11:20:43.215  7738  7738 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 11:20:43.216  7738  7738 D BluetoothMapEmailAppObserver: createReceiver()
08-26 11:20:43.217  7738  7738 D BluetoothMapEmailAppObserver: initObservers()
,08-26 11:20:43.217  7738  7738 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 11:20:43.228  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:43.232  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 11:20:43.235  7738  7982 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 11:20:43.236  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:43.238  7738  7982 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 11:20:43.239  7738  7982 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 11:20:43.239  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:43.243  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:43.245  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 11:20:43.248  7738  7738 V PanService: [BTUI] SIM Extra State :ABSENT
,08-26 11:20:43.251  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 11:20:43.255  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 11:20:43.255  7738  7738 V BluetoothMapService: Handler(): got msg=1
08-26 11:20:43.256  7738  7738 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:43.256  7738  7738 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:43.256  7738  7738 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 11:20:43.256  7738  7738 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:43.256  7738  7738 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 11:20:43.256  7738  7976 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 11:20:43.256  7738  7976 I bluedroid-qcom: enable
08-26 11:20:43.257  7738  7976 I bt_hci_bdroid: init
08-26 11:20:43.259  7738  7976 I bt_vendor: bt-vendor : init
08-26 11:20:43.260  7738  7976 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 11:20:43.260  7738  7976 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 11:20:43.260  7738  7976 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 11:20:43.260  7738  7976 D bt_userial_mct: userial_init
08-26 11:20:43.260  7738  8011 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 11:20:43.261  7738  8011 I bt-btu  : btu_task pending for preload complete event
08-26 11:20:43.263  7738  7976 D bt_hci_bdroid: set_power 1
08-26 11:20:43.263  7738  7976 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 11:20:43.263  7738  7976 I bt_vendor: Starting hciattach daemon
08-26 11:20:43.263  7738  7976 I bt_vendor: try to set true
,08-26 11:20:43.264  8014  8014 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 11:20:43.264  8014  8014 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:43.297  8015  8015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 11:20:43.366  8021  8021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 11:20:43.379  8022  8022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 11:20:43.406  8024  8024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 11:20:43.418  8025  8025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 11:20:43.431  8026  8026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 11:20:43.457  8027  8027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 11:20:43.478  8029  8029 I libmdmdetect: ESOC framework not supported
08-26 11:20:43.479  8029  8029 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 11:20:43.487  8029  8029 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 11:20:43.487  8029  8029 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 11:20:43.487  8029  8029 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 11:20:43.487  8029  8029 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-26 11:20:43.487  8029  8029 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 11:20:43.487  8029  8029 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 11:20:43.487  8029  8029 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 11:20:43.529  8029  8030 E QC-QMI  : qmi_client [8029] 15: failed to locate client data
08-26 11:20:43.530   477   477 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 11:20:43.530   477   477 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-26 11:20:43.564  8031  8031 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 11:20:43.578  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 11:20:43.616  7738  7976 I bt_vendor: bluetooth satus is on
08-26 11:20:43.616  7738  7976 D bt_hci_bdroid: preload
08-26 11:20:43.616  7738  8013 D bt_userial_mct: userial_open(port:0)
,08-26 11:20:43.616  7738  8013 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 11:20:43.620  7738  8013 I bt_vendor: Done intiailizing UART
08-26 11:20:43.621  7738  8013 I bt_vendor: Done intiailizing UART
08-26 11:20:43.621  7738  8013 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-26 11:20:43.621  7738  8013 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 11:20:43.621  7738  8011 I bt-btu  : btu_task received preload complete event
08-26 11:20:43.622  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 11:20:43.622  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 11:20:43.626  7738  8034 D bt_userial_mct: Entering userial_read_thread()
08-26 11:20:43.628  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 11:20:43.635  7738  8011 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_BNEP,
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_GAP,
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 11:20:43.636  7738  8011 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 11:20:43.729  7738  8011 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
,08-26 11:20:43.729  7738  8011 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa022f061 ,
08-26 11:20:43.729  7738  8011 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa022f061 
,08-26 11:20:43.773  7738  7980 E bt-btif : Calling BTA_HhEnable
08-26 11:20:43.773  7738  7980 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 11:20:43.774  7738  7980 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 11:20:43.777  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-26 11:20:43.779  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-26 11:20:43.779  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 11:20:43.779  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 11:20:43.779  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 11:20:43.780  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 11:20:43.780  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 11:20:43.780  7738  7980 D BluetoothAdapterProperties: Name is: G3
08-26 11:20:43.782  7738  7980 D BluetoothAdapterProperties: Scan Mode:20
08-26 11:20:43.782  7738  7980 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:43.782  7738  7980 D bt_hci_bdroid: postload
08-26 11:20:43.782  7738  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 11:20:43.783  7738  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 11:20:43.784  7738  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 11:20:43.784  7738  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 11:20:43.784  7738  7980 D bte_conf: Device ID record 1 : primary
08-26 11:20:43.785  7738  7980 D bte_conf:   vendorId            = 00c4
,08-26 11:20:43.785  7738  7980 D bte_conf:   vendorIdSource      = 0001
08-26 11:20:43.785  7738  7980 D bte_conf:   product             = 13a1
08-26 11:20:43.785  7738  7980 D bte_conf:   version             = 1000
08-26 11:20:43.785  7738  7980 D bte_conf:   clientExecutableURL = 
08-26 11:20:43.785  7738  7980 D bte_conf:   serviceDescription  = 
08-26 11:20:43.785  7738  7980 D bte_conf:   documentationURL    = 
08-26 11:20:43.785  7738  7980 D bte_conf: bte_load_did_conf no section named DID2.
08-26 11:20:43.790  7738  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:43.790  7738  8011 W bt-smp  : Plain text(LSB ~ MSB) = 85 ab 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:43.790  7738  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = c1 a0 f2 86 85 47 26 30 ba 38 14 cb a1 73 49 9f 
,08-26 11:20:43.796  7738  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 11:20:43.797  7738  8011 W bt-btm  : Stopping oneshot timer
08-26 11:20:43.797  7738  8034 E bt_mct  : hci lib postload completed
08-26 11:20:43.798  7738  7976 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 11:20:43.798  7738  7976 D BluetoothAdapterProperties: ScanMode =  20
08-26 11:20:43.798  7738  7976 D BluetoothAdapterProperties: State =  11
08-26 11:20:43.798  7738  7976 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 11:20:43.798  7738  7976 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 11:20:43.799  7738  7976 D BluetoothAdapterProperties: Setting state to 12
08-26 11:20:43.794  8039  8039 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:43.794  8039  8039 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:43.801  7738  7976 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 11:20:43.801  7738  7980 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 11:20:43.801  7738  7980 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 11:20:43.815  7738  7976 I BluetoothAdapterState: Entering On State
,08-26 11:20:43.822  1034  1116 D BluetoothManagerService: Message: 60
08-26 11:20:43.823  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 11:20:43.823  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 11:20:43.823  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 11:20:43.830  7738  7976 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 11:20:43.831  7738  7976 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 11:20:43.831  7738  7976 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-26 11:20:43.837  7738  7976 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 11:20:43.848  1034  1034 D BluetoothA2dp: Proxy object connected
,08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:43.856  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:43.857  7738  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:43.857  7738  8011 W bt-smp  : Plain text(LSB ~ MSB) = 0c 28 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:43.857  7738  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = 78 6d e2 3f 9c 22 f9 82 07 d2 02 28 19 fd db 3c 
08-26 11:20:43.857  7738  8011 W bt-btm  : Stopping oneshot timer
08-26 11:20:43.864  7738  7976 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 11:20:43.873  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:43.875  6853  6870 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 11:20:43.880  7738  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:43.880  7738  8011 W bt-smp  : Plain text(LSB ~ MSB) = 5e 6a 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:43.880  7738  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = 15 7a 68 db ed 0f ae 6a ab 6d 63 3c f6 56 02 53 
08-26 11:20:43.880  7738  8011 W bt-btm  : Stopping oneshot timer
08-26 11:20:43.897  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:43.900  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 11:20:43.901  6853  7655 D BluetoothPan: onBluetoothStateChange on: true
08-26 11:20:43.901  6853  7655 D BluetoothPan: onBluetoothStateChange call bindService
08-26 11:20:43.904  1853  3502 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 11:20:43.908  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 11:20:43.909  6853  6872 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 11:20:43.912  6853  7655 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 11:20:43.913  6853  6870 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 11:20:43.914  7738  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:43.914  7738  8011 W bt-smp  : Plain text(LSB ~ MSB) = 0b d1 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:43.914  7738  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = 7b 04 0b ca 75 c9 21 2f 2a 14 ba 06 c7 08 a7 91 
08-26 11:20:43.914  7738  8011 W bt-btm  : Stopping oneshot timer
08-26 11:20:43.915  6853  6853 D BluetoothHeadset: Proxy object connected
08-26 11:20:43.915  6853  6853 D HeadsetProfile: Bluetooth service connected
08-26 11:20:43.916  6853  6872 D BluetoothMap: onBluetoothStateChange: up=true
08-26 11:20:43.919  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 11:20:43.921  1034  1034 D BluetoothHeadset: Proxy object connected
08-26 11:20:43.922  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:43.923  8055  8055 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 11:20:43.924  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 11:20:43.926  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 11:20:43.926  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 11:20:43.926  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 11:20:43.928  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:43.928  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 11:20:43.928  1943  2115 D LGBluetoothAPIService: Message: 1
08-26 11:20:43.928  1943  2115 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 11:20:43.928  1943  2115 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-26 11:20:43.928  1943  2115 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 11:20:43.934  1034  1116 D BluetoothManagerService: Message: 40
08-26 11:20:43.934  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 11:20:43.935  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:43.935  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 11:20:43.936  6853  6853 D PanProfile: Bluetooth service connected
08-26 11:20:43.937  7738  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 11:20:43.937  7738  8011 W bt-smp  : Plain text(LSB ~ MSB) = 8a 62 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 11:20:43.937  7738  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 2c d2 c6 27 84 7a 5f d9 af 05 48 82 5e 11 8d 
08-26 11:20:43.937  7738  8011 W bt-btm  : Stopping oneshot timer
08-26 11:20:43.942  7738  7738 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:43.942  7738  7738 D BluetoothMapService: STATE_ON
,08-26 11:20:43.943  6853  6853 D BluetoothA2dp: Proxy object connected
08-26 11:20:43.943  6853  6853 D A2dpProfile: Bluetooth service connected
08-26 11:20:43.945  6853  6853 D BluetoothInputDevice: Proxy object connected
08-26 11:20:43.945  6853  6853 D HidProfile: Bluetooth service connected
08-26 11:20:43.947  6853  6853 D BluetoothMap: Proxy object connected
08-26 11:20:43.947  6853  6853 D MapProfile: Bluetooth service connected
08-26 11:20:43.947  6853  6853 D BluetoothMap: getConnectedDevices()
08-26 11:20:43.947  7738  8041 V BluetoothMapService: getConnectedDevices()
08-26 11:20:43.952  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 11:20:43.953  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 11:20:43.959  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-26 11:20:43.966  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
,08-26 11:20:43.966  7738  7738 V BluetoothPbapService: Pbap Service onCreate
08-26 11:20:43.966  7738  7738 V BluetoothPbapService: Starting PBAP service
08-26 11:20:43.967  7738  7738 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 11:20:43.967  7738  7738 V BluetoothPbapService: Pbap Service onBind
08-26 11:20:43.969  6853  6853 D BluetoothPbap: Proxy object connected
08-26 11:20:43.969  6853  6853 D PbapServerProfile: Bluetooth service connected
08-26 11:20:43.969  7738  7738 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:43.969  7738  7738 V BluetoothPbapService: state: 12
08-26 11:20:43.969  7738  7738 V BluetoothMapService: Handler(): got msg=1
08-26 11:20:43.970  7738  7738 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 11:20:43.970  7738  7738 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 11:20:43.971  7738  7738 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:43.971  7738  7738 V BluetoothPbapReceiver: ***********state = 12
08-26 11:20:43.971  7738  8063 D BluetoothMapMasInstance: MAS initSocket()
08-26 11:20:43.971  7738  8063 D BluetoothMapMasInstance:   masId = 00
08-26 11:20:43.971  7738  8063 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 11:20:43.971  7738  8063 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 11:20:43.971  7738  8063 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 11:20:43.973  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:43.974  7738  7738 V BluetoothPbapService: Handler(): got msg=1
08-26 11:20:43.975  7738  7738 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 11:20:43.976  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 11:20:43.976  2080  2080 D c       : Getting all permits...
08-26 11:20:43.976  2080  2080 D a       : Opening database...
08-26 11:20:43.976  7738  8063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:43.977  7738  8064 V BluetoothPbapService: Pbap Service initSocket
08-26 11:20:43.977  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 11:20:43.978  7738  8063 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 11:20:43.978  7738  8063 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 11:20:43.979  7738  8063 D BluetoothMapMasInstance: Accepting socket connection...
08-26 11:20:43.979  7738  8064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:43.980  7738  8064 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 11:20:43.980  7738  8064 V BluetoothPbapService: Succeed to create listening socket 
08-26 11:20:43.980  7738  8064 V BluetoothPbapService: Accepting socket connection...
08-26 11:20:43.983  2080  2080 D a       : Opening database auth.proximity.permit_store...
08-26 11:20:43.985  2080  2080 D a       : Closing database...
08-26 11:20:43.989  7738  7980 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:43.989  7738  7980 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-26 11:20:43.991  7738  7980 D BluetoothAdapterProperties: Scan Mode:21
08-26 11:20:43.992  7738  7980 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 11:20:43.993  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:43.999  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 11:20:44.000  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 11:20:44.002  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 11:20:44.004  7738  7738 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 11:20:44.005  7738  7738 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 11:20:44.010  7738  7738 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-26 11:20:44.024  7738  7738 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 11:20:44.024  7738  7738 V BtOppService: onCreate
,08-26 11:20:44.028  7738  7738 V BluetoothOppNotification: send message
08-26 11:20:44.031  7738  7738 V BtOppService: Starting RfcommListener
08-26 11:20:44.037  7738  7738 D BluetoothOppPreference: Dumping Names:  
08-26 11:20:44.037  7738  7738 D BluetoothOppPreference: {}
08-26 11:20:44.037  7738  7738 D BluetoothOppPreference: Dumping Channels:  
,08-26 11:20:44.037  7738  7738 D BluetoothOppPreference: {}
08-26 11:20:44.040  7738  7738 V BtOppService: onStartCommand
08-26 11:20:44.044  7738  8072 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 11:20:44.044  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:44.044  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 11:20:44.046  7738  7738 V BluetoothOppNotification: new notify threadi!
08-26 11:20:44.046  7738  7738 V BluetoothOppNotification: send delay message
08-26 11:20:44.047  7738  7738 V BtOppService: start RfcommListener
08-26 11:20:44.050  7738  7738 V BtOppService: RfcommListener started
,08-26 11:20:44.052  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 11:20:44.052  7738  8074 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 11:20:44.053  7738  8072 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 11:20:44.053  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:44.054  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@331b9c8d on behalf of 
08-26 11:20:44.054  7738  8069 V BtOppService: Deleted complete outbound shares, number =  0
08-26 11:20:44.055  7738  8074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:44.057  7738  8074 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-26 11:20:44.058  7738  8074 V BtOppRfcommListener: Started RFCOMM listener....
08-26 11:20:44.058  7738  8074 I BtOppRfcommListener: Accept thread started.
08-26 11:20:44.058  7738  8074 V BtOppRfcommListener: Accepting connection...
08-26 11:20:44.059  7738  8073 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 11:20:44.062  7738  8069 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 11:20:44.062  7738  8072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e82ce42 on behalf of 
,08-26 11:20:44.062  7738  8069 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 11:20:44.063  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
08-26 11:20:44.063  7738  7738 V BluetoothFtpService: Ftp Service onCreate
08-26 11:20:44.063  7738  7738 I BluetoothFtpService: Ftp Service onCreate
08-26 11:20:44.064  7738  7738 V BluetoothFtpService: Ftp Service onStartCommand
08-26 11:20:44.064  7738  7738 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:44.064  7738  7738 V BluetoothFtpService: Starting Listening on sockets
08-26 11:20:44.065  7738  8069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15a6390 on behalf of 
08-26 11:20:44.065  7738  7738 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 11:20:44.065  7738  7738 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 11:20:44.063  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 11:20:44.065  7738  7738 V BluetoothSapReceiver: SapReceiver onReceive 
,08-26 11:20:44.065  7738  7738 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-26 11:20:44.065  7738  7738 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 11:20:44.065  7738  7738 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 11:20:44.068  7738  7738 V BtOppService: ContentObserver received notification
08-26 11:20:44.068  7738  7738 V BtOppService: ContentObserver received notification
08-26 11:20:44.068  7738  7738 V BluetoothFtpService: Handler(): got msg=1
08-26 11:20:44.069  7738  7738 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 11:20:44.069  7738  7738 V BluetoothFtpService: Ftp Service initSocket
,08-26 11:20:44.071  7738  8072 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 11:20:44.071  7738  8072 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 11:20:44.072  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f327489 on behalf of 
08-26 11:20:44.073  7738  8072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22f38c8e on behalf of 
08-26 11:20:44.073  7738  8073 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 11:20:44.073  1034  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:44.073  7738  8072 V BluetoothOppNotification: update too frequent, put in queue
08-26 11:20:44.074  7738  7738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:44.075  7738  8072 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-26 11:20:44.078  7738  7738 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 11:20:44.078  7738  8073 V BluetoothOppNotification: outbound notification was removed.
08-26 11:20:44.078  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 11:20:44.079  7738  8075 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 11:20:44.080  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a5a4caf on behalf of 
08-26 11:20:44.081  7738  8073 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 11:20:44.082  7738  8073 V BluetoothOppNotification: inbound notification was removed.
08-26 11:20:44.083  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 11:20:44.084  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a2a28bc on behalf of 
08-26 11:20:44.094  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2b1601
,08-26 11:20:44.094  7738  7738 V BluetoothSapService: Sap Service onCreate
,08-26 11:20:44.098  7738  7738 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:44.098  7738  7738 V BluetoothSapService: state: 12
,08-26 11:20:44.098  7738  7738 V BluetoothSapService: Starting SAP server process
08-26 11:20:44.094  8076  8076 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:44.100  7738  7738 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 11:20:44.094  8076  8076 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:44.102  7738  8077 V BluetoothSapService: Sap Service initRfcommSocket
08-26 11:20:44.102  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:44.103  7738  8077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:44.104  7738  8077 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 11:20:44.104  7738  8077 V BluetoothSapService: Succeed to create listening socket 
08-26 11:20:44.105  7738  8077 V BluetoothSapService: Accepting socket connection...
08-26 11:20:44.113  8076  8076 V BT_SAP  : Event pipe created
08-26 11:20:44.113  8076  8076 V BT_SAP  : create_server_socket qcom.sap.server
08-26 11:20:44.113  8076  8076 V BT_SAP  : created socket fd 6
,08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:44.657  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:44.669  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:44.671  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:44.671  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fddb43a added. We now have 8 listener(s)
08-26 11:20:44.671  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:44.674  1034  1889 D WifiServiceImplEx: setWifiEnabled: false pid=6606, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 11:20:44.674  1034  1889 D WifiService: setWifiEnabled: false pid=6606, uid=10118
08-26 11:20:44.674  1034  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:44.682  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:44.683  1034  1703 D WifiServiceImplEx: setWifiEnabled: true pid=6606, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 11:20:44.684  1034  1703 D WifiService: setWifiEnabled: true pid=6606, uid=10118
08-26 11:20:44.684  1034  1703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:44.707  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 11:20:44.707  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 11:20:44.707  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 11:20:44.709  1034  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 11:20:44.709  1034  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 11:20:44.711  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 11:20:44.712  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 11:20:44.712  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 11:20:44.712  1034  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 11:20:44.712  1034  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 11:20:44.712  1034  1538 E WifiHW  : unknown target_country: EU , set to default
08-26 11:20:44.712  1034  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 11:20:44.712  1034  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 11:20:44.712  1034  1538 I WifiUtil: gEnableBmps=1
08-26 11:20:45.047  7738  7738 V BluetoothOppNotification: new notify threadi!
08-26 11:20:45.048  7738  7738 V BluetoothOppNotification: send delay message
,08-26 11:20:45.063  7738  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 11:20:45.073  7738  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19cf14a8 on behalf of 
08-26 11:20:45.074  7738  8090 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 11:20:45.109  7738  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 11:20:45.123  7738  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37672bc1 on behalf of 
,08-26 11:20:45.126  7738  8090 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 11:20:45.151  7738  8090 V BluetoothOppNotification: outbound notification was removed.
08-26 11:20:45.151  7738  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 11:20:45.159  7738  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e889f66 on behalf of 
08-26 11:20:45.160  7738  8090 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 11:20:45.164  7738  8090 V BluetoothOppNotification: inbound notification was removed.
08-26 11:20:45.164  7738  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 11:20:45.166  7738  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fa122a7 on behalf of 
08-26 11:20:45.255  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 11:20:45.255  1034  1116 D Tethering: InitialState.processMessage what=4
,08-26 11:20:45.261   329   892 D SoftapController: Softap fwReload - Ok
08-26 11:20:45.262  1034  1538 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (544ms)
08-26 11:20:45.262  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 11:20:45.264   329   892 D CommandListener: Setting iface cfg
08-26 11:20:45.264   329   892 D CommandListener: Trying to bring down wlan0
08-26 11:20:45.264   329   892 D CommandListener: Clearing all IP addresses on wlan0
08-26 11:20:45.264  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 11:20:45.264  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 11:20:45.264  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 11:20:45.264  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 11:20:45.265  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 11:20:45.267  1034  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 11:20:45.270  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:45.270  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:45.270  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 11:20:45.271  1034  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 11:20:45.271  1034  1538 D WifiMonitor: connecting to supplicant
08-26 11:20:45.272  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:45.273  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 11:20:45.277  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:45.274  8115  8115 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:45.274  8115  8115 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 11:20:45.284  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 11:20:45.287  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 11:20:45.287  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 11:20:45.287  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 11:20:45.287  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 11:20:45.287  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 11:20:45.288  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 11:20:45.291  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 11:20:45.291  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 11:20:45.291  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 11:20:45.292  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 11:20:45.292  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 11:20:45.293  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 11:20:45.294  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 11:20:45.294  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-26 11:20:45.296  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 11:20:45.296  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 11:20:45.296  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 11:20:45.303  8115  8115 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 11:20:45.333  8115  8115 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 11:20:45.333  8115  8115 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 11:20:45.342  1034  2034 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8117 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 11:20:45.367  8115  8115 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 11:20:45.409  8115  8115 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 11:20:45.416  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 11:20:45.416  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 11:20:45.417  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 11:20:45.417  1034  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 11:20:45.418  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:45.419  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:45.420  1034  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:45.420  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:45.421  1034  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 11:20:45.421  1034  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 11:20:45.421  1034  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 11:20:45.422  1034  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 11:20:45.422  1034  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 11:20:45.448  1034  2000 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8139 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 11:20:45.455  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 11:20:45.455  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 11:20:45.455  8115  8115 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 11:20:45.456  1034  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 11:20:45.456  1034  1538 E WifiStateMachine: useWiFiOffloading() : false
08-26 11:20:45.456  1034  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 11:20:45.456  8117  8136 W FormManager: Network not available. Please check & try again.
08-26 11:20:45.457  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 11:20:45.457  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 11:20:45.457  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 11:20:45.457  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 11:20:45.458  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.458  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.458  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.458  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.458  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 11:20:45.459  1034  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 11:20:45.459  1943  1943 D WfdService: Waiting for WifiP2p enabling
,08-26 11:20:45.460  1034  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-26 11:20:45.460  1034  1538 D WifiConfigStore: Loading config and enabling all networks 
08-26 11:20:45.460  1034  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 11:20:45.460  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 11:20:45.461  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 11:20:45.461  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:45.461  1034  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:45.465  6606  6606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:45.466  6606  6606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:45.475  8117  8138 V FormManager: Network unavailable.
,08-26 11:20:45.476  1034  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 11:20:45.477  8117  8138 V FormManager: Network unavailable.
08-26 11:20:45.485  1034  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 11:20:45.486  1034  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 11:20:45.488  1034  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-26 11:20:45.488  1034  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-26 11:20:45.489  1034  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 11:20:45.489  1034  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 11:20:45.489  1034  2000 I ActivityManager: Killing 7144:com.android.chrome/u0a57 (adj 15): empty #17
08-26 11:20:45.490  1034  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 11:20:45.490  1034  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-26 11:20:45.490  1034  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 11:20:45.490  1034  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 11:20:45.491  1034  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 11:20:45.491  1034  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-26 11:20:45.491  1034  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 11:20:45.491  1034  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 11:20:45.492  1034  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 11:20:45.492  1034  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 11:20:45.492  1034  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 11:20:45.517  1034  1576 W libprocessgroup: failed to open /acct/uid_10057/pid_7144/cgroup.procs: No such file or directory
08-26 11:20:45.517  1034  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 11:20:45.517  1034  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 11:20:45.518  1034  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 11:20:45.518  1034  1538 D WifiNative-HAL: Setting external_sim to 1
08-26 11:20:45.518  1034  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 11:20:45.518  1034  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 11:20:45.518  1034  1538 I WifiNative-HAL: startHal
08-26 11:20:45.518  1034  1538 D wifi    : setting scan oui 0xaf63eee0
08-26 11:20:45.518  1034  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 11:20:45.518  1034  1538 I WifiNative-HAL: startHal
08-26 11:20:45.519  1034  1538 D wifi    : setting scan oui 0xaf63eee0
08-26 11:20:45.519  1034  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 11:20:45.519  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 11:20:45.519  1943  2273 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 11:20:45.519  1943  2273 D WfdsService: Set the WFDS Monitor: true
08-26 11:20:45.519  1943  2273 D WfdsMonitor: WfdsMonitorThread create
08-26 11:20:45.519  1943  2273 D WfdsMonitor: WFDS Monitor is created and started
08-26 11:20:45.519  1943  2273 D WfdsService: WiFi: Supplicant connection re-established
08-26 11:20:45.520  7767  7767 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.520  1034  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 11:20:45.520  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 11:20:45.520  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 11:20:45.520  1943  8159 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 11:20:45.520  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 11:20:45.521  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 11:20:45.521  1943  8159 E CtrlSupplicant: Succeed to open control connection
08-26 11:20:45.521  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 11:20:45.521  1943  8159 E CtrlSupplicant: Succeed to open monitor connection
08-26 11:20:45.521  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 11:20:45.521  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 11:20:45.521  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 11:20:45.521  1943  8159 D WfdsMonitor: Supplicant connection established
08-26 11:20:45.522  1943  2273 D WfdsService: Connected to the supplicant for wfds
08-26 11:20:45.522  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 11:20:45.522  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 11:20:45.522  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 11:20:45.522  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 11:20:45.522  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 11:20:45.522  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 11:20:45.522  1034  1538 D WifiNative-wlan0: DRIVER RXFIL,TER-STOP: returned true
08-26 11:20:45.523  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 11:20:45.523  8115  8115 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 11:20:45.523  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 11:20:45.523  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 11:20:45.523  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 11:20:45.523  1034  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 11:20:45.524  1034  1538 E WifiNative: : [139,606,400 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 11:20:45.524  1034  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 11:20:45.524  1034  1538 D WifiNative-wlan0: RECONNECT: returned true
08-26 11:20:45.525  1034  1538 D WifiNative-wlan0: doString: [STATUS]
08-26 11:20:45.525  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 11:20:45.525  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 11:20:45.525  1034  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 11:20:45.525  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 11:20:45.526  1034  1538 D WifiNative-wlan0: SET ps 1: returned true
08-26 11:20:45.526  1034  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.527   329   892 D CommandListener: Setting iface cfg
08-26 11:20:45.527   329   892 D CommandListener: Trying to bring up p2p0
08-26 11:20:45.527  1034  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 11:20:45.527  1034  1537 D LGWifiP2pService: P2pEnablingState
08-26 11:20:45.528  1034  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.528  1034  1537 D LGWifiP2pService: P2p socket connection successful
08-26 11:20:45.528  1034  1537 D LGWifiP2pService: P2pEnabledState
08-26 11:20:45.528  1034  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 11:20:45.529  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 11:20:45.529  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 11:20:45.529  1943  2273 D WfdsService: Receive the WFDS_ENABLE Method
08-26 11:20:45.529  1943  2273 D WfdsService: Set the WFDS Monitor: true
08-26 11:20:45.529  1943  2273 D WfdsService: Connected to the supplicant for wfds
08-26 11:20:45.529  1943  2273 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 11:20:45.529  8115  8115 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 11:20:45.529  1943  2273 D WfdsService: selectPreferredScanChannel [36]
08-26 11:20:45.529  1943  2273 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 11:20:45.530  1034  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 11:20:45.530  1034  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 11:20:45.531  1034  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 11:20:45.531  1034  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 11:20:45.531  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 11:20:45.531  1034  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 11:20:45.532  1943  1943 D WfdsService: isConnected: false
08-26 11:20:45.532  1034  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 11:20:45.532  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139615  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 11:20:45.533  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 11:20:45.533  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 11:20:45.533  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.533  1034  1556 I WifiNative-HAL: startHal
08-26 11:20:45.533  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf63eee0
08-26 11:20:45.533  1034  1556 D wifi    : failed to get capabilities : -3
08-26 11:20:45.533  1034  1556 E WifiScanningService: could not get scan capabilities
08-26 11:20:45.533  1034  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 11:20:45.533  1034  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.533  1034  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-26 11:20:45.533  1034  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 11:20:45.533  1034  1537 D LGWifiP2pService: before postfix = G3
08-26 11:20:45.533  1034  1537 D WifiServerServiceExt: postfix byte check : 2
08-26 11:20:45.533  1034  1537 D LGWifiP2pService: after postfix = G3
08-26 11:20:45.533  1034  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 11:20:45.534  1034  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 11:20:45.534  1034  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 11:20:45.534  1034  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 11:20:45.534  1034  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 11:20:45.534  1034  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 11:20:45.534  1034  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 11:20:45.535  8139  8139 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:45.535  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:45.535  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:45.535  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139618  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 11:20:45.535  1034  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 11:20:45.535  1034  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-26 11:20:45.536  1034  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 11:20:45.536  1034  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 11:20:45.536  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.536  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.536  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:45.536  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 11:20:45.536  1034  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 11:20:45.537  1034  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 11:20:45.537  1034  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 11:20:45.537  8115  8115 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 11:20:45.539  1034  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 11:20:45.539  1034  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 11:20:45.539  1034  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 11:20:45.539  1034  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 11:20:45.540  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 11:20:45.540  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 11:20:45.540  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 11:20:45.541  1034  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 11:20:45.541  1034  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 11:20:45.541  1034  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 11:20:45.541  1034  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 11:20:45.542  1034  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 11:20:45.542  1034  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 11:20:45.543  1034  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 11:20:45.543  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 11:20:45.543  1034  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 11:20:45.547  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:45.548  1034  1887 I ActivityManager: Killing 7166:com.lge.drmservice/u0a62 (adj 15): empty #17
08-26 11:20:45.550  8115  8115 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 11:20:45.550  1034  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 11:20:45.550  1034  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 11:20:45.550  1034  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 11:20:45.551  1034  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 11:20:45.551  1034  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 11:20:45.551  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 11:20:45.552  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 11:20:45.552  8115  8115 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.552  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 11:20:45.552  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.552  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.552  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.553  8115  8115 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 11:20:45.553  8115  8115 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.553  1034  8137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.553  1034  8137 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.553  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.553  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.554  8115  8115 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.554  1034  8137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.554  1034  8137 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.554  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.554  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.555  1943  8159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.555  1943  8159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.555  1034  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 11:20:45.556  1034  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 11:20:45.556  1034  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 11:20:45.557  1034  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 11:20:45.557  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 11:20:45.557  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 11:20:45.557  8115  8115 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:45.557  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 11:20:45.557  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:45.557  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:45.557  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 11:20:45.558  1034  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 11:20:45.558  1034  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 11:20:45.558  1034  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 11:20:45.558  1034  1538 D WifiNative-wlan0: doBoolean: SCAN
08-26 11:20:45.559  1034  1538 D WifiNative-wlan0: SCAN: returned false
08-26 11:20:45.559  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_ST,ATE_CHANGE_EVENT 46 0 rt=139642  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 11:20:45.578  1034  1537 D LGWifiP2pService: InactiveState
,08-26 11:20:45.578  1034  1537 D LGWifiP2pService: InactiveState{ when=-37ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.578  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-37ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.578  1034  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 11:20:45.579  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 11:20:45.579  8115  8115 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.580  1034  8137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 11:20:45.580  1034  8137 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.580  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.580  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 11:20:45.580  8115  8115 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 11:20:45.580  8115  8115 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.580  1034  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 11:20:45.580  1034  1537 D LGWifiP2pService: InactiveState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.580  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.580  1943  8159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 11:20:45.580  1034  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.580  1943  8159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.580  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.580  1034  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  8115  8115 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1943  8159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 11:20:45.581  1034  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1034  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:45.581  1943  2273 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 11:20:45.581  1034  1034 E WifiServerServiceExt: No p2p device connected
,08-26 11:20:45.581  1034  1576 W libprocessgroup: failed to open /acct/uid_10062/pid_7166/cgroup.procs: No such file or directory
08-26 11:20:45.582  1034  8137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.582  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139664  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 11:20:45.582  1034  8137 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 11:20:45.582  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.582  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.582  1034  8137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 11:20:45.582  1034  8137 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 11:20:45.582  1034  8137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.582  1034  8137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 11:20:45.582  1034  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:45.583  1034  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:45.583  1034  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE,
08-26 11:20:45.584  1034  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:45.584  1034  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 11:20:45.584  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:45.584  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 11:20:45.585  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:45.585  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.585  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:45.585  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-26 11:20:45.587  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:45.587  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 11:20:45.588  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:45.588  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-26 11:20:45.600  8139  8139 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 11:20:45.603  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 11:20:45.608  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:45.621  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 11:20:45.622  4767  4767 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 11:20:45.623  8117  8161 W FormManager: Network not available. Please check & try again.
08-26 11:20:45.623  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 11:20:45.626  4767  4767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 11:20:45.632  4767  8163 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 11:20:45.635  4767  8164 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 11:20:45.636  4767  8164 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 11:20:45.691  1034  2000 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8165 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 11:20:45.697  8117  8162 V FormManager: Network unavailable.
,08-26 11:20:45.703  8117  8162 V FormManager: Network unavailable.
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:45.722  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:45.723  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:45.728  6606  6664 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 11:20:45.729  6606  6664 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 11:20:45.731  6606  6664 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3edf802c Bundle[{}]
08-26 11:20:45.731  6606  6664 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 11:20:45.731  6606  6664 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 11:20:45.732  6606  6664 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 11:20:45.733  6606  6664 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 11:20:45.733  6606  6664 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 11:20:45.734  6606  6664 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 11:20:45.740  6606  6664 I System.out: Running OutgoingSocketThread
08-26 11:20:45.741  6606  8182 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 872)
08-26 11:20:45.742  6606  8182 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35391
08-26 11:20:45.742  6606  8182 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-26 11:20:45.782  8165  8165 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 11:20:45.783  8165  8165 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 11:20:45.790  8165  8165 V [BNRBootReceiver]: Boot Receiver Return
08-26 11:20:45.793  8165  8165 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 11:20:45.844  7842  7853 E UEI.SmartControl: file observer is disposed!
,08-26 11:20:45.867  1034  1958 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8184 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 11:20:45.869  1034  1958 I ActivityManager: Killing 7191:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-26 11:20:45.942  1034  1050 W libprocessgroup: failed to open /acct/uid_10085/pid_7191/cgroup.procs: No such file or directory
,08-26 11:20:45.985  8184  8184 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 11:20:46.030  8184  8184 D PluginManager: init()
,08-26 11:20:46.042  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 11:20:46.042  1034  8137 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 11:20:46.043  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 11:20:46.043  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-26 11:20:46.043  1034  8137 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 11:20:46.043  8115  8115 E wpa_supplicant: USIM:  scard_init function
08-26 11:20:46.044  8115  8115 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 11:20:46.047  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 11:20:46.047  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 11:20:46.047  1034  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 11:20:46.049  1034  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,08-26 11:20:46.050  1034  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 11:20:46.051  1034  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 11:20:46.052  1034  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 11:20:46.064  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140146  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 11:20:46.065  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140147  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 11:20:46.068  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.068  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.068  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.068  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 11:20:46.068  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:46.068  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:46.068  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 11:20:46.069  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 11:20:46.164  8115  8115 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 11:20:46.176  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 11:20:46.176  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 11:20:46.176  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 11:20:46.176  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 11:20:46.176  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:46.176  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:46.177  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140260  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 11:20:46.178  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140260  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 11:20:46.179  1034  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140261
08-26 11:20:46.179  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 11:20:46.180  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:46.180  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:46.180  8115  8115 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 11:20:46.181  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 11:20:46.181  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 11:20:46.181  1034  8137 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 11:20:46.181  8115  8115 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 11:20:46.182  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 11:20:46.182  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 11:20:46.182  1034  8137 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 11:20:46.182  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:46.182  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:46.183  1034  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140266
08-26 11:20:46.184  1034  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140266
08-26 11:20:46.184  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140267
08-26 11:20:46.185  1034  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140267
08-26 11:20:46.185  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140268  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 11:20:46.188  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140270  SSID: NG700 BSSID: f4:f2:6d:22:,99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 11:20:46.189  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.190  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:46.192  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.194  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.194  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.195  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 11:20:46.199  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 11:20:46.200  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.200  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 11:20:46.201  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:46.201  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 11:20:46.201  1034  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:46.201  1034  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:46.202  1034  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:46.202  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:46.203  1034  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 11:20:46.203  1034  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140286  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 11:20:46.204  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140286  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 11:20:46.204  1034  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140287
08-26 11:20:46.205  1034  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140287
08-26 11:20:46.206  1034  1538 D WifiNative-wlan0: doString: [STATUS]
08-26 11:20:46.206  1034  8137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 11:20:46.206  1034  8137 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 11:20:46.207  1034  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 11:20:46.208  1034  1538 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 11:20:46.214  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.214  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 11:20:46.216  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.216  1034  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 11:20:46.216  1034  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 11:20:46.220  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.220  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.220  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-26 11:20:46.229  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.229  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.229  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 11:20:46.231  1034  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 11:20:46.231  1034  1545 D ConnectivityService: Got NetworkAgent Messenger
08-26 11:20:46.231  1034  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 11:20:46.231  1034  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 11:20:46.231  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 11:20:46.231  1034  1545 D ConnectivityService: NetworkAgent connected
08-26 11:20:46.231  1034  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 11:20:46.232  1034  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 11:20:46.235  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.235  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:46.236  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.236  1034  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 11:20:46.236  1034  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 11:20:46.236  1034  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 11:20:46.237  1034  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 11:20:46.237  1034  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 11:20:46.237  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.237  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:46.238  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.241  1034  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 11:20:46.243   329   892 D CommandListener: Setting iface cfg
08-26 11:20:46.245  1034  1538 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 11:20:46.245  1034  8205 D DhcpStateMachine: StoppedState
08-26 11:20:46.245  1034  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140328  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:46.245  1034  8205 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.245  1034  8205 D DhcpStateMachine: WaitBeforeStartState
08-26 11:20:46.246  1034  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140328  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:46.246  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140328  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:46.247  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:46.247  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 11:20:46.247  1034  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:46.247  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:46.247  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 11:20:46.248  1034  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:46.248  1034  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 11:20:46.249  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13683] from screen [on:0 period:-970536280] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 11:20:46.249  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-970536279] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 11:20:46.249  1034  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 11:20:46.254  1034  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-26 11:20:46.254  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.255  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.255  1034  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.255  1034  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.256  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.256  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.257  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 11:20:46.257  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
08-26 11:20:46.258  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
08-26 11:20:46.258  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 11:20:46.258  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 11:20:46.259  1034  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 11:20:46.259  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 11:20:46.259  1034  1538 D WifiNative-wlan0: SET ps 0: returned true
08-26 11:20:46.259  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 11:20:46.259  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 11:20:46.260  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 11:20:46.260  1034  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 11:20:46.260  1034  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 11:20:46.260  1034  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 11:20:46.260  1034  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@50e0eed target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.260  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@50e0eed target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.260  1034  8205 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.260  1034  8205 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 11:20:46.261   329   892 D CommandListener: Setting iface cfg
08-26 11:20:46.262   329   892 D CommandListener: Trying to bring up wlan0
08-26 11:20:46.262  1034  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 11:20:46.263  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:46.263  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 11:20:46.265  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 11:20:46.265  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 11:20:46.266  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.266  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.266  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.266  1034  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.267  1034  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.267  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 11:20:46.267  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 11:20:46.268  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 11:20:46.269  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 11:20:46.269  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 11:20:46.269  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 11:20:46.269  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 11:20:46.269  1034  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 11:20:46.269  1034  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 11:20:46.270  8115  8115 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 11:20:46.270  1034  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 11:20:46.270  1034  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 11:20:46.271  1034  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.271  1034  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.286  1034  1538 D WifiNative-wlan0: SET ps 1: returned true
08-26 11:20:46.287  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-26 11:20:46.287  1034  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 11:20:46.288  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 11:20:46.288  1034  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 11:20:46.289  1034  1545 D ConnectivityService: ignoring duplicate network state non-change
08-26 11:20:46.290  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 11:20:46.290  1034  1545 D ConnectivityService: Adding iface wlan0 to network 102
08-26 11:20:46.291  1034  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 11:20:46.293  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.293  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:46.294  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.296  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.296  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.296  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 11:20:46.301  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.301  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.301  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-26 11:20:46.303  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 11:20:46.306  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 11:20:46.308  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.308  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.308  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 11:20:46.309  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 11:20:46.311  1034  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 11:20:46.311  1034  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 11:20:46.312  1034  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 11:20:46.313   329   892 E Netd    : netlink response contains error (File exists)
,08-26 11:20:46.314  1034  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 11:20:46.315  1034  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 11:20:46.315  1034  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 11:20:46.315  1034  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 11:20:46.315  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.315  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 11:20:46.318  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.319  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.319  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:46.320  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 11:20:46.320  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 11:20:46.320  1034  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 11:20:46.320  1034  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 11:20:46.320  1034  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 11:20:46.320  1034  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:46.320  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:46.320  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 11:20:46.320  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.320  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 11:20:46.320  1034  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-26 11:20:46.320  1034  1545 D ConnectivityService:    accepting network in place of null
08-26 11:20:46.321  1034  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.321  1034  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.321  1034  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:46.321  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.321  1034  8204 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.321  1034  8204 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 11:20:46.321  1034  8204 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=5,32486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 11:20:46.321  1034  8204 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 11:20:46.321  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 11:20:46.322  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.323  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.323  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 11:20:46.323  1034  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 11:20:46.323  1034  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 11:20:46.324  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 11:20:46.324  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:46.324  1034  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 11:20:46.324  1034  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 11:20:46.324  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 11:20:46.324  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 11:20:46.325  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.325  1034  1545 D ConnectivityService: validation of new default Network = false
08-26 11:20:46.325  1034  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 11:20:46.325  1034  1545 D DSQN    : enableDataServiceNotify 
08-26 11:20:46.326   329  8215 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 11:20:46.325  1034  1545 D DSQN    : start dsqn bin
,08-26 11:20:46.331  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 11:20:46.331  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 11:20:46.331  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 11:20:46.331  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 11:20:46.334  1034  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 11:20:46.335  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.335  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:46.335  1034  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-26 11:20:46.334  8216  8216 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:46.334  8216  8216 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:46.340  1603  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 11:20:46.347  1034  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 11:20:46.351  8216  8216 E DSQN    : DSQN ssw
,08-26 11:20:46.359  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 11:20:46.360  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.360  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.379   329  8215 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 11:20:46.413   329  8215 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 11:20:46.448   329   891 D LGDataListener: argv[0]=dsqncommand
,08-26 11:20:46.448   329   891 D LGDataListener: argv[1]=wlan0
,08-26 11:20:46.448   329   891 D LGDataListener: argv[2]=1
08-26 11:20:46.448   329   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 11:20:46.450  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 11:20:46.450  1034  1114 D DSQN    : start to monitor internet connection
,08-26 11:20:46.463  1034  8205 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 11:20:46.464  1034  8205 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 11:20:46.464  1034  8205 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-26 11:20:46.464  8222  8222 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:46.464  8222  8222 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 11:20:46.483  1034  8204 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 09:20:46 GMT], X-Android-Received-Millis=[1472203246482], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472203246448]}
08-26 11:20:46.483  1034  8204 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 11:20:46.483  1034  8204 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-26 11:20:46.485  1034  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 11:20:46.485  1034  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 11:20:46.485  1034  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:46.485  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:46.485  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 11:20:46.485  1034  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 11:20:46.486  1034  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 11:20:46.486  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.486  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:46.487  1034  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:46.489  1603  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 11:20:46.490  8222  8222 I dhcpcd  : version 5.5.6 starting
08-26 11:20:46.491  1034  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.491  1034  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.491  1034  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 11:20:46.491  8222  8222 E dhcpcd  : get_duid: m
08-26 11:20:46.491  8222  8222 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 11:20:46.491  8222  8222 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 11:20:46.492  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 11:20:46.492  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:46.492  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 11:20:46.512  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 11:20:46.513  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 11:20:46.514  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 11:20:46.519  8184  8184 W ExternalStrings: load override strings
08-26 11:20:46.519  8184  8184 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:46.519  8184  8184 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:46.521  8184  8184 D StatusProvider: onCreate
08-26 11:20:46.535  8222  8222 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-26 11:20:46.536  8222  8222 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 11:20:46.536  8222  8222 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 11:20:46.536  8222  8222 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 11:20:46.536  8222  8222 D dhcpcd  : wlan0: sending REQUEST (xid 0x3c7a2d93), next in 3.93 seconds
08-26 11:20:46.569  8184  8184 V Signer  : override build config not found
,08-26 11:20:46.569  8184  8184 D Signer  : value of property debug is false
,08-26 11:20:46.578  8222  8222 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 11:20:46.598  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 11:20:46.598  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 11:20:46.599  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 11:20:46.599  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 11:20:46.599  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
,08-26 11:20:46.599  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 11:20:46.599  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,08-26 11:20:46.599  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 11:20:46.600  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 11:20:46.600  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,08-26 11:20:46.600  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 11:20:46.600  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,08-26 11:20:46.600  8184  8184 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-26 11:20:46.608  8184  8184 V LGMDMManager: Create singleton instance
,08-26 11:20:46.616  8222  8222 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 11:20:46.616  8222  8222 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 11:20:46.617  8222  8222 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-26 11:20:46.617  8222  8222 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 11:20:46.617  8222  8222 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 11:20:46.618  8222  8222 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 11:20:46.618  8222  8222 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 11:20:46.618  8222  8222 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-26 11:20:46.647  8184  8184 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 11:20:46.706  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:46.710  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 11:20:46.719  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:46.726  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:46.741  6606  6664 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 873)
08-26 11:20:46.741  6606  6664 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 873)
,08-26 11:20:46.745  6606  6664 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-26 11:20:46.750  6606  6664 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 11:20:46.750  6606  6664 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 879)
08-26 11:20:46.753  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:46.753  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d2b98eb added. We now have 2 listener(s)
,08-26 11:20:46.777  1034  2000 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8245 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 11:20:46.778  1034  2000 I ActivityManager: Killing 7222:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-26 11:20:46.796   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 383us total 19.185ms
,08-26 11:20:46.813   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 16.316ms
,08-26 11:20:46.821  8184  8233 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 11:20:46.828   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 387us total 14.044ms
,08-26 11:20:46.869  1034  8205 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-26 11:20:46.870  1034  8205 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-26 11:20:46.870  1034  8205 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 11:20:46.870  1034  8205 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 11:20:46.870  1034  8205 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 11:20:46.870  1034  8205 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 11:20:46.870  1034  8205 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 11:20:46.870  1034  8205 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 11:20:46.870  1034  8205 D DhcpStateMachine: RunningState
,08-26 11:20:46.983  7842  7962 D UEI.SmartControl: Internal timer expired: 3
,08-26 11:20:46.983  7842  7962 D UEI.SmartControl: unbind internal service
,08-26 11:20:47.009  1034  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 11:20:47.017  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 11:20:47.018  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.018  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 11:20:47.018  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.018  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e9e648 added. We now have 9 listener(s)
08-26 11:20:47.019  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.020  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:47.022  1034  1993 W libprocessgroup: failed to open /acct/uid_10093/pid_7222/cgroup.procs: No such file or directory
08-26 11:20:47.035  7842  7842 D UEI.SmartControl: Service.onUnbind: IControl
08-26 11:20:47.037  7842  7842 D UEI.SmartControl: Service.onDestroy
,08-26 11:20:47.037  7842  7842 D UEI.SmartControl: Lock is in USE false
08-26 11:20:47.037  7842  7842 D UEI.SmartControl: unbind internal service
08-26 11:20:47.038  7842  7842 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@24b38439
08-26 11:20:47.038  7842  7842 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 11:20:47.038  7842  7842 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 11:20:47.038  7842  7842 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 11:20:47.038  7842  7842 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 11:20:47.038  7842  7842 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 11:20:47.038  7842  7842 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 11:20:47.039  7842  7842 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 11:20:47.039  7842  7842 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
,08-26 11:20:47.039  7842  7842 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:47.039  7842  7842 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:47.039  7842  7842 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:47.039  7842  7842 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:47.039  7842  7842 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:47.039  7842  7842 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:47.039  7842  7842 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:47.039  7842  7842 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@24b38439
08-26 11:20:47.039  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:47.043  7842  7842 D serial_port: close(fd = 24)
08-26 11:20:47.047  7842  7842 I UEI.SmartControl: Serial port is closed.
08-26 11:20:47.047  7842  7842 I UEI.SmartControl: Serial port is closed.
08-26 11:20:47.047  7842  7842 D UEI.SmartControl: Blaster closed
08-26 11:20:47.047  7842  7842 D UEI.SmartControl: Shut down QS...
08-26 11:20:47.047  7842  7842 D UEI.SmartControl: Stopping QS lib
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:47.047  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:47.047  7842  7842 D UEI.SmartControl: QS lib stop result = true
08-26 11:20:47.047  7842  7842 D UEI.SmartControl: Stopped QS lib
08-26 11:20:47.047  7842  7842 D UEI.SmartControl: QS shutdown complete
08-26 11:20:47.050  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.050  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:47.050  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.050  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e2da06 added. We now have 3 listener(s)
08-26 11:20:47.051  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.052  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.056  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.057  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.057  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.057  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothCo,nnector: setIdentityString: 
08-26 11:20:47.057  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.057  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36a8d8c7 added. We now have 10 listener(s)
08-26 11:20:47.057  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.057  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:47.058  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:47.058  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:47.058  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.058  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.058  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:47.058  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.058  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d2b98eb removed from the list
08-26 11:20:47.058  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.058  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e9e648 removed from the list
08-26 11:20:47.058  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:47.058  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:47.062  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:47.062  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.063  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.063  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.063  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.063  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e9e648 not in the list
08-26 11:20:47.063  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.063  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.064  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.064  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.064  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.064  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36a8d8c7 removed from the list
08-26 11:20:47.064  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.064  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.064  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.064  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.064  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e2da06 removed from the list
08-26 11:20:47.065  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.065  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28db1ef4 added. We now have 2 listener(s)
08-26 11:20:47.066  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.069  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.069  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.069  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.070  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.070  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d72b61d added. We now have 9 listener(s)
08-26 11:20:47.070  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.070  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:47.071  8245  8245 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 11:20:47.073  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:47.078  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:47.080  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.080  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:47.080  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.080  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d03a63 added. We now have 3 listener(s)
08-26 11:20:47.081  1034  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.082  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.083  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.083  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.083  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.084  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.084  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13053660 added. We now have 10 listener(s)
08-26 11:20:47.084  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.084  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:47.084  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:47.084  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:47.084  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:47.084  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 11:20:47.087  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.089  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 11:20:47.089  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.094  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 11:20:47.094  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 11:20:47.097  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:47.097  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:47.099  6606  6664 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 11:20:47.099  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:47.099  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:47.102  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:47.102  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:47.102  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:47.102  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.102  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.102  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:47.102  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.102  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28db1ef4 removed from the list
08-26 11:20:47.102  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.102  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d72b61d removed from the list
08-26 11:20:47.102  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:47.102  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.103  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.103  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.103  8245  8245 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 11:20:47.104  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.104  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.104  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.104  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d72b61d not in the list
08-26 11:20:47.104  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.104  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.105  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.105  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:47.105  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:47.105  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.106  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.106  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13053660 removed from the list
08-26 11:20:47.106  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.106  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.106  6606  6,664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.106  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.106  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d03a63 removed from the list
08-26 11:20:47.107  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.107  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8219bf added. We now have 2 listener(s)
08-26 11:20:47.109  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.113  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.113  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.113  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.113  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.113  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f7588c added. We now have 9 listener(s)
08-26 11:20:47.114  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.114  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:47.118  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:47.125  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:47.127  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.127  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:47.127  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.127  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222b9fea added. We now have 3 listener(s)
08-26 11:20:47.128  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 11:20:47.129  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.131  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.131  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.131  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.131  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.131  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@304892db added. We now have 10 listener(s)
08-26 11:20:47.131  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.132  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:47.132  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:47.132  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:47.132  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:47.133  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:47.133  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:47.135  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.137  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 11:20:47.137  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.141  8245  8245 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 11:20:47.141  8245  8245 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 11:20:47.141  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 11:20:47.141  8245  8245 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 11:20:47.142  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 11:20:47.142  8245  8245 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 11:20:47.142  8245  8245 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 11:20:47.143  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:47.143  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:47.144  8245  8245 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 11:20:47.145  6606  6664 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 11:20:47.145  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:47.145  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:47.145  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:47.145  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.145  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.145  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:47.145  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.145  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8219bf removed from the list
08-26 11:20:47.145  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.145  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f7588c removed from the list
08-26 11:20:47.146  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:47.146  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.146  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.146  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.147  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.147  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.147  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.147  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f7588c not in the list
08-26 11:20:47.147  6606  6664 W org.thaliproject.p2p.btconn,ectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.147  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.148  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.149  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:47.149  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:47.149  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.149  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.149  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@304892db removed from the list
08-26 11:20:47.149  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.149  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.149  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.149  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.149  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222b9fea removed from the list
08-26 11:20:47.149  8245  8245 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 11:20:47.150  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.150  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1bd0b6 added. We now have 2 listener(s)
08-26 11:20:47.150  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.152  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.153  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.153  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173381b7 added. We now have 9 listener(s)
08-26 11:20:47.153  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.153  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 11:20:47.155  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:47.155  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.158  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:47.159  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:47.160  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.160  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:47.160  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.160  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d2608d added. We now have 3 listener(s)
,08-26 11:20:47.160  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.163  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.163  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.163  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.163  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.163  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380c4242 added. We now have 10 listener(s)
08-26 11:20:47.163  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.163  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:47.163  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:47.163  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:47.163  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:47.163  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:47.165  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:47.167  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 11:20:47.167  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.167  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.170  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 11:20:47.171  8245  8245 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:47.171  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 11:20:47.173  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:47.173  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.173  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 11:20:47.174  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:47.174  8245  8245 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 11:20:47.177  6606  6664 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 11:20:47.178  8245  8245 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 11:20:47.178  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:47.179  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:47.179  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:47.179  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.179  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.179  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:47.179  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.179  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1bd0b6 removed from the list
08-26 11:20:47.179  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.179  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173381b7 removed from the list
08-26 11:20:47.179  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:47.179  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.181  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.181  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.181  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:47.182  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.182  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.182  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.182  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173381b7 not in the list
08-26 11:20:47.182  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.182  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.182  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.183  6606  6664 D BluetoothLeScanner: could not find callback wrapper
08-26 11:20:47.183  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:47.183  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.183  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:47.183  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380c4242 removed from the list
08-26 11:20:47.183  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.183  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.183  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.183  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 11:20:47.183  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d2608d removed from the list
08-26 11:20:47.183  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.184  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22917889 added. We now have 2 listener(s)
08-26 11:20:47.184  1034  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 11:20:47.186  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
08-26 11:20:47.186  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.186  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.186  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.186  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0408e added. We now have 9 listener(s),
08-26 11:20:47.186  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.186  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:47.186  8184  8233 D LgDataFeature: LgDataFeature() Constructor: none
08-26 11:20:47.186  8184  8233 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:47.187  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.190  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:47.193  6606  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:47.194  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.194  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.194  6606  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:47.194  6606  6664 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:47.194  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:47.194  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747fcbc added. We now have 3 listener(s)
08-26 11:20:47.195  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 11:20:47.196  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.196  8245  8245 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 11:20:47.198  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 11:20:47.199  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:47.199  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:47.199  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.199  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e101445 added. We now have 10 listener(s)
08-26 11:20:47.199  6606  6664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.199  6606  6664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:47.199  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:47.199  6606  6664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:47.199  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:47.199  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.199  6606  6664 D org.thaliproject.p2p.b,tconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:47.199  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.199  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 11:20:47.199  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22917889 removed from the list
08-26 11:20:47.199  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.199  6606  6606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:47.199  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0408e removed from the list
08-26 11:20:47.200  6606  6664 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:47.200  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.200  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.200  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.201  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.201  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.201  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.201  6606  6664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0408e not in the list
08-26 11:20:47.201  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.201  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.202  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:47.202  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:47.202  6606  6664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:47.202  6606  6664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e101445 removed from the list
08-26 11:20:47.202  6606  6664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:47.202  6606  6664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:47.202  6606  6664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:47.202  6606  6664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:47.202  6606  6664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747fcbc removed from the list
08-26 11:20:47.202  6853  6853 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 11:20:47.202  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 11:20:47.203  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 11:20:47.203  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 11:20:47.203  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 11:20:47.203  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 11:20:47.203  6606  6664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:47.204  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.204  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 11:20:47.216  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 11:20:47.217  6606  8282 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 886, name: My test thread name)
08-26 11:20:47.217  6606  8282 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 886, thread name: My test thread name)
08-26 11:20:47.217  6606  8282 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 886, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 11:20:47.222  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 11:20:47.222  6606  8283 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 888, name: My test thread name)
08-26 11:20:47.222  6606  8283 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 888, thread name: My test thread name)
08-26 11:20:47.222  6606  8283 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 888, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 11:20:47.223  6606  6664 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 11:20:47.224  6606  6664 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 11:20:47.224  6606  6664 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 11:20:47.224  6606  6664 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 11:20:47.224  6606  6664 D com.test.thalitest.ThaliTestRunner: Total duration: 23201 ms
08-26 11:20:47.225  6606  6664 I jxcore-log: Total number of executed tests:  80
08-26 11:20:47.225  6606  6664 I jxcore-log: 
08-26 11:20:47.225  6606  6664 I jxcore-log: Number of passed tests:  80
08-26 11:20:47.225  6606  6664 I jxcore-log: 
08-26 11:20:47.225  6606  6664 I jxcore-log: Number of failed tests:  0
08-26 11:20:47.225  6606  6664 I jxcore-log: 
08-26 11:20:47.225  6606  6664 I jxcore-log: Number of ignored tests:  0
08-26 11:20:47.225  6606  6664 I jxcore-log: 
08-26 11:20:47.225  6606  6664 I jxcore-log: Total duration:  23201
08-26 11:20:47.225  6606  6664 I jxcore-log: 
08-26 11:20:47.226  6606  6664 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 11:20:47.226  6606  6664 I jxcore-log: 
08-26 11:20:47.228  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.228  6606  6664 I jxcore-log: 
08-26 11:20:47.229  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.230  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.230  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.230  6606  6664 I jxcore-log: 
08-26 11:20:47.230  8245  8245 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:47.232  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 11:20:47.232  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 11:20:47.232  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 11:20:47.232  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 11:20:47.232  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 11:20:47.232  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.232  6606  6664 I jxcore-log: 
08-26 11:20:47.233  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-26 11:20:47.233  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 11:20:47.233  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 11:20:47.233  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.233  6606  6664 I jxcore-log: 
08-26 11:20:47.233  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 11:20:47.233  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 11:20:47.233  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 11:20:47.233  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 11:20:47.234  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.234  6606  6664 I jxcore-log: 
08-26 11:20:47.235  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.235  6606  6664 I jxcore-log: 
08-26 11:20:47.236  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.236  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 11:20:47.237  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 11:20:47.237  6606  6664 I jxcore-log: 
08-26 11:20:47.239  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 11:20:47.239  6606  6664 I jxcore-log: 
08-26 11:20:47.239  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.239  6606  6664 I jxcore-log: 
08-26 11:20:47.239  6606  6606 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 11:20:47.240  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.240  6606  6664 I jxcore-log: 
08-26 11:20:47.241  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 11:20:47.241  6606  6664 I jxcore-log: 
08-26 11:20:47.242  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 11:20:47.242  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 11:20:47.242  6606  6664 I jxcore-log: 
08-26 11:20:47.243  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 11:20:47.243  6606  6664 I jxcore-log: 
08-26 11:20:47.244  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.244  6606  6664 I jxcore-log: 
,08-26 11:20:47.245  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.245  6606  6664 I jxcore-log: 
08-26 11:20:47.246  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.246  6606  6664 I jxcore-log: 
08-26 11:20:47.247  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.247  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.247  6606  6664 I jxcore-log: 
08-26 11:20:47.247  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.247  6606  6664 I jxcore-log: 
08-26 11:20:47.248  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.248  6606  6664 I jxcore-log: 
08-26 11:20:47.249  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.249  6606  6664 I jxcore-log: 
08-26 11:20:47.249  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:47.249  6606  6664 I jxcore-log: 
08-26 11:20:47.250  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 11:20:47.250  6606  6664 I jxcore-log: 
08-26 11:20:47.250  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 11:20:47.250  6606  6664 I jxcore-log: 
08-26 11:20:47.251  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.251  6606  6664 I jxcore-log: 
08-26 11:20:47.251  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.251  6606  6664 I jxcore-log: 
08-26 11:20:47.252  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.252  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.252  6606  6664 I jxcore-log: 
08-26 11:20:47.252  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.252  8245  8245 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:47.252  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.252  6606  6664 I jxcore-log: 
08-26 11:20:47.253  6606  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:47.253  6606  6664 I jxcore-log: 
08-26 11:20:47.254  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.254  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: ,android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 11:20:47.258  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:47.261  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.266  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.266  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.266  8245  8245 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:47.268  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:47.268  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 11:20:47.272  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:47.275  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.280  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:47.280  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.280  8245  8245 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:47.282  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.282  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 11:20:47.285  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:47.290  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.295  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.295  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.295  8245  8245 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:47.303  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:47.311  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 11:20:47.313  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:47.324  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.331  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:47.336  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.337  8184  8233 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-26 11:20:47.341  8245  8245 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:47.344  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.344  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 11:20:47.349  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:47.355  8184  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 11:20:47.356  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.363  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 11:20:47.363  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 11:20:47.364  8245  8245 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 11:20:47.366  8184  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 11:20:47.367  8184  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 11:20:47.367  8184  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 11:20:47.368  8184  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 11:20:47.368  8184  8233 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 11:20:47.369  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.369  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 11:20:47.371  8184  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-26 11:20:47.373  8139  8139 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 11:20:47.374  8184  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-26 11:20:47.376  8139  8139 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 11:20:47.381  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 11:20:47.397  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.397  1034  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:47.397  1034  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:47.398  1034  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 11:20:47.398  1034  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:47.398  1034  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:47.398  1034  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 11:20:47.399  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 11:20:47.399  1034  1545 D ConnectivityService: identical MTU - not setting
08-26 11:20:47.399  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 11:20:47.399  1034  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 11:20:47.399  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 11:20:47.399  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:47.400  1034  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 11:20:47.400  1603  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 11:20:47.402  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.402  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.404  8245  8245 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 11:20:47.405  8245  8245 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 11:20:47.406  8245  8245 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 11:20:47.410  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.410  8184  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 11:20:47.414  8139  8139 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 11:20:47.415  8139  8139 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 11:20:47.418  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 11:20:47.423  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 11:20:47.430  8245  8245 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 11:20:47.431  8245  8245 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 11:20:47.432  8245  8245 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 11:20:47.432  8245  8245 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 11:20:47.433  8245  8245 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 11:20:47.436  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-26 11:20:47.442  8245  8245 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 11:20:47.444  8245  8245 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 11:20:47.444  8245  8245 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 11:20:47.461  8284  8284 D AndroidRuntime: 
08-26 11:20:47.461  8284  8284 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 11:20:47.463  8284  8284 D AndroidRuntime: CheckJNI is OFF
08-26 11:20:47.487  8245  8245 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 11:20:47.487  8245  8245 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 11:20:47.492  8245  8245 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 11:20:47.494  8245  8245 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 11:20:47.494  8245  8245 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 11:20:47.494  8245  8245 V SoundPool: doLoad: loading sample sampleID=1
08-26 11:20:47.495  8245  8245 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 11:20:47.495  8245  8293 V SoundPool: Start decode
08-26 11:20:47.495  8245  8293 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 11:20:47.495   333  1382 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 11:20:47.496   333  1382 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 11:20:47.496   333  1382 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 11:20:47.496   333  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 11:20:47.496   333  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 11:20:47.496   333  1382 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 11:20:47.496   333  1382 V MediaPlayerService: player type = 3
08-26 11:20:47.496   333  1382 V AwesomePlayer: AwesomePlayer create()
08-26 11:20:47.498  8245  8245 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 11:20:47.499  7842  7842 D UEI.SmartControl: QS Service created
08-26 11:20:47.500  8245  8245 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 11:20:47.503  8245  8245 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 11:20:47.503   333  1382 V AwesomePlayer: reset_l() 
08-26 11:20:47.503   333  1382 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:47.503   333  1382 V AwesomePlayer: setAudioSink() 
,08-26 11:20:47.503   333  1382 V AwesomePlayer: reset_l() 
08-26 11:20:47.503   333  1382 V AudioCache: notify(0xb100a300, 8, 0, 0)
08-26 11:20:47.503   333  1382 V AudioCache: ignored
08-26 11:20:47.504   333  1382 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:47.504   333  1382 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 11:20:47.504   333  1382 V AwesomePlayer: setDataSource_l dataSource
08-26 11:20:47.504   333  1382 V LGParserOSAL: SniffLGParser start
08-26 11:20:47.504   333  1382 V LGParserOSAL: MainType:5, SubType=0
08-26 11:20:47.505   333  1382 V LGParserOSAL: #### check Mime : application/ogg
08-26 11:20:47.505   333  1382 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 11:20:47.505   333  1382 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 11:20:47.507  7842  7842 I UEI.SmartControl: Service initServices...
08-26 11:20:47.507  7842  7842 D UEI.SmartControl: QS start get config
08-26 11:20:47.537  8245  8245 V LGMDMManager: Create singleton instance
,08-26 11:20:47.553   333  1382 V LGParserOSAL: supported mime: application/ogg
08-26 11:20:47.553   333  1382 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 11:20:47.553   333  1382 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 11:20:47.553   333  1382 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 11:20:47.553   333  1382 V AwesomePlayer: AudioTrack Setting
08-26 11:20:47.553   333  1382 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 11:20:47.553   333  1382 V AwesomePlayer: setAudioSource() 
08-26 11:20:47.553   333  1382 V MediaPlayerService: prepare
08-26 11:20:47.553   333  1382 V AwesomePlayer: prepareAsync_l() 
08-26 11:20:47.554   333  1382 V MediaPlayerService: wait for prepare
08-26 11:20:47.554   333  8304 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 11:20:47.554   333  8304 V AwesomePlayer: initAudioDecoder() 
08-26 11:20:47.554   333  8304 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 11:20:47.554   333  8304 V AudioSystem: isOffloadSupported()
08-26 11:20:47.554   333  8304 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 11:20:47.554   333  8304 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 11:20:47.554   333  8304 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 11:20:47.554   333  8304 V AwesomePlayer: getUseOffload() = 0 
08-26 11:20:47.554   333  8304 V OMXCodec: OMXCodec::Create
08-26 11:20:47.554   333  8304 V OMXCodec: findMatchingCodecs()
08-26 11:20:47.554   333  8304 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 11:20:47.554   333  8304 V OMXCodec: matchingCodecs.size()=1
08-26 11:20:47.554   333  8304 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 11:20:47.555   333  8304 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 11:20:47.555   333  8304 V LGCodecAdapter: LG Codec Adapter start
08-26 11:20:47.555   333  8304 V OMXCodec: OMXCodec Createtor
,08-26 11:20:47.555   333  8304 V OMXCodec: setComponentRole
08-26 11:20:47.555   333  8304 V OMXCodec: configureCodec protected=0
08-26 11:20:47.555   333  8304 V LGCodecAdapter: called getLGCodecSpecificData
08-26 11:20:47.555   333  8304 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 11:20:47.555   333  8304 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 11:20:47.555   333  8304 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 11:20:47.555   333  8304 V LGCodecOSAL: Not support LGCodec
08-26 11:20:47.555   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 11:20:47.555   333  8304 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 11:20:47.555   333  8304 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 11:20:47.555   333  8304 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 11:20:47.555   333  8304 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 11:20:47.555   333  8304 V AudioSystem: isOffloadSupported()
08-26 11:20:47.555   333  8304 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 11:20:47.555   333  8304 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 11:20:47.555   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 11:20:47.555   333  8304 V OMXCodec: init()
08-26 11:20:47.555   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 11:20:47.555   333  8304 V OMXCodec: allocateBuffers
08-26 11:20:47.555   333  8304 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 11:20:47.555   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 11:20:47.555   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-26 11:20:47.555   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-26 11:20:47.555   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on input port
08-26 11:20:47.556   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on input port
08-26 11:20:47.556   333  8304 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 11:20:47.556   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 11:20:47.556   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-26 11:20:47.556   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c02e0 on output port
08-26 11:20:47.556   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0420 on output port
08-26 11:20:47.556   333  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c04c0 on output port
08-26 11:20:47.556   333  8304 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 11:20:47.561   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 11:20:47.561   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 11:20:47.561   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 11:20:47.561   333  8304 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 11:20:47.563   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 11:20:47.563   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 11:20:47.563   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 11:20:47.563   333  8304 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 11:20:47.563   333  8304 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 1,1:20:47.563   333  8304 V AudioCache: notify(0xb100a300, 5, 0, 0)
08-26 11:20:47.563   333  8304 V AudioCache: ignored
08-26 11:20:47.563   333  8304 V AudioCache: notify(0xb100a300, 1, 0, 0)
08-26 11:20:47.563   333  8304 V AudioCache: prepared
08-26 11:20:47.563   333  1382 V AudioCache: wait - success
08-26 11:20:47.563   333  1382 V MediaPlayerService: start
08-26 11:20:47.563   333  1382 V AwesomePlayer: play_l() 
08-26 11:20:47.563   333  1382 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 11:20:47.563   333  1382 V AwesomePlayer: createAudioPlayer_l
08-26 11:20:47.563   333  1382 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 11:20:47.563   333  1382 V AwesomePlayer: startAudioPlayer_l() 
08-26 11:20:47.563   333  1382 D AudioPlayer: start of Playback, useOffload 0
08-26 11:20:47.564   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 11:20:47.564   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803296
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803616
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803776
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 11:20:47.566   333  8306 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0420 on output port
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c02e0 on output port
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-26 11:20:47.566   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0740 on output port
08-26 11:20:47.567   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 11:20:47.567   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 11:20:47.567   333  1382 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 11:20:47.567   333  1382 V AudioCache: notify(0xb100a300, 6, 0, 0)
08-26 11:20:47.567   333  1382 V AudioCache: ignored
08-26 11:20:47.568   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.568   333  8307 V AudioCache: memcpy(0xabf08000, 0xb17fb000, 4096)
08-26 11:20:47.568   333  1382 V MediaPlayerService: wait for playback complete
08-26 11:20:47.569   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.569   333  8307 V AudioCache: memcpy(0xabf09000, 0xb17fb000, 4096)
08-26 11:20:47.570   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.570   333  8307 V AudioCache: memcpy(0xabf0a000, 0xb17fb000, 4096)
08-26 11:20:47.570   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.570   333  8307 V AudioCache: memcpy(0xabf0b000, 0xb17fb000, 4096)
08-26 11:20:47.571   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.571   333  8307 V AudioCache: memcpy(0xabf0c000, 0xb17fb000, 4096)
08-26 11:20:47.571   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.571   333  8307 V AudioCache: memcpy(0xabf0d000, 0xb17fb000, 4096)
08-26 11:20:47.571   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.571   333  8307 V AudioCache: memcpy(0xabf0e000, 0xb17fb000, 409,6)
08-26 11:20:47.572   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.572   333  8307 V AudioCache: memcpy(0xabf0f000, 0xb17fb000, 4096)
08-26 11:20:47.572   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.572   333  8307 V AudioCache: memcpy(0xabf10000, 0xb17fb000, 4096)
08-26 11:20:47.572   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.572   333  8307 V AudioCache: memcpy(0xabf11000, 0xb17fb000, 4096)
08-26 11:20:47.572   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.572   333  8307 V AudioCache: memcpy(0xabf12000, 0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: memcpy(0xabf13000, 0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: memcpy(0xabf14000, 0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: memcpy(0xabf15000, 0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.573   333  8307 V AudioCache: memcpy(0xabf16000, 0xb17fb000, 4096)
08-26 11:20:47.574   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.574   333  8307 V AudioCache: memcpy(0xabf17000, 0xb17fb000, 4096)
08-26 11:20:47.574   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.574   333  8307 V AudioCache: memcpy(0xabf18000, 0xb17fb000, 4096)
08-26 11:20:47.574   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.574   333  8307 V AudioCache: memcpy(0xabf19000, 0xb17fb000, 4096)
08-26 11:20:47.574   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.575   333  8307 V AudioCache: memcpy(0xabf1a000, 0xb17fb000, 4096)
08-26 11:20:47.578   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.578   333  8307 V AudioCache: memcpy(0xabf1b000, 0xb17fb000, 4096)
,08-26 11:20:47.580   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.580   333  8307 V AudioCache: memcpy(0xabf1c000, 0xb17fb000, 4096)
08-26 11:20:47.580   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.580   333  8307 V AudioCache: memcpy(0xabf1d000, 0xb17fb000, 4096)
,08-26 11:20:47.580   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.580   333  8307 V AudioCache: memcpy(0xabf1e000, 0xb17fb000, 4096)
08-26 11:20:47.580   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.580   333  8307 V AudioCache: memcpy(0xabf1f000, 0xb17fb000, 4096)
08-26 11:20:47.581   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.581   333  8307 V AudioCache: memcpy(0xabf20000, 0xb17fb000, 4096)
08-26 11:20:47.586   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.586   333  8307 V AudioCache: memcpy(0xabf21000, 0xb17fb000, 4096)
08-26 11:20:47.586   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.586   333  8307 V AudioCache: memcpy(0xabf22000, 0xb17fb000, 4096)
08-26 11:20:47.586   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.586   333  8307 V AudioCache: memcpy(0xabf23000, 0xb17fb000, 4096)
,08-26 11:20:47.587   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.587   333  8307 V AudioCache: memcpy(0xabf24000, 0xb17fb000, 4096)
,08-26 11:20:47.587   333  8307 V AudioCache: write(0xb17fb000, 4096)
,08-26 11:20:47.587   333  8307 V AudioCache: memcpy(0xabf25000, 0xb17fb000, 4096)
08-26 11:20:47.587   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.587   333  8307 V AudioCache: memcpy(0xabf26000, 0xb17fb000, 4096)
08-26 11:20:47.587   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.587   333  8307 V AudioCache: memcpy(0xabf27000, 0xb17fb000, 4096)
08-26 11:20:47.588   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.588   333  8307 V AudioCache: memcpy(0xabf28000, 0xb17fb000, 4096)
08-26 11:20:47.588   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.588   333  8307 V AudioCache: memcpy(0xabf29000, 0xb17fb000, 4096)
08-26 11:20:47.588   333  8307 V AudioCache: write(0xb17fb000, 4096)
,08-26 11:20:47.588   333  8307 V AudioCache: memcpy(0xabf2a000, 0xb17fb000, 4096)
,08-26 11:20:47.588   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.588   333  8307 V AudioCache: memcpy(0xabf2b000, 0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: memcpy(0xabf2c000, 0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: memcpy(0xabf2d000, 0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: write(0xb17fb000, 4096)
,08-26 11:20:47.589   333  8307 V AudioCache: memcpy(0xabf2e000, 0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: memcpy(0xabf2f000, 0xb17fb000, 4096)
,08-26 11:20:47.589   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: memcpy(0xabf30000, 0xb17fb000, 4096)
08-26 11:20:47.589   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.590   333  8307 V AudioCache: memcpy(0xabf31000, 0xb17fb000, 4096)
,08-26 11:20:47.590   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.590   333  8307 V AudioCache: memcpy(0xabf32000, 0xb17fb000, 4096)
08-26 11:20:47.590   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.590   333  8307 V AudioCache: memcpy(0xabf33000, 0xb17fb000, 4096)
,08-26 11:20:47.590   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.590   333  8307 V AudioCache: memcpy(0xabf34000, 0xb17fb000, 4096)
08-26 11:20:47.590   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.591   333  8307 V AudioCache: memcpy(0xabf35000, 0xb17fb000, 4096)
08-26 11:20:47.591   333  8307 V AudioCache: write(0xb17fb000, 4096)
,08-26 11:20:47.591   333  8307 V AudioCache: memcpy(0xabf36000, 0xb17fb000, 4096)
08-26 11:20:47.591   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.591   333  8307 V AudioCache: memcpy(0xabf37000, 0xb17fb000, 4096)
08-26 11:20:47.591   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 11:20:47.591   333  8307 V AudioCache: write(0xb17fb000, 4096)
,08-26 11:20:47.591   333  8307 V AudioCache: memcpy(0xabf38000, 0xb17fb000, 4096)
08-26 11:20:47.591   333  8307 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 11:20:47.591   333  8307 V AudioCache: write(0xb17fb000, 4096)
08-26 11:20:47.591   333  8307 V AudioCache: memcpy(0xabf39000, 0xb17fb000, 4096)
08-26 11:20:47.591   333  8307 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 11:20:47.591   333  8307 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-26 11:20:47.591   333  8307 V AwesomePlayer: postAudioEOS() 
08-26 11:20:47.591   333  8307 V AudioCache: write(0xb17fb000, 280)
08-26 11:20:47.591   333  8307 V AudioCache: memcpy(0xabf3a000, 0xb17fb000, 280)
08-26 11:20:47.593  8284  8284 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 11:20:47.596   333  8304 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
,08-26 11:20:47.596   333  8304 V AwesomePlayer: onStreamDone
08-26 11:20:47.596   333  8304 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 11:20:47.596   333  8304 V AudioCache: notify(0xb100a300, 2, 0, 0)
08-26 11:20:47.596   333  8304 V AudioCache: playback complete
,08-26 11:20:47.596   333  8304 V AwesomePlayer: pause_l() 
08-26 11:20:47.596   333  8304 V AudioCache: notify(0xb100a300, 7, 0, 0)
08-26 11:20:47.596   333  8304 V AudioCache: ignored
08-26 11:20:47.596   333  8304 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:47.596   333  1382 V AudioCache: wait - success
,08-26 11:20:47.596   333  1382 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 11:20:47.601  1034  1112 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 11:20:47.601  1034  1112 I ActivityManager: Killing 6606:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-26 11:20:47.602   333  8304 D AudioPlayer: Pause Playback at 1068125
,08-26 11:20:47.602   333  1382 V AwesomePlayer: reset_l() 
08-26 11:20:47.602   333  1382 V AudioCache: notify(0xb100a300, 8, 0, 0)
08-26 11:20:47.602   333  1382 V AudioCache: ignored
08-26 11:20:47.602   333  1382 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:47.602   333  1382 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-26 11:20:47.602   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 11:20:47.602   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 11:20:47.602   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 11:20:47.602   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.,
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 0
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 0
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0,
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0740 on port 1
,08-26 11:20:47.602   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c02e0 on port 1
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0420 on port 1
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 11:20:47.603   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 11:20:47.603   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 11:20:47.603   333  8306 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 11:20:47.603   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 11:20:47.603   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 11:20:47.603   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 11:20:47.603   333  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 11:20:47.604   333  1382 D AudioPlayer: AudioPlayer releasing audio source
08-26 11:20:47.604   333  1382 D AudioPlayer: AudioPlayer done releasing audio source
08-26 11:20:47.604   333  1382 V AwesomePlayer: reset_l() 
08-26 11:20:47.604   333  1382 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:47.604   333  1382 V AwesomePlayer: ~AwesomePlayer call
08-26 11:20:47.604   333  1382 V AwesomePlayer: reset_l() 
08-26 11:20:47.604   333  1382 V AwesomePlayer: cancelPlayerEvents
08-26 11:20:47.604  8245  8245 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 11:20:47.604  8245  8293 V SoundPool: close(31)
08-26 11:20:47.604  8245  8293 V SoundPool: pointer = 0xa0021000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 11:20:47.605  8245  8245 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 11:20:47.644  1034  1544 D WifiService: Client connection lost with reason: 4
08-26 11:20:47.644  1034  2029 I WindowState: WIN DEATH: Window{2e486c14 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 11:20:47.650  1034  2029 D InputDispatcher: Window went away: Window{2e486c14 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 11:20:47.771  7842  7842 I UEI.SmartControl: Supports setup maps: true
08-26 11:20:47.773  7842  7842 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 11:20:47.773  7842  7842 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-26 11:20:47.773  7842  7842 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-26 11:20:47.773  7842  7842 I UEI.SmartControl: ### init IR Blaster...
,08-26 11:20:47.777  7842  7842 D serial_port: Configuring serial port
,08-26 11:20:47.777  7842  7842 E UEI.SmartControl: UEIBLaster setting for 616
,08-26 11:20:47.777  7842  7842 I UEI.SmartControl: Setting serial record hearder size = 2
,08-26 11:20:47.777  7842  7842 I UEI.SmartControl: configuring settings for MAXQ616
08-26 11:20:47.777  7842  7842 I UEI.SmartControl: Get version...
08-26 11:20:47.798  7842  8310 D UEI.SmartControl: serial port data available: 21
,08-26 11:20:47.830  7842  7842 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 11:20:47.830  7842  7842 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 11:20:47.830  7842  7842 I UEI.SmartControl: QS saving settings...
08-26 11:20:47.830  1034  1112 I ActivityManager:   Force finishing activity ActivityRecord{c3f18d9 u0 com.test.thalitest/.MainActivity t6}
,08-26 11:20:47.831  7842  7842 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 11:20:47.850  7842  8310 D UEI.SmartControl: serial port data available: 4
08-26 11:20:47.858   350   366 E GBMv2   : DFP En is all cleared set to be enabled
08-26 11:20:47.858  1034  2000 W ActivityManager: Spurious death for ProcessRecord{398e9be7 6606:com.test.thalitest/u0a118}, curProc for 6606: null
08-26 11:20:47.860  8245  8245 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3344
08-26 11:20:47.861  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-26 11:20:47.866  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{c3f18d9 u0 com.test.thalitest/.MainActivity t6 f}
08-26 11:20:47.867  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{c3f18d9 u0 com.test.thalitest/.MainActivity t6 f}
08-26 11:20:47.877  7842  7842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 11:20:47.879  7842  8317 I UEI.SmartControl: Device manager: loading config....
08-26 11:20:47.880  7842  8317 D UEI.SmartControl: ----------- loading internal config...
08-26 11:20:47.890  7842  8317 E UEI.SmartControl: Loading SETTINGS...
,08-26 11:20:47.897  7842  8317 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 11:20:47.904  7842  8316 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 11:20:47.905  7842  8316 D UEI.SmartControl: -----service ready thread exits
,08-26 11:20:47.913  1943  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 11:20:47.913  1943  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e3e7211 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 11:20:47.914  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-26 11:20:47.916  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 11:20:47.916  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17def76 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 11:20:47.925  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 11:20:47.925  2720  2720 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-26 11:20:47.926  2434  2618 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 11:20:47.928  7738  7738 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 11:20:47.928  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 11:20:47.934  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:47.937  1034  1467 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 11:20:47.964  1034  1111 W InputMethodInfo: Duplicated subtype definition found: , voice
08-26 11:20:47.965  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 11:20:47.967  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 11:20:47.968  7842  7842 E UEI.SmartControl: Services init done
08-26 11:20:47.968  7842  7842 D UEI.SmartControl: QS Service init finished
,08-26 11:20:48.005  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 11:20:48.006  2035  2074 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-26 11:20:48.008  1034  2000 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:48.009  4935  4935 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 11:20:48.009  4935  4935 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 11:20:48.009  4935  4935 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 11:20:48.009  4935  4935 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 11:20:48.009  4935  4935 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 11:20:48.009  4935  4935 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 11:20:48.009  4935  4935 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 11:20:48.009  4935  4935 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 11:20:48.009  4935  4935 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:48.009  4935  4935 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 11:20:48.009  4935  4935 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 11:20:48.009  4935  4935 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 11:20:48.010  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-26 11:20:48.010  2720  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-26 11:20:48.010  7842  7842 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 11:20:48.010  7842  7842 D UEI.SmartControl: QS Service version code: 201091
08-26 11:20:48.011  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 11:20:48.011  7842  7842 D UEI.SmartControl: Service requested: Control
08-26 11:20:48.029  5033  5033 I art     : Explicit concurrent mark sweep GC freed 8203(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 572us total 139.128ms
08-26 11:20:48.033  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-26 11:20:48.052  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 11:20:48.053  1603  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 11:20:48.053  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.053  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-26 11:20:48.054  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:48.065  8245  8245 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 11:20:48.066  7842  7858 I UEI.SmartControl: ------ IControl API: 11
08-26 11:20:48.066  7842  7858 D UEI.SmartControl: File observer start...
08-26 11:20:48.066  7842  7858 E UEI.SmartControl: IR Port is disabled: false
08-26 11:20:48.066  7842  7858 D UEI.SmartControl: Starting file observer...
,08-26 11:20:48.066  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 11:20:48.067  7842  7842 D UEI.SmartControl: Internal service binding...
08-26 11:20:48.067  7842  7858 I UEI.SmartControl: Registering callback...
08-26 11:20:48.067  7842  7857 I UEI.SmartControl: ------ IControl API: 19
08-26 11:20:48.068  7842  7857 I UEI.SmartControl: Registering Services Ready callback...
08-26 11:20:48.068  7842  7857 I UEI.SmartControl: Notify client services are ready...
08-26 11:20:48.069  8245  8262 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 11:20:48.071  1034  1889 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:48.071  1034  1889 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:48.074  1603  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 11:20:48.074  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.076  8245  8291 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 11:20:48.084  8245  8291 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 11:20:48.084  8245  8245 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 11:20:48.084  8245  8245 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 11:20:48.084  7842  7858 I UEI.SmartControl: ------ IControl API: 8
,08-26 11:20:48.087  8245  8245 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 11:20:48.087  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 11:20:48.087  8245  8245 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 11:20:48.087  1603  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 11:20:48.088  8245  8245 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 11:20:48.088  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 11:20:48.088  8245  8245 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 11:20:48.089  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 11:20:48.089  8245  8245 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 11:20:48.089  8245  8245 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 11:20:48.090  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 11:20:48.090  1603  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-26 11:20:48.092  1603  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 11:20:48.092  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.095  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 11:20:48.096  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:48.096  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:48.100  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 11:20:48.100  1603  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 11:20:48.102  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 11:20:48.102  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 11:20:48.106  1603  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 11:20:48.106  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.113  1870  1870 D SplitUIManager: split_name #11 / not available #0
,08-26 11:20:48.114  1870  1870 D SplitUIService: removed split : 
,08-26 11:20:48.120  1034  1034 I art     : Explicit concurrent mark sweep GC freed 82672(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.398ms total 212.055ms
08-26 11:20:48.120  1034  1049 I art     : WaitForGcToComplete blocked for 52.767ms for cause Explicit
08-26 11:20:48.121  1603  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 11:20:48.121  1603  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 11:20:48.122  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 11:20:48.122  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 11:20:48.132  1034  2000 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 11:20:48.133  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 11:20:48.136  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 11:20:48.136  1603  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 11:20:48.140  1603  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 11:20:48.140  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.149  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-26 11:20:48.149  1870  1870 I SplitUIService: split app #11
,08-26 11:20:48.180  1034  1034 D administrator: Handling package changes for user 0
,08-26 11:20:48.194  1034  1049 I art     : Explicit concurrent mark sweep GC freed 7097(510KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.387ms total 74.310ms
,08-26 11:20:48.196  1034  1122 I art     : WaitForGcToComplete blocked for 100.256ms for cause Explicit
08-26 11:20:48.197  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:48.199  8245  8245 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 11:20:48.200  1034  1968 V SIM_STK : Menu title from STK is T-Mobile
08-26 11:20:48.207  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:48.210  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:48.214  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-26 11:20:48.214  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-26 11:20:48.215  2720  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 11:20:48.215  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-26 11:20:48.216  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 11:20:48.217  2720  2737 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 11:20:48.224  1603  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 11:20:48.224  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.226  8245  8245 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-26 11:20:48.228  1603  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 11:20:48.228  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.230  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 11:20:48.230  1603  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 11:20:48.232  1603  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 11:20:48.232  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.233  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:48.233  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 11:20:48.233  1603  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 11:20:48.235  1603  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 11:20:48.235  1603  1665 D KeyguardModel: createShortcutInfo...
08-26 11:20:48.237  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 11:20:48.237  1603  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 11:20:48.238  1603  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 11:20:48.238  1603  1665 D KeyguardModel: createShortcutInfo...
,08-26 11:20:48.250  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:48.251  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-26 11:20:48.251  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , display: false
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , animation: false }
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , display: false
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , animation: false }
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , create_time: 1471602816196
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , display: false
08-26 11:20:48.255  2035  2035 I GBoardWebViewUtils: , animation: false }
,08-26 11:20:48.261  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 11:20:48.263  2035  8327 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-26 11:20:48.278  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 11:20:48.283  8184  8184 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-26 11:20:48.284  1034  1993 I ActivityManager: Killing 7255:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 11:20:48.285  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 11:20:48.285  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 11:20:48.313  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 11:20:48.313  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 11:20:48.313  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 11:20:48.366  1034  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 11:20:48.372  1034  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 11:20:48.378  1034  1122 I art     : Explicit concurrent mark sweep GC freed 7171(464KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.964ms total 180.796ms
08-26 11:20:48.397  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-26 11:20:48.399  1034  1968 W libprocessgroup: failed to open /acct/uid_10005/pid_7255/cgroup.procs: No such file or directory
08-26 11:20:48.402  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 11:20:48.403  2080  2080 I ConfigService: onCreate
08-26 11:20:48.403  2080  2080 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 11:20:48.405  1034  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 11:20:48.407  2080  2080 I ConfigService: onBind returning update interface
08-26 11:20:48.412  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 11:20:48.412  2080  2080 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 11:20:48.412  2080  2080 I ConfigService: onBind returning config service
,08-26 11:20:48.420  1818  1818 I ConfigFetchService: service connected
08-26 11:20:48.428  2080  2080 I ConfigService: onDestroy
08-26 11:20:48.434  1818  8330 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-26 11:20:48.445  8284  8284 D AndroidRuntime: Shutting down VM
08-26 11:20:48.456  5796  8336 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-26 11:20:48.462  7055  7055 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-26 11:20:48.467  1818  8337 I PeopleContactsSync: CP2 sync disabled
08-26 11:20:48.480  2352  8338 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 11:20:48.486  1818  5179 I Icing   : doRemovePackageData com.test.thalitest
08-26 11:20:48.487  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-26 11:20:48.490  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.492  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 11:20:48.493  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 11:20:48.494  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 11:20:48.496  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 11:20:48.496  1034  1703 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8339 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-26 11:20:48.504  2080  2109 I art     : Explicit concurrent mark sweep GC freed 6646(389KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 644us total 37.480ms
,08-26 11:20:48.507  1818  8335 W GmsApplication: Using Auth Proxy for data requests.
08-26 11:20:48.511  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{370ff702 u0 com.lge.launcher2/.Launcher t5} time:142605
08-26 11:20:48.512  1818  8335 W GmsApplication: Using Auth Proxy for data requests.
08-26 11:20:48.512  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 11:20:48.514  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 11:20:48.515  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.519  2035  2123 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 11:20:48.519  2035  2123 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-26 11:20:48.529  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 11:20:48.529  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 11:20:48.529  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.536  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-26 11:20:48.539  2600  2600 D [Concierge]Service: onStartCommand(). Type : 8
08-26 11:20:48.539  2600  2600 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 11:20:48.540  2600  2600 D [Concierge]Service: Update widget ID : 11
08-26 11:20:48.540  2035  2035 D [Concierge]WidgetView: change position of spinner
08-26 11:20:48.542  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1472203248542
08-26 11:20:48.542  2600  2600 D [Concierge]Service: onStartCommand(). Type : 0
08-26 11:20:48.552  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 756796077
,08-26 11:20:48.553  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 11:20:48.553  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 11:20:48.556  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@39409350
08-26 11:20:48.556  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 11:20:48.557  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 11:20:48.557  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.561  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 11:20:48.561  8339  8339 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 11:20:48.562  8339  8339 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 11:20:48.562  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 11:20:48.562  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 11:20:48.562  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472203133777, New one : 1472203248542
08-26 11:20:48.563  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-26 11:20:48.563  8339  8339 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 11:20:48.563  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 11:20:48.563  8339  8339 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 11:20:48.563  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.564  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 11:20:48.565  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 11:20:48.567  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 11:20:48.568  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 11:20:48.569  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 11:20:48.573  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.574  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.611  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-26 11:20:48.625  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 11:20:48.625  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-26 11:20:48.626  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 11:20:48.648  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1108674a time:142742
,08-26 11:20:48.648  8339  8339 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-26 11:20:48.660  8339  8339 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 11:20:48.685  1034  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8362 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 11:20:48.690  8339  8339 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 11:20:48.719  8339  8339 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 11:20:48.719  8339  8339 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 11:20:48.735  1034  1958 I ActivityManager: Killing 7767:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 11:20:48.788  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 11:20:48.808  1034  1935 W libprocessgroup: failed to open /acct/uid_10072/pid_7767/cgroup.procs: No such file or directory
,08-26 11:20:48.824  2035  2867 I GBoardtInterface: onReloaded()
,08-26 11:20:48.826  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 11:20:48.827  2720  2735 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 11:20:48.831  2720  2777 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 11:20:48.839  1906  1906 D ActionManagerService: notifyUserLog: 1000001
,08-26 11:20:48.840  2720  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 11:20:48.840  2720  4929 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-26 11:20:48.843  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-26 11:20:48.844  2720  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 11:20:48.844  2720  4929 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 11:20:48.844  2720  4929 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-26 11:20:48.844  2720  4929 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-26 11:20:48.845  2720  2777 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 11:20:48.848  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-26 11:20:48.848  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-26 11:20:48.850  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-26 11:20:48.850  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 11:20:48.852  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-26 11:20:48.853  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay

```
