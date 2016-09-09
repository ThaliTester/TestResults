#### Test 836273375fe617f_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
09-09 13:41:01.267  1034  2262 W libprocessgroup: failed to open /acct/uid_10044/pid_6144/cgroup.procs: No such file or directory
09-09 13:41:01.329  6618  6618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:01.329  6618  6618 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:41:01.329  6618  6618 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 13:41:01.330  6618  6618 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
--------- beginning of main
09-09 13:41:01.442  6618  6618 I AppConfig: Total System Memory = 2995761152
09-09 13:41:01.455  6618  6618 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 13:41:01.494  1034  2023 I ActivityManager: Killing 6182:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-09 13:41:01.552  1034  1049 W libprocessgroup: failed to open /acct/uid_10080/pid_6182/cgroup.procs: No such file or directory
09-09 13:41:01.553  2050  2050 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-09 13:41:01.554  2050  2050 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-09 13:41:01.558  2050  2050 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-09 13:41:01.588  6481  6481 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 13:41:01.598  6481  6481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:01.666  1034  1981 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6651 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:01.778   326   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-09 13:41:01.779  3272  6670 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-09 13:41:01.925  6651  6651 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-09 13:41:02.045  6651  6651 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:02.045  6651  6651 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:02.136  6651  6651 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-09 13:41:02.159  6651  6651 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-09 13:41:02.161  6651  6651 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-09 13:41:02.178  6651  6651 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-09 13:41:02.178  6651  6651 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-09 13:41:02.208  1034  1750 I ActivityManager: Killing 5536:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-09 13:41:02.282  1034  2069 W libprocessgroup: failed to open /acct/uid_10085/pid_5536/cgroup.procs: No such file or directory
09-09 13:41:02.307  2853  6057 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-09 13:41:02.309  2853  6057 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34782d86 on behalf of 6651
09-09 13:41:02.315  5073  6701 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-09 13:41:02.357  1034  1981 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:41:02.368  6691  6691 D AndroidRuntime: 
09-09 13:41:02.368  6691  6691 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:41:02.371  6691  6691 D AndroidRuntime: CheckJNI is OFF
09-09 13:41:02.383  1034  2102 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6702 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:02.402  6651  6651 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-09 13:41:02.450  6651  6651 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-09 13:41:02.501  6691  6691 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:41:02.504  1034  1750 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:41:02.509  1841  1841 I art     : Explicit concurrent mark sweep GC freed 34371(2MB) AllocSpace objects, 13(231KB) LOS objects, 51% free, 29MB/61MB, paused 1.397ms total 40.778ms
09-09 13:41:02.519  1965  1990 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-09 13:41:02.522  1034  1750 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-09 13:41:02.523  1034  1750 D ActivityManager: setTaskToReturnTo : TaskRecord{3e1ddf91 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:41:02.523  1034  1750 D ActivityManager: setTaskToReturnTo : TaskRecord{3e1ddf91 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:41:02.524  1034  1750 D WindowStateEx: AppWindowTokenEx init.. 
09-09 13:41:02.524   333   344 E GBMv2   : DFP En is all cleared set to be enabled
09-09 13:41:02.564  1034  1750 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6740 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:41:02.566  6691  6691 D AndroidRuntime: Shutting down VM
09-09 13:41:02.575  6702  6702 D DocsApplication: Installing DEX configuration.
09-09 13:41:02.578   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 269us total 12.439ms
09-09 13:41:02.587  5073  6701 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 271 ms] updated apps [took 271 ms] 
09-09 13:41:02.592   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 271us total 13.059ms
09-09 13:41:02.595  6702  6702 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-09 13:41:02.599  6702  6702 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1853c11 com.google.android.apps.docs}
09-09 13:41:02.605   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 257us total 12.188ms
09-09 13:41:02.613  6702  6702 D TAG     : onCreate()
09-09 13:41:02.628  6702  6702 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-09 13:41:02.629  1965  1990 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-09 13:41:02.629  1965  1990 D SplitWindowPolicy: topRunningActivity=ActivityInfo{19a5d15d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 13:41:02.630  1965  1988 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-09 13:41:02.631  1965  1988 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c52aad2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,09-09 13:41:02.689  6740  6740 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 13:41:02.797  6740  6740 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 13:41:02.806  6740  6740 I LibraryLoader: Loading: webviewchromium
,09-09 13:41:02.809  6740  6740 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4289-4293)
09-09 13:41:02.809  6740  6740 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:41:02.826  6740  6740 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25bc5013}
,09-09 13:41:02.827  6740  6740 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:02.827  6740  6740 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:02.836  6740  6740 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 13:41:02.837  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:02.855   309   309 V AudioPolicyService: registerClient() client 0xb0410340, uid 10118
,09-09 13:41:02.859  1034  1116 D BluetoothManagerService: Message: 20
09-09 13:41:02.859  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38c3c3d0:true
09-09 13:41:02.860  6740  6740 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 13:41:02.861  6740  6740 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-09 13:41:02.862  6740  6740 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-09 13:41:02.875  6740  6740 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:02.875  6740  6740 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:02.875  6740  6740 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:41:02.875  6740  6740 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:41:02.875  6740  6740 I Adreno-EGL: Remote Branch: 
09-09 13:41:02.875  6740  6740 I Adreno-EGL: Local Patches: 
09-09 13:41:02.875  6740  6740 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:02.975  6740  6774 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-09 13:41:02.983  6740  6740 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-09 13:41:03.003  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:03.009  6740  6740 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 13:41:03.012  6740  6740 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,09-09 13:41:03.015  6740  6740 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 13:41:03.015  6740  6740 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-09 13:41:03.031  6740  6740 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-09 13:41:03.038  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:41:03.038  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:03.071  6740  6789 D OpenGLRenderer: Render dirty regions requested: true
09-09 13:41:03.071  6740  6789 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 13:41:03.077  6740  6789 D OpenGLRenderer: Enabling debug mode 0
09-09 13:41:03.085  6740  6740 D Atlas   : Validating map...
09-09 13:41:03.096  1034  1981 D SplitWindow: check instance of lgWin Window{1730d58a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:41:03.140  6740  6787 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:03.140  6740  6787 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:03.219  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +591ms (total +694ms)
09-09 13:41:03.219  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7fc8ef6 u0 com.test.thalitest/.MainActivity t6} time:104704
09-09 13:41:03.223  6740  6740 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2f3111fe time:104708
09-09 13:41:03.294  6740  6740 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:41:03.331  6740  6740 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-09 13:41:03.331  6740  6740 I chromium: 
,09-09 13:41:03.369  6740  6787 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-09 13:41:03.369  6740  6787 I chromium: 
,09-09 13:41:03.508  6740  6804 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,09-09 13:41:03.519  6740  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:41:03.519  6740  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:41:03.519  6740  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:41:03.519  6740  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:41:03.519  6740  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:41:03.519  6740  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b0ad662 added. We now have 1 listener(s)
09-09 13:41:03.524  1034  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:03.536  6740  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-09 13:41:03.541  6740  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-09 13:41:03.543  6740  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:03.543  6740  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 13:41:03.549  6740  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f7b329 added. We now have 1 listener(s)
09-09 13:41:03.549  6740  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:03.557  1034  1542 D WifiService: New client listening to asynchronous messages
,09-09 13:41:03.561  6740  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:03.561  6740  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 13:41:03.563  6740  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 13:41:03.563  6740  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:41:03.563  6740  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:41:03.568  6740  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:03.569  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:03.570  6740  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-09 13:41:03.579  6740  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:03.581  6740  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:03.581  6740  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:41:03.582  6740  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:03.582  6740  6804 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:41:03.585  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:03.587  1841  5259 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-09 13:41:03.587  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:03.627  6740  6740 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:41:03.650  1841  5259 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,09-09 13:41:03.714  1841  5259 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-09 13:41:04.017  6702  6702 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:04.017  6702  6702 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:04.227  1034  2038 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6824 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
09-09 13:41:04.228  1034  2038 I ActivityManager: Killing 6213:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-09 13:41:04.232   333   346 E GBMv2   : DFP En is all cleared set to be enabled
09-09 13:41:04.232   333   346 E GBMv2   : Set value is all cleared set the max
09-09 13:41:04.232   333   346 I GBMv2   : DFP Enabled. Ignore VFP set
09-09 13:41:04.293  1034  1049 W libprocessgroup: failed to open /acct/uid_10097/pid_6213/cgroup.procs: No such file or directory
,09-09 13:41:04.300  6702  6702 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-09 13:41:04.332  6824  6824 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 13:41:04.340  6824  6824 I LockScreenSettings: New app installed broadcast received ..
09-09 13:41:04.344  6824  6824 I LockScreenSettings: Number of installed packages  1
,09-09 13:41:04.394  1034  1984 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6845 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:04.443  6845  6845 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:04.536  6740  6808 W jxcore-log: Initializing JXcore engine
09-09 13:41:04.536  6740  6808 W jxcore-log: JXcore engine is ready
,09-09 13:41:04.561  6808  6808 W Thread-791: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8763]" dev="sockfs" ino=8763 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 13:41:04.561  6808  6808 W Thread-791: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-09 13:41:04.561  6808  6808 W Thread-791: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9636]" dev="sockfs" ino=9636 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 13:41:04.561  6808  6808 W Thread-791: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-09 13:41:04.561  6808  6808 W Thread-791: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30508]" dev="sockfs" ino=30508 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-09 13:41:04.584  6740  6808 W jxcore-log: Starting JXcore engine
09-09 13:41:04.660  6740  6808 W jxcore-log: Platform android
09-09 13:41:04.660  6740  6808 W jxcore-log: 
09-09 13:41:04.660  6740  6808 W jxcore-log: Process ARCH arm
09-09 13:41:04.660  6740  6808 W jxcore-log: 
,09-09 13:41:04.674  1034  1762 I art     : Explicit concurrent mark sweep GC freed 28298(1386KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.890ms total 134.732ms
09-09 13:41:04.880  1034  2023 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:41:04.920  1034  1750 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6878 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:41:04.970  6878  6878 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-09 13:41:04.970  6878  6878 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-09 13:41:04.975  5665  5665 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
09-09 13:41:04.979  6740  6808 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:41:04.979  6740  6808 I jxcore-log: 
09-09 13:41:04.979  6740  6808 W jxcore-log: JXcore engine is started
09-09 13:41:04.982  6740  6804 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 13:41:04.984  6740  6740 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:41:04.988  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 13:41:05.010  1034  1762 I ActivityManager: Killing 6242:com.google.android.gm/u0a64 (adj 15): empty #17
,09-09 13:41:05.140  1034  1049 W libprocessgroup: failed to open /acct/uid_10064/pid_6242/cgroup.procs: No such file or directory
,09-09 13:41:08.125  6702  6702 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-09 13:41:08.133  1034  2023 I ActivityManager: Killing 6040:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 13:41:08.227  1034  2102 W libprocessgroup: failed to open /acct/uid_10072/pid_6040/cgroup.procs: No such file or directory
,09-09 13:41:09.106  6702  6818 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:41:09.864  1034  1984 I ActivityManager: Killing 5805:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-09 13:41:09.885  5775  5775 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 13:41:09.885  5775  5775 W System.err: android.os.DeadObjectException
09-09 13:41:09.886  5775  5775 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:41:09.886  5775  5775 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:41:09.886  5775  5775 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 13:41:09.886  5775  5775 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 13:41:09.886  5775  5775 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 13:41:09.886  5775  5775 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 13:41:09.886  5775  5775 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:09.886  5775  5775 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:09.886  5775  5775 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:09.886  5775  5775 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:41:09.886  5775  5775 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:09.886  5775  5775 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:09.886  5775  5775 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:41:09.886  5775  5775 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:41:09.886  5775  5775 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 13:41:09.887  5775  5775 W System.err: android.os.DeadObjectException
09-09 13:41:09.887  5775  5775 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:41:09.887  5775  5775 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:41:09.887  5775  5775 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 13:41:09.887  5775  5775 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 13:41:09.887  5775  5775 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 13:41:09.887  5775  5775 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 13:41:09.887  5775  5775 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:09.887  5775  5775 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:09.887  5775  5775 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:09.887  5775  5775 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:41:09.887  5775  5775 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:09.887  5775  5775 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:09.887  5775  5775 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:41:09.887  5775  5775 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:41:09.887  5775  5775 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 13:41:09.888  5775  5775 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-09 13:41:10.011  2802  2802 I MusicWidget: mDelayedStopHandler : unbind
,09-09 13:41:10.118  1034  1762 W libprocessgroup: failed to open /acct/uid_1000/pid_5805/cgroup.procs: No such file or directory
09-09 13:41:10.119  1034  1762 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-09 13:41:10.133  5775  5775 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 13:41:10.134  5775  5775 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-09 13:41:10.141  2175  2175 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-09 13:41:10.141  2175  2175 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-09 13:41:10.141  2175  2175 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-09 13:41:10.146  2175  2175 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-09 13:41:10.147  2175  2175 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-09 13:41:10.147  2175  2175 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,09-09 13:41:10.187  1034  2023 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6908 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:41:10.194  2175  2175 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-09 13:41:10.194  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-09 13:41:10.200  1034  2013 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@ae5e9b9com.lge.music.MediaPlaybackService$5@2f3111fe
,09-09 13:41:10.201  5775  5775 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-09 13:41:10.202  2175  2175 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-09 13:41:10.202  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.203  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.203  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.204  2175  2175 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@e11da6f
09-09 13:41:10.204  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.205  2175  2175 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-09 13:41:10.205  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.237  2175  2175 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-09 13:41:10.237  2175  2175 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-09 13:41:10.237  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-09 13:41:10.245  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.246  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.247  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.247  2175  2175 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:41:10.252  2175  2175 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,09-09 13:41:10.255  2175  2175 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
,09-09 13:41:10.255  2175  2175 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-09 13:41:10.255  2175  2175 V MediaPlayer[Native]: reset
,09-09 13:41:10.263  2175  2175 V MediaPlayer[Native]: setListener
09-09 13:41:10.263  2175  2175 V MediaPlayer[Native]: disconnect
09-09 13:41:10.263  2175  2175 V MediaPlayer[Native]: destructor
09-09 13:41:10.263  1841  6512 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-09 13:41:10.264   309   309 V AudioFlinger: releasing 18 from 2175 for -1
09-09 13:41:10.265   309   309 V AudioFlinger:  decremented refcount to 0
09-09 13:41:10.265   309   309 V AudioFlinger: purging stale effects
09-09 13:41:10.265  2175  2175 V MediaPlayer[Native]: disconnect
,09-09 13:41:10.268  2175  2175 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-09 13:41:10.269   305  6934 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:10.269   305  6934 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-09 13:41:10.269   305  6934 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-09 13:41:10.272  2175  2175 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-09 13:41:10.273  2175  2175 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-09 13:41:10.274  2175  2175 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-09 13:41:10.274  2175  2175 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-09 13:41:10.274  2175  2175 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-09 13:41:10.274  2175  2175 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 869547359
09-09 13:41:10.275  2175  2175 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 869547359
09-09 13:41:10.278  6908  6908 D UEI.SmartControl: Quickset Services start...
09-09 13:41:10.280  6908  6908 I UEI.SmartControl: Manufacture = LGE
09-09 13:41:10.281  6908  6908 D UEI.SmartControl: Id = LGNevo
,09-09 13:41:10.283  6908  6908 D UEI.SmartControl: File observer start...
09-09 13:41:10.283  6908  6908 E UEI.SmartControl: IR Port is disabled: false
09-09 13:41:10.284  6908  6908 D UEI.SmartControl: Starting file observer...
09-09 13:41:10.284  6908  6908 D UEI.SmartControl: Extracting JNI libs...
09-09 13:41:10.284  6908  6908 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:41:10.288  2175  2175 I SmartShareClient: [SmartShareManagerClient] terminate service: 2175/MediaPlaybackService/1064339533
09-09 13:41:10.292  2175  2175 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-09 13:41:10.292  2175  2175 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@128b43ac
09-09 13:41:10.294  2175  2175 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-09 13:41:10.295  2175  2175 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,09-09 13:41:10.296  2175  2175 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-09 13:41:10.296  2175  2175 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-09 13:41:10.306  2175  2175 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
09-09 13:41:10.307  1034  2102 I ActivityManager: Killing 5775:com.lge.qremote/u0a112 (adj 15): empty #17
09-09 13:41:10.358  6908  6908 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-09 13:41:10.358  6908  6908 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:41:10.359  6908  6908 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-09 13:41:10.385  6908  6908 I UEI.SmartControl: --- Selecting new region: 6
,09-09 13:41:10.386  6908  6908 I UEI.SmartControl: Model = LG-D855
09-09 13:41:10.387  6908  6908 D UEI.SmartControl: QS Service created
09-09 13:41:10.397  1034  2013 W libprocessgroup: failed to open /acct/uid_10112/pid_5775/cgroup.procs: No such file or directory
,09-09 13:41:10.410  6908  6908 I UEI.SmartControl: Service initServices...
09-09 13:41:10.413  6908  6908 D UEI.SmartControl: QS start get config
,09-09 13:41:10.448  6908  6908 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:41:10.491  1841  1841 I ConfigFetchService: fetch service done; releasing wakelock
,09-09 13:41:10.494  1841  1841 I ConfigFetchService: stopping self
09-09 13:41:10.498  2263  2263 I ConfigService: onDestroy
09-09 13:41:10.685  6908  6908 I UEI.SmartControl: Supports setup maps: true
,09-09 13:41:10.688  6908  6908 D UEI.SmartControl: QS start statue = true Error code = 0
,09-09 13:41:10.688  6908  6908 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 13:41:10.688  6908  6908 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 13:41:10.688  6908  6908 I UEI.SmartControl: ### init IR Blaster...
09-09 13:41:10.700  6908  6908 D serial_port: Configuring serial port
,09-09 13:41:10.717  6908  6908 E UEI.SmartControl: UEIBLaster setting for 616
09-09 13:41:10.717  6908  6908 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 13:41:10.718  6908  6908 I UEI.SmartControl: configuring settings for MAXQ616
09-09 13:41:10.718  6908  6908 I UEI.SmartControl: Get version...
,09-09 13:41:10.734  6908  6942 D UEI.SmartControl: serial port data available: 21
,09-09 13:41:10.760  6908  6908 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 13:41:10.761  6908  6908 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 13:41:10.761  6908  6908 I UEI.SmartControl: QS saving settings...
09-09 13:41:10.761  6908  6908 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 13:41:10.780  6908  6942 D UEI.SmartControl: serial port data available: 4
,09-09 13:41:10.785  1034  1406 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1001977535, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
09-09 13:41:10.819  6908  6908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 13:41:10.828  4971  6944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
09-09 13:41:10.834  6908  6908 E UEI.SmartControl: Services init done
09-09 13:41:10.836  6908  6908 D UEI.SmartControl: QS Service init finished
,09-09 13:41:10.841  2678  2678 D [Concierge]Service: onStartCommand(). Type : 9
09-09 13:41:10.853  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1001977535 [*alarm*], flags=0x0
,09-09 13:41:10.859  6908  6908 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 13:41:10.859  6908  6908 D UEI.SmartControl: QS Service version code: 201091
09-09 13:41:10.860  6908  6908 D UEI.SmartControl: Service requested: Control
09-09 13:41:10.866  6908  6948 I UEI.SmartControl: Device manager: loading config....
09-09 13:41:10.867  6908  6948 D UEI.SmartControl: ----------- loading internal config...
,09-09 13:41:10.889  6908  6948 E UEI.SmartControl: Loading SETTINGS...
,09-09 13:41:10.897  6908  6908 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 13:41:10.899  6908  6948 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 13:41:10.905  6908  6908 D UEI.SmartControl: Service.onUnbind: IControl
09-09 13:41:10.905  6908  6908 D UEI.SmartControl: Service.onDestroy
09-09 13:41:10.905  6908  6908 D UEI.SmartControl: Lock is in USE false
09-09 13:41:10.905  6908  6908 D UEI.SmartControl: unbind internal service
09-09 13:41:10.906  6908  6908 D serial_port: close(fd = 25)
09-09 13:41:10.909  6908  6908 I UEI.SmartControl: Serial port is closed.
,09-09 13:41:10.910  6908  6908 I UEI.SmartControl: Serial port is closed.
09-09 13:41:10.911  6908  6908 D UEI.SmartControl: Blaster closed
09-09 13:41:10.911  6908  6908 D UEI.SmartControl: Shut down QS...
09-09 13:41:10.911  6908  6908 D UEI.SmartControl: Stopping QS lib
09-09 13:41:10.911  6908  6908 D UEI.SmartControl: QS lib stop result = true
09-09 13:41:10.911  6908  6908 D UEI.SmartControl: Stopped QS lib
09-09 13:41:10.911  6908  6908 D UEI.SmartControl: Stopped file observer...
09-09 13:41:10.911  6908  6908 D UEI.SmartControl: QS shutdown complete
09-09 13:41:10.912  6908  6908 D UEI.SmartControl: QS Service created
09-09 13:41:10.921  6908  6946 I UEI.SmartControl: Notify AllClients services are ready: 11
09-09 13:41:10.921  6908  6946 D UEI.SmartControl: -----service ready thread exits
,09-09 13:41:10.927  6908  6908 I UEI.SmartControl: Service initServices...
09-09 13:41:10.927  6908  6908 D UEI.SmartControl: QS start get config
09-09 13:41:11.204  6908  6908 I UEI.SmartControl: Supports setup maps: true
,09-09 13:41:11.207  6908  6908 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:41:11.207  6908  6908 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-09 13:41:11.207  6908  6908 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 13:41:11.207  6908  6908 I UEI.SmartControl: ### init IR Blaster...
09-09 13:41:11.210  6908  6908 D serial_port: Configuring serial port
09-09 13:41:11.211  6908  6908 E UEI.SmartControl: UEIBLaster setting for 616
09-09 13:41:11.211  6908  6908 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 13:41:11.211  6908  6908 I UEI.SmartControl: configuring settings for MAXQ616
09-09 13:41:11.211  6908  6908 I UEI.SmartControl: Get version...
09-09 13:41:11.229  6908  6962 D UEI.SmartControl: serial port data available: 21
,09-09 13:41:11.263  6908  6908 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 13:41:11.263  6908  6908 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 13:41:11.263  6908  6908 I UEI.SmartControl: QS saving settings...
09-09 13:41:11.264  6908  6908 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 13:41:11.278  6908  6962 D UEI.SmartControl: serial port data available: 4
,09-09 13:41:11.309  6908  6968 I UEI.SmartControl: Device manager: loading config....
09-09 13:41:11.311  6908  6908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 13:41:11.314  6908  6968 D UEI.SmartControl: ----------- loading internal config...
,09-09 13:41:11.314  6908  6908 E UEI.SmartControl: Services init done
09-09 13:41:11.314  6908  6908 D UEI.SmartControl: QS Service init finished
09-09 13:41:11.316  6908  6908 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 13:41:11.316  6908  6908 D UEI.SmartControl: QS Service version code: 201091
09-09 13:41:11.317  6908  6908 D UEI.SmartControl: Service requested: Control
09-09 13:41:11.324  6908  6968 E UEI.SmartControl: Loading SETTINGS...
,09-09 13:41:11.329  6908  6908 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 13:41:11.334  1034  1981 I ActivityManager: Killing 5711:com.android.calendar/u0a13 (adj 15): empty #17
09-09 13:41:11.346  6908  6968 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-09 13:41:11.372  6908  6967 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:41:11.372  6908  6967 D UEI.SmartControl: -----service ready thread exits
,09-09 13:41:11.427  1034  2013 W libprocessgroup: failed to open /acct/uid_10013/pid_5711/cgroup.procs: No such file or directory
,09-09 13:41:11.432  6908  6908 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@e11da6f that was originally bound here
09-09 13:41:11.432  6908  6908 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@e11da6f that was originally bound here
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:41:11.432  6908  6908 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-09 13:41:11.434  6908  6908 D UEI.SmartControl: Internal service binding...
09-09 13:41:11.906  6908  6960 D UEI.SmartControl: Internal timer expired: 2
,09-09 13:41:14.532  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:41:14.532  6740  6808 I jxcore-log: 
09-09 13:41:14.534  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:41:14.534  6740  6808 I jxcore-log: 
,09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:14.544  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:14.550  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:14.557  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:41:14.557  6740  6808 I jxcore-log: 
09-09 13:41:14.559  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:41:14.559  6740  6808 I jxcore-log: 
09-09 13:41:15.335  1034  1090 I ActivityManager: Waited long enough for: ServiceRecord{a0123c3 u0 com.google.android.gms/.wearable.service.WearableService}
,09-09 13:41:15.406  6908  6919 E UEI.SmartControl: file observer is disposed!
,09-09 13:41:15.595  6740  6808 I jxcore-log: Unit Test app is loaded
09-09 13:41:15.595  6740  6808 I jxcore-log: 
,09-09 13:41:15.604  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:15.604  6740  6808 I jxcore-log: 
09-09 13:41:15.612  6740  6808 D executeNativeTests: Running unit tests
09-09 13:41:15.613  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:15.613  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19feb413 added. We now have 2 listener(s)
09-09 13:41:15.613  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:41:15.618  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-09 13:41:15.619  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:15.619  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:15.619  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:15.619  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@602a650 added. We now have 2 listener(s)
09-09 13:41:15.619  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:15.619  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:15.625  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:15.632  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:15.636  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:15.636  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:15.638  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:15.640  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:15.640  6740  6740 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 13:41:16.310  6908  6969 D UEI.SmartControl: Internal timer expired: 3
,09-09 13:41:16.310  6908  6969 D UEI.SmartControl: unbind internal service
,09-09 13:41:16.329  6908  6908 D UEI.SmartControl: Service.onUnbind: IControl
,09-09 13:41:16.331  6908  6908 D UEI.SmartControl: Service.onDestroy
09-09 13:41:16.331  6908  6908 D UEI.SmartControl: Lock is in USE false
09-09 13:41:16.331  6908  6908 D UEI.SmartControl: unbind internal service
09-09 13:41:16.332  6908  6908 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3cd3a426
09-09 13:41:16.332  6908  6908 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-09 13:41:16.332  6908  6908 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-09 13:41:16.332  6908  6908 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-09 13:41:16.332  6908  6908 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-09 13:41:16.332  6908  6908 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-09 13:41:16.332  6908  6908 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-09 13:41:16.332  6908  6908 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-09 13:41:16.332  6908  6908 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-09 13:41:16.333  6908  6908 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:16.333  6908  6908 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:16.333  6908  6908 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:41:16.333  6908  6908 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:16.333  6908  6908 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:16.333  6908  6908 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:41:16.333  6908  6908 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:41:16.333  6908  6908 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3cd3a426
09-09 13:41:16.335  6908  6908 D serial_port: close(fd = 24)
09-09 13:41:16.342  6908  6908 I UEI.SmartControl: Serial port is closed.
09-09 13:41:16.342  6908  6908 I UEI.SmartControl: Serial port is closed.
09-09 13:41:16.342  6908  6908 D UEI.SmartControl: Blaster closed
09-09 13:41:16.342  6908  6908 D UEI.SmartControl: Shut down QS...
09-09 13:41:16.343  6908  6908 D UEI.SmartControl: Stopping QS lib
09-09 13:41:16.343  6908  6908 D UEI.SmartControl: QS lib stop result = true
09-09 13:41:16.343  6908  6908 D UEI.SmartControl: Stopped QS lib
09-09 13:41:16.343  6908  6908 D UEI.SmartControl: QS shutdown complete
,09-09 13:41:20.317  2175  2175 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,09-09 13:41:25.793  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:25.793  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe added. We now have 3 listener(s)
,09-09 13:41:25.798  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:25.802  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:25.802  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:25.802  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:25.802  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:25.802  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f added. We now have 3 listener(s)
09-09 13:41:25.802  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:25.803  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:25.807  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.812  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:25.814  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.814  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:25.816  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.817  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.824  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:41:25.830  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.830  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.830  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.834  6740  6808 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:41:25.835  6740  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:41:25.835  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:25.835  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.835  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.835  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.836  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:25.838  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.839  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.839  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:25.840  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe removed from the list
09-09 13:41:25.840  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.842  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f removed from the list
09-09 13:41:25.842  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.842  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.847  6740  6808 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 13:41:25.847  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.847  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.847  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.847  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.847  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.847  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.847  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.847  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.847  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no, peer name> 18:810:810:810:810:810]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:25.854  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010],
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:25.855  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:25.865  1034  1406 V AlarmManager: RTC_WAKEUP set : Alarm{3d49c090 type 0 when 1473421277184 com.android.vending} when 1473421277184
,09-09 13:41:25.871  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:25.871  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:25.871  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:25.871  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:25.871  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:25.872  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:25.872  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:25.872  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.872  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.872  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.872  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.872  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.872  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.872  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.872  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.872  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.873  6740  6808 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:41:25.878  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.888  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:25.890  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.890  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:25.894  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.896  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.897  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:25.898  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:25.898  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:25.898  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:25.898  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:25.909  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:25.911  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:25.918  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:25.926  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:25.931  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 13:41:25.931  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:25.935  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.937  6740  6808 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:25.938  6740  6808 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:25.942  6740  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:41:25.942  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:25.943  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:41:25.952  6740  6808 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:41:25.952  6740  6808 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:41:25.952  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:25.953  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:25.953  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:25.953  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:25.953  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:25.965  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:25.968  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.969  6740  6808 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:25.969  6740  6808 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:25.970  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.970  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.970  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.970  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.970  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.970  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.970  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.970  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.972  6740  6808 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:41:25.973  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.977  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:25.978  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.978  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:25.980  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.981  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.982  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:25.982  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:25.982  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:25.982  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:25.982  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:25.989  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:25.989  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.991  6740  6808 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:25.991  6740  6808 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:25.991  6740  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:41:25.991  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:25.991  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:41:25.993  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.993  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.993  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.994  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.994  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.994  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.994  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.994  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.995  6740  6808 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 13:41:25.996  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.996  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.996  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.996  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.996  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.996  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.996  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.996  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.996  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.997  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:25.997  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.997  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.997  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.997  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.997  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.997  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.997  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.997  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.997  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.998  6740  6808 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:41:25.998  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.998  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.998  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.998  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.998  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.998  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.998  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.998  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.998  6740  6808 D org.thali,project.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.999  6740  6808 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:41:25.999  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.999  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.999  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.999  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:25.999  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.999  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:25.999  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.999  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.999  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.999  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:25.999  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.999  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.999  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:25.999  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.999  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.999  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:26.000  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:26.000  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:26.000  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.000  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.000  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.000  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.000  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.000  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.000  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.000  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: r,elease: The given listener does not exist in the list - probably already removed
09-09 13:41:26.000  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.001  6740  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.001  6740  6808 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.001  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:26.005  6740  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.005  6740  6808 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:41:26.005  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:26.005  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:41:26.005  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:26.006  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:26.006  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:26.008  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:26.008  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:26.008  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:26.008  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:26.008  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:26.008  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:26.008  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:26.009  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:26.010  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:26.010  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:26.011  6740  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:41:26.013  6740  6808 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:26.013  6740  6808 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:41:26.013  6740  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.013  6740  6808 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:26.013  6740  6808 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:41:26.014  6740  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.014  6740  6808 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:26.014  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:26.016  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:41:26.017  1034  1762 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:41:26.017  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:41:26.017  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:41:26.018  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:41:26.018  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:41:26.018  6740  6808 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:41:26.018  6740  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.018  6740  6808 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:41:26.019  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.019  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.019  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.019  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:41:26.019  6740  7013 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 888)
09-09 13:41:26.020  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.020  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.020  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.020  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.020  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.020  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.021  6740  6808 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:41:26.021  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.021  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.021  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.021  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.021  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.021  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.021  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.021  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.021  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.022  6740  7014 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 888
09-09 13:41:26.022  6740  6808 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:41:26.022  6740  7014 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 888)
09-09 13:41:26.022  6740  7014 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 888)
09-09 13:41:26.023  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.023  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.023  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.023  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.023  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.023  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.023  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.023  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.023  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.024  6740  6808 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:41:26.024  6740  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:41:26.024  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:26.024  6740  6808 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:41:26.024  6740  6808 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.024  6740  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:41:26.024  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:26.025  6740  6808 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:41:26.025  6740  6808 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.025  6740  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.025  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:26.025  6740  6808 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:41:26.025  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.025  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.025  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.025  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.025  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.025  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.025  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.025  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.025  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.026  6740  6808 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 13:41:26.027  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:26.032  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:26.033  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.033  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:26.034  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:26.034  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:26.034  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:26.034  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.034  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:26.036  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.046  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:26.047  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:26.047  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.048  6740  6808 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:26.048  6740  6808 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:26.048  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.048  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.048  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:26.048  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.048  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.048  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.048  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.048  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.050  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.050  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.050  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.050  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.050  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.050  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.050  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.050  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.050  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.052  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:26.052  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.052  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:26.053  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:26.053  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:26.054  6740  6740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:26.054  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:26.054  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:26.055  1034  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:26.055  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.055  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:26.055  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:26.055  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:26.055  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.055  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:26.055  6740  6740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:26.056  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.056  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.056  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:26.056  6740  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:26.056  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:26.057  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:26.066  6740  6808 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:26.067  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:26.067  6740  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:26.067  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.067  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.067  6740  7017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:26.068  6740  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:26.068  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.068  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.068  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.068  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:26.069  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.069  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:26.069  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:26.070  6740  6808 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:41:26.070  6740  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:41:26.070  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:26.071  4347  4499 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-09 13:41:26.071  6740  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:26.071  6740  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:26.072  6740  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:26.072  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:26.072  6740  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:26.072  6740  6740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:26.072  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.072  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.072  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.072  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.072  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.072  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.072  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.072  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.072  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.074  1034  2023 D Bluetooth,ManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:26.075  1034  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:26.076  1034  2069 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:26.077  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.077  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.077  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.077  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
09-09 13:41:26.077  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.077  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.077  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.077  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.077  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.078  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.078  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.078  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.078  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b26c5fe not in the list
,09-09 13:41:26.078  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.078  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2049e15f not in the list
09-09 13:41:26.078  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.078  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.078  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.079  6740  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:41:26.079  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:26.079  6740  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-09 13:41:26.079  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:26.079  6740  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:41:26.079  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:26.080  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:26.081  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 13:41:26.081  6740  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:41:26.081  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 13:41:26.081  6740  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:41:26.081  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:41:26.081  6740  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:41:26.081  6740  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:41:26.082  6740  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:41:26.082  6740  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:41:26.082  6740  6808 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:41:26.082  6740  6808 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 13:41:26.083  6740  6808 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:41:26.083  6740  6808 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:41:26.084  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:26.085  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2088f52d added. We now have 3 listener(s)
09-09 13:41:26.085  1034  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:41:26.086  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:26.086  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:26.086  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:26.087  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:26.087  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22d24a62 added. We now have 3 listener(s)
09-09 13:41:26.087  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:26.087  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:26.090  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:26.094  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:26.096  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.096  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:26.098  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.098  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.098  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:26.098  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:26.098  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2088f52d removed from the list
09-09 13:41:26.098  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.098  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22d24a62 removed from the list
09-09 13:41:26.099  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.099  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.099  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.100  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:26.100  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32df8cb0 added. We now have 3 listener(s)
09-09 13:41:26.100  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:26.101  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.102  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:26.102  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:26.102  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:26.103  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:26.103  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62cb729 added. We now have 3 listener(s)
09-09 13:41:26.103  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:26.103  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:26.105  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor:     ,- is connected/connecting to active network: true
09-09 13:41:26.107  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:26.108  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.108  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:26.109  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.109  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.109  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:26.109  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:26.109  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32df8cb0 removed from the list
09-09 13:41:26.109  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.109  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62cb729 removed from the list
09-09 13:41:26.109  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.110  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.110  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.110  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:26.110  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c53e04f added. We now have 3 listener(s)
09-09 13:41:26.111  1034  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:26.111  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.113  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:26.113  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:26.113  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:26.113  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:26.114  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a28c3dc added. We now have 3 listener(s)
09-09 13:41:26.114  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:26.114  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:26.115  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.118  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:26.118  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.118  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:26.118  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:26.118  6,740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.118  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.118  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:26.118  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:26.119  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.119  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:26.121  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.122  1034  2013 D WifiServiceImplEx: setWifiEnabled: false pid=6740, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:41:26.122  1034  2013 D WifiService: setWifiEnabled: false pid=6740, uid=10118
09-09 13:41:26.122  1034  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 13:41:26.123  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.127  6740  7013 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-09 13:41:26.127  6740  7013 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 888)
09-09 13:41:26.130  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:26.130  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:26.130  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:26.130  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:26.130  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:26.131  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:26.131  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:26.131  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:26.132  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:41:26.132  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:26.132  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:41:26.132  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-09 13:41:26.132  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:41:26.137  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:41:26.137  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:41:26.137  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.137  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.137  2654  2654 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:41:26.137  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:41:26.137  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:41:26.137  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:41:26.138  1034  2824 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.143   305   891 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:26.176  1034  1762 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-09 13:41:26.176  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.176  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.176  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-09 13:41:26.176  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.176  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:26.178   305  7023 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 13:41:26.178  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-09 13:41:26.179  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:26.179  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:26.179  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:26.180  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:41:26.180  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:41:26.180  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-09 13:41:26.182  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:41:26.183  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:26.183  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:26.184  1034  1535 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.184  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.184  1034  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@6ff46e9
09-09 13:41:26.185  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:26.185  1965  1965 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 13:41:26.186  1034  1114 D DSQN    : Dns fail occured do internet check.
09-09 13:41:26.187  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:26.187  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
,09-09 13:41:26.187  1034  1034 D DSQN    : try Internet connection check
09-09 13:41:26.192  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.192  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.192  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:26.192  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:26.193  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.193  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.193  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:26.193  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:41:26.193  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:26.194  1034  1555 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.195  1034  1554 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.196  1034  1535 D LGWifiP2pService: P2pDisablingState
09-09 13:41:26.197  1034  1535 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.197  1034  1535 D LGWifiP2pService: p2p socket connection lost
09-09 13:41:26.197  1034  1535 D LGWifiP2pService: P2pDisabledState
09-09 13:41:26.197  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 13:41:26.197  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:41:26.198  2654  2654 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:41:26.198  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:41:26.198  1965  1965 D WfdsService: WifiP2pState is changed : false
09-09 13:41:26.198  1965  2351 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:41:26.198  1965  2351 D WfdsService: Set the WFDS Monitor: false
09-09 13:41:26.200  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.200  1034  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.200  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:41:26.200  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
,09-09 13:41:26.200  1965  2351 D WfdsMonitor: WFDS Monitor is stopped
,09-09 13:41:26.200  1965  2351 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:41:26.200  1965  2726 D CtrlSupplicant: Received on exit socket, terminate
09-09 13:41:26.201  1965  2726 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:41:26.201  1965  2726 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:41:26.201  1965  2726 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 13:41:26.201  1965  2351 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 13:41:26.201  1965  2352 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:41:26.203  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:41:26.204  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:26.218  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:41:26.218   305   891 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:26.218  1034  1543 D DSQN    : disableDataServiceNotify
09-09 13:41:26.218  1034  1543 D DSQN    : stop dsqn bin
09-09 13:41:26.218   305  7030 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 13:41:26.219  1034  7027 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
09-09 13:41:26.219  1034  7026 D DSQN    : ThreadInternetCheck internet check NOK 
,09-09 13:41:26.220  1034  7026 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
09-09 13:41:26.220  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-09 13:41:26.223  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:26.223  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:26.224  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 13:41:26.224  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:26.224  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:26.224  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:26.224  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.224  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:26.225  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:41:26.225  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 13:41:26.225  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:26.225  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.225  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:26.226  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:26.226  1034  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:41:26.229  6651  6651 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
09-09 13:41:26.241  1034  2038 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7032 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:41:26.243  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:26.243  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:26.244  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 13:41:26.244  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:26.244  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:26.245  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
09-09 13:41:26.245  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:26.245  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:26.245  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:26.245  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:41:26.245  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:26.245  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:26.246  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:26.246  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:26.246  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:26.246  1034  1543 D NetworkManagementService: Removing idletimer
09-09 13:41:26.246  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:26.246  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.247  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.248  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.248  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:26.248  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:26.248  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:26.248  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:26.248  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:26.248  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:26.249  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:26.249  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:26.250  1877  1877 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:26.250  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN,&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:41:26.250  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 13:41:26.255  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:26.256  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:26.256  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:26.256  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,09-09 13:41:26.259  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:26.262  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:26.264  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:26.267  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:26.269  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:26.275  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:26.276  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.276  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.277  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:41:26.277  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:26.277  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.292  2654  2654 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:41:26.292  2654  2654 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:41:26.292  2654  2654 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1965-2\x00 that cannot receive messages
,09-09 13:41:26.294  1034  2719 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 13:41:26.294  1034  2719 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-09 13:41:26.308  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:26.308  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.309  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.309  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.321  7032  7032 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:41:26.324  7032  7032 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:26.325  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:26.325  2654  2654 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:41:26.325  1034  2719 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 13:41:26.326  2654  2654 W wpa_supplicant: USIM:  scard_deinit function
09-09 13:41:26.326  1034  1116 D Tethering: InitialState.processMessage what=4
09-09 13:41:26.326  1034  2719 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:41:26.326  1034  2719 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:41:26.327  1034  2719 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 13:41:26.327  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:26.327  1034  2719 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:26.327  1034  2719 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:26.328  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=127801
09-09 13:41:26.328  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=127801
09-09 13:41:26.329  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=127802  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 13:41:26.329  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=127802  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 13:41:26.330  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:26.330  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:26.346  1034  2824 D DhcpStateMachine: StoppedState
09-09 13:41:26.346  1034  2824 D DhcpStateMachine: StoppedState{ when=-144ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:26.377  1034  1945 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=7053 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 13:41:26.378  1034  1945 I ActivityManager: Killing 6300:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-09 13:41:26.379  2654  2654 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:41:26.379  1034  2719 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 13:41:26.379  1034  2719 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 13:41:26.379  1034  2719 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 13:41:26.380  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-09 13:41:26.427  1034  1750 W libprocessgroup: failed to open /acct/uid_10014/pid_6300/cgroup.procs: No such file or directory
,09-09 13:41:26.454  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:26.454  7053  7053 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 13:41:26.454  7053  7053 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:26.455  7053  7053 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-09 13:41:26.456  7053  7053 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:26.457  7053  7053 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:41:26.482  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 13:41:26.482  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:26.482  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:26.482  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 13:41:26.486  1965  1965 D WfdsService: Supplicant Connection state is changed : false
09-09 13:41:26.486  1965  2351 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 13:41:26.487  1965  2351 D WfdsService: Set the WFDS Monitor: false
09-09 13:41:26.487  1965  2351 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:41:26.487  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:26.487  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:41:26.491  2497  2497 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.496  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 13:41:26.496  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 13:41:26.496  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:41:26.497  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:26.502  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.504  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.569  6740  6740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:26.574  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:26.599  7053  7053 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:26.599  7053  7053 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:26.607  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:26.685  1034  1537 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
09-09 13:41:26.685  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-09 13:41:26.693  1034  1981 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7071 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-09 13:41:26.696  1034  1981 I ActivityManager: Killing 6373:com.android.defcontainer/u0a4 (adj 15): empty #17
09-09 13:41:26.738  1034  2262 D WifiServiceImplEx: setWifiEnabled: true pid=6740, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:41:26.739  1034  2262 D WifiService: setWifiEnabled: true pid=6740, uid=10118
09-09 13:41:26.739  1034  2262 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:41:26.741  1034  1945 W libprocessgroup: failed to open /acct/uid_10004/pid_6373/cgroup.procs: No such file or directory
,09-09 13:41:26.758  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:26.758  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:26.758  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:26.759  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 13:41:26.759  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 13:41:26.760  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 13:41:26.760  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:41:26.761  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 13:41:26.761  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:41:26.761  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 13:41:26.761  1034  1537 E WifiHW  : unknown target_country: EU , set to default
09-09 13:41:26.761  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 13:41:26.761  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 13:41:26.761  1034  1537 I WifiUtil: gEnableBmps=1
09-09 13:41:26.789  7071  7071 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:26.813  7071  7071 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-09 13:41:26.854  7071  7071 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-09 13:41:26.855  7071  7071 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 13:41:26.855  7071  7071 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 13:41:26.856  7071  7071 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,09-09 13:41:26.856  7071  7071 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 13:41:26.858  7071  7071 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-09 13:41:26.864  7071  7071 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-09 13:41:26.872  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:26.879  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:26.908  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 13:41:26.911  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:26.915  7071  7071 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 13:41:26.916  7032  7032 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:26.916  7032  7032 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:26.916  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:26.919  7071  7071 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 13:41:26.922  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:26.934  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:26.953  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:26.955  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:26.957  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:26.960  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:26.963  7032  7032 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:26.963  7032  7032 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:26.963  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:26.966  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:26.974  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:26.981  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:26.982  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:26.984  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:27.038  1034  2023 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7096 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-09 13:41:27.147  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:27.150  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.158  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:27.178  7096  7115 W FormManager: Network not available. Please check & try again.
,09-09 13:41:27.187  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:27.187  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:41:27.187  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:41:27.187  7053  7053 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:41:27.188  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:41:27.197  7053  7053 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:41:27.198  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 13:41:27.198  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:41:27.198  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:41:27.198  7053  7053 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:41:27.198  7053  7053 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-09 13:41:27.210  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:27.211  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:27.211  7096  7116 V FormManager: Network unavailable.
,09-09 13:41:27.213  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:27.216  7096  7116 V FormManager: Network unavailable.
09-09 13:41:27.218  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:27.221  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
09-09 13:41:27.229  7032  7032 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:41:27.229  7032  7032 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:27.229  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:27.232  4799  7119 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:27.234  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:27.236  4799  7121 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:27.237  4799  7121 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 13:41:27.244  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:27.249  7096  7122 W FormManager: Network not available. Please check & try again.
09-09 13:41:27.253  7096  7123 V FormManager: Network unavailable.
,09-09 13:41:27.257  7096  7123 V FormManager: Network unavailable.
09-09 13:41:27.263  1034  1984 I ActivityManager: Killing 6521:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-09 13:41:27.298  1034  1049 W libprocessgroup: failed to open /acct/uid_10008/pid_6521/cgroup.procs: No such file or directory
,09-09 13:41:27.310  7071  7071 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 13:41:27.311  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 13:41:27.311  7071  7071 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-09 13:41:27.346  7071  7071 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:27.346  7071  7071 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:27.355  7071  7071 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 13:41:27.358  7071  7071 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-09 13:41:27.358  7071  7071 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-09 13:41:27.359  7071  7071 V SoundPool: doLoad: loading sample sampleID=1
09-09 13:41:27.360  7071  7132 V SoundPool: Start decode
09-09 13:41:27.360  7071  7132 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-09 13:41:27.360  7071  7071 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-09 13:41:27.361   309  1382 V MediaPlayerService: decode(22, 10857164, 17813)
09-09 13:41:27.361   309  1382 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-09 13:41:27.361   309  1382 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-09 13:41:27.362   309  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 13:41:27.362   309  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 13:41:27.362   309  1382 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 13:41:27.362   309  1382 V MediaPlayerService: player type = 3
09-09 13:41:27.362   309  1382 V AwesomePlayer: AwesomePlayer create()
09-09 13:41:27.364   309  1382 V AwesomePlayer: reset_l() 
09-09 13:41:27.364   309  1382 V AwesomePlayer: cancelPlayerEvents
09-09 13:41:27.364   309  1382 V AwesomePlayer: setAudioSink() 
09-09 13:41:27.364   309  1382 V AwesomePlayer: reset_l() 
09-09 13:41:27.364   309  1382 V AudioCache: notify(0xb5474c80, 8, 0, 0)
09-09 13:41:27.365   309  1382 V AudioCache: ignored
09-09 13:41:27.365   309  1382 V AwesomePlayer: cancelPlayerEvents
09-09 13:41:27.365   309  1382 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 13:41:27.365   309  1382 V AwesomePlayer: setDataSource_l dataSource
09-09 13:41:27.365   309  1382 V LGParserOSAL: SniffLGParser start
09-09 13:41:27.365   309  1382 V LGParserOSAL: MainType:5, SubType=0
09-09 13:41:27.365   309  1382 V LGParserOSAL: #### check Mime : application/ogg
09-09 13:41:27.366   309  1382 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 13:41:27.366   309  1382 E MediaExtractor: Use LGExtractor :application/ogg 
09-09 13:41:27.372  6908  6908 D UEI.SmartControl: QS Service created
,09-09 13:41:27.380  7071  7071 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-09 13:41:27.382  7071  7071 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:41:27.382  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 13:41:27.390  6908  6908 I UEI.SmartControl: Service initServices...
09-09 13:41:27.390  6908  6908 D UEI.SmartControl: QS start get config
09-09 13:41:27.397  7071  7071 V LGMDMManager: Create singleton instance
,09-09 13:41:27.434   305   891 D SoftapController: Softap fwReload - Ok
09-09 13:41:27.437  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:27.439  1034  1537 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (670ms)
09-09 13:41:27.441   305   891 D CommandListener: Setting iface cfg
09-09 13:41:27.441   305   891 D CommandListener: Trying to bring down wlan0
09-09 13:41:27.442   305   891 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:27.443  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-09 13:41:27.441  7134  7134 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:27.441  7134  7134 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 13:41:27.474  7134  7134 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:41:27.483   309  1382 V LGParserOSAL: supported mime: application/ogg
09-09 13:41:27.483   309  1382 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 13:41:27.483   309  1382 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 13:41:27.483   309  1382 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 13:41:27.483   309  1382 V AwesomePlayer: AudioTrack Setting
09-09 13:41:27.483   309  1382 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 13:41:27.483   309  1382 V AwesomePlayer: setAudioSource() 
09-09 13:41:27.483   309  1382 V MediaPlayerService: prepare
09-09 13:41:27.483   309  1382 V AwesomePlayer: prepareAsync_l() 
09-09 13:41:27.483   309  1382 V MediaPlayerService: wait for prepare
09-09 13:41:27.484   309  7140 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 13:41:27.484   309  7140 V AwesomePlayer: initAudioDecoder() 
09-09 13:41:27.484   309  7140 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 13:41:27.484   309  7140 V AudioSystem: isOffloadSupported()
09-09 13:41:27.484   309  7140 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 13:41:27.484   309  7140 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 13:41:27.484   309  7140 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 13:41:27.484   309  7140 V AwesomePlayer: getUseOffload() = 0 
09-09 13:41:27.484   309  7140 V OMXCodec: OMXCodec::Create
09-09 13:41:27.484   309  7140 V OMXCodec: findMatchingCodecs()
09-09 13:41:27.484   309  7140 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 13:41:27.484   309  7140 V OMXCodec: matchingCodecs.size()=1
09-09 13:41:27.484   309  7140 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-09 13:41:27.486   309  7140 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 13:41:27.486   309  7140 V LGCodecAdapter: LG Codec Adapter start
09-09 13:41:27.486   309  7140 V OMXCodec: OMXCodec Createtor
09-09 13:41:27.486   309  7140 V OMXCodec: setComponentRole
09-09 13:41:27.486   309  7140 V OMXCodec: configureCodec protected=0
09-09 13:41:27.486   309  7140 V LGCodecAdapter: called getLGCodecSpecificData
09-09 13:41:27.486   309  7140 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 13:41:27.486   309  7140 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 13:41:27.486   309  7140 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 13:41:27.486   309  7140 V LGCodecOSAL: Not support LGCodec
09-09 13:41:27.486   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 13:41:27.486   309  7140 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 13:41:27.486   309  7140 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 13:41:27.486   309  7140 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 13:41:27.486   309  7140 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 13:41:27.486   309  7140 V AudioSystem: isOffloadSupported()
09-09 13:41:27.486   309  7140 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 13:41:27.486   309  7140 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 13:41:27.486   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 13:41:27.486   309  7140 V OM,XCodec: init()
09-09 13:41:27.486   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-09 13:41:27.486   309  7140 V OMXCodec: allocateBuffers
09-09 13:41:27.486   309  7140 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 13:41:27.486   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on input port
09-09 13:41:27.487   309  7140 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fce0 on output port
,09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on output port
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb178f060 on output port
09-09 13:41:27.487   309  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb178f150 on output port
09-09 13:41:27.487   309  7140 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 13:41:27.488   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 13:41:27.488   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 13:41:27.488   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 13:41:27.488   309  7140 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 13:41:27.488   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 13:41:27.488   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 13:41:27.488   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 13:41:27.488   309  7140 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 13:41:27.488   309  7140 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 13:41:27.488   309  7140 V AudioCache: notify(0xb5474c80, 5, 0, 0)
09-09 13:41:27.488   309  7140 V AudioCache: ignored
09-09 13:41:27.488   309  7140 V AudioCache: notify(0xb5474c80, 1, 0, 0)
09-09 13:41:27.488   309  7140 V AudioCache: prepared
09-09 13:41:27.488   309  1382 V AudioCache: wait - success
09-09 13:41:27.488   309  1382 V MediaPlayerService: start
09-09 13:41:27.488   309  1382 V AwesomePlayer: play_l() 
09-09 13:41:27.488   309  1382 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 13:41:27.488   309  1382 V AwesomePlayer: createAudioPlayer_l
09-09 13:41:27.488   309  1382 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 13:41:27.488   309  1382 V AwesomePlayer: startAudioPlayer_l() 
09-09 13:41:27.488   309  1382 D AudioPlayer: start of Playback, useOffload 0
09-09 13:41:27.488   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 13:41:27.488   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049056
09-09 13:41:27.491   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975184
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977493088
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977493328
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 13:41:27.492   3,09  7142 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 13:41:27.492   309  7142 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb178f060 on output port
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on output port
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fce0 on output port
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb178f2e0 on output port
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 13:41:27.492   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 13:41:27.493   309  1382 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 13:41:27.493   309  1382 V AudioCache: notify(0xb5474c80, 6, 0, 0)
09-09 13:41:27.493   309  1382 V AudioCache: ignored
09-09 13:41:27.494   309  1382 V MediaPlayerService: wait for playback complete
09-09 13:41:27.499   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.499   309  7143 V AudioCache: memcpy(0xaf104000, 0xb1014000, 4096)
09-09 13:41:27.500   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.501   309  7143 V AudioCache: memcpy(0xaf105000, 0xb1014000, 4096)
09-09 13:41:27.501   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.501   309  7143 V AudioCache: memcpy(0xaf106000, 0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: memcpy(0xaf107000, 0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: memcpy(0xaf108000, 0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: memcpy(0xaf109000, 0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.503   309  7143 V AudioCache: memcpy(0xaf10a000, 0xb1014000, 4096)
09-09 13:41:27.505   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.505   309  7143 V AudioCache: memcpy(0xaf10b000, 0xb1014000, 4096)
09-09 13:41:27.505   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.505   309  7143 V AudioCache: memcpy(0xaf10c000, 0xb1014000, 4096)
09-09 13:41:27.506   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.506   309  7143 V AudioCache: memcpy(0xaf10d000, 0xb1014000, 4096)
09-09 13:41:27.507   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.507   309  7143 V AudioCache: memcpy(0xaf10e000, 0xb1014000, 4096)
09-09 13:41:27.507  7134  7134 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:27.507  7134  7134 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-09 13:41:27.509  1034  1116 D Tethering: InitialState.processMessage what=4
09-09 13:41:27.510  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:27.514   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.514   309  7143 V AudioCache: memcpy(0xaf10f000, 0xb1014000, 4096)
09-09 13:41:27.515   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.515   309  7143 V AudioCache: memcpy(0xaf110000, 0xb1014000, 4096)
09-09 13:41:27.515   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.515   309  7143 V AudioCache: memcpy(0xaf111000, 0xb1014000, 4096)
09-09 13:41:27.516   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.516   309  7143 V AudioCache: memcpy(0xaf112000, 0xb1014000, 4096)
09-09 13:41:27.517   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.517   309  7143 V AudioCache: memcpy(0xaf113000, 0xb1014000, 4096)
09-09 13:41:27.517   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.517   309  7143 V AudioCache: memcpy(0xaf114000, 0xb1014000, 4096)
09-09 13:41:27.518   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.518   309  7143 V AudioCache: memcpy(0xaf115000, 0xb1014000, 4096)
09-09 13:41:27.518   309  7143 V AudioCache: write(0xb1014000, 4096)
,09-09 13:41:27.518   309  7143 V AudioCache: memcpy(0xaf116000, 0xb1014000, 4096)
09-09 13:41:27.519   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.519   309  7143 V AudioCache: memcpy(0xaf117000, 0xb1014000, 4096)
09-09 13:41:27.520   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.520   309  7143 V AudioCache: memcpy(0xaf118000, 0xb1014000, 4096)
09-09 13:41:27.520   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.520   309  7143 V AudioCache: memcpy(0xaf119000, 0xb1014000, 4096)
09-09 13:41:27.521   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.521   309  7143 V AudioCache: memcpy(0xaf11a000, 0xb1014000, 4096)
09-09 13:41:27.521   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.521   309  7143 V AudioCache: memcpy(0xaf11b000, 0xb1014000, 4096)
09-09 13:41:27.522   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.522   309  7143 V AudioCache: memcpy(0xaf11c000, 0xb1014000, 4096)
09-09 13:41:27.523   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.523   309  7143 V AudioCache: memcpy(0xaf11d000, 0xb1014000, 4096)
09-09 13:41:27.523   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.523   309  7143 V AudioCache: memcpy(0xaf11e000, 0xb1014000, 4096)
09-09 13:41:27.524   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.524   309  7143 V AudioCache: memcpy(0xaf11f000, 0xb1014000, 4096)
09-09 13:41:27.525   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.525   309  7143 V AudioCache: memcpy(0xaf120000, 0xb1014000, 4096)
09-09 13:41:27.527   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.527   309  7143 V AudioCache: memcpy(0xaf121000, 0xb1014000, 4096)
09-09 13:41:27.528   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.528   309  7143 V AudioCache: memcpy(0xaf122000, 0xb1014000, 4096)
09-09 13:41:27.528   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.528   309  7143 V AudioCache: memcpy(0xaf123000, 0xb1014000, 4096)
09-09 13:41:27.529   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.529   309  7143 V AudioCache: memcpy(0xaf124000, 0xb1014000, 4096)
09-09 13:41:27.529   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.529   309  7143 V AudioCache: memcpy(0xaf125000, 0xb1014000, 4096)
09-09 13:41:27.530   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.530   309  7143 V AudioCache: memcpy(0xaf126000, 0xb1014000, 4096)
09-09 13:41:27.531   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.531   309  7143 V AudioCache: memcpy(0xaf127000, 0xb1014000, 4096)
09-09 13:41:27.531   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.531   309  7143 V AudioCache: memcpy(0xaf128000, 0xb1014000, 4096)
09-09 13:41:27.532   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.532   309  7143 V AudioCache: memcpy(0xaf129000, 0xb1014000, 4096)
09-09 13:41:27.532   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.533   309  7143 V AudioCache: memcpy(0xaf12a000, 0xb1014000, 4096)
09-09 13:41:27.533   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.533   309  7143 V AudioCache: memcpy(0xaf12b000, 0xb1014000, 4096)
09-09 13:41:27.534   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.534   309  7143 V AudioCache: memcpy(0xaf12c000, 0xb1014000, 4096)
09-09 13:41:27.534   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.534   309  7143 V AudioCache: memcpy(0xaf12d000, 0xb1014000, 4096)
09-09 13:41:27.535   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.535   309  7143 V AudioCache: memcpy(0xaf12e000, 0xb1014000, 4096)
09-09 13:41:27.536   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.536   309  7143 V AudioCache: memcpy(0xaf12f000, 0xb1014000, 4096)
09-09 13:41:27.536   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.536   309  7143 V AudioCache: memcpy(0xaf130000, 0xb1014000, 4096)
09-09 13:41:27.537   309  7143 V Au,dioCache: write(0xb1014000, 4096)
09-09 13:41:27.537   309  7143 V AudioCache: memcpy(0xaf131000, 0xb1014000, 4096)
09-09 13:41:27.537   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.537   309  7143 V AudioCache: memcpy(0xaf132000, 0xb1014000, 4096)
09-09 13:41:27.538   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.538   309  7143 V AudioCache: memcpy(0xaf133000, 0xb1014000, 4096)
09-09 13:41:27.538   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.538   309  7143 V AudioCache: memcpy(0xaf134000, 0xb1014000, 4096)
09-09 13:41:27.539   309  7143 V AudioCache: write(0xb1014000, 4096)
09-09 13:41:27.539   309  7143 V AudioCache: memcpy(0xaf135000, 0xb1014000, 4096)
09-09 13:41:27.539   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 13:41:27.539   309  7143 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 13:41:27.539   309  7143 V AwesomePlayer: postAudioEOS() 
09-09 13:41:27.539   309  7143 V AudioCache: write(0xb1014000, 280)
09-09 13:41:27.539   309  7143 V AudioCache: memcpy(0xaf136000, 0xb1014000, 280)
,09-09 13:41:27.545  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:27.545  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:27.545  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:41:27.545   309  7140 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 13:41:27.545   309  7140 V AwesomePlayer: onStreamDone
09-09 13:41:27.545   309  7140 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 13:41:27.545   309  7140 V AudioCache: notify(0xb5474c80, 2, 0, 0)
09-09 13:41:27.545   309  7140 V AudioCache: playback complete
09-09 13:41:27.545   309  7140 V AwesomePlayer: pause_l() 
09-09 13:41:27.545   309  7140 V AudioCache: notify(0xb5474c80, 7, 0, 0)
09-09 13:41:27.545   309  7140 V AudioCache: ignored
09-09 13:41:27.545   309  7140 V AwesomePlayer: cancelPlayerEvents
09-09 13:41:27.545  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:41:27.545  1034  1537 D WifiMonitor: connecting to supplicant
09-09 13:41:27.546   309  1382 V AudioCache: wait - success
09-09 13:41:27.546   309  1382 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 13:41:27.546   309  7140 D AudioPlayer: Pause Playback at 1068125
09-09 13:41:27.546   309  1382 V AwesomePlayer: reset_l() 
09-09 13:41:27.546   309  1382 V AudioCache: notify(0xb5474c80, 8, 0, 0)
09-09 13:41:27.546   309  1382 V AudioCache: ignored
09-09 13:41:27.546   309  1382 V AwesomePlayer: cancelPlayerEvents
09-09 13:41:27.546   309  1382 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 13:41:27.546   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 13:41:27.546   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-09 13:41:27.546   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 13:41:27.546   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 0
,09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb178f2e0 on port 1
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fce0 on port 1
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 13:41:27.547  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 1
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb178f060 on port 1
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 13:41:27.547   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 13:41:27.548   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 13:41:27.548   309  7142 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 13:41:27.548   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,09-09 13:41:27.548   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 13:41:27.548   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 13:41:27.548  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-09 13:41:27.549  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:27.550   309  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-09 13:41:27.550   309  1382 D AudioPlayer: AudioPlayer releasing audio source
09-09 13:41:27.550   309  1382 D AudioPlayer: AudioPlayer done releasing audio source
09-09 13:41:27.550   309  1382 V AwesomePlayer: reset_l() 
09-09 13:41:27.550   309  1382 V AwesomePlayer: cancelPlayerEvents
09-09 13:41:27.550   309  1382 V AwesomePlayer: ~AwesomePlayer call
,09-09 13:41:27.550   309  1382 V AwesomePlayer: reset_l() 
09-09 13:41:27.550   309  1382 V AwesomePlayer: cancelPlayerEvents
09-09 13:41:27.550  7071  7132 V SoundPool: close(31)
09-09 13:41:27.550  7071  7132 V SoundPool: pointer = 0x9ffdb000, size = 205080, sampleRate = 48000, numChannels = 2
09-09 13:41:27.551  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:27.552  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 13:41:27.552  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:27.552  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-09 13:41:27.553  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.554  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6022
09-09 13:41:27.557  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:27.557  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:41:27.557  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:41:27.557  7053  7053 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:41:27.557  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:41:27.558  7053  7053 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:41:27.558  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 13:41:27.558  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:41:27.558  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:41:27.558  7053  7053 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:41:27.558  7053  7053 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:41:27.570  7134  7134 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:27.574  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:27.577  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.579  7096  7146 W FormManager: Network not available. Please check & try again.
09-09 13:41:27.580  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:27.585  7096  7147 V FormManager: Network unavailable.
,09-09 13:41:27.589  7096  7147 V FormManager: Network unavailable.
,09-09 13:41:27.691  7134  7134 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 13:41:27.701  7134  7134 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-09 13:41:27.703  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 13:41:27.704  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-09 13:41:27.706  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:41:27.706  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 13:41:27.707  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 13:41:27.707  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:41:27.707  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:41:27.707  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:41:27.708  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:27.709  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:27.710  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:41:27.711  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:27.712  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 13:41:27.712  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 13:41:27.715  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 13:41:27.716  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 13:41:27.716  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:41:27.716  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:27.716  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:27.716  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:41:27.717  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:27.717  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:27.717  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:27.718  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:27.718  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-09 13:41:27.730  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:27.731  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:41:27.732  1965  1965 D WfdService: Waiting for WifiP2p enabling
09-09 13:41:27.732  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:41:27.734  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 13:41:27.734  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
09-09 13:41:27.734  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:41:27.734  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 13:41:27.736  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:27.739  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:27.742  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:27.745  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 13:41:27.748  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:27.755  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:27.756  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:27.756  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:41:27.758  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:27.760  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.762  7096  7150 W FormManager: Network not available. Please check & try again.
09-09 13:41:27.762  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
09-09 13:41:27.762  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 13:41:27.763  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 13:41:27.763  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 13:41:27.763  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 13:41:27.763  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 13:41:27.763  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 13:41:27.763  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 13:41:27.764  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 13:41:27.764  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:27.764  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:27.764  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 13:41:27.764  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 13:41:27.765  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 13:41:27.765  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 13:41:27.765  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 13:41:27.766  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:27.766  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 13:41:27.766  1965  1965 D WfdsService: Supplicant Connection state is changed : true
,09-09 13:41:27.767  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 13:41:27.767  1034  1537 D WifiNative-HAL: Setting external_sim to 1
09-09 13:41:27.767  1965  2351 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 13:41:27.767  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 13:41:27.767  1965  2351 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:27.767  1965  2351 D WfdsMonitor: WfdsMonitorThread create
09-09 13:41:27.767  1965  2351 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:41:27.767  1965  2351 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:41:27.767  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:27.767  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 13:41:27.767  7096  7151 V FormManager: Network unavailable.
09-09 13:41:27.767  1034  1537 I WifiNative-HAL: startHal
09-09 13:41:27.767  1034  1537 D wifi    : setting scan oui 0x957d9680
09-09 13:41:27.768  1965  7152 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:41:27.768  1965  7152 E CtrlSupplicant: Succeed to open control connection
09-09 13:41:27.768  1965  7152 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:41:27.769  1965  7152 D WfdsMonitor: Supplicant connection established
09-09 13:41:27.769  1965  2351 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:27.769  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:27.769  1034  1537 I WifiNative-HAL: startHal
09-09 13:41:27.769  1034  1537 D wifi    : setting scan oui 0x957d9680
09-09 13:41:27.770  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 13:41:27.770  6740  6808 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 13:41:27.770  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 13:41:27.770  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 13:41:27.770  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 13:41:27.771  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 13:41:27.771  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:41:27.771  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:41:27.771  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:41:27.771  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 13:41:27.771  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,09-09 13:41:27.772  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 13:41:27.772  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:41:27.772  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:41:27.772  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:41:27.772  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:41:27.772  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:41:27.773  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:41:27.773  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 13:41:27.773  7134  7134 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 13:41:27.773  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 13:41:27.773  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:41:27.773  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:41:27.773  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:41:27.774  1034  1537 E WifiNative: : [129,247,285 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 13:41:27.774  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 13:41:27.774  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:27.775  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
09-09 13:41:27.775  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-09 13:41:27.775  7096  7151 V FormManager: Network unavailable.
09-09 13:41:27.775  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:41:27.775  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 13:41:27.775  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 13:41:27.775  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:41:27.776  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:41:27.776  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.777   305   891 D CommandListener: Setting iface cfg
09-09 13:41:27.777   305   891 D CommandListener: Trying to bring up p2p0
09-09 13:41:27.778  1034  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:27.778  1034  1535 D LGWifiP2pService: P2pEnablingState
09-09 13:41:27.778  1034  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.778  1034  1535 D LGWifiP2pService: P2p socket connection successful
09-09 13:41:27.778  1034  1535 D LGWifiP2pService: P2pEnabledState
09-09 13:41:27.778  1034  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 13:41:27.779  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 13:41:27.779  1965  1965 D WfdsService: WifiP2pState is changed : true
09-09 13:41:27.779  1965  2351 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:41:27.780  1965  2351 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:27.780  1965  2351 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:27.780  1965  2351 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:41:27.780  7134  7134 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:41:27.780  1965  2351 D WfdsService: selectPreferredScanChannel [36]
09-09 13:41:27.780  1965  2351 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 13:41:27.781  1034  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 13:41:27.781  1034  1535 D WifiNativ,e-p2p0: SET persistent_reconnect 1: returned true
09-09 13:41:27.782  1034  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 13:41:27.782  1965  1965 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:41:27.782  1965  1965 D WfdsService: isConnected: false
09-09 13:41:27.783  1034  1535 D WifiNative-p2p0: SET device_name G3: returned true
09-09 13:41:27.783  1034  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:41:27.783  1034  1535 D LGWifiP2pService: before postfix = G3
09-09 13:41:27.783  1034  1535 D WifiServerServiceExt: postfix byte check : 2
09-09 13:41:27.783  1034  1535 D LGWifiP2pService: after postfix = G3
09-09 13:41:27.783  1034  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-09 13:41:27.785  1034  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 13:41:27.785  1034  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 13:41:27.786  1034  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 13:41:27.786  1034  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 13:41:27.786  1034  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 13:41:27.786  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 13:41:27.786  1034  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 13:41:27.786  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:41:27.786  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 13:41:27.787  1034  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 13:41:27.787  1034  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 13:41:27.787  1034  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 13:41:27.787  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 13:41:27.788  1034  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 13:41:27.788  1034  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 13:41:27.788  1965  1965 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 13:41:27.788  1034  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 13:41:27.788  1965  1965 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:41:27.788  1034  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 13:41:27.788  1965  1965 D WfdsService: Update P2p Interface State: 3
09-09 13:41:27.789  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:41:27.789  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:27.789  1034  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.789  1034  1554 I WifiNative-HAL: startHal
,09-09 13:41:27.789  1034  1555 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.789  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 13:41:27.790  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 13:41:27.790  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 13:41:27.791  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 13:41:27.791  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 13:41:27.792  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 13:41:27.792  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 13:41:27.792  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 13:41:27.792  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:27.793  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:27.794  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:27.796  7134  7134 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 13:41:27.796  1034  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 13:41:27.797  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 13:41:27.797  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 13:41:27.797  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:41:27.797  7134  7134 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:41:27.797  1034  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 13:41:27.797  1034  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 13:41:27.797  1034  1554 D wifi    : getting scan capabilities on interface[1] = 0x957d9680
09-09 13:41:27.797  1034  1554 D wifi    : failed to get capabilities : -3
09-09 13:41:27.797  1034  1554 E WifiScanningService: could not get scan capabilities
09-09 13:41:27.797  1034  1535 D LGWifiP2pService: InactiveState
09-09 13:41:27.798  1034  1535 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.798  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.798  1034  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,09-09 13:41:27.798  1034  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 13:41:27.798  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.798  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:27.798  1034  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.798  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.798  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.798  1034  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.798  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-09 13:41:27.799  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.799  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.799  1965  2351 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:41:27.799  1034  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.799  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.799  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.799  7134  7134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.799  1034  7148 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ],
09-09 13:41:27.799  1965  7152 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:41:27.799  1034  7148 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.799  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.799  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.799  7134  7134 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 13:41:27.799  7134  7134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.799  1965  7152 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-09 13:41:27.799  1034  7148 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:27.800  1034  7148 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-09 13:41:27.800  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:27.800  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.800  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.800  7134  7134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.800  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 13:41:27.800  1034  7148 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:27.800  1034  7148 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
09-09 13:41:27.800  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.800  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.800  1034  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.800  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz,
09-09 13:41:27.801  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 13:41:27.801  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 13:41:27.801  1965  7152 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:27.801  1034  1034 E WifiServerServiceExt: No p2p device connected
09-09 13:41:27.803  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 13:41:27.803  5665  5665 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:27.803  5665  5665 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 13:41:27.803  7134  7134 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.804  7134  7134 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 13:41:27.804  7134  7134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.804  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 13:41:27.804  7134  7134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.804  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:41:27.804  5665  5665 V [BNRBootReceiver]: Boot Receiver Return
09-09 13:41:27.805  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:41:27.805  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:41:27.805  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.805  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.805  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:27.805  1034  7148 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:27.805  1034  7148 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.805  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.805  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.805  1034  7148 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:27.805  1034  7148 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.806  1965  7152 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:27.806  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.806  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:27.806  1965  7152 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:27.806  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:41:27.806  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 13:41:27.806  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 13:41:27.806  7134  7134 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:27.807  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 13:41:27.807  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:27.807  1034  7148 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:27.807  1034  7148 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:27.807  1034  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.807  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.807  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 13:41:27.807  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 13:41:27.808  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 13:41:27.808  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
09-09 13:41:27.808  1034  1537 D WifiNative-wlan0: SCAN: returned false
09-09 13:41:27.809  1034  1537 E WifiStateMachine:  DisconnectedState SUP,PLICANT_STATE_CHANGE_EVENT 23 0 rt=129282  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:41:27.809  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=129283  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:41:27.810  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:27.810  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:27.810  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:27.810  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:27.811  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:27.811  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:27.811  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:27.811  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:27.812  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:27.812  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:27.812  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:27.813  4799  7154 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:27.814  4799  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:27.814  4799  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:27.814  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:27.814  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:41:27.815  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:41:27.822  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:27.826  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:27.832  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:27.833  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:27.834  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:27.885  6908  6908 I UEI.SmartControl: Supports setup maps: true
,09-09 13:41:27.887  6908  6908 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:41:27.887  6908  6908 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-09 13:41:27.888  6908  6908 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 13:41:27.888  6908  6908 I UEI.SmartControl: ### init IR Blaster...
09-09 13:41:27.891  6908  6908 D serial_port: Configuring serial port
09-09 13:41:27.891  6908  6908 E UEI.SmartControl: UEIBLaster setting for 616
09-09 13:41:27.891  6908  6908 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 13:41:27.891  6908  6908 I UEI.SmartControl: configuring settings for MAXQ616
09-09 13:41:27.891  6908  6908 I UEI.SmartControl: Get version...
09-09 13:41:27.909  6908  7156 D UEI.SmartControl: serial port data available: 21
,09-09 13:41:27.936  6908  6908 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 13:41:27.936  6908  6908 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 13:41:27.936  6908  6908 I UEI.SmartControl: QS saving settings...
,09-09 13:41:27.938  6908  6908 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 13:41:27.955  6908  7156 D UEI.SmartControl: serial port data available: 4
,09-09 13:41:27.988  6908  7159 I UEI.SmartControl: Device manager: loading config....
,09-09 13:41:27.990  6908  6908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 13:41:27.992  6908  7159 D UEI.SmartControl: ----------- loading internal config...
09-09 13:41:27.994  6908  6908 E UEI.SmartControl: Services init done
09-09 13:41:27.995  6908  6908 D UEI.SmartControl: QS Service init finished
09-09 13:41:27.997  6908  6908 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 13:41:27.997  6908  6908 D UEI.SmartControl: QS Service version code: 201091
09-09 13:41:27.997  6908  6908 D UEI.SmartControl: Service requested: Control
09-09 13:41:28.007  6908  7159 E UEI.SmartControl: Loading SETTINGS...
09-09 13:41:28.008  6908  6908 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 13:41:28.013  6908  6908 D UEI.SmartControl: Internal service binding...
09-09 13:41:28.015  7071  7071 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 13:41:28.017  6908  6923 I UEI.SmartControl: ------ IControl API: 11
09-09 13:41:28.018  6908  6923 D UEI.SmartControl: File observer start...
09-09 13:41:28.019  6908  6923 E UEI.SmartControl: IR Port is disabled: false
09-09 13:41:28.019  6908  6923 D UEI.SmartControl: Starting file observer...
09-09 13:41:28.020  6908  7159 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 13:41:28.022  6908  6923 I UEI.SmartControl: Registering callback...
,09-09 13:41:28.024  6908  6928 I UEI.SmartControl: ------ IControl API: 19
09-09 13:41:28.027  6908  6928 I UEI.SmartControl: Registering Services Ready callback...
09-09 13:41:28.047  6908  7158 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:41:28.047  6908  7158 D UEI.SmartControl: -----service ready thread exits
09-09 13:41:28.048  7071  7087 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 13:41:28.049  7071  7130 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 13:41:28.050  7071  7130 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-09 13:41:28.051  7071  7071 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,09-09 13:41:28.052  7071  7071 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 13:41:28.052  6908  6970 I UEI.SmartControl: ------ IControl API: 8
09-09 13:41:28.056  7071  7071 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 13:41:28.057  7071  7071 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 13:41:28.057  7071  7071 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 13:41:28.058  7071  7071 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 13:41:28.059  7071  7071 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 13:41:28.059  7071  7071 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 13:41:28.061  7071  7071 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 13:41:28.072  7071  7071 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-09 13:41:28.077  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 13:41:28.079  7071  7071 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:41:28.080  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 13:41:28.083  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 13:41:28.086  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 13:41:28.087  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,09-09 13:41:28.090  7071  7071 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473421288089]
09-09 13:41:28.096  7071  7071 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-09 13:41:28.099  1034  2013 I ActivityManager: Killing 6568:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-09 13:41:28.136  7071  7164 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-09 13:41:28.147  1034  1762 W libprocessgroup: failed to open /acct/uid_10011/pid_6568/cgroup.procs: No such file or directory
,09-09 13:41:28.155  7071  7071 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-09 13:41:28.156  7071  7071 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:41:28.157  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 13:41:28.157  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 13:41:28.157  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 13:41:28.158  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 13:41:28.158  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 13:41:28.168  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 13:41:28.271  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 13:41:28.272  1034  7148 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,09-09 13:41:28.272  7134  7134 E wpa_supplicant: USIM:  scard_init function
,09-09 13:41:28.272  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 13:41:28.272  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-09 13:41:28.272  1034  7148 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,09-09 13:41:28.273  7134  7134 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 13:41:28.274  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 13:41:28.284  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 13:41:28.287  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:41:28.288  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-09 13:41:28.291  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 13:41:28.291  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 13:41:28.291  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 13:41:28.297  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=129770  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 13:41:28.300  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 13:41:28.300  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=129773  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 13:41:28.305  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.305  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:28.306  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.308  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.308  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.308  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:28.309  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.309  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.309  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-09 13:41:28.310  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:28.310  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:41:28.312  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.312  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:28.315  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.319  7053  7053 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:41:28.323  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.331  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:28.338  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.346  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:28.346  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.348  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:28.353  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.360  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:28.366  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.372  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:28.374  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.374  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:41:28.399  7134  7134 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:41:28.400  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 13:41:28.400  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 13:41:28.400  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 13:41:28.400  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 13:41:28.400  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:28.400  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-09 13:41:28.401  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=129874  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:41:28.402  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=129875  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:41:28.402  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129876
09-09 13:41:28.403  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129876
09-09 13:41:28.404  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129877
09-09 13:41:28.404  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129877
09-09 13:41:28.405  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129878
09-09 13:41:28.408  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:28.408  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:28.408  7134  7134 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:28.408  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 13:41:28.408  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:28.409  1034  7148 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:28.409  7134  7134 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:41:28.411  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 13:41:28.411  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:41:28.412  1034  7148 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:41:28.416  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:28.416  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-09 13:41:28.406  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=129878  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 13:41:28.421  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:28.424  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:28.424  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:41:28.424  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:41:28.424  7053  7053 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:41:28.425  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.425  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:28.431  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.431  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.431  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.431  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:41:28.433  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=129906  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 13:41:28.435  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.435  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.436  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:41:28.437  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:28.437  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 13:41:28.437  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=129909  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:41:28.438  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=129911  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:41:28.439  1034  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:28.439  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:28.440  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:28.440  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:41:28.441  7053  7053 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:41:28.441  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 13:41:28.441  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:41:28.441  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:41:28.441  7053  7053 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:41:28.441  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 13:41:28.442  7053  7053 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:41:28.442  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:41:28.443  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:28.443  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=129917
09-09 13:41:28.444  1034  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=129917
09-09 13:41:28.444  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-09 13:41:28.445  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:28.445  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:28.445  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 13:41:28.448  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:41:28.450  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.454  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.454  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:28.458  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 13:41:28.458  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 13:41:28.459  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.464  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.464  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.464  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:41:28.469  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:28.469  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.469  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:41:28.474  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:28.479  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.479  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:28.480  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.483  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.483  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:28.484  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,09-09 13:41:28.484  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.486  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:41:28.486  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:41:28.486  1034  1543 D ConnectivityService: NetworkAgent connected
09-09 13:41:28.486  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:28.486  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:41:28.487  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:41:28.487  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:41:28.488  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.494  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:41:28.494  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:28.494  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:41:28.495  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:41:28.495  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 13:41:28.500  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:28.501  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.501  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:41:28.501  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:28.503   305   891 D CommandListener: Setting iface cfg
09-09 13:41:28.507  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:41:28.513  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:28.514  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 13:41:28.515  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=129988  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:28.515  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=129989  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:28.516  1034  7177 D DhcpStateMachine: StoppedState
09-09 13:41:28.516  1034  7177 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:28.516  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=129989  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:28.516  1034  7177 D DhcpStateMachine: WaitBeforeStartState
09-09 13:41:28.517  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:28.517  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 13:41:28.518  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:28.518  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,09-09 13:41:28.520  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=129993  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:28.521  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=129994  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:28.522  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=129995  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:28.523  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:83655] from screen [on:0 period:247505995] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 13:41:28.524  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:247505996] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 13:41:28.524  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 13:41:28.524  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.529  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-09 13:41:28.529  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.529  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.530  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 13:41:28.531  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.530  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.533  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.533  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.533  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:41:28.534  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
09-09 13:41:28.534  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:28.535  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
09-09 13:41:28.535  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 13:41:28.535  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 13:41:28.535  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 13:41:28.536  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 13:41:28.536  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.536  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:28.540  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.540  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
09-09 13:41:28.540  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 13:41:28.540  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 13:41:28.541  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 13:41:28.541  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:41:28.541  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:28.541  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:28.541  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30cc230a target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:28.541  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30cc230a target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:28.543  1034  7177 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:28.543  1034  7177 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 13:41:28.545   305   891 D CommandListener: Setting iface cfg
09-09 13:41:28.546   305   891 D CommandListener: Trying to bring up wlan0
09-09 13:41:28.546  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:41:28.549  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:28.549  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:41:28.552  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.552  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:28.553  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.553  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:28.553  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-09 13:41:28.553  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.554  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.554  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.555  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:28.556  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:41:28.556  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:41:28.556  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:41:28.556  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:28.556  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:28.557  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:41:28.557  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:41:28.557  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:41:28.557  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 13:41:28.557  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 13:41:28.558  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 13:41:28.558  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:41:28.560  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.567  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:28.567  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.567  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:28.572  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.574  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:41:28.575  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 13:41:28.575  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:41:28.575  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 13:41:28.575  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:41:28.576  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:41:28.578  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.579  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:28.581  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.581  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.581  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:41:28.581  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.582  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:41:28.584  1034  1543 D ConnectivityService: Adding iface wlan0 to network 101
09-09 13:41:28.587  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:41:28.587  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.588  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.588  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:41:28.589  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:28.592  1965  1965 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-09 13:41:28.594  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.594  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.594  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:28.595  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:28.601  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.601  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:28.601  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:28.603  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.603  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:28.606  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.606  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:28.609  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:41:28.609  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:28.609  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.613  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.614  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:28.614  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:28.614  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.620  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:28.621  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.621  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:28.622  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:28.622  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 13:41:28.624  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 13:41:28.625   305   891 E Netd    : netlink response contains error (File exists)
09-09 13:41:28.625  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 13:41:28.626  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:41:28.626  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 13:41:28.627  1034  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 13:41:28.628  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-09 13:41:28.628  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:28.628  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:28.628  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:41:28.628  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:28.628  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:28.628  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:28.628  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:41:28.628  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:28.629  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:28.629  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.629  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:41:28.629  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:28.629  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:41:28.629  1034  1543 D ConnectivityService:    accepting network in place of null
09-09 13:41:28.629  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.630  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.630  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:41:28.630  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.630  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:28.631  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:41:28.631  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:41:28.631  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:28.632   305  7185 D libc-netbsd: res_queryN name = clients3.google.,com, class = 1, type = 28
09-09 13:41:28.633  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:28.633  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 13:41:28.634  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 13:41:28.635  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:41:28.635  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:28.635  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:28.635  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-09 13:41:28.641  1034  1543 D ConnectivityService: validation of new default Network = false
09-09 13:41:28.641  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:41:28.641  1034  1543 D DSQN    : enableDataServiceNotify 
09-09 13:41:28.641  1034  1543 D DSQN    : start dsqn bin
09-09 13:41:28.644  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.647  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:28.647  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:28.647  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:28.648  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:28.648  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:28.641  7186  7186 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:28.641  7186  7186 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:28.660  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:28.663  7186  7186 E DSQN    : DSQN ssw
09-09 13:41:28.669  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.675  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:28.676  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:41:28.678  1034  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 13:41:28.679  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:28.682  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.691  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:28.692   305  7185 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 13:41:28.696  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:28.697  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.698  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.698  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.704  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:28.704  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.705  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:41:28.710  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.714  7032  7032 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:28.718  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:28.722  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:28.728  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.729   305  7185 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 13:41:28.739  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:28.739  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.740  7071  7071 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 13:41:28.742  7071  7071 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-09 13:41:28.742  7071  7071 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 13:41:28.745  1034  7177 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 13:41:28.746  1034  7177 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 13:41:28.747  1034  7177 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-09 13:41:28.750  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:28.741  7190  7190 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:28.741  7190  7190 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:28.757  7032  7032 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:28.757   305   890 D LGDataListener: argv[0]=dsqncommand
09-09 13:41:28.757   305   890 D LGDataListener: argv[1]=wlan0
09-09 13:41:28.757   305   890 D LGDataListener: argv[2]=1
09-09 13:41:28.757   305   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:41:28.758  7032  7032 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:28.758  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
,09-09 13:41:28.759  1034  1114 D DSQN    : start to monitor internet connection
,09-09 13:41:28.765  7190  7190 I dhcpcd  : version 5.5.6 starting
09-09 13:41:28.766  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:28.768  7190  7190 E dhcpcd  : get_duid: m
09-09 13:41:28.768  7190  7190 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 13:41:28.768  7190  7190 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-09 13:41:28.776  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:28.783  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:28.783  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.784  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:28 GMT], X-Android-Received-Millis=[1473421288783], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421288755]}
,09-09 13:41:28.784  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:28.784  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:28.784  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 13:41:28.784  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:41:28.785  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:28.785  7071  7071 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 13:41:28.785  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:28.785  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:28.785  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 13:41:28.785  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:28.785  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.785  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 13:41:28.786  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:28.786  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.786  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:28.786  7071  7071 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 13:41:28.787  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.787  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:28.787  7071  7071 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 13:41:28.788  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:28.788  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.790  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-09 13:41:28.815  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 13:41:28.817  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.818  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:28.841  7190  7190 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:41:28.841  7190  7190 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:41:28.841  7190  7190 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-09 13:41:28.841  7190  7190 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 13:41:28.842  7190  7190 D dhcpcd  : wlan0: sending REQUEST (xid 0xe7ec9d14), next in 3.30 seconds
,09-09 13:41:28.854  7190  7190 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 13:41:28.855  7190  7190 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-09 13:41:28.855  7190  7190 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-09 13:41:28.856  7190  7190 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,09-09 13:41:28.856  7190  7190 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 13:41:28.856  7190  7190 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 13:41:28.856  7190  7190 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:41:28.856  7190  7190 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:41:28.856  7190  7190 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 13:41:29.244  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:29.260  1034  1116 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:29.286  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:29.292  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:29.293  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:29.301  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:29.305  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:29.309  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:29.311  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:29.316  1034  1116 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:29.338  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 13:41:29.348  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:29.351  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.351  1034  7177 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 13:41:29.356  1034  7177 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 13:41:29.359  1034  7177 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:29.360  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:29.361  5839  5839 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:29.363  1034  7177 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 13:41:29.363  1034  7177 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:41:29.363  1034  7177 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:29.363  1034  7177 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:41:29.363  1034  7177 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,09-09 13:41:29.368  6481  6505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:41:29.370  1034  7177 D DhcpStateMachine: RunningState
,09-09 13:41:29.388  5839  5839 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:29.404  2263  2263 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:29.418   305  7244 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:29.419   305  7244 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,09-09 13:41:29.425  1034  1574 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-09 13:41:29.426  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:29.426  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:29.426  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:29.426  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:29.426  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:29.428  1034  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:29.430  1034  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:29.430  1034  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:29.430  1034  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:41:29.451   305  7244 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-09 13:41:29.458  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:29 GMT], X-Android-Received-Millis=[1473421289458], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421289427]}
,09-09 13:41:29.458  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:29.458  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:29.459  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 13:41:29.459  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:41:29.459  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:29.459  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:29.459  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:29.459  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 13:41:29.459  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:29.459  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:29.459  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:29.460  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:29.460  1034  1953 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7256 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-09 13:41:29.462  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:29.532  7256  7256 I AppUp4:AppBoxCP: onCreate
,09-09 13:41:29.532  7256  7256 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:41:29.541  7256  7256 I AppUp4:DB:  setFingerPrint start
,09-09 13:41:29.541  7256  7256 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-09 13:41:29.549  7256  7256 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-09 13:41:29.549  7256  7256 I AppUp4:DB:  SDK version = 21
09-09 13:41:29.549  7256  7256 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:41:29.550  7256  7256 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:41:29.551  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:29.551  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:29.553  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:29.553  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:41:29.559  7256  7256 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 13:41:29.592  7256  7256 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 13:41:29.593  7256  7256 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:29.598  7256  7256 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@25bc5013
09-09 13:41:29.598  7256  7256 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:29.598  7256  7256 D AppUp4:CustFacade: isPhone : true
09-09 13:41:29.599  7256  7256 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:29.599  7256  7256 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:41:29.599  7256  7256 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:41:29.600  7256  7276 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:41:29.600  7256  7276 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:41:29.601  7256  7276 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:41:29.602  1034  1050 I ActivityManager: Killing 6100:com.android.contacts/u0a19 (adj 15): empty #17
09-09 13:41:29.648  1034  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:41:29.659  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:29.660  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:29.661  1034  1945 W libprocessgroup: failed to open /acct/uid_10019/pid_6100/cgroup.procs: No such file or directory
,09-09 13:41:29.665  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:29.668  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:29.672  4799  7280 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:29.675  2853  2853 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:29.676  4799  7280 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:29.680  2853  2853 V DownloadManager: DownloadService onCreate
09-09 13:41:29.682  4799  7281 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:29.682  4799  7281 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:29.686  2853  7282 I DownloadManager: in removeSpuriousFiles
09-09 13:41:29.687  2853  7282 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:41:29.695  4799  7280 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:29.699  2853  7282 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f555e74 on behalf of 2853
,09-09 13:41:29.703  4799  4799 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:41:29.704  4799  4799 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:41:29.704  4799  4799 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:29.706  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:41:29.706  4799  4799 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:29.706  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:41:29.706  2853  2853 V DownloadManager: DownloadService onStartCommand
09-09 13:41:29.706  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:41:29.707  2853  7282 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:41:29.707  2853  7283 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:29.709  2853  7283 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3e611fe3 on behalf of 2853
09-09 13:41:29.709  2853  7282 I DownloadManager: in trimDatabase
09-09 13:41:29.709  2853  7282 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:29.712  2853  7283 V DownloadManager: processing inserted download 1
09-09 13:41:29.712  2853  7282 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@33a3ede0 on behalf of 2853
09-09 13:41:29.715  4799  4799 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:41:29.716  2853  7283 V DownloadManager: processing inserted download 4
,09-09 13:41:29.717  2853  7283 V DownloadManager: processing inserted download 7
09-09 13:41:29.718  6589  6589 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 13:41:29.718  2853  7283 V DownloadManager: processing inserted download 8
09-09 13:41:29.720  2853  7283 V DownloadManager: processing inserted download 9
09-09 13:41:29.721  2853  7283 V DownloadManager: processing inserted download 10
09-09 13:41:29.722  2853  7283 V DownloadManager: processing inserted download 11
09-09 13:41:29.724  2853  7283 V DownloadManager: processing inserted download 12
09-09 13:41:29.725  2853  7283 V DownloadManager: processing inserted download 13
09-09 13:41:29.727  2853  7283 V DownloadManager: processing inserted download 14
09-09 13:41:29.728  2853  7283 V DownloadManager: processing inserted download 16
,09-09 13:41:29.733  2853  2853 V DownloadManager: DownloadService onDestroy
09-09 13:41:29.746  3211  3211 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:29.747  3211  3211 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:29.747  3211  3211 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 13:41:29.754  6589  6589 I HubEmail: JNI_OnLoad()
,09-09 13:41:29.754  6589  6589 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:29.754  6589  6589 I HubEmail: registerNatives()
09-09 13:41:29.754  6589  6589 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:29.754  6589  6589 I HubEmail: registerNativeMethods()
09-09 13:41:29.754  6589  6589 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:29.754  6589  6589 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 13:41:29.779   305  7293 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:29.779   305  7293 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-09 13:41:29.805  1034  2262 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7294 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-09 13:41:29.809  6589  7291 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:29.826   305  7293 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-09 13:41:29.948  7294  7294 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:29.949  7294  7294 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:29.952  7294  7294 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:41:29.973  7294  7294 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:41:29.976  7294  7294 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 13:41:29.980  1034  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-09 13:41:29.981  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:29.983  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:29.984  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:29.985  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:29.987  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:29.988  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-09 13:41:29.988  1034  1543 D ConnectivityService: identical MTU - not setting
09-09 13:41:29.988  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:29.988  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:29.989  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:29.989  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:29.990  1034  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:29.994  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:41:29.996  7294  7294 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-09 13:41:30.024  1034  1953 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7317 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:30.037  7096  7290 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:41:30.039  7294  7294 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:41:30.039  7294  7294 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:41:30.042  7294  7294 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 13:41:30.042   348   348 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 280us total 16.155ms
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-09 13:41:30.042  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 13:41:30.043  7294  7294 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 13:41:30.043  7294  7294 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-09 13:41:30.056   348   348 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 270us total 12.741ms
09-09 13:41:30.061  7096  7290 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:41:30.068   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 247us total 12.242ms
09-09 13:41:30.069  7294  7294 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-09 13:41:30.073  1841  7326 I CheckinService: active receiver: enabled
,09-09 13:41:30.090  1841  7326 I CheckinService: Preparing to send checkin request
09-09 13:41:30.090  1841  7326 I EventLogService: Accumulating logs since 1473421201517
09-09 13:41:30.093  1034  1981 I ActivityManager: Killing 6618:com.android.gallery3d/u0a27 (adj 15): empty #17
09-09 13:41:30.152  1034  1750 W libprocessgroup: failed to open /acct/uid_10027/pid_6618/cgroup.procs: No such file or directory
,09-09 13:41:30.154  1841  7326 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 13:41:30.260  1034  2023 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7341 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-09 13:41:30.319  1034  1945 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7359 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-09 13:41:30.320  1034  1945 I ActivityManager: Killing 6702:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-09 13:41:30.382  1034  1981 W libprocessgroup: failed to open /acct/uid_10061/pid_6702/cgroup.procs: No such file or directory
,09-09 13:41:30.411  7341  7341 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 13:41:30.412  7341  7341 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 13:41:30.442  7341  7341 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:41:30.443  7341  7341 I MultiDex: install
09-09 13:41:30.443  7341  7341 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:41:30.453  7341  7341 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-09 13:41:30.585  1034  1750 I art     : Explicit concurrent mark sweep GC freed 112777(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 5.876ms total 178.122ms
,09-09 13:41:30.661  1034  2262 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7381 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:30.662  1034  2262 I ActivityManager: Killing 6824:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-09 13:41:30.757  1034  2069 W libprocessgroup: failed to open /acct/uid_10080/pid_6824/cgroup.procs: No such file or directory
,09-09 13:41:30.802  7381  7381 I art     : Almond Protected OAT
,09-09 13:41:30.861  7381  7381 D WeatherApplication: removeAccount
,09-09 13:41:30.862  7381  7381 D WeatherApplication: Account.length = 0
09-09 13:41:30.863  7381  7381 E WeatherApplication: OPERATOR:OPEN
09-09 13:41:30.869  7381  7381 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:30
09-09 13:41:30.872  7381  7381 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:41:30.872  7381  7381 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:41:30.874  7381  7381 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:30.877  7381  7381 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:30.878  7381  7381 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-09 13:41:30.897  7381  7381 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:41:30.897  7381  7381 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:41:30.897  7381  7381 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-09 13:41:30.926  7381  7381 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-09 13:41:30.926  7381  7381 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:30
09-09 13:41:30.978  1034  1750 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7400 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:30.979  1034  1750 I ActivityManager: Killing 6845:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-09 13:41:31.056  7417  7417 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:41:31.057  1034  1981 W libprocessgroup: failed to open /acct/uid_10097/pid_6845/cgroup.procs: No such file or directory
,09-09 13:41:31.128  7417  7417 I dex2oat : dex2oat took 72.332ms (threads: 4)
,09-09 13:41:31.145  7341  7358 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:31.145  7341  7358 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:31.145  7341  7358 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:41:31.145  7341  7358 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:41:31.145  7341  7358 I Adreno-EGL: Remote Branch: 
09-09 13:41:31.145  7341  7358 I Adreno-EGL: Local Patches: 
09-09 13:41:31.145  7341  7358 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:31.187   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:31.187   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:31.187   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:31.189  7400  7424 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:31.192   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:31.192   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:31.192   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:31.192  7400  7424 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-09 13:41:31.199  1034  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:31.199  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:31.199  1034  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:31.216   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:31.216   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:31.216   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:31.217  7400  7429 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 13:41:31.219   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:31.220   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:31.220   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:31.220  7400  7429 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:31.248  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:41:31.249  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:41:31.250  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:41:31.251  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:41:31.252  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:41:31.253  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-09 13:41:31.369  7341  7358 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 13:41:31.370  7341  7358 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 13:41:31.433  7400  7400 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 13:41:31.447  7400  7400 I LibraryLoader: Loading: webviewchromium
09-09 13:41:31.451  7400  7400 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2931-2935)
09-09 13:41:31.451  7400  7400 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:41:31.459  7400  7400 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2088500a}
09-09 13:41:31.460  7400  7400 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:31.461  7400  7400 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:31.474  7400  7400 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 13:41:31.476  7400  7400 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:41:31.493  7400  7400 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-09 13:41:31.494  7400  7400 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-09 13:41:31.495  7400  7400 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-09 13:41:31.495   309  2206 V AudioPolicyService: registerClient() client 0xb04105c0, uid 10093
09-09 13:41:31.497  7400  7449 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:41:31.512  7400  7400 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:31.512  7400  7400 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:31.512  7400  7400 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:41:31.512  7400  7400 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:41:31.512  7400  7400 I Adreno-EGL: Remote Branch: 
09-09 13:41:31.512  7400  7400 I Adreno-EGL: Local Patches: 
09-09 13:41:31.512  7400  7400 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:31.529  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=54.5, 0.0, 0.0  rx=61.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:247509001] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:31.530  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=54.5, 0.0, 0.0  rx=61.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:247509002] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:31.530  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:41:31.542  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:31.591  1034  1538 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-09 13:41:31.602  7400  7400 I NSApplication: Starting up...
09-09 13:41:31.621  7341  7358 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:31.621  7341  7358 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:31.621  7341  7358 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:41:31.621  7341  7358 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:41:31.621  7341  7358 I Adreno-EGL: Remote Branch: 
09-09 13:41:31.621  7341  7358 I Adreno-EGL: Local Patches: 
09-09 13:41:31.621  7341  7358 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:31.635  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:31.681  1034  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7467 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:31.685  1034  1953 I ActivityManager: Killing 6878:com.lge.eula/1000 (adj 15): empty #17
,09-09 13:41:31.686  7341  7358 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:31.686  7341  7358 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:31.686  7341  7358 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:41:31.686  7341  7358 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:41:31.686  7341  7358 I Adreno-EGL: Remote Branch: 
09-09 13:41:31.686  7341  7358 I Adreno-EGL: Local Patches: 
09-09 13:41:31.686  7341  7358 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:31.750  1034  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_6878/cgroup.procs: No such file or directory
,09-09 13:41:31.764  1034  1116 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:31.766  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:31.768  1034  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:31.770  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:31.774  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:31.774  5839  5839 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:31.777  1034  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:31.790  7467  7467 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:31.794   305  7486 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:31.794   305  7486 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-09 13:41:31.834   305  7486 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-09 13:41:31.968  1841  7326 I CheckinTask: Sending checkin request (8223 bytes)
,09-09 13:41:32.051  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 13:41:32.056  6481  6505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:41:32.067  2263  2263 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:32.075   305  7500 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:32.076   305  7500 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-09 13:41:32.076   305  7500 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-09 13:41:32.077  1034  2023 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-09 13:41:32.077  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:32.077  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:32.077  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:32.077  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:32.077  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:32.079  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:32.079  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.079  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:32.079  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 13:41:32.081  7256  7256 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:32.089  7256  7256 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@25bc5013
09-09 13:41:32.090  7256  7256 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:32.090  7256  7256 D AppUp4:CustFacade: isPhone : true
09-09 13:41:32.090  7256  7256 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:32.090  7256  7256 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:41:32.093  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:32.093  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:32.094  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:41:32.101  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:32.102  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:32 GMT], X-Android-Received-Millis=[1473421292101], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421292079]}
09-09 13:41:32.102  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:32.102  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:32.102  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 13:41:32.102  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:41:32.102  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:32.102  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:32.102  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:32.102  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 13:41:32.102  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:32.102  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:32.102  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:32.103  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:32.103  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:32.108  4799  7503 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:32.108  2853  2853 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:32.110  4799  7504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.110  4799  7504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:32.112  2853  2853 V DownloadManager: DownloadService onCreate
09-09 13:41:32.116  4799  7503 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:32.116  2853  7506 I DownloadManager: in removeSpuriousFiles
09-09 13:41:32.117  2853  7506 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:41:32.120  2853  7506 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@26f1675e on behalf of 2853
,09-09 13:41:32.121  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:41:32.121  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:41:32.122  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:41:32.122  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:41:32.122  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:41:32.123  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:41:32.123  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:41:32.123  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:41:32.123  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:41:32.123  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:41:32.123  2853  7506 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:41:32.124  2853  7506 I DownloadManager: in trimDatabase
09-09 13:41:32.124  2853  7506 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:32.126  2853  7506 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@32fbd73f on behalf of 2853
,09-09 13:41:32.138  4799  7503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:32.141  2853  2853 V DownloadManager: DownloadService onStartCommand
,09-09 13:41:32.141  2853  7507 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:32.145  4799  4799 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:41:32.146  4799  4799 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:41:32.148  4799  4799 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:32.149  4799  4799 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:32.153  4799  4799 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-09 13:41:32.154  2853  7507 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3ee89b6a on behalf of 2853
09-09 13:41:32.158  2853  7507 V DownloadManager: processing inserted download 1
09-09 13:41:32.159  2853  7507 V DownloadManager: processing inserted download 4
09-09 13:41:32.159  2853  7507 V DownloadManager: processing inserted download 7
09-09 13:41:32.160  2853  7507 V DownloadManager: processing inserted download 8
09-09 13:41:32.161  2853  7507 V DownloadManager: processing inserted download 9
09-09 13:41:32.161  2853  7507 V DownloadManager: processing inserted download 10
09-09 13:41:32.162  2853  7507 V DownloadManager: processing inserted download 11
09-09 13:41:32.163  2853  7507 V DownloadManager: processing inserted download 12
09-09 13:41:32.164  2853  7507 V DownloadManager: processing inserted download 13
09-09 13:41:32.164  2853  7507 V DownloadManager: processing inserted download 14
,09-09 13:41:32.165  2853  7507 V DownloadManager: processing inserted download 16
09-09 13:41:32.170  3211  3211 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:32.170  3211  3211 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.171  3211  3211 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 13:41:32.174  6589  7512 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:32.174  2853  2853 V DownloadManager: DownloadService onDestroy
09-09 13:41:32.176  7294  7294 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:41:32.176  7294  7294 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:41:32.191  7381  7381 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:32
,09-09 13:41:32.195  7381  7381 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:41:32.195  7381  7381 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:41:32.196  7381  7381 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:32.197  7381  7381 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:32.197  7381  7381 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@284a5c49
09-09 13:41:32.198  7381  7381 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:41:32.198  7381  7381 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:41:32.198  7381  7381 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:41:32.198  7381  7381 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:32.198  7381  7381 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:32
09-09 13:41:32.226  2263  2263 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-09 13:41:32.235  1841  7326 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-09 13:41:32.245  1841  7326 I CheckinService: active receiver: disabled
,09-09 13:41:32.254  7096  7514 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:41:32.261  7096  7514 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:41:32.265  2263  2263 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-09 13:41:32.265  2263  2263 D c       : Getting all permits...
09-09 13:41:32.265  2263  2263 D a       : Opening database...
,09-09 13:41:32.268  2263  2263 D a       : Opening database auth.proximity.permit_store...
09-09 13:41:32.268  2263  2263 D a       : Closing database...
09-09 13:41:32.277  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 13:41:32.278  6481  6505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 13:41:32.305  2263  2263 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:32.312  1034  1981 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,09-09 13:41:32.312  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:32.312  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:32.312  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:32.312  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:32.312  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:32.315  1841  7525 I CheckinService: active receiver: disabled
09-09 13:41:32.320  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:32.320  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.321  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:32.321  7256  7256 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:41:32.323  7256  7256 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 13:41:32.327  7256  7256 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@25bc5013
09-09 13:41:32.327  7256  7256 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:32.327  7256  7256 D AppUp4:CustFacade: isPhone : true
09-09 13:41:32.328  7256  7256 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:32.328  7256  7256 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:41:32.333  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.333  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:41:32.336  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:32.337  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:32 GMT], X-Android-Received-Millis=[1473421292336], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421292313]}
09-09 13:41:32.337  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:32.337  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:32.338  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 13:41:32.338  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:41:32.338  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:32.338  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:32.338  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:32.338  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 13:41:32.338  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:32.338  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:32.338  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:32.339  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:32.339  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:32.340  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:32.344  2853  2853 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.346  4799  7528 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 13:41:32.347  2853  2853 V DownloadManager: DownloadService onCreate
09-09 13:41:32.350  4799  7528 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:41:32.354  4799  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.356  4799  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:32.358  2853  7530 I DownloadManager: in removeSpuriousFiles
09-09 13:41:32.359  2853  7530 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-09 13:41:32.370  4799  7528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:32.371  2853  7530 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3bd598f8 on behalf of 2853
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:41:32.372  2853  7530 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-09 13:41:32.379  2853  7530 I DownloadManager: in trimDatabase
09-09 13:41:32.380  2853  7530 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:32.380  4799  4799 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:41:32.381  2853  7530 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@196d0436 on behalf of 2853
09-09 13:41:32.381  4799  4799 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:41:32.382  4799  4799 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:32.384  4799  4799 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-09 13:41:32.385  2853  2853 V DownloadManager: DownloadService onStartCommand
09-09 13:41:32.385  6589  7533 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:32.386  2853  7531 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:32.390  4799  4799 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:41:32.391  2853  7531 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c474ca4 on behalf of 2853
09-09 13:41:32.397  3211  3211 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:32.397  3211  3211 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:32.397  3211  3211 I LgeMiscReceiver: networkInfo.isConnected() = true
,09-09 13:41:32.397  3211  3211 D PhoneState: setPdpRejectCasuse : false
09-09 13:41:32.399  2853  7531 V DownloadManager: processing inserted download 1
09-09 13:41:32.400  2853  7531 V DownloadManager: processing inserted download 4
09-09 13:41:32.402  2853  7531 V DownloadManager: processing inserted download 7
09-09 13:41:32.402  7294  7294 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:41:32.403  7294  7294 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:41:32.404  2853  7531 V DownloadManager: processing inserted download 8
09-09 13:41:32.406  2853  7531 V DownloadManager: processing inserted download 9
09-09 13:41:32.408  2853  7531 V DownloadManager: processing inserted download 10
09-09 13:41:32.409  2853  7531 V DownloadManager: processing inserted download 11
09-09 13:41:32.411  2853  7531 V DownloadManager: processing inserted download 12
,09-09 13:41:32.412  2853  7531 V DownloadManager: processing inserted download 13
09-09 13:41:32.413  7381  7381 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:32
09-09 13:41:32.415  7381  7381 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:41:32.415  7381  7381 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:41:32.415  7381  7381 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:32.415  7381  7381 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:32.416  7381  7381 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@284a5c49
09-09 13:41:32.416  2853  7531 V DownloadManager: processing inserted download 14
09-09 13:41:32.416  7381  7381 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:41:32.416  7381  7381 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:41:32.416  7381  7381 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:41:32.416  7381  7381 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:32.417  7381  7381 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:32
09-09 13:41:32.418  2853  7531 V DownloadManager: processing inserted download 16
09-09 13:41:32.424  2853  2853 V DownloadManager: DownloadService onDestroy
,09-09 13:41:32.440  2263  2263 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-09 13:41:32.452  2263  2263 I GCM     : GCM config loaded
,09-09 13:41:32.459  7096  7536 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:41:32.470  7294  7294 V SetupWizard: Connected to Gservices successfully
,09-09 13:41:32.472  7096  7536 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:41:32.478  2263  2263 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-09 13:41:32.764  2263  7543 D GCM     : Connected
,09-09 13:41:32.799  2263  7543 D GCM     : Message class com.google.e.a.a.q
,09-09 13:41:32.803  6740  7153 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:41:32.806  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:32.806   305  7550 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:32.806  1034  1050 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@688752b mBinding = false
09-09 13:41:32.806   305  7550 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-09 13:41:32.830  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:32.830  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:32.830  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-09 13:41:32.834  1034  1116 D BluetoothManagerService: Message: 2
09-09 13:41:32.835  1034  1116 D BluetoothManagerService: Sending off request.
09-09 13:41:32.836  4347  4499 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,09-09 13:41:32.837  4347  4423 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 13:41:32.837  4347  4423 D BluetoothAdapterProperties: Setting state to 13
09-09 13:41:32.837  4347  4423 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:41:32.837  1034  1116 D BluetoothManagerService: Message: 60
09-09 13:41:32.837  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 13:41:32.837  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 13:41:32.838  4347  4423 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:41:32.838  4347  4423 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 13:41:32.841  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:32.845  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 13:41:32.849   305  7550 D libc-netbsd: res_queryN name = www.google.com succeed
09-09 13:41:32.850  4347  4347 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:32.850  4347  4347 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:41:32.850  4347  4347 V BtOppService: Receiver DISABLED_ACTION 
09-09 13:41:32.850  4347  4347 V BluetoothMapService: Handler(): got msg=4
09-09 13:41:32.850  4347  4347 D BluetoothMapService: MAP Service closeService in
,09-09 13:41:32.851  4347  4347 D BluetoothMapMasInstance: MAP Service shutdown
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 13:41:32.851  4347  4759 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 13:41:32.852  4347  4347 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:41:32.852  4347  4347 V BluetoothMapService: MAP Service closeService out
09-09 13:41:32.853  4347  4347 I BtOppRfcommListener: stopping Accept Thread
09-09 13:41:32.853  4347  4347 V BtOppRfcommListener: close mBtServerSocket
,09-09 13:41:32.853  4347  4347 V BtOppRfcommListener: waiting for thread to terminate
09-09 13:41:32.853  4347  4821 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:32.853  4347  4821 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:41:32.854  4347  4347 V BtOppRfcommListener: done waiting for thread to terminate
09-09 13:41:32.855  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:32.855  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:32.857  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:32.857  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:32.861   305  7554 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:32.861   305  7554 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 13:41:32.861   305  7554 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-09 13:41:32.862  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:32.862  4347  4427 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:32.862  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:32.863  4347  4423 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:41:32.863  4347  4760 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:32.864  4347  4423 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 13:41:32.864  4347  4822 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:32.864  4347  4824 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:32.865  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 13:41:32.865  4347  4537 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:41:32.869  4347  4537 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:41:32.870  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 13:41:32.870  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 13:41:32.870  4347  4537 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-09 13:41:32.872  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:32.872  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:32.888  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:32.888  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:32.889  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:32.890  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:32.891  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:32.893  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:32.895  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:32.900  7053  7053 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:41:32.920  1034  1539 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-09 13:41:32.922  1034  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7559 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-09 13:41:32.931  4347  4347 V BtOppService: onDestroy
09-09 13:41:32.941  4347  4347 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-09 13:41:32.950  4347  4347 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:41:32.950  4347  4347 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:32.950  4347  4347 V BluetoothPbapReceiver: ***********state = 13
09-09 13:41:32.952  4347  4347 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-09 13:41:32.955  4347  4347 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:32.955  4347  4347 V BluetoothPbapService: state: 13
09-09 13:41:32.955  4347  4347 V BluetoothPbapService: Pbap Service closeService in
09-09 13:41:32.955  2263  2263 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:41:32.956  4347  4347 V BluetoothPbapService: successfully stopped pbap service
09-09 13:41:32.956  4347  4347 V BluetoothPbapService: Pbap Service closeService out
09-09 13:41:32.956  4347  4347 V BluetoothPbapService: Pbap Service onDestroy
09-09 13:41:32.956  4347  4347 V BluetoothPbapService: Pbap Service closeService in
09-09 13:41:32.956  4347  4347 V BluetoothPbapService: Pbap Service closeService out
09-09 13:41:32.956  4347  4347 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 13:41:32.958  1034  1116 D BluetoothManagerService: Message: 20
09-09 13:41:32.958  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30973907:true
09-09 13:41:32.972  1034  1116 D BluetoothManagerService: Message: 30
,09-09 13:41:32.980  1034  1116 D BluetoothManagerService: Message: 30
09-09 13:41:32.983  7053  7053 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 13:41:32.985  7053  7053 D BluetoothMap: Create BluetoothMap proxy object
09-09 13:41:32.986  1034  1116 D BluetoothManagerService: Message: 30
09-09 13:41:32.988  6908  7160 D UEI.SmartControl: Internal timer expired: 4
09-09 13:41:32.988  6908  7160 D UEI.SmartControl: unbind internal service
09-09 13:41:33.000  1034  1116 D BluetoothManagerService: Message: 30
,09-09 13:41:33.004  7053  7053 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 13:41:33.005  7053  7053 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-09 13:41:33.018  7053  7053 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-09 13:41:33.028  7053  7053 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-09 13:41:33.036  7053  7053 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:33.040  7053  7053 D BluetoothInputDevice: Proxy object connected
09-09 13:41:33.041  7053  7053 D HidProfile: Bluetooth service connected
09-09 13:41:33.041  7053  7053 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 13:41:33.042  7053  7053 D PanProfile: Bluetooth service connected
09-09 13:41:33.043  7053  7053 D BluetoothMap: Proxy object connected
09-09 13:41:33.043  7053  7053 D MapProfile: Bluetooth service connected
09-09 13:41:33.043  7053  7053 D BluetoothMap: getConnectedDevices()
09-09 13:41:33.044  7053  7053 D BluetoothMap: Bluetooth is Not enabled
09-09 13:41:33.044  7053  7053 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 13:41:33.064  7559  7559 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 13:41:33.065  7559  7559 W LG Account v2.2: No ProfileInfo entries
09-09 13:41:33.065  7559  7559 I LG Account v2.2: isEnabled: false
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Country: EU
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Operator: OPEN
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Ranking support: false
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Comfort support: false
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Accessory: true
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Health device: true
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Extra Pedometer: false
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Blood glucose device: false
09-09 13:41:33.065  7559  7559 I Feature : [Lifetracker]Device Number: 3
,09-09 13:41:33.074  7053  7053 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 13:41:33.078  7053  7053 D BluetoothPermissionRequest: onReceive
,09-09 13:41:33.080  7053  7053 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 13:41:33.086  7053  7053 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 13:41:33.087  1034  1049 I ActivityManager: Killing 2175:com.lge.music/u0a34 (adj 15): empty #17
09-09 13:41:33.102   309  1382 V AudioFlinger: 2175 died, releasing its sessions
09-09 13:41:33.102   309  1382 V AudioFlinger:  pid 1877 @ 0
09-09 13:41:33.102   309  1382 V AudioFlinger:  pid 3211 @ 1
,09-09 13:41:33.102   309  1382 V AudioFlinger:  pid 3211 @ 2
,09-09 13:41:33.152  6908  7157 D serial_port: close(fd = 24)
09-09 13:41:33.156  6908  7157 I UEI.SmartControl: Serial port is closed.
,09-09 13:41:33.174  4347  4347 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-09 13:41:33.175  4347  4347 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-09 13:41:33.176  4347  4347 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 13:41:33.177  1034  2262 W libprocessgroup: failed to open /acct/uid_10034/pid_2175/cgroup.procs: No such file or directory
09-09 13:41:33.193  4347  4347 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:33.193  4347  4347 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-09 13:41:33.196  4347  4347 V BluetoothFtpService: Ftp Service onStartCommand
,09-09 13:41:33.196  4347  4347 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:33.197  4347  4347 V BluetoothFtpService: Ftp Service closeService
09-09 13:41:33.197  4347  4347 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 13:41:33.200  4347  4347 V BluetoothFtpService: successfully stopped ftp service
09-09 13:41:33.201  4347  4347 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:41:33.201  4347  4347 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:41:33.201  4347  4347 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:41:33.202  4347  4347 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:33.202  4347  4347 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 13:41:33.202  4347  4347 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 13:41:33.205  4347  4347 V BluetoothFtpService: Ftp Service onDestroy
09-09 13:41:33.205  4347  4347 V BluetoothFtpService: Ftp Service closeService
09-09 13:41:33.281  1034  1574 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7594 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 13:41:33.283  4347  4347 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:33.283  4347  4347 V BluetoothSapService: state: 13
09-09 13:41:33.283  4347  4347 V BluetoothSapService: Stopping SAP server process
,09-09 13:41:33.290  4347  4347 V BluetoothSapService: Sap Service closeSapService in
09-09 13:41:33.290  4347  4347 V BluetoothSapService: Close listen Socket : 
09-09 13:41:33.290  4347  4347 V BluetoothSapService: Close rfcomm Socket : 
09-09 13:41:33.290  4347  4347 V BluetoothSapService: Close sapd  Socket : 
09-09 13:41:33.291  4347  4347 V BluetoothSapService: Sap Service closeSapService out
09-09 13:41:33.291  4347  4347 V BluetoothSapService: Sap Service onDestroy
09-09 13:41:33.291  4347  4347 V BluetoothSapService: Sap Service closeSapService in
09-09 13:41:33.292  4347  4347 V BluetoothSapService: Close listen Socket : 
09-09 13:41:33.292  4347  4347 V BluetoothSapService: Close rfcomm Socket : 
09-09 13:41:33.292  4347  4347 V BluetoothSapService: Close sapd  Socket : 
09-09 13:41:33.292  4347  4347 V BluetoothSapService: Sap Service closeSapService out
,09-09 13:41:33.366  7594  7594 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:33.390  1034  1750 I ActivityManager: Killing 6651:com.android.vending/u0a44 (adj 15): empty #17
,09-09 13:41:33.424  1034  2038 W libprocessgroup: failed to open /acct/uid_10044/pid_6651/cgroup.procs: No such file or directory
,09-09 13:41:33.873  4347  4427 D bt_hci_bdroid: cleanup
,09-09 13:41:33.881  4347  4539 I bt_lpm  : LPM is already off!!!
,09-09 13:41:33.881  4347  4730 I bt_userial_mct: exiting userial_read_thread
,09-09 13:41:33.881  4347  4730 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 13:41:33.882  4347  4537 W bt-btif : ag scb idx 1 not allocated
09-09 13:41:33.882  4347  4537 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:41:33.882  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:41:33.882  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:33.882  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:41:33.882  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:33.882  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019,
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
,09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-09 13:41:33.883  4347  4537 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:41:33.883  4347  4537 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:41:33.886  4347  4427 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 13:41:33.887  4347  4539 I bt_vendor: hw_epilog_process
09-09 13:41:33.888  4347  4427 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 13:41:33.888  4347  4427 D bt_userial_mct: userial_close
,09-09 13:41:33.888  4347  4427 E bt_userial_mct: pthread_join() FAILED result:3
09-09 13:41:33.888  4347  4427 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 13:41:33.898  4347  4427 D bt_hci_bdroid: set_power 0
09-09 13:41:33.899  4347  4427 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
09-09 13:41:33.899  4347  4427 I bt_vendor: bluetooth satus is on
09-09 13:41:33.899  4347  4427 I bt_vendor: bt-vendor : resetting BT status
09-09 13:41:33.899  4347  4427 I bt_vendor: Starting hciattach daemon,
09-09 13:41:33.899  4347  4427 I bt_vendor: try to set false,
,09-09 13:41:33.921  4347  4427 I bt_vendor: Starting hciattach daemon,
09-09 13:41:33.921  4347  4427 I bt_vendor: try to set false
09-09 13:41:33.923  4347  4427 I bt_vendor: cleanup
09-09 13:41:33.924  4347  4537 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-09 13:41:33.926  4347  4427 I GKI_LINUX: GKI_exit_task 0 done
09-09 13:41:33.926  4347  4427 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 13:41:33.928  4347  4423 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 13:41:33.933  4347  4347 D HeadsetService: Received stop request...Stopping profile...
09-09 13:41:33.934  4347  4347 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:41:33.934  4347  4347 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:33.934  4347  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33461250
09-09 13:41:33.935  4347  4485 D HeadsetStateMachine: Exit Disconnected: -1
09-09 13:41:33.939  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:33.939  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-09 13:41:33.942  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:33.942  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:33.943  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:33.945  4347  4347 D A2dpService: Received stop request...Stopping profile...
09-09 13:41:33.948  4347  4423 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 13:41:33.949  4347  4347 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 13:41:33.951  4347  4347 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 13:41:33.951  4347  4347 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:33.951  4347  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33461250
,09-09 13:41:33.955  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:33.955  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 13:41:33.956  4347  4347 D HidService: Received stop request...Stopping profile...
09-09 13:41:33.957  4347  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33461250
09-09 13:41:33.958  4347  4347 D HealthService: Received stop request...Stopping profile...
09-09 13:41:33.958  4347  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33461250
09-09 13:41:33.960  4347  4347 D HeadsetStateMachine: Unbinding service...
09-09 13:41:33.962  4347  4347 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:41:33.962  4347  4347 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:41:33.962  4347  4347 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:41:33.962  4347  4347 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:41:33.962  4347  4347 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:41:33.962  4347  4347 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:33.962  4347  4347 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:41:33.963  4347  4347 D PanService: Received stop request...Stopping profile...
,09-09 13:41:33.966  4347  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33461250
09-09 13:41:33.968  4347  4347 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:41:33.969  4347  4347 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:41:33.969  4347  4347 D BtGatt.GattService: stop()
09-09 13:41:33.969  4347  4347 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:41:33.972  4347  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33461250
09-09 13:41:33.974  4347  4347 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:41:33.974  4347  4347 D BluetoothMapService: stop()
09-09 13:41:33.974  4347  4347 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 13:41:33.975  4347  4347 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 13:41:33.975  4347  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33461250
,09-09 13:41:33.979  4347  4347 I BluetoothA2dpServiceJni: cleanupNative
09-09 13:41:33.980  4347  4520 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 13:41:33.980  4347  4347 I GKI_LINUX: GKI_exit_task 2 done
09-09 13:41:33.980  4347  4347 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 13:41:33.981  4347  4347 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:41:33.981  4347  4347 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:41:33.981  4347  4347 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:41:33.981  4347  4347 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:41:33.981  4347  4347 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:41:33.982  4347  4347 V BluetoothMapService: Handler(): got msg=4
09-09 13:41:33.982  4347  4347 D BluetoothMapService: MAP Service closeService in
09-09 13:41:33.982  4347  4347 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:41:33.982  4347  4347 V BluetoothMapService: MAP Service closeService out
09-09 13:41:33.983  4347  4423 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 13:41:33.983  4347  4423 D BluetoothAdapterProperties: Setting state to 10
09-09 13:41:33.983  4347  4423 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 13:41:33.984  4347  4519 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:41:33.985  1034  1116 D BluetoothManagerService: Message: 60
09-09 13:41:33.985  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 13:41:33.985  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 13:41:33.985  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:41:33.986  4347  4347 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:41:33.986  4347  4347 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:41:33.987  4347  4423 I BluetoothAdapterState: Entering OffState
,09-09 13:41:33.991  4347  4347 D BluetoothMapService: cleanup()
09-09 13:41:33.991  4347  4347 D BluetoothMapService: MAP Service closeService in
09-09 13:41:33.991  4347  4347 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:41:33.991  4347  4347 V BluetoothMapService: MAP Service closeService out
09-09 13:41:33.992  7053  7069 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:41:33.994  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:33.994  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:33.994  7053  7069 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:41:33.996  7053  7069 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:41:33.997  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:33.998  7053  7069 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:41:33.998  1877  2564 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:34.000  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 13:41:34.000  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-09 13:41:34.004  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 13:41:34.004  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 13:41:34.004  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@688752b mBinding = false
09-09 13:41:34.006  1034  1116 D BluetoothManagerService: Sending unbind request.
09-09 13:41:34.016  4347  4427 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 13:41:34.018  4347  4347 I GKI_LINUX: GKI_exit_task 1 done
09-09 13:41:34.018  4347  4347 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 13:41:34.018  4347  4347 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 13:41:34.019  4347  4347 I art     : --- WEIRD: removing null entry 246
09-09 13:41:34.019  4347  4347 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-09 13:41:34.019  4347  4347 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 13:41:34.020  4347  4347 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 13:41:34.021  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 13:41:34.025  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:34.026  1965  2174 D LGBluetoothAPIService: Message: 2
09-09 13:41:34.026  1965  2174 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@faae7a3 mBinding = false
09-09 13:41:34.026  1965  2174 D LGBluetoothAPIService: Sending unbind request.
09-09 13:41:34.028  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:34.031  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-09 13:41:34.033  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.034  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.050  7053  7053 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-09 13:41:34.058  1601  1601 D BluetoothAdapter: 147265512: getState() :  mService = null. Returning STATE_OFF
09-09 13:41:34.058  1601  1601 D BluetoothAdapter: 147265512: getState() :  mService = null. Returning STATE_OFF
09-09 13:41:34.059  4347  4347 I art     : System.exit called, status: 0
09-09 13:41:34.059  4347  4347 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 13:41:34.060  7053  7053 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 13:41:34.060  7053  7053 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 13:41:34.064  7053  7053 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:41:34.074  7053  7053 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:34.090   309  2206 V AudioFlinger: 4347 died, releasing its sessions
09-09 13:41:34.090   309  2206 V AudioFlinger:  pid 1877 @ 0
,09-09 13:41:34.090   309  2206 V AudioFlinger:  pid 3211 @ 1
09-09 13:41:34.090   309  2206 V AudioFlinger:  pid 3211 @ 2
09-09 13:41:34.090  7053  7053 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 13:41:34.146  1034  1762 I ActivityManager: Process com.android.bluetooth (pid 4347) has died
09-09 13:41:34.146  1034  1762 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-09 13:41:34.152  2263  2263 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:41:34.170  7053  7053 D BluetoothPermissionRequest: onReceive
,09-09 13:41:34.178  7053  7053 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 13:41:34.178  7053  7053 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 13:41:34.183  7053  7053 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 13:41:34.239  1034  2262 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7640 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 13:41:34.334  7640  7640 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-09 13:41:34.335  7640  7640 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:34.336  7640  7640 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-09 13:41:34.337  7640  7640 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:41:34.370  7640  7640 D BluetoothAdapterApp: Loading JNI Library
,09-09 13:41:34.410  7640  7640 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1853c11 Instance Count = 1
,09-09 13:41:34.418  7640  7640 D BluetoothAdapterApp: onCreate
09-09 13:41:34.444  7640  7640 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 13:41:34.444  7640  7640 D ProfileConfigQcom: Adding HeadsetService
09-09 13:41:34.445  7640  7640 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-09 13:41:34.445  7640  7640 D ProfileConfigQcom: Adding A2dpService
09-09 13:41:34.445  7640  7640 D ProfileConfigQcom: [BTUI] HidService is supported
,09-09 13:41:34.445  7640  7640 D ProfileConfigQcom: Adding HidService
,09-09 13:41:34.446  7640  7640 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 13:41:34.446  7640  7640 D ProfileConfigQcom: Adding HealthService
09-09 13:41:34.446  7640  7640 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 13:41:34.447  7640  7640 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 13:41:34.447  7640  7640 D ProfileConfigQcom: Adding PanService
09-09 13:41:34.447  7640  7640 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 13:41:34.448  7640  7640 D ProfileConfigQcom: Adding GattService
09-09 13:41:34.448  7640  7640 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-09 13:41:34.448  7640  7640 D ProfileConfigQcom: Adding BluetoothMapService,
09-09 13:41:34.448  7640  7640 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,09-09 13:41:34.450  7640  7640 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-09 13:41:34.459  7053  7053 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-09 13:41:34.462  7640  7640 V LGMDMManagerInternal: Create singleton instance
,09-09 13:41:34.545  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=38.2, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:247512017] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:34.546  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=38.2, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:247512018] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:34.547  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:41:34.550  7640  7640 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:34.554  7640  7640 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:41:34.555  7640  7640 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:41:34.555  7640  7640 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:41:34.556  7640  7640 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:34.556  7640  7640 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-09 13:41:34.564  7594  7594 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-09 13:41:34.567  1034  2013 I ActivityManager: Killing 5665:com.lge.bnr/1000 (adj 15): empty #17
,09-09 13:41:34.595  1034  1953 W libprocessgroup: failed to open /acct/uid_1000/pid_5665/cgroup.procs: No such file or directory
,09-09 13:41:36.204  7400  7426 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:41:36.754  1034  1049 I ActivityManager: Killing 7032:com.lge.sync/1000 (adj 15): empty #17
,09-09 13:41:36.825  1034  2102 W libprocessgroup: failed to open /acct/uid_1000/pid_7032/cgroup.procs: No such file or directory
,09-09 13:41:37.057  1034  2069 I ActivityManager: Killing 6908:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-09 13:41:37.080  7071  7071 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 13:41:37.080  7071  7071 W System.err: android.os.DeadObjectException
09-09 13:41:37.081  7071  7071 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:41:37.081  7071  7071 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:41:37.081  7071  7071 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 13:41:37.081  7071  7071 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 13:41:37.081  7071  7071 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 13:41:37.081  7071  7071 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 13:41:37.081  7071  7071 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:37.081  7071  7071 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:37.081  7071  7071 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:37.081  7071  7071 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:41:37.081  7071  7071 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:37.081  7071  7071 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:37.081  7071  7071 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:41:37.081  7071  7071 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:41:37.082  7071  7071 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 13:41:37.082  7071  7071 W System.err: android.os.DeadObjectException
09-09 13:41:37.082  7071  7071 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:41:37.082  7071  7071 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:41:37.082  7071  7071 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 13:41:37.082  7071  7071 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 13:41:37.082  7071  7071 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 13:41:37.082  7071  7071 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 13:41:37.082  7071  7071 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:37.082  7071  7071 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:37.082  7071  7071 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:37.082  7071  7071 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:41:37.082  7071  7071 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:37.082  7071  7071 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:37.083  7071  7071 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:41:37.083  7071  7071 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:41:37.083  7071  7071 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 13:41:37.083  7071  7071 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-09 13:41:37.117  1034  1953 W libprocessgroup: failed to open /acct/uid_1000/pid_6908/cgroup.procs: No such file or directory
09-09 13:41:37.117  1034  1953 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-09 13:41:37.123  7071  7071 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 13:41:37.123  7071  7071 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 13:41:37.174  1034  2102 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7671 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:41:37.226  7071  7071 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 13:41:37.399  1034  1574 I art     : Explicit concurrent mark sweep GC freed 35186(1789KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.001ms total 143.348ms
,09-09 13:41:37.456  7671  7671 D UEI.SmartControl: Quickset Services start...
09-09 13:41:37.459  7671  7671 I UEI.SmartControl: Manufacture = LGE
09-09 13:41:37.459  7671  7671 D UEI.SmartControl: Id = LGNevo
,09-09 13:41:37.463  7671  7671 D UEI.SmartControl: File observer start...
09-09 13:41:37.465  7671  7671 E UEI.SmartControl: IR Port is disabled: false
09-09 13:41:37.466  7671  7671 D UEI.SmartControl: Starting file observer...
09-09 13:41:37.466  7671  7671 D UEI.SmartControl: Extracting JNI libs...
09-09 13:41:37.467  7671  7671 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-09 13:41:37.570  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=44.6, 0.0, 0.0  rx=40.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:247515042] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:41:37.573  7671  7671 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-09 13:41:37.574  7671  7671 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:41:37.574  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=44.6, 0.0, 0.0  rx=40.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:247515045] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:37.574  7671  7671 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 13:41:37.574  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 13:41:37.613  7671  7671 I UEI.SmartControl: --- Selecting new region: 6
09-09 13:41:37.616  7671  7671 I UEI.SmartControl: Model = LG-D855
,09-09 13:41:37.618  7671  7671 D UEI.SmartControl: QS Service created
,09-09 13:41:37.634  7671  7671 I UEI.SmartControl: Service initServices...
,09-09 13:41:37.639  7671  7671 D UEI.SmartControl: QS start get config
,09-09 13:41:37.683  7671  7671 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:41:37.852  6740  7552 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
09-09 13:41:37.854  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:37.854  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:37.856  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:37.856  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:37.856  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:37.856  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:37.856  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c53e04f removed from the list
09-09 13:41:37.856  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:37.856  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a28c3dc removed from the list
,09-09 13:41:37.856  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:37.856  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:37.856  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:37.857  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:37.857  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d9ec3ba added. We now have 3 listener(s)
,09-09 13:41:37.865  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:37.867  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:37.867  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:37.867  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:37.868  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:37.868  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2818326b added. We now have 3 listener(s)
09-09 13:41:37.868  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:37.871  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:37.876  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:37.884  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:37.884  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:37.884  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:37.884  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.884  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:37.885  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:37.885  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:37.885  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:37.885  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:37.885  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d9ec3ba removed from the list
09-09 13:41:37.886  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:37.886  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2818326b removed from the list
09-09 13:41:37.886  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:37.886  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:37.896  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:37.896  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d32261 added. We now have 3 listener(s)
,09-09 13:41:37.896  1034  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:37.897  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:37.900  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:37.900  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:37.900  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:37.900  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:37.900  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23656186 added. We now have 3 listener(s)
09-09 13:41:37.900  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:37.901  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:37.902  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:37.903  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:37.903  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:37.904  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:37.904  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.904  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:37.904  1034  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:37.904  1034  1984 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-09 13:41:37.905  1034  1116 D BluetoothManagerService: Message: 2
09-09 13:41:37.905  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:37.907  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:37.910  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:37.911  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:37.911  1034  1574 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-09 13:41:37.927  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:37.927  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:37.928  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:37.928  1034  1116 D BluetoothManagerService: Message: 1
09-09 13:41:37.928  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-09 13:41:37.951  1034  1116 D BluetoothManagerService: Message: 20
09-09 13:41:37.951  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16b3502c:true
,09-09 13:41:37.952  7640  7640 D BluetoothAdapterState: make
09-09 13:41:37.958  7640  7640 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 13:41:37.959  7640  7715 I BluetoothAdapterState: Entering OffState
09-09 13:41:37.959  7640  7640 I bluedroid-qcom: init
09-09 13:41:37.963  7640  7640 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 13:41:37.964  7640  7640 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 13:41:37.964  7640  7640 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:41:37.964  7640  7640 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 13:41:37.964  7640  7640 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 13:41:37.969  7640  7640 I bluedroid-qcom: get_profile_interface socket
09-09 13:41:37.969  7640  7640 I bluedroid-qcom: get_profile_interface map_client
09-09 13:41:37.971  7640  7723 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 13:41:37.973  7640  7723 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 13:41:37.974  7722  7722 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 13:41:37.974  7722  7722 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 13:41:37.961  7722  7722 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:37.974  7722  7722 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-09 13:41:37.961  7722  7722 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:37.975  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 13:41:37.976  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 13:41:37.976  7640  7723 D BluetoothAdapterProperties: Name is: G3
,09-09 13:41:37.977  7722  7722 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 13:41:37.983  7722  7722 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 13:41:37.983  7722  7722 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 13:41:37.985  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 13:41:37.985  1034  1116 D BluetoothManagerService: Message: 40
09-09 13:41:37.985  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 13:41:37.986  7640  7657 I bluedroid-qcom: config_hci_snoop_log
09-09 13:41:37.987  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 13:41:37.987  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 13:41:37.992  7640  7715 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-09 13:41:37.992  7640  7715 D BluetoothAdapterProperties: Setting state to 11
09-09 13:41:37.993  7640  7715 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 13:41:37.995  1034  1116 D BluetoothManagerService: Message: 60
09-09 13:41:37.995  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 13:41:37.995  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 13:41:37.996  7640  7715 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 13:41:37.997  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:37.999  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 13:41:38.000  7053  7053 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 13:41:38.002  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:38.004  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:38.006  7640  7640 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:41:38.007  7640  7640 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:38.007  7640  7640 V BluetoothPbapReceiver: ***********state = 11
09-09 13:41:38.008  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:38.010  2263  2263 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:41:38.010  7640  7715 D BluetoothBondStateMachine: make
09-09 13:41:38.017  7640  7726 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:41:38.017  7640  7715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.018  7640  7715 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 13:41:38.018  7640  7715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.018  7640  7715 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 13:41:38.019  7640  7715 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 13:41:38.023  7640  7715 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:41:38.030  7640  7640 D HeadsetService: Received start request. Starting profile...
09-09 13:41:38.031  7640  7640 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 13:41:38.031  7640  7640 D LGBluetoothHfpAdapter: Version 1.6
09-09 13:41:38.033  7640  7640 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 13:41:38.033  7640  7640 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 13:41:38.034  7640  7640 D HeadsetStateMachine: make
,09-09 13:41:38.036  7053  7053 D BluetoothPermissionRequest: onReceive
09-09 13:41:38.036  7640  7715 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:41:38.040  7640  7715 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:41:38.044  7053  7053 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 13:41:38.049  7640  7715 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 13:41:38.053  7640  7715 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:41:38.058  7640  7715 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:41:38.060  7640  7640 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:38.060  7640  7640 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 13:41:38.063  7640  7640 D HeadsetStateMachine: max_hf_connections = 1
09-09 13:41:38.063  7640  7640 I bluedroid-qcom: get_profile_interface handsfree
09-09 13:41:38.063  7640  7715 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:41:38.064  7640  7640 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-09 13:41:38.065   309  1383 V AudioPolicyService: registerClient() client 0xb1024be0, uid 1002
09-09 13:41:38.065   309   309 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 13:41:38.065   309   309 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 13:41:38.065   309   309 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 13:41:38.065  7640  7640 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 13:41:38.066   309  1382 V AudioFlinger: registerClient() client 0xb55818e0, pid 7640
09-09 13:41:38.066   309  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:41:38.066   309  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:41:38.066  1034  1984 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:41:38.066  1034  1984 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:41:38.067  7640  7656 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:41:38.067  1601  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:41:38.067  1601  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:41:38.067  1877  2564 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:41:38.067  1877  2564 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:41:38.067  3211  3233 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:41:38.067  3211  3233 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:41:38.067   309  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:41:38.067   309  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:41:38.067  1034  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:41:38.067  1034  1574 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:41:38.067  1601  2610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:41:38.067  1601  2610 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:41:38.067  1877  4685 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:41:38.067  1877  4685 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:41:38.068  3211  3232 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:41:38.068  3211  3232 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:41:38.068  7640  7656 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 13:41:38.068  7640  7656 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:41:38.068  7640  7656 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 13:41:38.073  7640  7715 V LGMDMManager: Create singleton instance
09-09 13:41:38.074  7640  7715 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 13:41:38.069  7640  7640 V ToneGenerator: Create Track: 0xb4928a80
09-09 13:41:38.075  7640  7640 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 13:41:38.075  7640  7640 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
,09-09 13:41:38.077   309  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 13:41:38.077   309  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 13:41:38.077   309  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 13:41:38.077   309  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 13:41:38.078   309   309 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 13:41:38.078   309  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 13:41:38.078   309  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 13:41:38.078   309  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 13:41:38.078   309  1382 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 13:41:38.078  7640  7640 V AudioSystem: getLatency() output 2, latency 50
09-09 13:41:38.078  7640  7640 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 13:41:38.078  7640  7640 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 13:41:38.078   309  2206 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 13:41:38.078   309  2206 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 13:41:38.078   309  2206 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 13:41:38.078   309  2206 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 13:41:38.078   309  2206 V AudioFlinger: createTrack() lSessionId: 22
09-09 13:41:38.079  7640  7640 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 13:41:38.079   309  1383 V AudioFlinger: acquiring 22 from 7640, for 7640
09-09 13:41:38.079   309  1383 V AudioFlinger:  added new entry for 22
09-09 13:41:38.080  7640  7640 V ToneGenerator: ToneGenerator INIT OK, time: 139564
09-09 13:41:38.080  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.081  7640  7728 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 13:41:38.081  7640  7728 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:41:38.081  7640  7728 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:41:38.081  7640  7728 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 13:41:38.081   309   309 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7640
09-09 13:41:38.081  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.082   309   309 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 13:41:38.082   309   309 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 13:41:38.082   309   309 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 13:41:38.082   309   309 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 13:41:38.082   309   309 V voice   : voice_set_parameters: exit with code(0)
09-09 13:41:38.082   309   309 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 13:41:38.082   309   309 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 13:41:38.082   309   309 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 13:41:38.082   309   309 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 13:41:38.082   309   309 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 13:41:38.082   309   309 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 13:41:38.083  7640  7640 D A2dpService: Received start request. Starting profile...
09-09 13:41:38.083 , 7640  7640 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 13:41:38.084  7640  7640 V Avrcp   : make
09-09 13:41:38.085  7640  7640 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 13:41:38.085  7640  7640 I bluedroid-qcom: get_profile_interface avrcp
09-09 13:41:38.085  7640  7728 V ToneGenerator: ToneGenerator destructor
09-09 13:41:38.085  7640  7728 V ToneGenerator: stopTone
09-09 13:41:38.085  7640  7728 V ToneGenerator: Delete Track: 0xb4928a80
09-09 13:41:38.086  7640  7728 V AudioTrack: ~AudioTrack, releasing session id from 7640 on behalf of 7640
09-09 13:41:38.086   309  2206 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 13:41:38.086   309  2206 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 13:41:38.086   309  1382 V AudioFlinger: releasing 22 from 7640 for 7640
09-09 13:41:38.086   309  2206 V AudioFlinger: PlaybackThread::Track destructor
09-09 13:41:38.086   309  1264 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:41:38.086   309  2206 V AudioFlinger: removeClient_l() pid 7640, calling pid 309
09-09 13:41:38.086   309  1264 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 13:41:38.086   309  1264 V AudioPolicyManager: releaseOutput() 2
09-09 13:41:38.086   309  1264 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:41:38.086   309  1382 V AudioFlinger:  decremented refcount to 0
09-09 13:41:38.086   309  1382 V AudioFlinger: purging stale effects
09-09 13:41:38.087  1034  1945 W Process : Unable to open /proc/7733/status
09-09 13:41:38.093  7640  7640 V AudioManager: registerRemoteController: size of Media player list: 0
09-09 13:41:38.094  7640  7640 E AudioManager: No RCC entry present to update
09-09 13:41:38.094  7640  7640 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 13:41:38.097  7640  7640 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 13:41:38.098  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 13:41:38.098  7640  7640 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-09 13:41:38.102  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 13:41:38.142  7671  7671 I UEI.SmartControl: Supports setup maps: true
,09-09 13:41:38.147  7671  7671 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:41:38.147  7671  7671 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 13:41:38.147  7671  7671 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 13:41:38.148  7671  7671 I UEI.SmartControl: ### init IR Blaster...
09-09 13:41:38.153  7671  7671 D serial_port: Configuring serial port
,09-09 13:41:38.157  7671  7671 E UEI.SmartControl: UEIBLaster setting for 616
09-09 13:41:38.157  7671  7671 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 13:41:38.157  7671  7671 I UEI.SmartControl: configuring settings for MAXQ616
09-09 13:41:38.157  7671  7671 I UEI.SmartControl: Get version...
09-09 13:41:38.175  7671  7738 D UEI.SmartControl: serial port data available: 21
,09-09 13:41:38.204  1034  2262 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:41:38.204  1034  2262 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:41:38.211  7671  7671 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-09 13:41:38.211  7671  7671 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 13:41:38.211  7671  7671 I UEI.SmartControl: QS saving settings...
09-09 13:41:38.213  7671  7671 D UEI.SmartControl: IR Blaster version: 25672567
09-09 13:41:38.230  7671  7738 D UEI.SmartControl: serial port data available: 4
,09-09 13:41:38.266  7671  7741 I UEI.SmartControl: Device manager: loading config....
,09-09 13:41:38.268  7671  7741 D UEI.SmartControl: ----------- loading internal config...
,09-09 13:41:38.273  7671  7671 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 13:41:38.273  1034  1574 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 13:41:38.276  7671  7671 E UEI.SmartControl: Services init done
09-09 13:41:38.276  7671  7671 D UEI.SmartControl: QS Service init finished
09-09 13:41:38.279  7671  7671 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 13:41:38.279  7671  7671 D UEI.SmartControl: QS Service version code: 201091
09-09 13:41:38.281  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 13:41:38.283  7671  7671 D UEI.SmartControl: Service requested: Control
,09-09 13:41:38.285  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 13:41:38.286  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 13:41:38.286  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 13:41:38.286  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 13:41:38.287  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:41:38.287  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 13:41:38.287  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 13:41:38.287  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 13:41:38.287  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:41:38.287  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 13:41:38.287  7640  7640 I BluetoothA2dpServiceJni: classInitNative
09-09 13:41:38.287  7640  7640 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:41:38.287  7640  7640 D A2dpStateMachine: make
09-09 13:41:38.288  7671  7741 E UEI.SmartControl: Loading SETTINGS...
09-09 13:41:38.289  7671  7671 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 13:41:38.290  7640  7640 I bluedroid-qcom: get_profile_interface a2dp
09-09 13:41:38.290  7640  7744 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 13:41:38.292  7640  7640 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:41:38.292  7640  7640 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 13:41:38.293  7071  7071 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 13:41:38.294  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.294  7671  7687 I UEI.SmartControl: ------ IControl API: 11
,09-09 13:41:38.295  7640  7640 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 13:41:38.297  7640  7743 D A2dpStateMachine: Enter Disconnected: -2
09-09 13:41:38.301  7640  7640 D HidService: Received start request. Starting profile...
09-09 13:41:38.301  7640  7640 I bluedroid-qcom: get_profile_interface hidhost
09-09 13:41:38.301  7671  7687 I UEI.SmartControl: Registering callback...
09-09 13:41:38.301  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.302  7640  7640 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 13:41:38.302  7671  7671 D UEI.SmartControl: Internal service binding...
09-09 13:41:38.304  7640  7640 D HealthService: Received start request. Starting profile...
09-09 13:41:38.305  7640  7640 I bluedroid-qcom: get_profile_interface health
09-09 13:41:38.305  7640  7640 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 13:41:38.306  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.306  7671  7686 I UEI.SmartControl: ------ IControl API: 19
09-09 13:41:38.306  7640  7640 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 13:41:38.307  7671  7686 I UEI.SmartControl: Registering Services Ready callback...
,09-09 13:41:38.308  7640  7640 D PanService: Received start request. Starting profile...
09-09 13:41:38.308  7640  7640 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:41:38.308  7640  7640 I bluedroid-qcom: get_profile_interface pan
09-09 13:41:38.310  7671  7741 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 13:41:38.315  7640  7640 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 13:41:38.315  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.316  7640  7640 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 13:41:38.319  7640  7640 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:41:38.319  7640  7640 D BtGatt.GattService: Received start request. Starting profile...
,09-09 13:41:38.319  7640  7640 D BtGatt.GattService: start()
09-09 13:41:38.319  7640  7640 I bluedroid-qcom: get_profile_interface gatt
09-09 13:41:38.320  7640  7640 D BtGatt.AdvertiseManager: advertise manager created
09-09 13:41:38.324  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.324  7671  7740 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:41:38.325  7640  7640 D HeadsetStateMachine: Proxy object connected
09-09 13:41:38.325  7071  7087 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 13:41:38.325  7671  7740 D UEI.SmartControl: -----service ready thread exits
09-09 13:41:38.325  7640  7640 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,09-09 13:41:38.326  7640  7640 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 13:41:38.326  7071  7130 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 13:41:38.326  7071  7130 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-09 13:41:38.326  7071  7071 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-09 13:41:38.326  7071  7071 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 13:41:38.326  7671  7687 I UEI.SmartControl: ------ IControl API: 8
09-09 13:41:38.327  7071  7071 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 13:41:38.327  7071  7071 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 13:41:38.327  7071  7071 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 13:41:38.328  7071  7071 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 13:41:38.328  7071  7071 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 13:41:38.329  7071  7071 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 13:41:38.329  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.329  7640  7640 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 13:41:38.331  7640  7640 V BluetoothMapService: BluetoothMapBinder()
09-09 13:41:38.331  7071  7071 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-09 13:41:38.332  7640  7640 D BluetoothMapService: Received start request. Starting profile...
09-09 13:41:38.332  7640  7640 D BluetoothMapService: start()
09-09 13:41:38.332  7071  7071 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 13:41:38.332  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 13:41:38.333  7071  7071 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:41:38.333  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 13:41:38.334  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 13:41:38.334  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 13:41:38.334  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-09 13:41:38.335  7071  7071 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473421298334]
,09-09 13:41:38.335  7640  7640 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 13:41:38.335  7640  7640 D BluetoothMapEmailAppObserver: createReceiver()
09-09 13:41:38.338  7640  7640 D BluetoothMapEmailAppObserver: initObservers()
09-09 13:41:38.338  7640  7640 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 13:41:38.346  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:38.349  7640  7728 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-09 13:41:38.350  7640  7728 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:41:38.351  7640  7728 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 13:41:38.353  7640  7640 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 13:41:38.356  7640  7640 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 13:41:38.361  7640  7640 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 13:41:38.366  7640  7640 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:38.367  7071  7751 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
09-09 13:41:38.370  7640  7640 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 13:41:38.371  7071  7071 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-09 13:41:38.372  7071  7071 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:41:38.372  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 13:41:38.372  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 13:41:38.373  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 13:41:38.373  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 13:41:38.373  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 13:41:38.374  7640  7640 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 13:41:38.375  7640  7640 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 13:41:38.375  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 13:41:38.380  7640  7640 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 13:41:38.380  7640  7640 V BluetoothMapService: Handler(): got msg=1
09-09 13:41:38.381  7640  7640 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:41:38.381  7640  7640 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:41:38.381  7640  7640 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:41:38.381  7640  7715 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 13:41:38.381  7640  7715 I bluedroid-qcom: enable
09-09 13:41:38.381  7640  7640 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:38.382  7640  7640 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 13:41:38.382  7640  7715 I bt_hci_bdroid: init
09-09 13:41:38.382  7640  7752 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 13:41:38.382  7640  7752 I bt-btu  : btu_task pending for preload complete event
09-09 13:41:38.383  7640  7715 I bt_vendor: bt-vendor : init
09-09 13:41:38.383  7640  7715 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 13:41:38.383  7640  7715 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 13:41:38.383  7640  7715 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 13:41:38.383  7640  7715 D bt_userial_mct: userial_init
09-09 13:41:38.383  7640  7715 D bt_hci_bdroid: set_power 1
09-09 13:41:38.383  7640  7715 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 13:41:38.383  7640  7715 I bt_vendor: Starting hciattach daemon
09-09 13:41:38.383  7640  7715 I bt_vendor: try to set true
09-09 13:41:38.381  7755  7755 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:38.381  7755  7755 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 13:41:38.411  7756  7756 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 13:41:38.531  7762  7762 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 13:41:38.559  7763  7763 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:41:38.589  7765  7765 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 13:41:38.604  7766  7766 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 13:41:38.620  7767  7767 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 13:41:38.636  7768  7768 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 13:41:38.671  7773  7773 I libmdmdetect: ESOC framework not supported
,09-09 13:41:38.672  7773  7773 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 13:41:38.684  7773  7773 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-09 13:41:38.684  7773  7773 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-09 13:41:38.684  7773  7773 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 13:41:38.684  7773  7773 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 13:41:38.684  7773  7773 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 13:41:38.684  7773  7773 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 13:41:38.684  7773  7773 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-09 13:41:38.728  7773  7774 E QC-QMI  : qmi_client [7773] 14: failed to locate client data
,09-09 13:41:38.729   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 13:41:38.729   483   483 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-09 13:41:38.762  7781  7781 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 13:41:38.778  7782  7782 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:41:38.839  7640  7715 I bt_vendor: bluetooth satus is on
,09-09 13:41:38.839  7640  7715 D bt_hci_bdroid: preload
,09-09 13:41:38.843  7640  7754 D bt_userial_mct: userial_open(port:0)
,09-09 13:41:38.843  7640  7754 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-09 13:41:38.848  7640  7754 I bt_vendor: Done intiailizing UART
,09-09 13:41:38.850  7640  7754 I bt_vendor: Done intiailizing UART
09-09 13:41:38.850  7640  7754 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 13:41:38.850  7640  7754 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 13:41:38.852  7640  7752 I bt-btu  : btu_task received preload complete event
,09-09 13:41:38.853  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 13:41:38.853  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 13:41:38.857  7640  7784 D bt_userial_mct: Entering userial_read_thread()
,09-09 13:41:38.869  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_BNEP,
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_BTM,
,09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_GAP,
,09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_PAN,
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 13:41:38.872  7640  7752 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 13:41:38.986  7640  7752 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-09 13:41:38.986  7640  7752 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e9061 
09-09 13:41:38.986  7640  7752 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e9061 
,09-09 13:41:39.023  7640  7723 E bt-btif : Calling BTA_HhEnable
09-09 13:41:39.023  7640  7723 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 13:41:39.024  7640  7723 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 13:41:39.026  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 13:41:39.026  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 13:41:39.026  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 13:41:39.028  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 13:41:39.028  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 13:41:39.029  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-09 13:41:39.029  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 13:41:39.029  7640  7723 D BluetoothAdapterProperties: Name is: G3
09-09 13:41:39.030  7640  7723 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:39.031  7640  7723 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:41:39.031  7640  7723 D bt_hci_bdroid: postload
09-09 13:41:39.031  7640  7754 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 13:41:39.032  7640  7723 D bte_conf: Device ID record 1 : primary
09-09 13:41:39.032  7640  7723 D bte_conf:   vendorId            = 00c4
09-09 13:41:39.032  7640  7723 D bte_conf:   vendorIdSource      = 0001
09-09 13:41:39.032  7640  7723 D bte_conf:   product             = 13a1
09-09 13:41:39.032  7640  7723 D bte_conf:   version             = 1000
09-09 13:41:39.032  7640  7723 D bte_conf:   clientExecutableURL = 
09-09 13:41:39.032  7640  7723 D bte_conf:   serviceDescription  = 
09-09 13:41:39.032  7640  7723 D bte_conf:   documentationURL    = 
09-09 13:41:39.032  7640  7723 D bte_conf: bte_load_did_conf no section named DID2.
09-09 13:41:39.033  7640  7752 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 13:41:39.036  7640  7754 D bt_hci_bdroid: Used up Tx Cmd credits
,09-09 13:41:39.040  7640  7754 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 13:41:39.041  7640  7715 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 13:41:39.041  7640  7715 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:41:39.041  7640  7715 D BluetoothAdapterProperties: State =  11
09-09 13:41:39.042  7640  7715 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 13:41:39.042  7640  7715 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 13:41:39.042  7640  7715 D BluetoothAdapterProperties: Setting state to 12
,09-09 13:41:39.042  7640  7715 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 13:41:39.043  7640  7723 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 13:41:39.043  7640  7723 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 13:41:39.041  7786  7786 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 13:41:39.051  7786  7786 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:39.066  1034  1116 D BluetoothManagerService: Message: 60
09-09 13:41:39.066  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 13:41:39.066  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-09 13:41:39.066  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:41:39.069  7640  7752 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:41:39.070  7640  7752 W bt-smp  : Plain text(LSB ~ MSB) = f1 12 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:41:39.070  7640  7752 W bt-smp  : Encrypted text(LSB ~ MSB) = 13 52 9f 4b 7f b7 62 07 85 b0 7b 44 b7 a2 b1 81 
09-09 13:41:39.070  7640  7754 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 13:41:39.070  7640  7752 W bt-btm  : Stopping oneshot timer
09-09 13:41:39.071  7640  7715 I BluetoothAdapterState: Entering On State
09-09 13:41:39.075  7640  7715 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 13:41:39.075  7640  7715 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 13:41:39.075  7640  7715 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 13:41:39.078  7640  7715 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-09 13:41:39.082  7640  7784 E bt_mct  : hci lib postload completed
09-09 13:41:39.085  1034  1034 D BluetoothA2dp: Proxy object connected
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:39.087  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:39.106  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:39.110  7640  7723 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:41:39.110  7640  7723 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 13:41:39.116  7640  7752 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:41:39.117  7640  7752 W bt-smp  : Plain text(LSB ~ MSB) = d1 e5 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:41:39.117  7640  7752 W bt-smp  : Encrypted text(LSB ~ MSB) = dd a9 ae b3 f5 3f 54 fc 66 12 d6 d9 dc 4d 03 80 
09-09 13:41:39.117  7640  7752 W bt-btm  : Stopping oneshot timer
09-09 13:41:39.122  7640  7715 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:39.126  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:39.130  7640  7752 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:41:39.130  7640  7752 W bt-smp  : Plain text(LSB ~ MSB) = df 4f 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:41:39.130  7640  7752 W bt-smp  : Encrypted text(LSB ~ MSB) = 55 d6 6e ed aa a6 a8 a6 e9 cc 5e 40 19 8b a5 f3 
09-09 13:41:39.131  7640  7752 W bt-btm  : Stopping oneshot timer
09-09 13:41:39.137  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:39.140  7640  7752 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:41:39.140  7640  7752 W bt-smp  : Plain text(LSB ~ MSB) = 6b 3c 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-09 13:41:39.140  7640  7752 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 d4 ad f4 8a c5 a5 bb fa a0 61 bf 98 dc 50 80 
09-09 13:41:39.141  7640  7752 W bt-btm  : Stopping oneshot timer
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:39.154  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:39.164  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:39.165  7053  7069 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:41:39.168  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:41:39.170  7640  7752 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:41:39.170  7640  7752 W bt-smp  : Plain text(LSB ~ MSB) = d9 ff 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:41:39.170  7640  7752 W bt-smp  : Encrypted text(LSB ~ MSB) = fd 9a 37 9c e1 9f 36 dd 32 a6 9c 11 84 4d 53 7d 
,09-09 13:41:39.172  7640  7752 W bt-btm  : Stopping oneshot timer
09-09 13:41:39.173  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:41:39.174  7053  7068 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:41:39.176  1877  1877 D BluetoothHeadset: Proxy object connected
09-09 13:41:39.177  1034  1034 D BluetoothHeadset: Proxy object connected
09-09 13:41:39.183  7053  7068 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:41:39.183  7053  7068 D BluetoothPan: onBluetoothStateChange call bindService
,09-09 13:41:39.186  7053  7053 D BluetoothInputDevice: Proxy object connected
09-09 13:41:39.186  7053  7053 D HidProfile: Bluetooth service connected
09-09 13:41:39.188  7053  7053 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:39.189  1877  4685 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:41:39.189  7053  7053 D PanProfile: Bluetooth service connected
09-09 13:41:39.191  1877  1877 D BluetoothHeadset: Proxy object connected
09-09 13:41:39.192  7053  7069 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:41:39.192  7807  7807 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-09 13:41:39.196  7053  7053 D BluetoothMap: Proxy object connected
09-09 13:41:39.196  7053  7053 D MapProfile: Bluetooth service connected
,09-09 13:41:39.196  7053  7053 D BluetoothMap: getConnectedDevices()
09-09 13:41:39.196  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:41:39.197  7640  7656 V BluetoothMapService: getConnectedDevices()
09-09 13:41:39.200  1877  1877 D BluetoothHeadset: Proxy object connected
09-09 13:41:39.201  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 13:41:39.201  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-09 13:41:39.203  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-09 13:41:39.203  1034  1116 D BluetoothManagerService: Message: 40
09-09 13:41:39.203  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 13:41:39.204  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 13:41:39.207  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.208  1965  2174 D LGBluetoothAPIService: Message: 1
09-09 13:41:39.208  1965  2174 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,09-09 13:41:39.209  7640  7640 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.209  7640  7640 D BluetoothMapService: STATE_ON
09-09 13:41:39.213  6740  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 13:41:39.216  1965  2174 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-09 13:41:39.217  7053  7053 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 13:41:39.220  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:39.222  1034  1116 D BluetoothManagerService: Message: 30
09-09 13:41:39.223  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.225  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.225  7053  7053 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 13:41:39.227  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:39.228  7640  7640 V BluetoothPbapService: Pbap Service onCreate
09-09 13:41:39.228  7640  7640 V BluetoothPbapService: Starting PBAP service
09-09 13:41:39.229  7640  7640 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 13:41:39.229  1034  1116 D BluetoothManagerService: Message: 30
09-09 13:41:39.230  7640  7640 V BluetoothPbapService: Pbap Service onBind
09-09 13:41:39.231  7640  7640 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.231  7640  7640 V BluetoothPbapService: state: 12
09-09 13:41:39.232  7640  7640 V BluetoothMapService: Handler(): got msg=1
,09-09 13:41:39.234  7640  7640 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 13:41:39.236  7053  7053 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-09 13:41:39.236  7640  7812 D BluetoothMapMasInstance: MAS initSocket()
09-09 13:41:39.237  7640  7812 D BluetoothMapMasInstance:   masId = 00
09-09 13:41:39.237  7640  7812 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 13:41:39.237  7640  7812 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 13:41:39.237  7640  7812 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 13:41:39.237  7053  7053 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:41:39.239  7640  7640 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 13:41:39.239  7640  7640 D LGBluetoothAPIServer: [BTUI] onBind()
09-09 13:41:39.241  1034  1750 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:39.241  7640  7640 V BluetoothPbapService: Handler(): got msg=1
09-09 13:41:39.241  7053  7053 D BluetoothA2dp: Proxy object connected
09-09 13:41:39.242  7053  7053 D A2dpProfile: Bluetooth service connected
09-09 13:41:39.243  1965  1965 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 13:41:39.243  1965  2174 D LGBluetoothAPIService: Message: 100
09-09 13:41:39.243  1965  2174 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-09 13:41:39.244  7053  7053 D BluetoothHeadset: Proxy object connected
09-09 13:41:39.245  7640  7812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:39.243  7640  7640 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 13:41:39.245  7053  7053 D HeadsetProfile: Bluetooth service connected
09-09 13:41:39.246  7640  7640 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:41:39.246  7640  7640 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.246  7640  7640 V BluetoothPbapReceiver: ***********state = 12
09-09 13:41:39.246  7640  7813 V BluetoothPbapService: Pbap Service initSocket
09-09 13:41:39.247  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:39.247  7640  7812 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 13:41:39.247  7640  7812 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 13:41:39.248  7640  7812 D BluetoothMapMasInstance: Accepting socket connection...
09-09 13:41:39.248  7640  7723 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:41:39.249  7640  7723 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 13:41:39.250  7053  7053 D BluetoothPbap: Proxy object connected
09-09 13:41:39.250  7053  7053 D PbapServerProfile: Bluetooth service connected
09-09 13:41:39.250  7640  7813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:39.252  7640  7813 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 13:41:39.252  7640  7813 V BluetoothPbapService: Succeed to create listening socket 
09-09 13:41:39.252  7640  7813 V BluetoothPbapService: Accepting socket connection...
09-09 13:41:39.252  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.253  2263  2263 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:41:39.254  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:39.256  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.257  7053  7053 D DockEventReceiver: finishStartingService: stopping service
09-09 13:41:39.257  2263  2263 D c       : Getting all permits...
09-09 13:41:39.257  2263  2263 D a       : Opening database...
09-09 13:41:39.261  2263  2263 D a       : Opening database auth.proximity.permit_store...
09-09 13:41:39.262  2263  2263 D a       : Closing database...
09-09 13:41:39.272  7053  7053 D BluetoothPermissionRequest: onReceive
,09-09 13:41:39.274  7053  7053 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 13:41:39.276  7053  7053 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 13:41:39.280  7640  7640 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-09 13:41:39.281  7640  7640 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-09 13:41:39.288  7640  7640 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-09 13:41:39.321  7640  7640 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-09 13:41:39.321  7640  7640 V BtOppService: onCreate
,09-09 13:41:39.327  7640  7640 V BluetoothOppNotification: send message
09-09 13:41:39.332  7640  7640 V BtOppService: Starting RfcommListener
09-09 13:41:39.348  7640  7640 D BluetoothOppPreference: Dumping Names:  
09-09 13:41:39.348  7640  7640 D BluetoothOppPreference: {}
09-09 13:41:39.349  7640  7640 D BluetoothOppPreference: Dumping Channels:  
09-09 13:41:39.349  7640  7640 D BluetoothOppPreference: {}
,09-09 13:41:39.350  7640  7640 V BtOppService: onStartCommand
,09-09 13:41:39.353  7640  7820 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,09-09 13:41:39.360  7640  7640 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.360  7640  7640 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 13:41:39.362  7640  7817 V BtOppService: Deleted complete outbound shares, number =  0
09-09 13:41:39.363  7640  7640 V BluetoothOppNotification: new notify threadi!
,09-09 13:41:39.364  7640  7640 V BluetoothOppNotification: send delay message
09-09 13:41:39.365  7640  7640 V BtOppService: start RfcommListener
09-09 13:41:39.367  7640  7817 V BtOppService: Deleted complete inbound failed shares, number = 0
,09-09 13:41:39.369  7640  7640 V BtOppService: RfcommListener started
09-09 13:41:39.369  7640  7640 V BtOppService: ContentObserver received notification
,09-09 13:41:39.370  7640  7820 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 13:41:39.372  7640  7822 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 13:41:39.372  7640  7820 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ee89b6a on behalf of 
09-09 13:41:39.372  7640  7817 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 13:41:39.375  1034  2069 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:39.375  7640  7817 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@660a85b on behalf of 
09-09 13:41:39.376  7640  7821 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 13:41:39.377  7640  7822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:39.378  7640  7822 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-09 13:41:39.379  7640  7822 V BtOppRfcommListener: Started RFCOMM listener....
09-09 13:41:39.379  7640  7822 I BtOppRfcommListener: Accept thread started.
09-09 13:41:39.379  7640  7822 V BtOppRfcommListener: Accepting connection...
09-09 13:41:39.381  7640  7821 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bd598f8 on behalf of 
,09-09 13:41:39.386  7640  7821 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 13:41:39.386  7640  7820 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 13:41:39.387  7640  7820 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 13:41:39.388  7640  7821 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 13:41:39.388  7640  7820 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@165de1d1 on behalf of 
09-09 13:41:39.390  7640  7820 V BluetoothOppNotification: update too frequent, put in queue
09-09 13:41:39.390  7640  7821 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@196d0436 on behalf of 
09-09 13:41:39.391  7640  7820 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 13:41:39.391  7640  7821 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-09 13:41:39.393  7640  7821 V BluetoothOppNotification: outbound notification was removed.
09-09 13:41:39.394  7640  7821 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-09 13:41:39.396  7640  7821 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2776f37 on behalf of 
09-09 13:41:39.398  7640  7821 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 13:41:39.398  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:39.398  7640  7640 V BluetoothFtpService: Ftp Service onCreate
09-09 13:41:39.398  7640  7640 I BluetoothFtpService: Ftp Service onCreate
09-09 13:41:39.401  7640  7640 V BluetoothFtpService: Ftp Service onStartCommand
09-09 13:41:39.401  7640  7640 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.401  7640  7640 V BluetoothFtpService: Starting Listening on sockets
09-09 13:41:39.401  7640  7640 V BtOppService: ContentObserver received notification
09-09 13:41:39.402  7640  7821 V BluetoothOppNotification: inbound notification was removed.
09-09 13:41:39.402  7640  7640 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:41:39.402  7640  7821 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 13:41:39.402  7640  7640 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:41:39.402  7640  7640 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:41:39.402  7640  7640 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.403  7640  7823 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 13:41:39.403  7640  7823 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 13:41:39.403  7640  7640 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 13:41:39.403  7640  7640 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 13:41:39.404  7640  7823 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e8dca0d on behalf of 
09-09 13:41:39.405  7640  7821 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28fd2dc2 on behalf of 
09-09 13:41:39.405  7640  7823 V BluetoothOppNotification: update too frequent, put in queue
09-09 13:41:39.407  7640  7640 V BluetoothFtpService: Handler(): got msg=1
,09-09 13:41:39.408  7640  7640 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,09-09 13:41:39.408  7640  7640 V BluetoothFtpService: Ftp Service initSocket
09-09 13:41:39.411  1034  2069 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:39.412  7640  7823 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 13:41:39.412  7640  7640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:39.417  7640  7640 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-09 13:41:39.419  7640  7824 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-09 13:41:39.435  7640  7640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284a5c49
09-09 13:41:39.435  7640  7640 V BluetoothSapService: Sap Service onCreate
,09-09 13:41:39.437  7640  7640 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:39.437  7640  7640 V BluetoothSapService: state: 12
09-09 13:41:39.438  7640  7640 V BluetoothSapService: Starting SAP server process
09-09 13:41:39.431  7825  7825 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:39.439  7640  7640 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 13:41:39.431  7825  7825 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:39.441  7640  7826 V BluetoothSapService: Sap Service initRfcommSocket
09-09 13:41:39.442  1034  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:39.443  7640  7826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:39.445  7640  7826 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-09 13:41:39.445  7640  7826 V BluetoothSapService: Succeed to create listening socket 
09-09 13:41:39.445  7640  7826 V BluetoothSapService: Accepting socket connection...
09-09 13:41:39.445  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.445  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:39.446  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:39.446  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:39.446  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:39.446  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d32261 removed from the list
09-09 13:41:39.446  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:39.446  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23656186 removed from the list
09-09 13:41:39.446  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:39.446  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:39.447  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:39.447  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17e7b274 added. We now have 3 listener(s)
09-09 13:41:39.448  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:41:39.452  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:39.452  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:39.452  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:39.453  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:39.453  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fbe839d added. We now have 3 listener(s)
09-09 13:41:39.453  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:39.453  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:39.456  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:39.458  7825  7825 V BT_SAP  : Event pipe created
09-09 13:41:39.459  7825  7825 V BT_SAP  : create_server_socket qcom.sap.server
09-09 13:41:39.459  7825  7825 V BT_SAP  : created socket fd 6
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:39.462  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:39.464  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:39.465  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:39.466  1034  1750 D WifiServiceImplEx: setWifiEnabled: false pid=6740, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:41:39.466  1034  1750 D WifiService: setWifiEnabled: false pid=6740, uid=10118
09-09 13:41:39.466  1034  1750 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 13:41:39.470  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.472  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:39.481  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:39.481  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:39.481  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-09 13:41:39.482  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:39.483  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:39.484  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:39.484  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:39.486  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:41:39.486  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:41:39.486  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:39.486  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:41:39.487  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:41:39.487  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:41:39.496  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:41:39.496  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.497  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.497  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:41:39.497  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:41:39.498  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:41:39.498  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:41:39.499  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
,09-09 13:41:39.500  1034  7177 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.505   305   891 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:39.552  1034  1050 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-09 13:41:39.552  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.552  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.552  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:39.553  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.553  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-09 13:41:39.566  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:41:39.566  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-09 13:41:39.568  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:39.569  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:39.569  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:39.569  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:41:39.570  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:39.570  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:39.570  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 13:41:39.577  1034  1535 D LGWifiP2pService: InactiveState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.577  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.577  1034  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@6ff46e9
09-09 13:41:39.579  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:39.579  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:39.579  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.579  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:39.579  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.579  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:39.580  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:39.581  1965  1965 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 13:41:39.585  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.585  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.585  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:39.585  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:41:39.585  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:39.586  1034  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.586  1034  1555 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.587  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:39.590  1034  1535 D LGWifiP2pService: P2pDisablingState
09-09 13:41:39.590  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:39.591  1034  1535 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.591  1034  1535 D LGWifiP2pService: p2p socket connection lost
09-09 13:41:39.591  1034  1535 D LGWifiP2pService: P2pDisabledState
09-09 13:41:39.592  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:41:39.592  1965  1965 D WfdsService: WifiP2pState is changed : false
09-09 13:41:39.592  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:39.592  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:39.593  1965  2351 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:41:39.593  1965  2351 D WfdsService: Set the WFDS Monitor: false
09-09 13:41:39.593  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 13:41:39.594  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:41:39.594  7134  7134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:41:39.594  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.594  1034  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.594  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:39.594  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:41:39.595  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:41:39.596  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:41:39.596  1965  2351 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:41:39.596  1965  2351 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:41:39.596  1965  7152 D CtrlSupplicant: Received on exit socket, terminate
09-09 13:41:39.596  1965  7152 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:41:39.596  1965  7152 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:41:39.596  1965  7152 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 13:41:39.596  1965  2352 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:41:39.597  1965  2351 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 13:41:39.625  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:41:39.625  1034  1543 D DSQN    : disableDataServiceNotify
09-09 13:41:39.625  1034  1543 D DSQN    : stop dsqn bin
09-09 13:41:39.625   305   891 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:39.627   305  7833 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 13:41:39.628  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-09 13:41:39.629  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 13:41:39.632  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:39.632  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:39.632  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:39.633  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:39.633  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:39.633  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:39.633  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.633  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.633  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:41:39.634  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:41:39.634  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:41:39.634  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:39.641  1034  1050 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:41:39.644  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 13:41:39.645  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.645  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:39.645  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
09-09 13:41:39.645  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:39.645  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:39.645  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:41:39.645  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.646  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:39.646  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:39.646  1034  1543 D NetworkManagementService: Removing idletimer
09-09 13:41:39.646  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.646  1034  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 13:41:39.648  1877  1877 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:39.648  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:41:39.649  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:39.649  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.649  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.649  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:39.649  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:39.649  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:39.649  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:39.650  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:39.650  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:39.650  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:39.650  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:39.650  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:39.650  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:39.650  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:39.651  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:39.651  1034  1537 D WIFI    :   my score=60, my, filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:39.651  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:41:39.651  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:39.652  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:39.653  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-09 13:41:39.657  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 13:41:39.657  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:39.658  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:39.659  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:39.661  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:39.664  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:39.668  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:39.671  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:39.673  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:39.677  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:39.678  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:39.679  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:39.701  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:39.702  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:39.702  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:39.703  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:39.706  7134  7134 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 13:41:39.706  7134  7134 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:41:39.706  7134  7134 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1965-4\x00 that cannot receive messages
09-09 13:41:39.707  1034  7148 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 13:41:39.707  1034  7148 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 13:41:39.714  1034  7177 D DhcpStateMachine: StoppedState
09-09 13:41:39.714  1034  7177 D DhcpStateMachine: StoppedState{ when=-119ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.715  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 13:41:39.716  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 13:41:39.740  7134  7134 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:41:39.741  1034  1116 D Tethering: InitialState.processMessage what=4
09-09 13:41:39.741  7134  7134 W wpa_supplicant: USIM:  scard_deinit function
09-09 13:41:39.741  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 13:41:39.742  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:41:39.742  1034  7148 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:41:39.742  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:39.743  1034  7148 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 13:41:39.743  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:39.743  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:39.744  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=141217
09-09 13:41:39.745  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=141218
09-09 13:41:39.747  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=141220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 13:41:39.747  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=141220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 13:41:39.748  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:39.749  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:39.755  7834  7834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:41:39.762  7834  7834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:39.762  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:39.767  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:39.773  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:39.780  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:39.781  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:41:39.783  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:39.786  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:39.789  7834  7834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:39.789  7834  7834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:39.789  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:39.793  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:39.802  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:39.806  7134  7134 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 13:41:39.807  1034  7148 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 13:41:39.807  1034  7148 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 13:41:39.807  1034  7148 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 13:41:39.809  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-09 13:41:39.812  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:39.813  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:39.814  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:39.818  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:41:39.823  7834  7834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:39.823  7834  7834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:39.823  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:39.828  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:39.838  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:39.847  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:39.848  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:39.850  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:39.865  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:39.869  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:39.881  7096  7855 W FormManager: Network not available. Please check & try again.
,09-09 13:41:39.888  7096  7856 V FormManager: Network unavailable.
,09-09 13:41:39.890  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:39.902  7096  7856 V FormManager: Network unavailable.
,09-09 13:41:39.909  1034  1984 I ActivityManager: Killing 7256:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-09 13:41:39.949  1034  1945 W libprocessgroup: failed to open /acct/uid_10011/pid_7256/cgroup.procs: No such file or directory
,09-09 13:41:39.957  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 13:41:39.957  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:39.957  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:39.957  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:41:39.958  1965  1965 D WfdsService: Supplicant Connection state is changed : false
09-09 13:41:39.958  1965  2351 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 13:41:39.958  1965  2351 D WfdsService: Set the WFDS Monitor: false
09-09 13:41:39.958  1965  2351 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:41:39.963  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:39.964  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,09-09 13:41:39.964  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 13:41:39.964  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:41:39.966  2497  2497 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.967  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:41:39.978  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:39.979  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.981  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:39.981  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:41:39.981  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:41:39.981  7053  7053 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:41:39.983  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.984  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:41:39.986  7053  7053 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:41:39.986  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 13:41:39.986  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:39.986  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:41:39.987  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:41:39.987  7053  7053 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:41:39.987  7053  7053 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:41:39.993  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-09 13:41:39.994  1034  2023 D WifiServiceImplEx: setWifiEnabled: true pid=6740, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:41:39.994  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:39.994  1034  2023 D WifiService: setWifiEnabled: true pid=6740, uid=10118
09-09 13:41:39.994  1034  2023 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 13:41:39.999  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:40.003  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:40.007  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:40.007  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:40.007  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-09 13:41:40.015  4799  7859 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:40.017  7834  7834 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:41:40.017  7834  7834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:40.017  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:40.021  4799  7860 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:40.021  4799  7860 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 13:41:40.023  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:40.030  7096  7862 W FormManager: Network not available. Please check & try again.
09-09 13:41:40.032  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:40.042  7096  7863 V FormManager: Network unavailable.
,09-09 13:41:40.048  7096  7863 V FormManager: Network unavailable.
,09-09 13:41:40.148  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 13:41:40.157  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:41:40.162  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 13:41:40.162  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-09 13:41:40.165  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 13:41:40.165  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:41:40.165  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 13:41:40.165  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:41:40.166  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 13:41:40.166  1034  1537 E WifiHW  : unknown target_country: EU , set to default
09-09 13:41:40.166  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 13:41:40.166  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 13:41:40.166  1034  1537 I WifiUtil: gEnableBmps=1
,09-09 13:41:40.191  1034  1463 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:41:40.208  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 13:41:40.217  1034  1034 D administrator: Handling package changes for user 0
09-09 13:41:40.225  1034  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7864 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 13:41:40.227  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 13:41:40.228  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 13:41:40.241   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 356us total 17.128ms
,09-09 13:41:40.258   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 281us total 15.476ms
,09-09 13:41:40.271   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 279us total 13.041ms
,09-09 13:41:40.287  7864  7864 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:40.352  7864  7864 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:40.352  7864  7864 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:40.357  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 13:41:40.357  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:41:40.365  7640  7640 V BluetoothOppNotification: new notify threadi!
09-09 13:41:40.365  7640  7640 V BluetoothOppNotification: send delay message
09-09 13:41:40.366  7640  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-09 13:41:40.374  7640  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1774640e on behalf of 
09-09 13:41:40.374  7640  7881 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-09 13:41:40.375  7640  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 13:41:40.376  7640  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23df0e2f on behalf of 
09-09 13:41:40.376  7640  7881 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 13:41:40.377  7640  7881 V BluetoothOppNotification: outbound notification was removed.
09-09 13:41:40.377  7640  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 13:41:40.378  7640  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23a58c3c on behalf of 
09-09 13:41:40.378  7640  7881 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 13:41:40.379  7640  7881 V BluetoothOppNotification: inbound notification was removed.
09-09 13:41:40.379  7640  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 13:41:40.380  7640  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@109f2dc5 on behalf of 
09-09 13:41:40.407  1034  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:40.413  1034  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 13:41:40.420  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-09 13:41:40.421  2497  2497 V GmsNetworkLocationProvi: DISABLE
,09-09 13:41:40.457  2497  2497 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-09 13:41:40.457  1034  1089 D LocationProviderProxy: applying state to connected service
09-09 13:41:40.475  7864  7892 I Babel   : MmsConfig: mnc/mcc: 0/0
09-09 13:41:40.475  7864  7892 I Babel   : MmsConfig.loadMmsSettings
,09-09 13:41:40.478  7864  7892 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 13:41:40.478  7864  7892 I Babel   : MmsConfig.loadFromDatabase
,09-09 13:41:40.502  7864  7892 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-09 13:41:40.502  7864  7892 I Babel   : MmsConfig.loadFromResources
09-09 13:41:40.509  7864  7892 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 13:41:40.511  7864  7864 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:40.511  7864  7892 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-09 13:41:40.532  1841  7895 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 13:41:40.532  1841  7895 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-09 13:41:40.539  7864  7891 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:41:40.541  7864  7891 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:40.544  7864  7891 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:40.553  7864  7891 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-09 13:41:40.554  7864  7891 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:40.555  7864  7891 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:41:40.562  7864  7891 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-09 13:41:40.564  7864  7891 W VideoCapabilities: Unsupported mime video/divx
,09-09 13:41:40.565  7864  7891 W VideoCapabilities: Unsupported mime video/divx311
09-09 13:41:40.567  7864  7891 W VideoCapabilities: Unsupported mime video/divx4
09-09 13:41:40.573  1034  2023 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7898 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-09 13:41:40.573  7864  7891 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-09 13:41:40.579  1034  2023 I ActivityManager: Killing 6589:com.lge.email/u0a23 (adj 15): empty #17
,09-09 13:41:40.590  7864  7891 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-09 13:41:40.593  7864  7891 W AudioCapabilities: Unsupported mime audio/eac3
09-09 13:41:40.593  7864  7891 W AudioCapabilities: Unsupported mime audio/ac3
,09-09 13:41:40.594  7864  7891 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:41:40.595  7864  7891 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:41:40.596  7864  7891 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 13:41:40.597  7864  7891 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:41:40.599  7864  7891 W VideoCapabilities: Unsupported mime video/theora
09-09 13:41:40.600  1841  5259 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-09 13:41:40.606  7864  7891 W VideoCapabilities: Unsupported mime video/mjpg
,09-09 13:41:40.683  1034  1984 W libprocessgroup: failed to open /acct/uid_10023/pid_6589/cgroup.procs: No such file or directory
,09-09 13:41:40.705  7898  7898 I AppUp4:AppBoxCP: onCreate
09-09 13:41:40.707  7898  7898 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:41:40.713  7898  7898 I AppUp4:DB:  setFingerPrint start
09-09 13:41:40.713  7898  7898 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-09 13:41:40.719  7898  7898 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-09 13:41:40.719  7898  7898 I AppUp4:DB:  SDK version = 21
09-09 13:41:40.719  7898  7898 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:41:40.721  7898  7898 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:41:40.726  7898  7898 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:40.747  7898  7898 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:40.747  7898  7898 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:40.751  7898  7898 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a11be4
,09-09 13:41:40.751  7898  7898 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:40.751  7898  7898 D AppUp4:CustFacade: isPhone : true
09-09 13:41:40.751  7898  7898 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:40.752  7898  7898 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 13:41:40.802  1034  1762 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7924 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-09 13:41:40.803  1034  1762 I ActivityManager: Killing 7317:com.android.chrome/u0a57 (adj 15): empty #17
,09-09 13:41:40.888  1034  1050 W libprocessgroup: failed to open /acct/uid_10057/pid_7317/cgroup.procs: No such file or directory
,09-09 13:41:40.917  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:41:40.921  1034  1116 D Tethering: InitialState.processMessage what=4
09-09 13:41:40.921  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:40.922   305   891 D SoftapController: Softap fwReload - Ok
09-09 13:41:40.923  1034  1537 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (720ms)
09-09 13:41:40.927   305   891 D CommandListener: Setting iface cfg
09-09 13:41:40.927   305   891 D CommandListener: Trying to bring down wlan0
09-09 13:41:40.929   305   891 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:40.934  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 13:41:40.936  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:40.936  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:40.936  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 13:41:40.938  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:41:40.941  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:40.931  7942  7942 W wpa_supplicant: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:40.931  7942  7942 W wpa_supplicant: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:40.944  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:40.945  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:41:40.945  1034  1537 D WifiMonitor: connecting to supplicant
09-09 13:41:40.945  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-09 13:41:40.946  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:40.947  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:40.957  7924  7924 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:40.957  7924  7924 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:40.957  7924  7924 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:41:40.960  7924  7924 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 13:41:40.961  7924  7924 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-09 13:41:40.967  7942  7942 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:41:41.000  7942  7942 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:41.000  7942  7942 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-09 13:41:41.020  7924  7924 I SystemConfig: BUILD Country: EU
09-09 13:41:41.020  7924  7924 I SystemConfig: BUILD Operator: OPEN
,09-09 13:41:41.063  1034  2038 I ActivityManager: Killing 7359:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-09 13:41:41.088  7942  7942 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:41.118  7942  7942 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 13:41:41.124  7942  7942 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-09 13:41:41.126  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 13:41:41.127  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 13:41:41.128  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:41:41.129  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:41:41.130  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3537] from screen [on:0 period:247518602] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:41.132  1034  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:247518604] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:41.133  1034  1984 W libprocessgroup: failed to open /acct/uid_10062/pid_7359/cgroup.procs: No such file or directory
09-09 13:41:41.137  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:41.137  7942  7942 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-09 13:41:41.138  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:41.140  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:41.140  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:41.141  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 13:41:41.141  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 13:41:41.142  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 13:41:41.142  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 13:41:41.142  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:41:41.143  7924  7943 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 13:41:41.143  7924  7943 I SystemConfig: existFile = false
09-09 13:41:41.143  7924  7943 I SystemConfig: canReadFile = false
09-09 13:41:41.145  7924  7943 I SystemConfig: systemFeature RCS result false
09-09 13:41:41.147  1034  7945 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 13:41:41.147  1034  7945 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 13:41:41.147  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,09-09 13:41:41.147  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 13:41:41.147  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 13:41:41.147  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 13:41:41.147  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:41:41.148  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:41:41.148  7924  7943 D SystemConfig: refreshRcsSupport() :false
,09-09 13:41:41.185  1034  2038 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7946 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
09-09 13:41:41.186  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:41:41.186  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:41:41.186  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:41:41.186  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.186  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.186  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.186  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.186  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:41.187  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 13:41:41.187  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
09-09 13:41:41.187  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:41:41.187  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 13:41:41.187  1965  1965 D WfdService: Waiting for WifiP2p enabling
09-09 13:41:41.188  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 13:41:41.189  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:41.191  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:41:41.191  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:41.194  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:41.196  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:41.197  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network:, false
09-09 13:41:41.199  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:41.201  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:41.204  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:41.206  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:41.210  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-09 13:41:41.211  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:41:41.212  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
09-09 13:41:41.212  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 13:41:41.213  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 13:41:41.213  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 13:41:41.214  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 13:41:41.214  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,09-09 13:41:41.215  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 13:41:41.215  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 13:41:41.216  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 13:41:41.216  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 13:41:41.216  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 13:41:41.216  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 13:41:41.217  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 13:41:41.217  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 13:41:41.217  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 13:41:41.218  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:41.218  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 13:41:41.218  1965  1965 D WfdsService: Supplicant Connection state is changed : true
09-09 13:41:41.218  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 13:41:41.218  1034  1537 D WifiNative-HAL: Setting external_sim to 1
09-09 13:41:41.218  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 13:41:41.218  1965  2351 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 13:41:41.218  1965  2351 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:41.218  1965  2351 D WfdsMonitor: WfdsMonitorThread create
09-09 13:41:41.218  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 13:41:41.218  1034  1537 I WifiNative-HAL: startHal
09-09 13:41:41.219  1034  1537 D wifi    : setting scan oui 0x957d9680
09-09 13:41:41.219  1965  2351 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:41:41.219  1965  2351 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:41:41.219  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:41.219  1034  1537 I WifiNative-HAL: startHal
09-09 13:41:41.219  1034  1537 D wifi    : setting scan oui 0x957d9680
09-09 13:41:41.219  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 13:41:41.219  1965  7963 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:41:41.220  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 13:41:41.220  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 13:41:41.220  1965  7963 E CtrlSupplicant: Succeed to open control connection
09-09 13:41:41.220  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 13:41:41.220  1965  7963 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:41:41.220  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 13:41:41.220  1965  7963 D WfdsMonitor: Supplicant connection established
09-09 13:41:41.220  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:41:41.221  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:41:41.221  1965  2351 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:41.221  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:41:41.221  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 13:41:41.221  7864  7864 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.221  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 13:41:41.221  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 13:41:41.221  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:41:41.221  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:41:41.222  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:4,1:41.222  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:41:41.222  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:41:41.222  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:41:41.222  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 13:41:41.222  7942  7942 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 13:41:41.223  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 13:41:41.223  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:41:41.223  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:41:41.223  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:41:41.224  1034  1537 E WifiNative: : [142,696,900 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 13:41:41.224  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 13:41:41.224  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
09-09 13:41:41.224  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-09 13:41:41.225  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:41:41.225  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 13:41:41.226  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 13:41:41.226  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:41:41.226  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:41:41.226  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.228   305   891 D CommandListener: Setting iface cfg
09-09 13:41:41.228   305   891 D CommandListener: Trying to bring up p2p0
09-09 13:41:41.228  1034  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:41.229  1034  1535 D LGWifiP2pService: P2pEnablingState
09-09 13:41:41.229  1034  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.229  1034  1535 D LGWifiP2pService: P2p socket connection successful
09-09 13:41:41.229  1034  1535 D LGWifiP2pService: P2pEnabledState
09-09 13:41:41.229  1034  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 13:41:41.230  1034  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 13:41:41.230  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,09-09 13:41:41.230  1034  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 13:41:41.231  1965  1965 D WfdsService: WifiP2pState is changed : true
09-09 13:41:41.231  1034  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 13:41:41.231  1965  2351 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:41:41.231  1965  2351 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:41.231  1965  2351 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:41.231  1965  2351 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:41:41.231  7942  7942 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:41:41.231  1034  1535 D WifiNative-p2p0: SET device_name G3: returned true
09-09 13:41:41.231  1034  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:41:41.231  1034  1535 D LGWifiP2pService: before postfix = G3
09-09 13:41:41.231  1034  1535 D WifiServerServiceExt: postfix byte check : 2
09-09 13:41:41.232  1034  1535 D LGWifiP2pService: after postfix = G3
09-09 13:41:41.232  1034  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-09 13:41:41.232  1034  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 13:41:41.232  1034  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
,09-09 13:41:41.233  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 13:41:41.233  1034  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 13:41:41.233  1034  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 13:41:41.233  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 13:41:41.233  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 13:41:41.234  1034  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 13:41:41.234  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 13:41:41.234  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 13:41:41.234  1034  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 13:41:41.234  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:41:41.234  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=142707  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:41:41.234  1965  1965 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:41:41.234  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 13:41:41.235  1965  1965 D WfdsService: isConnected: false
09-09 13:41:41.235  1034  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 13:41:41.235  1034  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 13:41:41.235  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:41:41.235  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:41.236  1034  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.236  1034  1554 I WifiNative-HAL: startHal
09-09 13:41:41.236  1034  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.236  1034  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 13:41:41.236  1034  1554 D wifi    : getting scan capabilities on interface[1] = 0x957d9680
09-09 13:41:41.236  1034  1554 D wifi    : failed to get capabilities : -3
09-09 13:41:41.236  1034  1554 E WifiScanningService: could not get scan capabilities
09-09 13:41:41.236  1965  2351 D WfdsService: selectPreferredScanChannel [36]
09-09 13:41:41.236  1965  2351 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 13:41:41.236  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 13:41:41.236  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=142709  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:41:41.236  1034  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 13:41:41.237  1034  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 13:41:41.237  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 13:41:41.238  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 13:41:41.238  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.238  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.238  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:41.238  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 13:41:41.239  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 13:41:41.239  7942  7942 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 13:41:41.239  1034  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 13:41:41.239  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: ,(unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:41.239  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 13:41:41.239  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:41.240  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 13:41:41.240  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:41:41.240  7942  7942 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:41:41.240  1034  1535 D WifiNative-p2p0:    returned OK
09-09 13:41:41.240  1034  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 13:41:41.241  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 13:41:41.241  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 13:41:41.241  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 13:41:41.242  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 13:41:41.242  1965  1965 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 13:41:41.242  1965  1965 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:41:41.242  1965  1965 D WfdsService: Update P2p Interface State: 3
09-09 13:41:41.243  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:41.263  7946  7946 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:41.263  7946  7946 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:41:41.263  7946  7946 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-09 13:41:41.263  7946  7946 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 13:41:41.263  1034  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
,09-09 13:41:41.263  1034  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 13:41:41.264  1034  1535 D LGWifiP2pService: InactiveState
09-09 13:41:41.264  1034  1535 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.264  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.264  1034  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 13:41:41.265  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 13:41:41.265  7942  7942 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.265  1965  7963 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:41:41.266  1034  7945 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:41:41.266  1034  7945 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.266  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.266  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.266  7942  7942 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,09-09 13:41:41.266  7942  7942 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.266  1965  7963 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.266  1034  7945 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.266  1034  7945 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.266  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.266  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.267  7942  7942 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.267  1965  7963 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.267  1034  7945 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.267  1034  7945 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.267  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.267  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.268  1034  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 13:41:41.268  1034  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.268  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.268  1034  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.268  1034  1535 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.268  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.268  1034  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.268  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 13:41:41.268  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:41.268  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.269  1034  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.269  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.269  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.269  7942  7942 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.269  1034  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.269  1034  1034 E WifiServerServiceExt: No p2p device connected
09-09 13:41:41.269  1965  2351 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:41:41.269  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:41:41.269  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.269  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.269  7942  7942 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 13:41:41.269  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:41:41.269  7942  7942 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.270  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 13:41:41.270  7942  7942 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.270  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:41:41.270  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:41:41.271  1034  7945 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.271  1034  7945 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.271  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.271  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.271  1034  7945 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.271  1034  7945 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.271  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:41:41.271  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.271  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 13:41:41.271  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:41:41.271  1965  7963 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.271  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 13:41:41.271  1965  7963 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:41:41.271  7942  7942 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:41.271  1034  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.271  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:41.272  1034  7945 D WifiMonitor: Event [IFNAME=wlan0, CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 13:41:41.272  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:41.272  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 13:41:41.272  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 13:41:41.272  1034  7945 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:41.272  1034  7945 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:41.272  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 13:41:41.272  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
09-09 13:41:41.272  1034  1537 D WifiNative-wlan0: SCAN: returned false
09-09 13:41:41.273  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=142746  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:41:41.274  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=142747  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:41:41.275  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:41.276  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:41.276  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:41.276  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.277  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.277  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:41.277  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:41.277  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:41.277  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:41.277  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:41:41.278  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:41.278  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-09 13:41:41.279  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:41.279  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:41.279  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:41:41.351  7946  7946 I AppConfig: Total System Memory = 2995761152
,09-09 13:41:41.360  7946  7946 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-09 13:41:41.450  1034  2262 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7966 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:41.452  1034  2262 I ActivityManager: Killing 7381:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-09 13:41:41.496  1034  2069 W libprocessgroup: failed to open /acct/uid_10085/pid_7381/cgroup.procs: No such file or directory
,09-09 13:41:41.511  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:41.512  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:41.512  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:41.512  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:41.512  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:41.512  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17e7b274 removed from the list
09-09 13:41:41.512  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:41.513  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fbe839d removed from the list
09-09 13:41:41.513  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:41.513  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:41.524  6740  7983 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 13:41:41.524  6740  7983 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 13:41:41.534  6740  7983 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-09 13:41:41.534  6740  7983 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:41.535  6740  7983 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:41.536  6740  7983 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:41.537  6740  7983 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:41:41.539  6740  7985 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:41:41.539  6740  7985 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:41.542  6740  7985 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:41.543  6740  7988 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 948, name: OutgoingSocketThread/Sender)
09-09 13:41:41.546  6740  7985 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:41.547  6740  7985 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:41:41.551  6740  7989 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 949, name: OutgoingSocketThread/Receiver)
09-09 13:41:41.553  6740  7989 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 949, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:41.553  6740  7989 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:41.554  6740  7989 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 949, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:41:41.555  6740  7990 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 950, name: IncomingSocketThread/Sender)
09-09 13:41:41.558  6740  7991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 951, name: IncomingSocketThread/Receiver)
09-09 13:41:41.558  6740  7991 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 951, thread name: IncomingSocketThread/Receiver)
09-09 13:41:41.558  6740  7991 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:41.559  6740  7991 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 951, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:41:41.732  7966  7966 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-09 13:41:41.788  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 13:41:41.788  7942  7942 E wpa_supplicant: USIM:  scard_init function
09-09 13:41:41.788  1034  7945 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,09-09 13:41:41.788  7942  7942 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 13:41:41.788  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 13:41:41.789  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 13:41:41.789  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 13:41:41.789  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-09 13:41:41.789  1034  7945 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 13:41:41.789  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:41:41.789  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-09 13:41:41.790  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 13:41:41.791  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 13:41:41.791  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 13:41:41.796  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=143270  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 13:41:41.798  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=143271  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 13:41:41.798  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:41.798  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:41.799  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.799  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.799  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:41:41.800  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:41.800  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-09 13:41:41.800  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:41:41.805  1034  1981 I art     : Explicit concurrent mark sweep GC freed 73778(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.370ms total 158.059ms
09-09 13:41:41.816  7966  7966 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:41.816  7966  7966 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:41.856  7966  7966 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-09 13:41:41.868  7966  7966 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-09 13:41:41.868  7966  7966 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 13:41:41.877  7966  7966 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-09 13:41:41.877  7966  7966 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-09 13:41:41.891  1034  1574 I ActivityManager: Killing 7400:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-09 13:41:41.904  7942  7942 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:41:41.905  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,09-09 13:41:41.905  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 13:41:41.905  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 13:41:41.905  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 13:41:41.905  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:41.905  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:41.906  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=143379  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:41:41.906  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=143380  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:41:41.908  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143381
09-09 13:41:41.908  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143381
09-09 13:41:41.908  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143381
09-09 13:41:41.909  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143382
09-09 13:41:41.909  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143382
09-09 13:41:41.909  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=143383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 13:41:41.913  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:41.913  7942  7942 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:41.913  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:41.913  7942  7942 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:41:41.913  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 13:41:41.913  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:41.913  1034  7945 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:41.913  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 13:41:41.914  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:41:41.914  1034  7945 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:41:41.914  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:41.914  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:41.953  1034  1750 W libprocessgroup: failed to open /acct/uid_10093/pid_7400/cgroup.procs: No such file or directory
09-09 13:41:41.953  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:41:41.959  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=143432  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 13:41:41.962  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:41.962  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:41.962  5073  8013 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-09 13:41:41.963  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:41.968  2853  4247 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-09 13:41:41.969  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.970  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.970  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:41:41.971  2853  4247 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@28fd2dc2 on behalf of 7966
09-09 13:41:41.973  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.973  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:41.973  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:41:41.974  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:41.974  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 13:41:41.974  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=143447  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:41:41.975  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=143448  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:41:41.976  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=143449
09-09 13:41:41.977  1034  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=143450
09-09 13:41:41.977  1034  1537 D WifiNative-wlan0: doString: [STATUS]
09-09 13:41:41.978  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-09 13:41:41.980  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:41:41.981  1034  7945 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:41:41.982  1034  7945 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:41:41.988  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:41.988  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:41.990  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:42.023  1034  2069 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8014 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:42.027  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 13:41:42.027  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 13:41:42.034  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.034  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.034  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:41:42.034  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.034  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:42.037  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:42.046  6740  6808 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 13:41:42.047  6740  6808 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:41:42.048  6740  6808 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bc11ebd Bundle[{}]
09-09 13:41:42.049  6740  6808 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:41:42.049  6740  6808 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:41:42.049  6740  6808 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 13:41:42.050  6740  6808 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:41:42.050  6740  6808 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:41:42.050  6740  6808 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 13:41:42.052  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.052  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.052  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-09 13:41:42.058  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 13:41:42.058  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:42.058  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:41:42.059  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:41:42.059  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:41:42.060  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.060  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:42.060  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:41:42.060  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:41:42.061  1034  1543 D ConnectivityService: NetworkAgent connected
09-09 13:41:42.061  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.062  7966  7966 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-09 13:41:42.064  6740  8033 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-09 13:41:42.064  6740  8033 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 13:41:42.070  6740  8033 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:41:42.070  6740  8033 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:42.070  6740  8033 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:42.070  6740  8033 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:42.071  6740  8033 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:42.071  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:41:42.072  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:42.072  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:41:42.072  6740  8040 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 963, name: OutgoingSocketThread/Receiver)
09-09 13:41:42.072  6740  8040 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 963, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:42.072  6740  8040 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 13:41:42.072  6740  8040 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 963, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:41:42.072  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:41:42.072  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:41:42.073  7966  7966 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-09 13:41:42.073  6740  8036 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 13:41:42.073  6740  8036 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:42.076  6740  8036 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:42.076  6740  8036 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:42.077  6740  8039 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 962, name: OutgoingSocketThread/Sender)
09-09 13:41:42.079  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:41:42.079  6740  8036 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:41:42.080   305   891 D CommandListener: Setting iface cfg
09-09 13:41:42.081  6740  8041 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 964, name: IncomingSocketThread/Sender)
09-09 13:41:42.082  6740  8042 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 965, name: IncomingSocketThread/Receiver)
09-09 13:41:42.082  6740  8042 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 965, thread name: IncomingSocketThread/Receiver)
09-09 13:41:42.082  6740  8042 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:42.082  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 13:41:42.082  6740  8042 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 965, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:41:42.083  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143556  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:42.083  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143556  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:42.084  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143557  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:42.084  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:42.084  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 13:41:42.085  1034  8043 D DhcpStateMachine: StoppedState
09-09 13:41:42.085  1034  8043 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.085  1034  8043 D DhcpStateMachine: WaitBeforeStartState
09-09 13:41:42.085  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:42.086  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:42.086  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:41:42.086  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:41:42.087  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:42.087  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:41:42.088  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:42.088  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 13:41:42.089  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=143562  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:42.089  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=143562  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:42.089  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=143563  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:41:42.090  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:955] from screen [on:0 period:247519562] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:42.091  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:247519563] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:42.091  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 13:41:42.096  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.097  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.097  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-09 13:41:42.097  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.097  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.097  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.098  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 13:41:42.098  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.098  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:41:42.099  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:42.099  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:41:42.099  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=183,0,0
09-09 13:41:42.100  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=183,0,0
09-09 13:41:42.100  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 13:41:42.100  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 13:41:42.100  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 13:41:42.100  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 13:41:42.100  8014  8014 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
09-09 13:41:42.101  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
09-09 13:41:42.101  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 13:41:42.101  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 13:41:42.101  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 13:41:42.101  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:41:42.101  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:42.101  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:42.101  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4858d85 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.102  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4858d85 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.102  1034  8043 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.102  1034  8043 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 13:41:42.102   305   891 D CommandListener: Setting iface cfg
09-09 13:41:42.102   305   891 D CommandListener: Trying to bring up wlan0
09-09 13:41:42.103  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:41:42.104  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:42.104  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:41:42.104  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.105  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.105  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.106  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.106  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.107  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:41:42.107  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:41:42.107  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:41:42.108  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:41:42.108  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:4,2.108  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.108  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:41:42.109  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:41:42.109  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:41:42.109  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 13:41:42.109  7942  7942 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 13:41:42.110  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 13:41:42.110  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
,09-09 13:41:42.117  8014  8014 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-09 13:41:42.117  8014  8014 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-09 13:41:42.117  8014  8014 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 13:41:42.117  8014  8014 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 13:41:42.117  8014  8014 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-09 13:41:42.117  8014  8014 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-09 13:41:42.123  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:42.123  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:41:42.123  7053  7053 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:41:42.123  7053  7053 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:41:42.124  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:41:42.124  7053  7053 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:41:42.124  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 13:41:42.124  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:41:42.124  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:41:42.124  7053  7053 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:41:42.124  7053  7053 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 13:41:42.124  7053  7053 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-09 13:41:42.128  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:41:42.128  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:41:42.129  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 13:41:42.129  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 13:41:42.129  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:41:42.129  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:41:42.133  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.133  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:42.133  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.133  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.134  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:41:42.134  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:41:42.134  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.135  1034  1543 D ConnectivityService: Adding iface wlan0 to network 102
09-09 13:41:42.137  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.137  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.137  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-09 13:41:42.142  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:42.145  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:42.146  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.146  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.146  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:42.146  1965  1965 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 13:41:42.149  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:42.151  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:42.152  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.152  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:42.152  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:42.155  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.155  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:42.156  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.157  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:42.158  7096  8047 W FormManager: Network not available. Please check & try again.
09-09 13:41:42.159  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.159  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:42.159  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.162  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.162  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.162  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:42.162  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.164  7096  8048 V FormManager: Network unavailable.
,09-09 13:41:42.166  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:42.166  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 13:41:42.167  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 13:41:42.167   305   891 E Netd    : netlink response contains error (File exists)
09-09 13:41:42.168  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 13:41:42.168  7096  8048 V FormManager: Network unavailable.
09-09 13:41:42.168  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:41:42.168  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 13:41:42.168  1034  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 13:41:42.169  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:42.169  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.169  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.169  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.169  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:42.169  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.169  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:42.169  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.169  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:41:42.169  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:41:42.169  1034  1543 D ConnectivityService:    accepting network in place of null
09-09 13:41:42.169  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.169  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.170  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.170  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:41:42.170  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.170  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:42.170  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.171  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:41:42.171  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  ,lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:41:42.171  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 13:41:42.171  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:42.169  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:42.176  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:42.176  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 13:41:42.176   305  8051 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 13:41:42.176  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 13:41:42.177  1034  1543 D ConnectivityService: validation of new default Network = false
09-09 13:41:42.177  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:41:42.177  1034  1543 D DSQN    : enableDataServiceNotify 
09-09 13:41:42.177  1034  1543 D DSQN    : start dsqn bin
09-09 13:41:42.178  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,09-09 13:41:42.178  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
,09-09 13:41:42.178  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:42.178  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:42.184  1034  1984 I ActivityManager: Killing 7294:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-09 13:41:42.186  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.186  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.186  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.186  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.187  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:42.181  8052  8052 W dsqn    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:42.181  8052  8052 W dsqn    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:42.197  8052  8052 E DSQN    : DSQN ssw
,09-09 13:41:42.217  1034  1981 W libprocessgroup: failed to open /acct/uid_10046/pid_7294/cgroup.procs: No such file or directory
,09-09 13:41:42.228   305  8051 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 13:41:42.229  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:42.240  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:42.244  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.248  1034  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-09 13:41:42.259  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:42.260  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.261  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.261  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:42.261  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:42.262   305  8060 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:42.262   305  8060 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-09 13:41:42.262   305  8051 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-09 13:41:42.262  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:42.265  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:42.270  4799  8061 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:42.271  4799  8062 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:42.271  4799  8062 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:42.272  4799  8061 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:41:42.288   305   890 D LGDataListener: argv[0]=dsqncommand
09-09 13:41:42.288   305   890 D LGDataListener: argv[1]=wlan0
,09-09 13:41:42.288   305   890 D LGDataListener: argv[2]=1
09-09 13:41:42.288   305   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:41:42.288  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:41:42.288  1034  1114 D DSQN    : start to monitor internet connection
09-09 13:41:42.304  1034  8043 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 13:41:42.304  1034  8043 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-09 13:41:42.304  1034  8043 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 13:41:42.301  8068  8068 W dhcpcd  : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:42.301  8068  8068 W dhcpcd  : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:41:42.311  1034  1762 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8065 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-09 13:41:42.311   305  8060 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-09 13:41:42.315  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:42 GMT], X-Android-Received-Millis=[1473421302315], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421302288]}
09-09 13:41:42.315  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:42.316  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:42.316  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.316  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.316  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:41:42.316  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.316  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:42.316  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 13:41:42.316  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.316  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.316  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.317  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.318  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.318  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:42.318  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:42.318  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.319  8068  8068 I dhcpcd  : version 5.5.6 starting
,09-09 13:41:42.319  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:42.321  8068  8068 E dhcpcd  : get_duid: m
09-09 13:41:42.321  8068  8068 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 13:41:42.321  8068  8068 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-09 13:41:42.321  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.324  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:41:42.324  4799  8061 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:42.328  4799  4799 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:41:42.329  4799  4799 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:41:42.329  4799  4799 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:42.330  4799  4799 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-09 13:41:42.336  4799  4799 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-09 13:41:42.347  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:42.348  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:41:42.349  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:42.371  8068  8068 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:41:42.371  8068  8068 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:41:42.371  8068  8068 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 13:41:42.371  8068  8068 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 13:41:42.371  8068  8068 D dhcpcd  : wlan0: sending REQUEST (xid 0x72557435), next in 4.81 seconds
09-09 13:41:42.372  7096  8058 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:41:42.375  7096  8058 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-09 13:41:42.400  8068  8068 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 13:41:42.427  8065  8065 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:42.427  8065  8065 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 13:41:42.431  1034  2069 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:41:42.432  8065  8065 V [BNRBootReceiver]: Boot Receiver Return
09-09 13:41:42.432  8065  8065 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:41:42.434  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.438  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.443  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.445  8068  8068 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 13:41:42.445  8068  8068 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 13:41:42.445  8068  8068 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 13:41:42.445  8068  8068 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 13:41:42.445  8068  8068 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 13:41:42.446  8068  8068 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:41:42.446  8068  8068 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:41:42.446  8068  8068 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 13:41:42.447  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.447  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.448  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:42.450  5073  8013 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 488 ms] updated apps [took 487 ms] 
09-09 13:41:42.451  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.457  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.461  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.466  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.466  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.467  7071  7071 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:41:42.470  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-09 13:41:42.473  7053  7053 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:41:42.477  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.484  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.490  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.496  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:42.496  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.497  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:41:42.499  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.512  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.519  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.528  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:41:42.529  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.529  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:42.535  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.544  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.550  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.558  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.558  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:41:42.559  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:41:42.564  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.580  6740  6808 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 974)
09-09 13:41:42.581  6740  6808 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:41:42.581  6740  6808 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 975)
09-09 13:41:42.584  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:42.584  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178683e3 added. We now have 3 listener(s)
,09-09 13:41:42.585  1034  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:42.587  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:41:42.588  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:42.588  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:42.588  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:42.588  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250781e0 added. We now have 3 listener(s)
09-09 13:41:42.588  6740  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:42.589  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:42.591  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:42.594  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.600  6740  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:42.603  6740  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.603  6740  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:42.606  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.606  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.606  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:42.606  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:42.606  6740  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178683e3 removed from the list
09-09 13:41:42.606  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.606  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250781e0 removed from the list
09-09 13:41:42.606  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.607  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.609  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.609  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.610  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.611  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:42.611  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:42.611  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:42.611  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:42.611  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:42.615  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.616  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.616  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:41:42.621  6740  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:41:42.621  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:42.621  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.625  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:42.626  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:41:42.628  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:42.630  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:42.631  6740  6808 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:42.632  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:42.645  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:42.646  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:42.646  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.648  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:42.649  5839  5839 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.651  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:42.652  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.655  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.658  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:42.660  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.661  5839  5839 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:42.662  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.663  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.666  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.667  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.667  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:42.670  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:41:42.677  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:42.682  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:42.687  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.687  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.688  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:42.691  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.697  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.701  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.705  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.706  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.706  7071  7071 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:41:42.709  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.709  1034  8043 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 13:41:42.710  1034  8043 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 13:41:42.710  1034  8043 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:42.710  1034  8043 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 13:41:42.710  1034  8043 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:41:42.710  1034  8043 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:42.710  1034  8043 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:41:42.710  1034  8043 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 13:41:42.711  1034  8043 D DhcpStateMachine: RunningState
09-09 13:41:42.712  7834  7834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:42.715  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:42.718  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.721  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:42.726  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.727  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.728  7071  7071 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 13:41:42.729  7071  7071 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 13:41:42.729  7071  7071 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 13:41:42.732  1034  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:42.732  1034  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:42.733  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:41:42.733  1034  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.734  1034  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.737  7834  7834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:42.738  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:42.741  7053  7053 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:42.745  7053  7053 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:42.751  7071  7071 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:41:42.752  7071  7071 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:41:42.753  7071  7071 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 13:41:42.754  7071  7071 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 13:41:42.755  7071  7071 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 13:41:42.768  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 13:41:42.770  6481  6505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:41:42.771  1034  1984 I ActivityManager: Killing 7341:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-09 13:41:42.824  1034  1981 W libprocessgroup: failed to open /acct/uid_10005/pid_7341/cgroup.procs: No such file or directory
,09-09 13:41:42.844  2263  2263 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:42.854  1034  1750 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-09 13:41:42.854  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.854  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.854  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:42.854  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.855  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:42.857   305  8112 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:42.857   305  8112 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-09 13:41:42.861  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:42.861  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:42.867  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:42.867  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 13:41:42.872  7898  7898 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 13:41:42.879  7898  7898 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a11be4
,09-09 13:41:42.879  7898  7898 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:42.880  7898  7898 D AppUp4:CustFacade: isPhone : true
09-09 13:41:42.880  7898  7898 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:42.880  7898  7898 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:41:42.881  7898  7898 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:41:42.881  7898  7916 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:41:42.882  7898  7916 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:41:42.882  7898  7916 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:41:42.885  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:42 GMT], X-Android-Received-Millis=[1473421302884], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421302856]}
09-09 13:41:42.885  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:42.885  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:42.885  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.885  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.885  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:42.885  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.886  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:42.886  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 13:41:42.886  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:42.886  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.886  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.886  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:42.886  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:42.887  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:42.887  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:42.889  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:41:42.892  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:42.896  2853  2853 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:42.897   305  8112 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-09 13:41:42.899  2853  2853 V DownloadManager: DownloadService onCreate
09-09 13:41:42.900  2853  8115 I DownloadManager: in removeSpuriousFiles
09-09 13:41:42.901  2853  8115 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:41:42.902  4799  8114 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:42.902  4799  8114 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:42.902  4799  8113 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 13:41:42.905  2853  8115 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3dc9c7d3 on behalf of 2853
09-09 13:41:42.906  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:41:42.907  2853  8115 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:41:42.908  2853  8115 I DownloadManager: in trimDatabase
09-09 13:41:42.909  2853  8115 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:42.909  4799  8113 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:42.910  2853  8115 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2759fa09 on behalf of 2853
09-09 13:41:42.958  1034  2038 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8118 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 13:41:42.964  4799  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:42.964  2853  2853 V DownloadManager: DownloadService onStartCommand
09-09 13:41:42.968  2853  8116 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:42.970  4799  4799 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:41:42.970  4799  4799 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:41:42.971  4799  4799 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-09 13:41:42.973  4799  4799 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:42.974  2853  8116 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@23df0e2f on behalf of 2853
09-09 13:41:42.976  2853  8116 V DownloadManager: processing inserted download 1
09-09 13:41:42.978  2853  8116 V DownloadManager: processing inserted download 4
09-09 13:41:42.979  2853  8116 V DownloadManager: processing inserted download 7
09-09 13:41:42.980  2853  8116 V DownloadManager: processing inserted download 8
09-09 13:41:42.981  2853  8116 V DownloadManager: processing inserted download 9
09-09 13:41:42.982  2853  8116 V DownloadManager: processing inserted download 10
09-09 13:41:42.984  2853  8116 V DownloadManager: processing inserted download 11
09-09 13:41:42.985  4799  4799 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:41:42.985  2853  8116 V DownloadManager: processing inserted download 12
09-09 13:41:42.986  2853  8116 V DownloadManager: processing inserted download 13
09-09 13:41:42.987  2853  8116 V DownloadManager: processing inserted download 14
,09-09 13:41:42.988  2853  8116 V DownloadManager: processing inserted download 16
09-09 13:41:42.993  2853  2853 V DownloadManager: DownloadService onDestroy
,09-09 13:41:43.027  8118  8118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:43.027  8118  8118 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:43.029  8118  8118 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:43.029  8118  8118 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 13:41:43.100  8118  8118 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 13:41:43.113  8118  8118 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-09 13:41:43.147  8118  8118 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:41:43.182  8118  8118 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:43.182  8118  8118 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 13:41:43.186  1034  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 13:41:43.270  7671  7742 D UEI.SmartControl: Internal timer expired: 1
09-09 13:41:43.270  7671  7742 D UEI.SmartControl: unbind internal service
,09-09 13:41:43.328  8118  8118 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:41:43.388  3211  3211 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:43.388  3211  3211 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:43.389  3211  3211 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 13:41:43.398  8118  8118 I HubEmail: JNI_OnLoad()
09-09 13:41:43.398  8118  8118 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:43.398  8118  8118 I HubEmail: registerNatives()
09-09 13:41:43.398  8118  8118 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:43.398  8118  8118 I HubEmail: registerNativeMethods()
09-09 13:41:43.398  8118  8118 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:43.399  8118  8118 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-09 13:41:43.443  1034  1574 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8147 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-09 13:41:43.446  8118  8145 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:43.483  7671  7739 D serial_port: close(fd = 25)
,09-09 13:41:43.487  7671  7739 I UEI.SmartControl: Serial port is closed.
09-09 13:41:43.567  8147  8147 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:41:43.567  8147  8147 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:41:43.571  8147  8147 D PhoneMonitor: Register our PhoneStateListener
09-09 13:41:43.594  8147  8147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 13:41:43.600  8147  8147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 13:41:43.630  8147  8147 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-09 13:41:43.631  8147  8147 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:41:43.631  8147  8147 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:41:43.634  7096  8146 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:41:43.634  8147  8147 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-09 13:41:43.634  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 13:41:43.635  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 13:41:43.635  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 13:41:43.635  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 13:41:43.635  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-09 13:41:43.635  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-09 13:41:43.635  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 13:41:43.635  8147  8147 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 13:41:43.635  8147  8147 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-09 13:41:43.646  7096  8146 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:41:43.647  8147  8147 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:41:43.657  1034  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:43.657  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:43.658  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:43.658  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:43.659  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:41:43.659  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-09 13:41:43.660  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-09 13:41:43.660  1034  1543 D ConnectivityService: identical MTU - not setting
09-09 13:41:43.660  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:43.660  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 13:41:43.660  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:43.660  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:43.661  1034  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:43.661  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:41:43.664  1034  2102 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8167 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:43.667  1034  2102 I ActivityManager: Killing 7559:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-09 13:41:43.718  1034  2023 W libprocessgroup: failed to open /acct/uid_10037/pid_7559/cgroup.procs: No such file or directory
,09-09 13:41:43.758  1034  1945 I ActivityManager: Killing 7594:com.lge.settings.easy/1000 (adj 15): empty #17
09-09 13:41:43.806  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7594/cgroup.procs: No such file or directory
,09-09 13:41:43.810  1841  8184 I CheckinService: active receiver: disabled
,09-09 13:41:43.976  1034  2038 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8187 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-09 13:41:43.979  1034  2038 I ActivityManager: Killing 7864:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 13:41:44.078  1034  2023 W libprocessgroup: failed to open /acct/uid_10072/pid_7864/cgroup.procs: No such file or directory
,09-09 13:41:44.202  1034  2102 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8204 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:44.203  1034  2102 I ActivityManager: Killing 7924:com.android.contacts/u0a19 (adj 15): empty #17
09-09 13:41:44.229   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 508us total 23.148ms
,09-09 13:41:44.252   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 459us total 21.429ms
,09-09 13:41:44.274   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.639ms
,09-09 13:41:44.277  1034  2038 W libprocessgroup: failed to open /acct/uid_10019/pid_7924/cgroup.procs: No such file or directory
09-09 13:41:44.307  8204  8204 I art     : Almond Protected OAT
,09-09 13:41:44.364  8204  8204 D WeatherApplication: removeAccount
,09-09 13:41:44.367  8204  8204 D WeatherApplication: Account.length = 0
09-09 13:41:44.369  8204  8204 E WeatherApplication: OPERATOR:OPEN
09-09 13:41:44.380  8204  8204 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:44
,09-09 13:41:44.388  8204  8204 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:41:44.389  8204  8204 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:41:44.391  8204  8204 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:44.394  8204  8204 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:44.397  8204  8204 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-09 13:41:44.416  8204  8204 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:41:44.417  8204  8204 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:41:44.417  8204  8204 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-09 13:41:44.452  8204  8204 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-09 13:41:44.452  8204  8204 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:44
09-09 13:41:44.507  1034  2262 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8222 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:44.508  1034  2262 I ActivityManager: Killing 7946:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-09 13:41:44.592  1034  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:44.592  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:44.592  1034  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:44.611  1034  2023 W libprocessgroup: failed to open /acct/uid_10027/pid_7946/cgroup.procs: No such file or directory
,09-09 13:41:44.647  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-09 13:41:44.648  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:41:44.648  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:41:44.648  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:41:44.649  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:41:44.649  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:41:44.718   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:44.718   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:44.718   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:44.721  8222  8243 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:44.723   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:44.723   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:44.723   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:44.724  8222  8243 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-09 13:41:44.740   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-09 13:41:44.740   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:44.740   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:44.743  8222  8245 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:44.746   277   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:44.746   277   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:44.746   277   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:44.747  8222  8245 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:44.982  8222  8222 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 13:41:44.994  8222  8222 I LibraryLoader: Loading: webviewchromium
,09-09 13:41:44.998  8222  8222 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6478-6483)
,09-09 13:41:44.998  8222  8222 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:41:45.004  8222  8222 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2088500a}
,09-09 13:41:45.006  8222  8222 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:45.006  8222  8222 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:45.018  8222  8222 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 13:41:45.019  8222  8222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:45.038  8222  8222 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 13:41:45.039  8222  8222 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-09 13:41:45.039  8222  8222 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-09 13:41:45.043   309  2206 V AudioPolicyService: registerClient() client 0xb0410540, uid 10093
09-09 13:41:45.044  8222  8267 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:41:45.062  8222  8222 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:45.062  8222  8222 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:45.062  8222  8222 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:41:45.062  8222  8222 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:41:45.062  8222  8222 I Adreno-EGL: Remote Branch: 
09-09 13:41:45.062  8222  8222 I Adreno-EGL: Local Patches: 
09-09 13:41:45.062  8222  8222 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:45.099  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=91.5, 0.0, 0.0  rx=90.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:247522570] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:45.101  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=91.5, 0.0, 0.0  rx=90.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:247522573] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:45.101  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:41:45.119  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:41:45.144  8222  8222 I NSApplication: Starting up...
,09-09 13:41:45.149  1034  1538 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-09 13:41:45.169  1034  1049 I ActivityManager: Killing 7966:com.android.vending/u0a44 (adj 15): empty #17
,09-09 13:41:45.179  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.210  1034  2102 W libprocessgroup: failed to open /acct/uid_10044/pid_7966/cgroup.procs: No such file or directory
,09-09 13:41:45.220  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:45.223  1034  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.229  5839  5839 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:45.239  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:45.241  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 13:41:45.244  6481  6505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:41:45.245  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:45.247  1034  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:45.260  2263  2263 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:45.273   305  8282 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:41:45.273  1034  1574 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-09 13:41:45.273   305  8282 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-09 13:41:45.274   305  8282 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-09 13:41:45.274  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:45.274  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:45.274  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:45.274  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:45.274  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-09 13:41:45.280  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:45.280  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.280  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:45.280  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:41:45.282  7898  7898 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:45.289  7898  7898 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a11be4
09-09 13:41:45.290  7898  7898 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:45.290  7898  7898 D AppUp4:CustFacade: isPhone : true
,09-09 13:41:45.292  7898  7898 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:45.293  7898  7898 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:41:45.297  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.297  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:45.299  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:45.301  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:45.305  2853  2853 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:45.306  4799  8283 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:45.309  4799  8284 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.310  4799  8284 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:45.314  2853  2853 V DownloadManager: DownloadService onCreate
09-09 13:41:45.317  4799  8283 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:45.327  2853  8285 I DownloadManager: in removeSpuriousFiles
09-09 13:41:45.328  2853  8285 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-09 13:41:45.336  2853  8285 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@109f2dc5 on behalf of 2853
09-09 13:41:45.337  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:41:45.337  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:41:45.337  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:41:45.338  2853  8285 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:41:45.340  4799  8283 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:45.343  8118  8287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:45.346  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:45 GMT], X-Android-Received-Millis=[1473421305340], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421305276]}
09-09 13:41:45.346  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:45.346  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:45.347  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 13:41:45.347  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:41:45.347  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:45.348  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:45.348  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:45.348  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 13:41:45.348  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:45.348  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:45.348  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:45.348  3211  3211 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:45.348  3211  3211 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.348  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:45.348  3211  3211 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 13:41:45.349  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:45.350  2853  2853 V DownloadManager: DownloadService onStartCommand
09-09 13:41:45.352  8147  8147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:41:45.352  8147  8147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:41:45.355  4799  4799 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:41:45.356  4799  4799 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:41:45.356  4799  4799 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:45.358  4799  4799 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-09 13:41:45.360  2853  8285 I DownloadManager: in trimDatabase
09-09 13:41:45.360  2853  8285 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:45.361  2853  8286 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:45.364  2853  8285 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@265d3028 on behalf of 2853
09-09 13:41:45.366  2853  8286 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2149e141 on behalf of 2853
09-09 13:41:45.369  2853  8286 V DownloadManager: processing inserted download 1
09-09 13:41:45.370  2853  8286 V DownloadManager: processing inserted download 4
09-09 13:41:45.371  2853  8286 V DownloadManager: processing inserted download 7
09-09 13:41:45.372  4799  4799 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:41:45.373  2853  8286 V DownloadManager: processing inserted download 8
09-09 13:41:45.375  2853  8286 V DownloadManager: processing inserted download 9
09-09 13:41:45.376  8204  8204 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:45
,09-09 13:41:45.378  8204  8204 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:41:45.378  8204  8204 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:41:45.379  2853  8286 V DownloadManager: processing inserted download 10
09-09 13:41:45.379  8204  8204 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:45.379  8204  8204 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:45.379  8204  8204 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@284a5c49
09-09 13:41:45.380  2853  8286 V DownloadManager: processing inserted download 11
,09-09 13:41:45.381  2853  8286 V DownloadManager: processing inserted download 12
09-09 13:41:45.382  8204  8204 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:41:45.382  8204  8204 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-09 13:41:45.382  2853  8286 V DownloadManager: processing inserted download 13
09-09 13:41:45.382  8204  8204 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:41:45.382  8204  8204 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:45.382  8204  8204 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:45
09-09 13:41:45.383  2853  8286 V DownloadManager: processing inserted download 14
09-09 13:41:45.384  2853  8286 V DownloadManager: processing inserted download 16
09-09 13:41:45.388  2853  2853 V DownloadManager: DownloadService onDestroy
,09-09 13:41:45.410  2263  2263 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-09 13:41:45.437  7096  8301 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:41:45.441  7096  8301 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:41:45.469  2263  2263 I art     : Explicit concurrent mark sweep GC freed 10407(742KB) AllocSpace objects, 10(160KB) LOS objects, 52% free, 29MB/61MB, paused 1.156ms total 50.513ms
,09-09 13:41:45.483  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 13:41:45.488  6481  6505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:41:45.504  2263  2263 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:45.518  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-09 13:41:45.518  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.518  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:45.519  7898  7898 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 13:41:45.522  1034  2102 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-09 13:41:45.522  7898  7898 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:45.522  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:45.522  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:45.522  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:45.522  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:45.522  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:45.529  7898  7898 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a11be4
09-09 13:41:45.529  7898  7898 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:45.529  7898  7898 D AppUp4:CustFacade: isPhone : true
09-09 13:41:45.530  7898  7898 D AppUp4:CustModeStarterReceiver: begin check event
,09-09 13:41:45.531  7898  7898 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:41:45.536  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.537  4799  4799 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:45.538  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:41:45.541  4799  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:41:45.546  2853  2853 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.549  2853  2853 V DownloadManager: DownloadService onCreate
09-09 13:41:45.550  4799  8310 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:45.553  4799  8310 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:45.554  4799  8313 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.554  4799  8313 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:45.557  2853  8311 I DownloadManager: in removeSpuriousFiles
09-09 13:41:45.558  2853  8311 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:41:45.559  2853  8311 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39cc9427 on behalf of 2853
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:41:45.560  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:41:45.561  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:41:45.561  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:41:45.561  2853  8311 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:41:45.561  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:45 GMT], X-Android-Received-Millis=[1473421305560], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421305524]}
09-09 13:41:45.561  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:45.561  1034  8030 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:45.562  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 13:41:45.562  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:41:45.562  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:45.562  1034  1543 D ConnectivityService: ,  checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:45.562  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:45.562  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 13:41:45.562  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:45.562  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:45.562  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 13:41:45.563  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:45.565  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:45.566  2853  2853 V DownloadManager: DownloadService onStartCommand
09-09 13:41:45.567  2853  8312 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:45.568  2853  8311 I DownloadManager: in trimDatabase
09-09 13:41:45.568  2853  8311 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:45.568  2853  8312 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@18808b72 on behalf of 2853
09-09 13:41:45.569  2853  8311 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@25644bc3 on behalf of 2853
09-09 13:41:45.570  4799  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:45.572  4799  4799 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:41:45.573  4799  4799 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:41:45.573  4799  4799 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-09 13:41:45.577  8118  8315 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:45.578  4799  4799 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:45.581  4799  4799 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:41:45.582  2853  8312 V DownloadManager: processing inserted download 1
09-09 13:41:45.584  2853  8312 V DownloadManager: processing inserted download 4
09-09 13:41:45.588  2853  8312 V DownloadManager: processing inserted download 7
09-09 13:41:45.588  3211  3211 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:45.588  3211  3211 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:45.589  3211  3211 I LgeMiscReceiver: networkInfo.isConnected() = true
09-09 13:41:45.589  3211  3211 D PhoneState: setPdpRejectCasuse : false
09-09 13:41:45.589  2853  8312 V DownloadManager: processing inserted download 8
09-09 13:41:45.590  2853  8312 V DownloadManager: processing inserted download 9
09-09 13:41:45.591  2853  8312 V DownloadManager: processing inserted download 10
,09-09 13:41:45.592  2853  8312 V DownloadManager: processing inserted download 11
,09-09 13:41:45.593  2853  8312 V DownloadManager: processing inserted download 12
09-09 13:41:45.594  8147  8147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:41:45.594  8147  8147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:41:45.595  2853  8312 V DownloadManager: processing inserted download 13
09-09 13:41:45.596  2853  8312 V DownloadManager: processing inserted download 14
09-09 13:41:45.598  2853  8312 V DownloadManager: processing inserted download 16
09-09 13:41:45.604  2853  2853 V DownloadManager: DownloadService onDestroy
,09-09 13:41:45.607  8204  8204 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:45
09-09 13:41:45.609  8204  8204 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:41:45.609  8204  8204 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:41:45.609  8204  8204 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:45.609  8204  8204 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:45.609  8204  8204 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@284a5c49
09-09 13:41:45.610  8204  8204 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:41:45.610  8204  8204 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:41:45.610  8204  8204 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:41:45.610  8204  8204 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:45.611  8204  8204 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:45
09-09 13:41:45.632  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:45.632  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:41:45.633  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:45.633  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:45.633  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:45.633  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178683e3 not in the list
09-09 13:41:45.633  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:45.634  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250781e0 not in the list
09-09 13:41:45.634  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:45.634  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:45.634  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:45.635  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:45.636  6740  6808 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:41:45.636  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:41:45.636  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:45.636  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:45.636  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:45.636  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:45.637  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:45.637  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:45.638  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:45.638  6740  6740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:45.639  1034  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:45.639  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:45.639  6740  8321 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:45.639  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:45.639  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:45.639  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:45.640  7640  7725 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-09 13:41:45.640  6740  8321 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:45.644  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.Wif,iDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:45.645  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:45.647  6740  6808 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:45.647  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:45.647  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:45.647  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:45.647  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:45.647  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:45.647  6740  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:45.647  6740  8321 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:45.647  6740  8321 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:45.647  6740  8321 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:45.648  6740  6740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:45.648  6740  6740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:45.648  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178683e3 not in the list
09-09 13:41:45.648  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:45.648  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250781e0 not in the list
09-09 13:41:45.648  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:45.648  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:45.648  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:45.649  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:45.650  6740  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:45.650  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:45.650  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:45.650  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:45.650  7096  8319 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:41:45.653  7096  8319 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:41:45.753  1034  2262 I art     : Explicit concurrent mark sweep GC freed 79828(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.627ms total 102.047ms
,09-09 13:41:45.757  6740  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:45.758  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:45.759  6740  6808 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 13:41:46.371   305  8332 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:41:46.384   305  8332 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-09 13:41:46.423   305  8332 D libc-netbsd: res_queryN name = www.google.com succeed
,09-09 13:41:46.432   305  8334 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:41:46.432   305  8334 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 13:41:46.432   305  8334 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 13:41:46.499  1034  1539 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-09 13:41:48.130  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=59.2, 0.0, 0.0  rx=55.8 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:247525602] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:41:48.134  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=59.2, 0.0, 0.0  rx=55.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:247525605] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:48.134  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:41:48.760  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:48.760  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:48.760  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:48.760  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178683e3 not in the list
09-09 13:41:48.760  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:48.760  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250781e0 not in the list
09-09 13:41:48.761  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:48.761  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:48.761  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:48.762  6740  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:48.762  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:48.762  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:48.762  6740  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178683e3 not in the list
09-09 13:41:48.762  6740  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:48.762  6740  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250781e0 not in the list
09-09 13:41:48.762  6740  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:48.762  6740  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:48.762  6740  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:48.763  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:48.763  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:48.764  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:48.764  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:48.764  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:48.764  6740  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:48.787  6740  8335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 994, name: My test thread name)
,09-09 13:41:48.927  1034  1406 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c79bd9b type 2 when 150383 com.google.android.gms} when 150383
,09-09 13:41:48.934  7071  7071 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-09 13:41:48.935  7071  7071 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6022
09-09 13:41:48.942   305  8337 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:41:48.945   305  8337 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,09-09 13:41:48.945   305  8337 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-09 13:41:49.248  2263  8338 D GCM     : Connected
,09-09 13:41:49.295  2263  8338 D GCM     : Message class com.google.e.a.a.q
,09-09 13:41:49.762  8222  8246 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:41:50.783  6740  6808 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 994
,09-09 13:41:50.783  6740  6808 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 994, name: My test thread name)
,09-09 13:41:50.798  6740  8341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 995, name: My test thread name)
09-09 13:41:50.798  6740  8341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 995, thread name: My test thread name)
09-09 13:41:50.798  6740  8341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 995, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-09 13:41:50.800  6740  6808 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:50.805  6740  8342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 999, name: My test thread name)
09-09 13:41:50.805  6740  8342 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 999, thread name: My test thread name): Test exception.
09-09 13:41:50.805  6740  8342 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 999, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:41:50.811  6740  6808 I jxcore-log: Total number of executed tests:  82
09-09 13:41:50.811  6740  6808 I jxcore-log: 
09-09 13:41:50.811  6740  6808 I jxcore-log: Number of passed tests:  82
09-09 13:41:50.811  6740  6808 I jxcore-log: 
09-09 13:41:50.811  6740  6808 I jxcore-log: Number of failed tests:  0
09-09 13:41:50.811  6740  6808 I jxcore-log: 
09-09 13:41:50.812  6740  6808 I jxcore-log: Number of ignored tests:  0
09-09 13:41:50.812  6740  6808 I jxcore-log: 
09-09 13:41:50.812  6740  6808 I jxcore-log: Total duration:  25020
09-09 13:41:50.812  6740  6808 I jxcore-log: 
09-09 13:41:50.814  6740  6808 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 13:41:50.814  6740  6808 I jxcore-log: 
09-09 13:41:50.815  6740  6808 I jxcore-log: My device name is: LGE-LG-D855
09-09 13:41:50.815  6740  6808 I jxcore-log: 
09-09 13:41:50.819  6740  6808 I jxcore-log: WARN testUtils: myNameCallback not set!
09-09 13:41:50.819  6740  6808 I jxcore-log: 
,09-09 13:41:50.834  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.834  6740  6808 I jxcore-log: 
,09-09 13:41:50.838  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.838  6740  6808 I jxcore-log: 
09-09 13:41:50.843  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.843  6740  6808 I jxcore-log: 
09-09 13:41:50.844  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.844  6740  6808 I jxcore-log: 
09-09 13:41:50.851  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.851  6740  6808 I jxcore-log: 
09-09 13:41:50.853  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.853  6740  6808 I jxcore-log: 
09-09 13:41:50.854  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.854  6740  6808 I jxcore-log: 
09-09 13:41:50.854  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.854  6740  6808 I jxcore-log: 
,09-09 13:41:50.859  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:50.859  6740  6808 I jxcore-log: 
09-09 13:41:50.860  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:50.860  6740  6808 I jxcore-log: 
09-09 13:41:50.861  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:50.861  6740  6808 I jxcore-log: 
09-09 13:41:50.862  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:50.862  6740  6808 I jxcore-log: 
09-09 13:41:50.864  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:50.864  6740  6808 I jxcore-log: 
09-09 13:41:50.865  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:50.865  6740  6808 I jxcore-log: 
09-09 13:41:50.866  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:50.866  6740  6808 I jxcore-log: 
09-09 13:41:50.866  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.866  6740  6808 I jxcore-log: 
09-09 13:41:50.867  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.867  6740  6808 I jxcore-log: 
09-09 13:41:50.868  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.868  6740  6808 I jxcore-log: 
09-09 13:41:50.869  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.869  6740  6808 I jxcore-log: 
09-09 13:41:50.870  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.870  6740  6808 I jxcore-log: 
09-09 13:41:50.870  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.870  6740  6808 I jxcore-log: 
09-09 13:41:50.871  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.871  6740  6808 I jxcore-log: 
09-09 13:41:50.872  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.872  6740  6808 I jxcore-log: 
09-09 13:41:50.873  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.873  6740  6808 I jxcore-log: 
09-09 13:41:50.873  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f,2:6d:22:99:3e"}
09-09 13:41:50.873  6740  6808 I jxcore-log: 
09-09 13:41:50.874  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.874  6740  6808 I jxcore-log: 
09-09 13:41:50.875  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.875  6740  6808 I jxcore-log: 
09-09 13:41:50.876  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:50.876  6740  6808 I jxcore-log: 
,09-09 13:41:50.880  6740  8335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 994, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
09-09 13:41:50.882  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:50.882  6740  6808 I jxcore-log: 
09-09 13:41:50.883  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:50.883  6740  6808 I jxcore-log: 
09-09 13:41:50.884  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:50.884  6740  6808 I jxcore-log: 
09-09 13:41:50.885  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:50.885  6740  6808 I jxcore-log: 
09-09 13:41:50.886  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:50.886  6740  6808 I jxcore-log: 
09-09 13:41:50.887  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.887  6740  6808 I jxcore-log: 
09-09 13:41:50.888  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.888  6740  6808 I jxcore-log: 
09-09 13:41:50.889  6740  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:50.889  6740  6808 I jxcore-log: 
,09-09 13:41:51.156  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=44.6, 0.0, 0.0  rx=38.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:247528628] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:51.157  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=44.6, 0.0, 0.0  rx=38.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:247528629] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:41:51.157  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:41:51.162  8343  8343 D AndroidRuntime: 
09-09 13:41:51.162  8343  8343 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:41:51.165  8343  8343 D AndroidRuntime: CheckJNI is OFF
,09-09 13:41:51.290  8343  8343 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:41:51.306  1034  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-09 13:41:51.306  1034  1090 I ActivityManager: Killing 6740:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-09 13:41:51.366  1034  1050 I WindowState: WIN DEATH: Window{1730d58a u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 13:41:51.370  1034  1542 D WifiService: Client connection lost with reason: 4
,09-09 13:41:51.376  1034  1050 D InputDispatcher: Window went away: Window{1730d58a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:41:51.428  1034  1090 I ActivityManager:   Force finishing activity ActivityRecord{7fc8ef6 u0 com.test.thalitest/.MainActivity t6}
,09-09 13:41:51.498   333   344 E GBMv2   : DFP En is all cleared set to be enabled
,09-09 13:41:51.504  1034  2069 W ActivityManager: Spurious death for ProcessRecord{5040a76 6740:com.test.thalitest/u0a118}, curProc for 6740: null
,09-09 13:41:51.504  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-09 13:41:51.510  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{7fc8ef6 u0 com.test.thalitest/.MainActivity t6 f}
09-09 13:41:51.511  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{7fc8ef6 u0 com.test.thalitest/.MainActivity t6 f}
,09-09 13:41:51.545  2093  2093 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-09 13:41:51.546  1965  1988 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-09 13:41:51.547  1965  1988 D SplitWindowPolicy: topRunningActivity=ActivityInfo{178ca21e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 13:41:51.548  2093  2093 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-09 13:41:51.550  1965  2934 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-09 13:41:51.550  1965  2934 D SplitWindowPolicy: topRunningActivity=ActivityInfo{217a5aff co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 13:41:51.551  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-09 13:41:51.552  2093  2195 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-09 13:41:51.556  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-09 13:41:51.566  1034  1463 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:41:51.579  2050  2050 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,09-09 13:41:51.581  2497  2608 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:41:51.582  3791  3791 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-09 13:41:51.585  7640  7640 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-09 13:41:51.585  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 13:41:51.586  1928  1928 D ActionManagerService: notifyUserLog: 1000003
09-09 13:41:51.587  3791  4963 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-09 13:41:51.593  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-09 13:41:51.622  1034  2262 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:41:51.633  6481  6481 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 13:41:51.643  2093  2093 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-09 13:41:51.653  4971  4971 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 13:41:51.653  4971  4971 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-09 13:41:51.653  4971  4971 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 13:41:51.653  4971  4971 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-09 13:41:51.653  4971  4971 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:51.653  4971  4971 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:51.653  4971  4971 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:51.653  4971  4971 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:41:51.653  4971  4971 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:51.653  4971  4971 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:51.653  4971  4971 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:41:51.654  4971  4971 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:41:51.701  1034  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-09 13:41:51.713  5073  5073 I art     : Explicit concurrent mark sweep GC freed 8196(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 385us total 193.608ms
09-09 13:41:51.730  1034  1953 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:41:51.730  1034  1953 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:41:51.738  1841  1841 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-09 13:41:51.745  1601  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 13:41:51.745  1601  1650 D KeyguardModel: createShortcutInfo...
09-09 13:41:51.746  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-09 13:41:51.748  1601  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:41:51.748  1601  1650 D KeyguardModel: createShortcutInfo...
,09-09 13:41:51.753  1601  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 13:41:51.754  1601  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:51.754  1601  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:41:51.755  1601  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 13:41:51.755  1601  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:41:51.755  1601  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 13:41:51.759  1601  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:41:51.759  1601  1650 D KeyguardModel: createShortcutInfo...
09-09 13:41:51.762  1601  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 13:41:51.762  1601  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:51.763  1601  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:41:51.763  1601  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 13:41:51.764  1601  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:41:51.764  1601  1650 D KeyguardModel: createShortcutInfo...
09-09 13:41:51.768  1601  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:51.768  1601  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:41:51.768  1601  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-09 13:41:51.768  1601  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 13:41:51.769  1601  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:41:51.769  1601  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 13:41:51.770  2093  2093 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-09 13:41:51.776  1601  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:41:51.776  1601  1650 D KeyguardModel: createShortcutInfo...
09-09 13:41:51.776  1034  1034 I art     : Explicit concurrent mark sweep GC freed 15294(1080KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.103ms total 229.710ms
09-09 13:41:51.778  1034  1122 I art     : WaitForGcToComplete blocked for 8.588ms for cause Explicit
09-09 13:41:51.778  2093  2093 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-09 13:41:51.785  1034  1953 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:41:51.789  2263  2263 I ConfigService: onCreate
09-09 13:41:51.789  2263  2263 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-09 13:41:51.791  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-09 13:41:51.792  1894  1894 D SplitUIManager: split_name #11 / not available #0
09-09 13:41:51.792  1894  1894 D SplitUIService: removed split : 
09-09 13:41:51.793  1034  1750 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 13:41:51.793  1928  1928 D ActionManagerService: notifyUserLog: 1000004
,09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:41:51.793  7640  7640 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 13:41:51.794  3791  4963 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-09 13:41:51.794  2263  2263 I ConfigService: onBind returning update interface
09-09 13:41:51.795  3791  4959 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 13:41:51.798  1841  1841 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-09 13:41:51.799  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-09 13:41:51.799  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-09 13:41:51.808  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-09 13:41:51.808  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 13:41:51.808  2263  2263 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-09 13:41:51.808  2263  2263 I ConfigService: onBind returning config service
,09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , create_time: 1430832262123
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , expire_time: 0
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , display: false
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , animation: false }
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , create_time: 1430832262287
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , expire_time: 0
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , display: false
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , animation: false }
09-09 13:41:51.811  1841  1841 I ConfigFetchService: service connected
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , create_time: 1473420113195
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , expire_time: 0
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , display: false
09-09 13:41:51.811  2093  2093 I GBoardWebViewUtils: , animation: false }
09-09 13:41:51.811  1841  1841 I ConfigClient: service connected
09-09 13:41:51.813  1894  1894 D SplitUIManager: split_name #11 / not available #0
09-09 13:41:51.813  1894  1894 I SplitUIService: split app #11
09-09 13:41:51.816  2093  8376 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-09 13:41:51.822  2263  2263 I ConfigService: onDestroy
,09-09 13:41:51.833  1841  8378 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-09 13:41:51.836  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 13:41:51.837  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-09 13:41:51.859  1601  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 13:41:51.859  1601  1650 D KeyguardModel: createShortcutInfo...
,09-09 13:41:51.862  1601  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:41:51.862  1601  1650 D KeyguardModel: createShortcutInfo...
09-09 13:41:51.863  1601  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:41:51.863  1601  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 13:41:51.866  1601  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:41:51.866  1601  1650 D KeyguardModel: createShortcutInfo...
09-09 13:41:51.872  1601  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:41:51.872  1601  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-09 13:41:51.877  1601  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:41:51.878  1601  1650 D KeyguardModel: createShortcutInfo...
09-09 13:41:51.878  1034  1034 D administrator: Handling package changes for user 0
09-09 13:41:51.878  1601  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:41:51.879  5885  8385 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-09 13:41:51.879  1601  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 13:41:51.885  1601  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:41:51.885  1601  1650 D KeyguardModel: createShortcutInfo...
,09-09 13:41:51.890  1841  8386 I PeopleContactsSync: CP2 sync disabled
09-09 13:41:51.892  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-09 13:41:51.892  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 13:41:51.899  7898  7898 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-09 13:41:51.901  1841  5259 I Icing   : doRemovePackageData com.test.thalitest
,09-09 13:41:51.936  1034  1750 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8389 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-09 13:41:51.956  1841  8384 W GmsApplication: Using Auth Proxy for data requests.
,09-09 13:41:51.960  1841  8384 W GmsApplication: Using Auth Proxy for data requests.
,09-09 13:41:51.984  8389  8389 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:51.984  8389  8389 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:51.984  8389  8389 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:41:51.985  8389  8389 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 13:41:51.985  8389  8389 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:51.989  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-09 13:41:51.989  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:41:51.990  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 13:41:51.993  1034  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-09 13:41:52.017  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-09 13:41:52.020  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:41:52.021  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-09 13:41:52.023  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-09 13:41:52.024  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 13:41:52.025  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-09 13:41:52.039  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{131ed62e u0 com.lge.launcher2/.Launcher t5} time:153524
,09-09 13:41:52.044  2093  2093 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-09 13:41:52.044  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-09 13:41:52.045  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:41:52.045   326   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-09 13:41:52.045  3272  8408 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-09 13:41:52.052  2093  2309 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 13:41:52.052  2093  2309 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 13:41:52.054  8389  8389 I SystemConfig: BUILD Country: EU
09-09 13:41:52.055  8389  8389 I SystemConfig: BUILD Operator: OPEN
09-09 13:41:52.059  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-09 13:41:52.060  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 13:41:52.060  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:41:52.067  2093  2093 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-09 13:41:52.068  2678  2678 D [Concierge]Service: onStartCommand(). Type : 8
09-09 13:41:52.068  2678  2678 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-09 13:41:52.069  2678  2678 D [Concierge]Service: Update widget ID : 11
,09-09 13:41:52.071  1034  1122 I art     : Explicit concurrent mark sweep GC freed 10634(725KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 6.541ms total 293.018ms
09-09 13:41:52.071  2093  2093 D [Concierge]WidgetView: change position of spinner
09-09 13:41:52.073  2678  2678 D [Concierge]Service: onStartCommand(). Type : 0
09-09 13:41:52.073  2093  2093 I [Concierge]WidgetView: initWebView(). Time : 1473421312073
09-09 13:41:52.091  2093  2093 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 206486646
09-09 13:41:52.091  2093  2093 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-09 13:41:52.091  2093  2093 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 13:41:52.094  2093  2093 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@22919f7
09-09 13:41:52.094  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-09 13:41:52.097  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 13:41:52.097  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:41:52.102  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-09 13:41:52.102  2093  2093 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-09 13:41:52.102  2093  2093 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 13:41:52.103  2093  2093 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473421187446, New one : 1473421312073
09-09 13:41:52.103  2093  2093 D [Concierge]WidgetView: Unregister all receivers
09-09 13:41:52.103  2093  2093 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 13:41:52.103  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:41:52.106  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 13:41:52.107  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-09 13:41:52.109  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-09 13:41:52.110  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-09 13:41:52.110  1034  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:52.111  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-09 13:41:52.115  1034  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 13:41:52.115  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 13:41:52.115  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:41:52.116  1034  1050 I ActivityManager: Killing 8065:com.lge.bnr/1000 (adj 15): empty #17
09-09 13:41:52.131  8343  8343 D AndroidRuntime: Shutting down VM
,09-09 13:41:52.167  1034  2069 W libprocessgroup: failed to open /acct/uid_1000/pid_8065/cgroup.procs: No such file or directory
,09-09 13:41:52.171  2093  2093 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 13:41:52.172  2224  8412 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 13:41:52.175  8118  8118 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-09 13:41:52.176  8389  8410 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 13:41:52.176  8389  8410 I SystemConfig: existFile = false
09-09 13:41:52.176  8389  8410 I SystemConfig: canReadFile = false
09-09 13:41:52.176  8389  8410 I SystemConfig: systemFeature RCS result false
09-09 13:41:52.176  8389  8410 D SystemConfig: refreshRcsSupport() :false
09-09 13:41:52.190  2093  2093 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-09 13:41:52.190  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,09-09 13:41:52.191  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 13:41:52.192  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:41:52.199  1034  2013 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8413 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
09-09 13:41:52.212  2093  2093 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25644bc3 time:153697
,09-09 13:41:52.232  8413  8413 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:52.232  8413  8413 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:52.232  8413  8413 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-09 13:41:52.232  8413  8413 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 13:41:52.280  8413  8413 I AppConfig: Total System Memory = 2995761152
,09-09 13:41:52.285  8413  8413 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 13:41:52.301  1034  1762 I ActivityManager: Killing 7834:com.lge.sync/1000 (adj 15): empty #17
,09-09 13:41:52.310  2093  2093 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-09 13:41:52.349  2093  2952 I GBoardtInterface: onReloaded()
,09-09 13:41:52.350  2093  2093 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-09 13:41:52.396  2050  2050 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 13:41:52.396  2050  2050 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-09 13:41:52.397  1034  1953 W libprocessgroup: failed to open /acct/uid_1000/pid_7834/cgroup.procs: No such file or directory
09-09 13:41:52.397  2050  2050 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,09-09 13:41:52.399  3791  4959 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 13:41:52.431  1034  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8433 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 13:41:52.432  6481  6481 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 13:41:52.469  1034  2102 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8455 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:52.475  3791  3809 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 13:41:52.485  1928  1928 D ActionManagerService: notifyUserLog: 1000001
,09-09 13:41:52.487  3791  4963 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 13:41:52.487  3791  4963 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 13:41:52.490  1928  1928 D ActionManagerService: notifyUserLog: 1000001
09-09 13:41:52.490  3791  3809 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 13:41:52.491  3791  4963 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 13:41:52.492  3791  4963 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 13:41:52.492  3791  4963 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-09 13:41:52.492  3791  4963 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-09 13:41:52.493  2093  2093 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-09 13:41:52.493  2093  2093 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-09 13:41:52.494  2093  2093 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-09 13:41:52.494  2093  2093 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 13:41:52.496  2093  2093 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-09 13:41:52.496  2093  2093 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 13:41:52.506  1034  1574 I ActivityManager: Killing 7053:com.android.settings/1000 (adj 15): empty #17

```
