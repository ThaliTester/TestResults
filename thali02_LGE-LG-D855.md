#### Test 8362733705cfec3_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-12 13:56:52.353  6647  6647 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
09-12 13:56:52.410  1035  2006 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6680 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
09-12 13:56:52.412  1035  2006 I ActivityManager: Killing 6211:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-12 13:56:52.459  1035  1940 W libprocessgroup: failed to open /acct/uid_10080/pid_6211/cgroup.procs: No such file or directory
09-12 13:56:52.492  6680  6680 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:56:52.493  6680  6680 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 13:56:52.493  6680  6680 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-12 13:56:52.493  6680  6680 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 13:56:52.590  6680  6680 I AppConfig: Total System Memory = 2995761152
09-12 13:56:52.601  6680  6680 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-12 13:56:52.635  1035  1751 I ActivityManager: Killing 6159:com.android.vending/u0a44 (adj 15): empty #17
09-12 13:56:52.671  1994  1994 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-12 13:56:52.672  1994  1994 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-12 13:56:52.675  1035  1903 W libprocessgroup: failed to open /acct/uid_10044/pid_6159/cgroup.procs: No such file or directory
09-12 13:56:52.680  1994  1994 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-12 13:56:52.703  6537  6537 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-12 13:56:52.709  6537  6537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-12 13:56:52.760  1035  2359 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6703 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:56:53.003   340   416 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-12 13:56:53.006  3288  6725 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-12 13:56:53.033  6703  6703 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-12 13:56:53.124  6703  6703 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:56:53.124  6703  6703 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 13:56:53.182  6703  6703 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-12 13:56:53.203  6703  6703 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-12 13:56:53.204  6703  6703 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-12 13:56:53.220  6703  6703 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 13:56:53.220  6703  6703 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-12 13:56:53.241  1035  2031 I ActivityManager: Killing 5497:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-12 13:56:53.282  1035  1050 W libprocessgroup: failed to open /acct/uid_10085/pid_5497/cgroup.procs: No such file or directory
09-12 13:56:53.297  5092  6742 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-12 13:56:53.300  3388  3405 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-12 13:56:53.307  3388  3405 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2aa6faca on behalf of 6703
09-12 13:56:53.354  1035  1576 V SIM_STK : Menu title from STK is T-Mobile
09-12 13:56:53.372  1035  1867 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6745 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:56:53.404   350   350 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 26.960ms
09-12 13:56:53.426   350   350 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 19.209ms
09-12 13:56:53.446   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.485ms
09-12 13:56:53.452  6703  6703 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-12 13:56:53.477  6703  6703 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-12 13:56:53.514  5092  6742 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 217 ms] updated apps [took 216 ms] 
09-12 13:56:53.565  6745  6745 D DocsApplication: Installing DEX configuration.
09-12 13:56:53.593  6745  6745 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-12 13:56:53.600  6745  6745 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3c1b33dc com.google.android.apps.docs}
09-12 13:56:53.618  6745  6745 D TAG     : onCreate()
09-12 13:56:53.623  6743  6743 D AndroidRuntime: 
09-12 13:56:53.623  6743  6743 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 13:56:53.628  6743  6743 D AndroidRuntime: CheckJNI is OFF
09-12 13:56:53.644  6745  6745 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-12 13:56:53.880  6743  6743 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 13:56:53.893  1035  2030 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 13:56:53.910  1941  2949 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-12 13:56:53.914  1035  2030 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-12 13:56:53.915  1035  2030 D ActivityManager: setTaskToReturnTo : TaskRecord{1b9acabf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-12 13:56:53.915  1035  2030 D ActivityManager: setTaskToReturnTo : TaskRecord{1b9acabf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-12 13:56:53.917  1035  2030 D WindowStateEx: AppWindowTokenEx init.. 
09-12 13:56:53.918   346   359 E GBMv2   : DFP En is all cleared set to be enabled
09-12 13:56:53.952  1035  2030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6796 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 13:56:53.954  6743  6743 D AndroidRuntime: Shutting down VM
09-12 13:56:54.030  1941  2949 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-12 13:56:54.031  1941  2949 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1333c18 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-12 13:56:54.033  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-12 13:56:54.033  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{31b01671 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-12 13:56:54.080  6796  6796 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-12 13:56:54.150  6796  6796 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-12 13:56:54.171  6796  6796 I LibraryLoader: Loading: webviewchromium
,09-12 13:56:54.180  6796  6796 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 4331-4341)
09-12 13:56:54.181  6796  6796 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:56:54.197  1035  1426 V AlarmManager: ELAPSED_WAKEUP set : Alarm{8bb53db type 2 when 104346 com.google.android.gms} when 104346
,09-12 13:56:54.203  6796  6796 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c445186}
09-12 13:56:54.204  6796  6796 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:56:54.204  6796  6796 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:56:54.213  6796  6796 I BrowserStartupController: Initializing chromium process, renderers=0
09-12 13:56:54.214  6796  6796 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:56:54.229  6796  6796 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-12 13:56:54.230   324  2149 V AudioPolicyService: registerClient() client 0xb57d3c00, uid 10118
09-12 13:56:54.234  6796  6796 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-12 13:56:54.235  1035  1117 D BluetoothManagerService: Message: 20
09-12 13:56:54.235  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16fa45b6:true
09-12 13:56:54.235  6796  6796 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-12 13:56:54.254  6796  6796 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 13:56:54.254  6796  6796 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 13:56:54.254  6796  6796 I Adreno-EGL: Build Date: 12/12/14 금
09-12 13:56:54.254  6796  6796 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 13:56:54.254  6796  6796 I Adreno-EGL: Remote Branch: 
09-12 13:56:54.254  6796  6796 I Adreno-EGL: Local Patches: 
09-12 13:56:54.254  6796  6796 I Adreno-EGL: Reconstruct Branch: 
,09-12 13:56:54.319  6796  6831 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-12 13:56:54.324  6796  6796 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-12 13:56:54.337  6796  6796 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:56:54.342  6796  6796 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-12 13:56:54.345  6796  6796 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-12 13:56:54.347  6796  6796 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-12 13:56:54.347  6796  6796 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-12 13:56:54.358  6796  6796 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-12 13:56:54.371  6796  6796 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:56:54.371  6796  6796 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:56:54.399  6796  6843 D OpenGLRenderer: Render dirty regions requested: true
09-12 13:56:54.399  6796  6843 I OpenGLRenderer: Initialized EGL, version 1.4
09-12 13:56:54.404  6796  6843 D OpenGLRenderer: Enabling debug mode 0
,09-12 13:56:54.410  6796  6796 D Atlas   : Validating map...
09-12 13:56:54.413  1035  1940 D SplitWindow: check instance of lgWin Window{113b71c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 13:56:54.452  6796  6841 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:56:54.452  6796  6841 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:56:54.509  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +481ms (total +591ms)
09-12 13:56:54.509  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3968b58c u0 com.test.thalitest/.MainActivity t6} time:104671
,09-12 13:56:54.515  6796  6796 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26983e0d time:104676
09-12 13:56:54.517  1815  5261 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,09-12 13:56:54.577  1815  5261 I art     : Explicit concurrent mark sweep GC freed 23731(1508KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 1.015ms total 37.480ms
,09-12 13:56:54.614  1815  5261 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,09-12 13:56:54.621  6796  6796 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-12 13:56:54.650  6796  6796 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-12 13:56:54.650  6796  6796 I chromium: 
09-12 13:56:54.651  1815  5261 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-12 13:56:54.713  6796  6859 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434983936
,09-12 13:56:54.724  6796  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:56:54.724  6796  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:56:54.724  6796  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:56:54.724  6796  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:56:54.724  6796  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-12 13:56:54.725  6796  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d0a1541 added. We now have 1 listener(s)
,09-12 13:56:54.729  1035  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:56:54.730  6796  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-12 13:56:54.732  6796  6859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 13:56:54.733  6796  6859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:56:54.733  6796  6859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:56:54.738  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 13:56:54.739  6796  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377dead4 added. We now have 1 listener(s)
09-12 13:56:54.739  6796  6859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:56:54.744  1035  1544 D WifiService: New client listening to asynchronous messages
09-12 13:56:54.746  6796  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:56:54.746  6796  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 13:56:54.746  6796  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 13:56:54.746  6796  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 13:56:54.746  6796  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-12 13:56:54.750  6796  6859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:56:54.751  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 13:56:54.753  6796  6859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-12 13:56:54.759  6796  6859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:56:54.760  6796  6859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:56:54.760  6796  6859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 13:56:54.760  6796  6859 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:56:54.760  6796  6859 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 13:56:54.763  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:56:54.766  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:56:54.788  6796  6841 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-12 13:56:54.788  6796  6841 I chromium: 
,09-12 13:56:54.828  6796  6796 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:56:55.139  6745  6745 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:56:55.139  6745  6745 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:56:55.291  1035  1693 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6870 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
09-12 13:56:55.292  1035  1693 I ActivityManager: Killing 6243:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-12 13:56:55.379  1035  1867 W libprocessgroup: failed to open /acct/uid_10097/pid_6243/cgroup.procs: No such file or directory
09-12 13:56:55.394  6745  6745 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-12 13:56:55.429  6870  6870 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-12 13:56:55.443  6870  6870 I LockScreenSettings: New app installed broadcast received ..
,09-12 13:56:55.446  6870  6870 I LockScreenSettings: Number of installed packages  1
09-12 13:56:55.491  1035  1992 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6891 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 13:56:55.560  6891  6891 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:56:55.661   346   361 E GBMv2   : DFP En is all cleared set to be enabled
09-12 13:56:55.661   346   361 E GBMv2   : Set value is all cleared set the max
09-12 13:56:55.661   346   361 I GBMv2   : DFP Enabled. Ignore VFP set
,09-12 13:56:55.679  6796  6863 W jxcore-log: Initializing JXcore engine
09-12 13:56:55.679  6796  6863 W jxcore-log: JXcore engine is ready
,09-12 13:56:55.729  6863  6863 W Thread-796: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7354]" dev="sockfs" ino=7354 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-12 13:56:55.729  6863  6863 W Thread-796: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-12 13:56:55.729  6863  6863 W Thread-796: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9965]" dev="sockfs" ino=9965 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-12 13:56:55.729  6863  6863 W Thread-796: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-12 13:56:55.729  6863  6863 W Thread-796: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30586]" dev="sockfs" ino=30586 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-12 13:56:55.756  6796  6863 W jxcore-log: Starting JXcore engine
,09-12 13:56:55.763  1035  2030 I art     : Explicit concurrent mark sweep GC freed 27602(1331KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 11.919ms total 151.528ms
09-12 13:56:55.845  6796  6863 W jxcore-log: Platform android
09-12 13:56:55.845  6796  6863 W jxcore-log: 
09-12 13:56:55.845  6796  6863 W jxcore-log: Process ARCH arm
09-12 13:56:55.845  6796  6863 W jxcore-log: 
,09-12 13:56:55.981  1035  1693 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:56:56.032  6796  6863 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:56:56.032  6796  6863 I jxcore-log: 
09-12 13:56:56.033  6796  6863 W jxcore-log: JXcore engine is started
,09-12 13:56:56.036  1035  1693 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6920 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 13:56:56.040  6796  6859 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-12 13:56:56.048  6796  6796 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:56:56.103  6920  6920 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-12 13:56:56.103  6920  6920 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-12 13:56:56.107  5613  5613 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
09-12 13:56:56.119  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-12 13:56:56.156  1035  1050 I ActivityManager: Killing 6273:com.google.android.gm/u0a64 (adj 15): empty #17
,09-12 13:56:56.261  1035  1903 W libprocessgroup: failed to open /acct/uid_10064/pid_6273/cgroup.procs: No such file or directory
,09-12 13:56:56.319  1815  1815 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-12 13:56:56.323  1815  6939 I ConfigFetchService: running network task: configservice_periodic
09-12 13:56:59.210  6745  6745 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-12 13:56:59.213  1035  2031 I ActivityManager: Killing 6048:com.google.android.talk/u0a72 (adj 15): empty #17
09-12 13:56:59.280  1035  1867 W libprocessgroup: failed to open /acct/uid_10072/pid_6048/cgroup.procs: No such file or directory
,09-12 13:57:00.044  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-12 13:57:00.044  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
09-12 13:57:00.045  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-12 13:57:00.045  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,09-12 13:57:00.053  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
09-12 13:57:00.053  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
09-12 13:57:00.055  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
09-12 13:57:00.057  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
09-12 13:57:00.210  6745  6864 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-12 13:57:00.955  1035  1939 I ActivityManager: Killing 5758:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-12 13:57:00.971  5723  5723 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-12 13:57:00.972  5723  5723 W System.err: android.os.DeadObjectException
,09-12 13:57:00.973  5723  5723 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-12 13:57:00.973  5723  5723 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 13:57:00.973  5723  5723 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-12 13:57:00.973  5723  5723 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-12 13:57:00.973  5723  5723 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 13:57:00.973  5723  5723 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 13:57:00.973  5723  5723 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:00.973  5723  5723 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:00.973  5723  5723 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,09-12 13:57:00.973  5723  5723 W System.err: ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
,09-12 13:57:00.973  5723  5723 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,09-12 13:57:00.973  5723  5723 W System.err: ,	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:00.973  5723  5723 W System.err: ,	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:00.973  5723  5723 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704),
09-12 13:57:00.974  5723  5723 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,09-12 13:57:00.974  5723  5723 W System.err: android.os.DeadObjectException
,09-12 13:57:00.974  5723  5723 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-12 13:57:00.974  5723  5723 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 13:57:00.974  5723  5723 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-12 13:57:00.974  5723  5723 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,09-12 13:57:00.974  5723  5723 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 13:57:00.974  5723  5723 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 13:57:00.974  5723  5723 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:00.974  5723  5723 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:00.974  5723  5723 W System.err: 	,at android.os.Looper.loop(Looper.java:135)
09-12 13:57:00.974  5723  5723 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 13:57:00.974  5723  5723 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:00.974  5723  5723 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:00.974  5723  5723 W System.err: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:00.975  5723  5723 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 13:57:00.975  5723  5723 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-12 13:57:00.975  5723  5723 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-12 13:57:01.200  1035  2030 W libprocessgroup: failed to open /acct/uid_1000/pid_5758/cgroup.procs: No such file or directory
09-12 13:57:01.200  1035  2030 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-12 13:57:01.210  5723  5723 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-12 13:57:01.211  5723  5723 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-12 13:57:01.268  1035  1903 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 13:57:01.269  5723  5723 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-12 13:57:01.337  6966  6966 D UEI.SmartControl: Quickset Services start...
,09-12 13:57:01.340  6966  6966 I UEI.SmartControl: Manufacture = LGE
09-12 13:57:01.341  6966  6966 D UEI.SmartControl: Id = LGNevo
09-12 13:57:01.342  6966  6966 D UEI.SmartControl: File observer start...
09-12 13:57:01.342  6966  6966 E UEI.SmartControl: IR Port is disabled: false
09-12 13:57:01.342  6966  6966 D UEI.SmartControl: Starting file observer...
09-12 13:57:01.343  6966  6966 D UEI.SmartControl: Extracting JNI libs...
09-12 13:57:01.343  6966  6966 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-12 13:57:01.399  6966  6966 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-12 13:57:01.399  6966  6966 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-12 13:57:01.399  6966  6966 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-12 13:57:01.418  6966  6966 I UEI.SmartControl: --- Selecting new region: 6
,09-12 13:57:01.420  6966  6966 I UEI.SmartControl: Model = LG-D855
09-12 13:57:01.421  6966  6966 D UEI.SmartControl: QS Service created
09-12 13:57:01.429  6966  6966 I UEI.SmartControl: Service initServices...
09-12 13:57:01.431  6966  6966 D UEI.SmartControl: QS start get config
,09-12 13:57:01.439  1815  6570 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-12 13:57:01.441   316  6989 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:01.441   316  6989 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-12 13:57:01.441   316  6989 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-12 13:57:01.453  6966  6966 D UEI.SmartControl: Loading JNI Libs...
,09-12 13:57:01.667  6966  6966 I UEI.SmartControl: Supports setup maps: true
,09-12 13:57:01.670  6966  6966 D UEI.SmartControl: QS start statue = true Error code = 0
,09-12 13:57:01.670  6966  6966 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-12 13:57:01.671  6966  6966 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-12 13:57:01.671  6966  6966 I UEI.SmartControl: ### init IR Blaster...
09-12 13:57:01.676  6966  6966 D serial_port: Configuring serial port
09-12 13:57:01.679  6966  6966 E UEI.SmartControl: UEIBLaster setting for 616
09-12 13:57:01.680  6966  6966 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 13:57:01.680  6966  6966 I UEI.SmartControl: configuring settings for MAXQ616
09-12 13:57:01.680  6966  6966 I UEI.SmartControl: Get version...
09-12 13:57:01.680  1815  1815 I ConfigFetchService: launchTask
,09-12 13:57:01.697  6966  6991 D UEI.SmartControl: serial port data available: 21
,09-12 13:57:01.721  1035  2359 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:57:01.724  6966  6966 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-12 13:57:01.724  6966  6966 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 13:57:01.724  6966  6966 I UEI.SmartControl: QS saving settings...
09-12 13:57:01.724  6966  6966 D UEI.SmartControl: IR Blaster version: 25672567
09-12 13:57:01.730  1815  6570 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-12 13:57:01.738  6966  6991 D UEI.SmartControl: serial port data available: 4
,09-12 13:57:01.787  6966  6995 I UEI.SmartControl: Device manager: loading config....
,09-12 13:57:01.788  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-12 13:57:01.789  6966  6995 D UEI.SmartControl: ----------- loading internal config...
,09-12 13:57:01.792  6966  6966 E UEI.SmartControl: Services init done
09-12 13:57:01.792  6966  6966 D UEI.SmartControl: QS Service init finished
09-12 13:57:01.795  6966  6966 D UEI.SmartControl: QS Service version name: 2.1.91
09-12 13:57:01.795  6966  6966 D UEI.SmartControl: QS Service version code: 201091
09-12 13:57:01.796  6966  6966 D UEI.SmartControl: Service requested: Control
09-12 13:57:01.799  6966  6995 E UEI.SmartControl: Loading SETTINGS...
09-12 13:57:01.801  6966  6966 D UEI.SmartControl: Request IControl service: devices are loaded...
09-12 13:57:01.804  1035  1051 I ActivityManager: Killing 5723:com.lge.qremote/u0a112 (adj 15): empty #17
,09-12 13:57:01.809  6966  6995 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-12 13:57:01.825  6966  6994 I UEI.SmartControl: Notify AllClients services are ready: 0
09-12 13:57:01.825  6966  6994 D UEI.SmartControl: -----service ready thread exits
,09-12 13:57:01.910  1815  6570 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-12 13:57:01.921  1035  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_5723/cgroup.procs: No such file or directory
,09-12 13:57:01.926  6966  6966 D UEI.SmartControl: Internal service binding...
09-12 13:57:01.927  1815  1815 I ConfigFetchService: fetch service done; releasing wakelock
,09-12 13:57:01.929  1815  1815 I ConfigFetchService: stopping self
09-12 13:57:01.966  2206  2206 I ConfigService: onDestroy
,09-12 13:57:02.673  2790  2790 I MusicWidget: mDelayedStopHandler : unbind
,09-12 13:57:02.680  2126  2126 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-12 13:57:02.681  2126  2126 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-12 13:57:02.682  2126  2126 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-12 13:57:02.686  2126  2126 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-12 13:57:02.687  2126  2126 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-12 13:57:02.687  2126  2126 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,09-12 13:57:02.694  2126  2126 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-12 13:57:02.695  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-12 13:57:02.697  1035  1903 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@24e310a4com.lge.music.MediaPlaybackService$5@26983e0d
09-12 13:57:02.698  2126  2126 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-12 13:57:02.699  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.701  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-12 13:57:02.706  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.709  2126  2126 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@18840012
09-12 13:57:02.709  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.710  2126  2126 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-12 13:57:02.710  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.710  2126  2126 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-12 13:57:02.711  2126  2126 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-12 13:57:02.711  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.711  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.712  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.713  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-12 13:57:02.713  2126  2126 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-12 13:57:02.716  2126  2126 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-12 13:57:02.718  2126  2126 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-12 13:57:02.718  2126  2126 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-12 13:57:02.718  2126  2126 V MediaPlayer[Native]: reset
09-12 13:57:02.724  2126  2126 V MediaPlayer[Native]: setListener
09-12 13:57:02.724  2126  2126 V MediaPlayer[Native]: disconnect
09-12 13:57:02.724  2126  2126 V MediaPlayer[Native]: destructor
09-12 13:57:02.725   324  1382 V AudioFlinger: releasing 18 from 2126 for -1
09-12 13:57:02.725   324  1382 V AudioFlinger:  decremented refcount to 0
09-12 13:57:02.725   324  1382 V AudioFlinger: purging stale effects
,09-12 13:57:02.726  2126  2126 V MediaPlayer[Native]: disconnect
09-12 13:57:02.728  2126  2126 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-12 13:57:02.729  2126  2126 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-12 13:57:02.729  2126  2126 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-12 13:57:02.730  2126  2126 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-12 13:57:02.731  2126  2126 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-12 13:57:02.731  2126  2126 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-12 13:57:02.731  2126  2126 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 482906562
09-12 13:57:02.731  2126  2126 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 482906562
09-12 13:57:02.744  2126  2126 I SmartShareClient: [SmartShareManagerClient] terminate service: 2126/MediaPlaybackService/303411656
09-12 13:57:02.747  2126  2126 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-12 13:57:02.748  2126  2126 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1bdb5bd3
,09-12 13:57:02.752  2126  2126 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-12 13:57:02.752  2126  2126 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-12 13:57:02.753  2126  2126 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-12 13:57:02.753  2126  2126 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-12 13:57:02.756  1035  1940 I ActivityManager: Killing 5658:com.android.calendar/u0a13 (adj 15): empty #17
09-12 13:57:02.757  2126  2126 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
09-12 13:57:02.850  1035  1973 W libprocessgroup: failed to open /acct/uid_10013/pid_5658/cgroup.procs: No such file or directory
,09-12 13:57:02.962  1035  1426 D PowerManagerServiceEx: acquireWakeLockInternal: lock=219467340, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-12 13:57:02.995  2576  2576 D [Concierge]Service: onStartCommand(). Type : 9
,09-12 13:57:03.007  4993  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-12 13:57:03.016  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=219467340 [*alarm*], flags=0x0
,09-12 13:57:06.648  1035  1095 I ActivityManager: Waited long enough for: ServiceRecord{3ef1ce3d u0 com.google.android.gms/.wearable.service.WearableService}
,09-12 13:57:06.778  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 13:57:06.778  6796  6863 I jxcore-log: 
,09-12 13:57:06.782  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 13:57:06.782  6796  6863 I jxcore-log: 
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:06.785  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:06.788  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:06.788  6966  6996 D UEI.SmartControl: Internal timer expired: 1
09-12 13:57:06.788  6966  6996 D UEI.SmartControl: unbind internal service
09-12 13:57:06.790  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 13:57:06.790  6796  6863 I jxcore-log: 
09-12 13:57:06.791  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 13:57:06.791  6796  6863 I jxcore-log: 
,09-12 13:57:06.804  6966  6966 D UEI.SmartControl: Service.onUnbind: IControl
09-12 13:57:06.806  6966  6966 D UEI.SmartControl: Service.onDestroy
09-12 13:57:06.806  6966  6966 D UEI.SmartControl: Lock is in USE false
09-12 13:57:06.806  6966  6966 D UEI.SmartControl: unbind internal service
09-12 13:57:06.807  6966  6966 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@18840012
09-12 13:57:06.807  6966  6966 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-12 13:57:06.810  6966  6992 D serial_port: close(fd = 25)
,09-12 13:57:06.811  6966  6966 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-12 13:57:06.811  6966  6966 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-12 13:57:06.811  6966  6966 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-12 13:57:06.811  6966  6966 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-12 13:57:06.811  6966  6966 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-12 13:57:06.811  6966  6966 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-12 13:57:06.811  6966  6966 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-12 13:57:06.811  6966  6966 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:06.811  6966  6966 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 13:57:06.811  6966  6966 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 13:57:06.811  6966  6966 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:06.812  6966  6966 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:06.812  6966  6966 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:06.812  6966  6966 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 13:57:06.812  6966  6966 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@18840012
09-12 13:57:06.814  6966  6992 I UEI.SmartControl: Serial port is closed.
09-12 13:57:06.814  6966  6966 I UEI.SmartControl: Serial port is closed.
09-12 13:57:06.814  6966  6966 I UEI.SmartControl: Serial port is closed.
09-12 13:57:06.815  6966  6966 D UEI.SmartControl: Blaster closed
09-12 13:57:06.815  6966  6966 D UEI.SmartControl: Shut down QS...
09-12 13:57:06.815  6966  6966 D UEI.SmartControl: Stopping QS lib
09-12 13:57:06.815  6966  6966 D UEI.SmartControl: QS lib stop result = true
09-12 13:57:06.815  6966  6966 D UEI.SmartControl: Stopped QS lib
09-12 13:57:06.816  6966  6966 D UEI.SmartControl: Stopped file observer...
09-12 13:57:06.816  6966  6966 D UEI.SmartControl: QS shutdown complete
09-12 13:57:07.307  6796  6863 I jxcore-log: Unit Test app is loaded
09-12 13:57:07.307  6796  6863 I jxcore-log: 
,09-12 13:57:07.316  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:07.316  6796  6863 I jxcore-log: 
09-12 13:57:07.320  6796  6863 D executeNativeTests: Running unit tests
09-12 13:57:07.321  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:57:07.321  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20f18586 added. We now have 2 listener(s)
09-12 13:57:07.321  1035  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:07.324  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 13:57:07.324  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:57:07.324  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:57:07.324  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:57:07.324  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2928de47 added. We now have 2 listener(s)
09-12 13:57:07.324  6796  6863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:57:07.324  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:57:07.326  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:07.329  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:07.330  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:07.330  6796  6863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:57:07.331  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:07.332  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:07.338  6796  6796 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 13:57:12.769  2126  2126 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19985
,09-12 13:57:15.984  1035  1426 V AlarmManager: RTC_WAKEUP set : Alarm{7711f11 type 0 when 1473681428225 com.android.vending} when 1473681428225
,09-12 13:57:16.103  1035  1992 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:57:16.271  6703  6703 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-12 13:57:17.488  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:57:17.488  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d added. We now have 3 listener(s)
,09-12 13:57:17.491  1035  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:17.494  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 13:57:17.494  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:57:17.494  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:57:17.495  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:57:17.495  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 added. We now have 3 listener(s)
09-12 13:57:17.495  6796  6863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:57:17.495  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:57:17.499  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:17.503  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:17.507  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.507  6796  6863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:57:17.510  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.512  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.518  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 13:57:17.523  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:17.523  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:17.523  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:17.526  6796  6863 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 13:57:17.527  6796  6863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:57:17.527  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:57:17.527  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:17.527  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:17.527  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:17.528  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.528  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.529  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.529  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:57:17.529  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d removed from the list
09-12 13:57:17.529  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.529  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 removed from the list
09-12 13:57:17.529  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.529  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.532  6796  6863 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 13:57:17.533  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.533  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.533  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.533  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.533  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.533  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.533  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.533  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.533  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release,: 2 listener(s) left
,09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:57:17.549  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:57:17.550  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.550  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.550  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.550  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.550  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.550  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.550  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.550  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.550  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.551  6796  6863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:57:17.561  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:17.564  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:17.565  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.566  6796  6863 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:57:17.569  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.571  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.572  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:17.572  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:57:17.573  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:57:17.573  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.573  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:17.577  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:57:17.580  1035  1751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:17.587  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:57:17.593  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:17.597  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-12 13:57:17.599  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:17.600  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.602  6796  6863 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 13:57:17.603  6796  6863 I io.jxcore.node.ConnectionHelper: start: OK
09-12 13:57:17.604  6796  6863 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-12 13:57:17.604  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:57:17.604  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:57:17.607  6796  6863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 13:57:17.607  6796  6863 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-12 13:57:17.607  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:17.607  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:57:17.607  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:57:17.610  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.610  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:17.616  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:17.617  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.618  6796  6863 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 13:57:17.619  6796  6863 I io.jxcore.node.ConnectionHelper: start: OK
09-12 13:57:17.619  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.619  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.619  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.619  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.619  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.619  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.619  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.619  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:17.623  6796  6863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 13:57:17.626  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:17.635  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:17.641  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.641  6796  6863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:57:17.642  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:17.642  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:57:17.642  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:57:17.642  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.642  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:17.645  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.649  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:17.655  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:17.655  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.657  6796  6863 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 13:57:17.657  6796  6863 I io.jxcore.node.ConnectionHelper: start: OK
09-12 13:57:17.657  6796  6863 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-12 13:57:17.657  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:57:17.657  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:57:17.661  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.661  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.661  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.661  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.661  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.661  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.661  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.661  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:17.663  6796  6863 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 13:57:17.663  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.664  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.664  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.664  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.664  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.664  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.664  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.664  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.664  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.665  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:57:17.666  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.666  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.666  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.666  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.666  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.666  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.666  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.666  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.666  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.667  6796  6863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 13:57:17.667  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.667  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.667  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.667  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.667  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.667  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.667  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.667  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMan,ager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.667  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.669  6796  6863 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 13:57:17.669  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.669  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.669  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-12 13:57:17.669  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.669  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.669  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.669  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.669  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:17.669  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.670  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:57:17.670  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:17.670  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:17.670  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:57:17.670  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:17.670  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:17.670  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:57:17.670  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:17.670  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:57:17.670  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.671  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.671  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.671  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.671  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.671  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.671  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.671  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.671  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:17.672  6796  6863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:17.672  6796  6863 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:57:17.672  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:57:17.675  6796  6863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:17.676  6796  6863 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:57:17.676  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:57:17.677  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:57:17.677  6796  6863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 13:57:17.677  6796  6863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:57:17.677  6796  6863 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:57:17.678  6796  6863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:17.678  6796  6863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:57:17.678  6796  6863 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:57:17.678  6796  6863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:17.678  6796  6863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:57:17.678  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 13:57:17.687  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 13:57:17.689  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 13:57:17.689  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 13:57:17.690  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 13:57:17.690  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:57:17.690  6796  6863 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 13:57:17.690  6796  6863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:17.690  6796  6863 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 13:57:17.691  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.691  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.691  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.691  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 13:57:17.692  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.692  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.692  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.692  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.692  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.692  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.693  6796  6863 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 13:57:17.693  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.693  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.693  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.693  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.693  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.693  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.693  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.693  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.693  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.694  6796  7044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 893)
09-12 13:57:17.694  6796  6863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:57:17.695  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.695  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.695  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.695  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.695  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.695  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.695  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.695  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.695  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.696  6796  6863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 13:57:17.696  6796  6863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:57:17.697  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:57:17.698  6796  6863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:57:17.698  6796  6863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:57:17.698  6796  6863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:57:17.698  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:57:17.698  6796  6863 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:57:17.706  6796  6863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:57:17.706  6796  6863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:57:17.706  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:57:17.706  6796  6863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:57:17.706  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.706  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.706  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.706  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.706  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.706  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.706  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.706  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.706  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.707  6796  6863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 13:57:17.708  6796  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 893
09-12 13:57:17.708  6796  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 893)
09-12 13:57:17.709  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.710  6796  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 893)
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:17.713  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:17.714  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.715  6796  6863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:57:17.716  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.717  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:17.717  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:57:17.717  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:57:17.717  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.717  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:17.730  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.731  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:17.731  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.733  6796  6863 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 13:57:17.733  6796  6863 I io.jxcore.node.ConnectionHelper: start: OK
09-12 13:57:17.733  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.733  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.733  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:17.733  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.733  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.733  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.733  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.733  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.736  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.736  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.736  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.736  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.736  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.736  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.736  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.736  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.736  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.738  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:17.739  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:17.743  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:57:17.744  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:57:17.744  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:57:17.747  6796  6796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:57:17.747  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:17.747  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:57:17.750  1035  1867 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:17.751  6796  7047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:17.752  4342  4359 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-12 13:57:17.752  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.753  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:57:17.753  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:57:17.753  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:17.753  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.753  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:17.754  6796  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:17.754  6796  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:17.754  6796  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:57:17.755  6796  6796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:57:17.756  6796  6796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:17.756  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.756  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.756  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:17.757  6796  6863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:17.757  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:57:17.758  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:57:17.760  6796  6863 D BluetoothLeScanner: could not find callback wrapper
09-12 13:57:17.760  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:57:17.760  6796  6863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:57:17.760  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.760  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.761  6796  6863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:57:17.762  6796  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:17.762  6796  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:17.762  6796  6796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:57:17.762  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.762  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.762  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.762  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.763  6796  6863 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 13:57:17.764  6796  6863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:57:17.764  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:57:17.764  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:17.764  6796  6863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:17.764  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.765  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.765  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.765  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.765  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.765  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.765  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.765  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.765  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.768  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:17.769  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:17.770  1035  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:17.771  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.771  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.771  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.771  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.771  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.771  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.771  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.771  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.771  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.773  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:17.773  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.773  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.773  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3237020d not in the list
09-12 13:57:17.773  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:17.773  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a05c2 not in the list
09-12 13:57:17.773  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:17.773  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:17.773  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:17.775  6796  6863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 13:57:17.775  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:57:17.775  6796  6863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 13:57:17.775  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:57:17.775  6796  6863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:57:17.775  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:57:17.777  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:57:17.777  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 13:57:17.779  6796  6863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:57:17.779  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:57:17.780  6796  6863 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:57:17.780  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:57:17.780  6796  6863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 13:57:17.780  6796  6863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-12 13:57:17.787  6796  6863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 13:57:17.787  6796  6863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 13:57:17.789  6796  6863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:57:17.789  6796  6863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:57:17.789  6796  6863 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:57:17.789  6796  6863 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 13:57:17.791  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:57:17.791  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1cc828 added. We now have 3 listener(s)
09-12 13:57:17.791  1035  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:17.793  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 13:57:17.793  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:57:17.793  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:57:17.794  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:57:17.794  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272d9941 added. We now have 3 listener(s)
09-12 13:57:17.794  6796  6863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:57:17.794  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:57:17.797  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:17.800  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:17.801  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:17.801  6796  6863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:57:17.802  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.803  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:17.804  6796  6863 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 13:57:17.805  1035  2006 D WifiServiceImplEx: setWifiEnabled: true pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 13:57:17.805  1035  2006 D WifiService: setWifiEnabled: true pid=6796, uid=10118
09-12 13:57:17.805  1035  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:17.814  1035  1939 D WifiServiceImplEx: setWifiEnabled: false pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 13:57:17.815  1035  1939 D WifiService: setWifiEnabled: false pid=6796, uid=10118
09-12 13:57:17.815  1035  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:17.829  6796  7044 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,09-12 13:57:17.829  6796  7044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 893)
09-12 13:57:17.835  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 13:57:17.835  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 13:57:17.835  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-12 13:57:17.836  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:17.837  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:17.837  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:17.837  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:17.839  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
,09-12 13:57:17.839  1035  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 13:57:17.839  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:57:17.839  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 13:57:17.840  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 13:57:17.840  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 13:57:17.855  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 13:57:17.856  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.856  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.856  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 13:57:17.856  2673  2673 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 13:57:17.857  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 13:57:17.857  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:17.857  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:17.858  1035  2859 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.858   316   893 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:57:17.916  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 13:57:17.917  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-12 13:57:17.919  1035  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-12 13:57:17.919  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.919  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.920  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:57:17.920  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.920  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,09-12 13:57:17.929  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-12 13:57:17.934  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-12 13:57:17.934  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:17.934  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-12 13:57:17.937  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:17.937  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:17.937  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 13:57:17.939  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:17.949  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-12 13:57:17.949  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:17.949  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:17.949  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-12 13:57:17.951  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:17.951  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 13:57:17.951  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.951  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.951  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-12 13:57:17.951  1035  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@27ccd994
09-12 13:57:17.951  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.951  1035  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.952  1035  1537 D LGWifiP2pService: P2pDisablingState
09-12 13:57:17.952  1035  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.952  1035  1537 D LGWifiP2pService: p2p socket connection lost
09-12 13:57:17.952  1035  1537 D LGWifiP2pService: P2pDisabledState
09-12 13:57:17.953  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:17.953  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 13:57:17.953  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:17.953  1941  1941 D WfdsService: WifiP2pState is changed : false
09-12 13:57:17.953  1941  2316 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-12 13:57:17.953  1941  2316 D WfdsService: Set the WFDS Monitor: false
09-12 13:57:17.954  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:17.954  1941  2316 D WfdsMonitor: WFDS Monitor is stopped
09-12 13:57:17.954  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:17.954  1941  2316 D WfdsService: STATE : WfdsDisabledState - enter
09-12 13:57:17.955  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:17.955  1941  2320 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-12 13:57:17.955  1941  2716 D CtrlSupplicant: Received on exit socket, terminate
09-12 13:57:17.955  1941  2716 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-12 13:57:17.955  1941  2716 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-12 13:57:17.955  1941  2716 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-12 13:57:17.955  1941  2316 W WfdsService: DefaultState - msg [9445378] is not handled
09-12 13:57:17.955  1035  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:57:17.956  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-12 13:57:17.957  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.957  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.957  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 13:57:17.958  2673  2673 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 13:57:17.958  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 13:57:17.958  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:17.959  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:17.961  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnec,tedToProvisioningNetwork: false]
09-12 13:57:17.961  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:17.961  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:17.969   316   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:57:17.969  1035  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-12 13:57:17.969  1035  1545 D DSQN    : disableDataServiceNotify
09-12 13:57:17.969  1035  1545 D DSQN    : stop dsqn bin
09-12 13:57:17.970   316  7067 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-12 13:57:17.970  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-12 13:57:17.970  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-12 13:57:17.971  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:17.972  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-12 13:57:17.973  1035  1538 D WifiNative-p2p0: doBoolean: TERMINATE
09-12 13:57:17.973  1035  1538 D WifiNative-p2p0: TERMINATE: returned true
09-12 13:57:17.973  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:17.973  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:17.973  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:17.975  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:17.975  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:17.975  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 13:57:17.981  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 13:57:17.981  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:17.982  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:17.988  1035  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 13:57:17.988  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:17.988  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:17.989  1035  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:17.989  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-12 13:57:17.989  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.989  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:17.989  1035  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 13:57:17.989  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 13:57:17.990  1035  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-12 13:57:17.990  1035  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 13:57:17.990  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 13:57:18.012  1035  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7068 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 13:57:18.014  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:18.014  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 13:57:18.015  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 13:57:18.015  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 13:57:18.015  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 13:57:18.016  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 13:57:18.016  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 13:57:18.017  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-12 13:57:18.018  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-12 13:57:18.019  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:18.019  1035  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:18.019  1035  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:18.019  1035  1545 D NetworkManagementService: Removing idletimer
09-12 13:57:18.020  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:18.020  1035  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:18.020  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 13:57:18.020  1035  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 13:57:18.020  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:18.020  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-12 13:57:18.021  1035  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:18.021  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:18.022  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:18.022  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:18.022  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 13:57:18.022  1035  1035 D LocSvc_java:, getAGpsConnectionInfo connType - 4
09-12 13:57:18.022  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 13:57:18.022  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-12 13:57:18.025  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:18.028  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:18.029  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:18.031  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:18.032  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:18.040  2673  2673 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 13:57:18.040  2673  2673 I wpa_supplicant: monitor socket send errors count : 1
09-12 13:57:18.040  2673  2673 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,09-12 13:57:18.041  1035  2713 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-12 13:57:18.041  1035  2713 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-12 13:57:18.044  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 13:57:18.045  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:18.045  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:18.046  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:18.065  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 13:57:18.066  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:18.067  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:18.075  1035  2859 D DhcpStateMachine: StoppedState
09-12 13:57:18.075  1035  2859 D DhcpStateMachine: StoppedState{ when=-117ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:18.076  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-12 13:57:18.076  1035  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-12 13:57:18.078  2673  2673 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:57:18.078  1035  2713 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-12 13:57:18.078  1035  2713 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:57:18.078  1035  2713 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:57:18.078  1035  2713 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-12 13:57:18.078  2673  2673 W wpa_supplicant: USIM:  scard_deinit function
09-12 13:57:18.079  1035  2713 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:18.079  1035  2713 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:18.079  1035  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128228
09-12 13:57:18.079  1035  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128228
09-12 13:57:18.079  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=128228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 13:57:18.080  1035  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=128229  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 13:57:18.080  1035  1117 D Tethering: InitialState.processMessage what=4
09-12 13:57:18.081  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:18.082  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:18.082  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:18.094  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-12 13:57:18.097  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:18.098  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:18.132  1035  1867 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=7089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 13:57:18.133  1035  1867 I ActivityManager: Killing 6328:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-12 13:57:18.169  2673  2673 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-12 13:57:18.170  1035  2713 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-12 13:57:18.170  1035  2713 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-12 13:57:18.171  1035  2713 D WifiMonitor: Disconnecting from the supplicant, no more events
09-12 13:57:18.172  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-12 13:57:18.179  1035  1940 W libprocessgroup: failed to open /acct/uid_10014/pid_6328/cgroup.procs: No such file or directory
,09-12 13:57:18.212  7089  7089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:57:18.212  7089  7089 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-12 13:57:18.212  7089  7089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 13:57:18.213  7089  7089 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,09-12 13:57:18.214  7089  7089 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-12 13:57:18.215  7089  7089 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:57:18.263  6796  6796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:57:18.275  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-12 13:57:18.275  1035  1538 D WifiOffDelayIfNotUsed: stopMonitoring
09-12 13:57:18.276  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:18.276  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:18.276  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:18.276  1941  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-12 13:57:18.276  1941  2316 D WfdsService: Set the WFDS Monitor: false
09-12 13:57:18.276  1941  2316 D WfdsMonitor: WFDS Monitor is stopped
09-12 13:57:18.278  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:18.279  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-12 13:57:18.284  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-12 13:57:18.285  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:18.285  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-12 13:57:18.285  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:18.292  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:18.294  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:18.295  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:18.343  1035  1693 D WifiServiceImplEx: setWifiEnabled: true pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-12 13:57:18.345  1035  1693 D WifiService: setWifiEnabled: true pid=6796, uid=10118
09-12 13:57:18.345  1035  1693 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:18.350  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:18.359  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 13:57:18.359  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 13:57:18.359  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-12 13:57:18.403  7089  7089 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 13:57:18.404  7089  7089 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 13:57:18.415  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 13:57:18.478  1035  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-12 13:57:18.478  1035  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-12 13:57:18.479  1035  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7112 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-12 13:57:18.482  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-12 13:57:18.482  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 13:57:18.483  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-12 13:57:18.483  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 13:57:18.483  1035  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-12 13:57:18.483  1035  1538 E WifiHW  : unknown target_country: EU , set to default
09-12 13:57:18.483  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-12 13:57:18.483  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-12 13:57:18.483  1035  1538 I WifiUtil: gEnableBmps=1
09-12 13:57:18.484  1035  1051 I ActivityManager: Killing 6438:com.android.defcontainer/u0a4 (adj 15): empty #17
09-12 13:57:18.523  1035  1903 W libprocessgroup: failed to open /acct/uid_10004/pid_6438/cgroup.procs: No such file or directory
,09-12 13:57:18.554  7112  7112 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-12 13:57:18.581  7112  7112 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-12 13:57:18.616  7112  7112 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-12 13:57:18.616  7112  7112 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,09-12 13:57:18.617  7112  7112 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-12 13:57:18.617  7112  7112 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-12 13:57:18.618  7112  7112 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,09-12 13:57:18.622  7112  7112 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-12 13:57:18.631  7112  7112 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-12 13:57:18.639  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:18.644  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:18.666  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 13:57:18.669  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:18.672  7112  7112 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-12 13:57:18.672  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 13:57:18.672  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:18.672  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:18.674  7112  7112 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-12 13:57:18.676  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:18.687  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:18.696  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:18.697  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:18.700  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 13:57:18.703  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:18.706  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 13:57:18.706  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:18.706  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:18.710  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:18.719  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:18.727  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:18.728  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:18.730  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 13:57:18.794  1035  2030 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7132 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-12 13:57:18.861  1035  2006 D WifiServiceImplEx: setWifiEnabled: true pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 13:57:18.862  1035  2006 D WifiService: setWifiEnabled: true pid=6796, uid=10118
09-12 13:57:18.863  1035  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:18.864  1035  1544 D WifiController: Mismatch in the state 1
,09-12 13:57:18.897  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 13:57:18.901  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:18.909  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:18.930  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:18.930  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 13:57:18.930  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 13:57:18.931  7089  7089 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 13:57:18.931  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-12 13:57:18.934  7132  7151 W FormManager: Network not available. Please check & try again.,
09-12 13:57:18.946  7089  7089 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 13:57:18.946  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,09-12 13:57:18.946  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 13:57:18.946  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 13:57:18.946  7089  7089 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 13:57:18.947  7089  7089 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-12 13:57:18.961  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-12 13:57:18.964  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:18.968  7132  7152 V FormManager: Network unavailable.
09-12 13:57:18.969  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:18.975  7132  7152 V FormManager: Network unavailable.
09-12 13:57:18.976  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 13:57:18.987  7068  7068 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-12 13:57:18.987  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:18.987  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:18.990  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:18.994  4834  7162 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 13:57:18.995  4834  7161 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:19.000  7132  7164 W FormManager: Network not available. Please check & try again.
,09-12 13:57:19.002  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:19.006  4834  7162 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:19.007  7132  7165 V FormManager: Network unavailable.
09-12 13:57:19.013  7132  7165 V FormManager: Network unavailable.
09-12 13:57:19.018  1035  1939 I ActivityManager: Killing 6580:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-12 13:57:19.048  1035  2031 W libprocessgroup: failed to open /acct/uid_10008/pid_6580/cgroup.procs: No such file or directory
,09-12 13:57:19.054  7112  7112 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-12 13:57:19.055  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-12 13:57:19.055  7112  7112 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-12 13:57:19.095  7112  7112 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:57:19.095  7112  7112 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:57:19.106  7112  7112 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-12 13:57:19.109  7112  7112 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-12 13:57:19.109  7112  7112 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-12 13:57:19.109  7112  7112 V SoundPool: doLoad: loading sample sampleID=1
,09-12 13:57:19.112  7112  7168 V SoundPool: Start decode
09-12 13:57:19.113  7112  7168 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-12 13:57:19.115   324  1383 V MediaPlayerService: decode(22, 10857164, 17813)
09-12 13:57:19.115   324  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-12 13:57:19.115   324  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-12 13:57:19.115   324  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-12 13:57:19.115   324  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-12 13:57:19.115   324  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-12 13:57:19.115   324  1383 V MediaPlayerService: player type = 3
09-12 13:57:19.116   324  1383 V AwesomePlayer: AwesomePlayer create()
09-12 13:57:19.116  7112  7112 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-12 13:57:19.116   324  1383 V AwesomePlayer: reset_l() 
09-12 13:57:19.117   324  1383 V AwesomePlayer: cancelPlayerEvents
09-12 13:57:19.117   324  1383 V AwesomePlayer: setAudioSink() 
09-12 13:57:19.117   324  1383 V AwesomePlayer: reset_l() 
09-12 13:57:19.117   324  1383 V AudioCache: notify(0xb5474600, 8, 0, 0)
09-12 13:57:19.117   324  1383 V AudioCache: ignored
09-12 13:57:19.117   324  1383 V AwesomePlayer: cancelPlayerEvents
09-12 13:57:19.117   324  1383 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-12 13:57:19.117   324  1383 V AwesomePlayer: setDataSource_l dataSource
09-12 13:57:19.117   324  1383 V LGParserOSAL: SniffLGParser start
09-12 13:57:19.118   324  1383 V LGParserOSAL: MainType:5, SubType=0
09-12 13:57:19.118   324  1383 V LGParserOSAL: #### check Mime : application/ogg
09-12 13:57:19.118   324  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-12 13:57:19.118   324  1383 E MediaExtractor: Use LGExtractor :application/ogg 
09-12 13:57:19.145  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:19.146  1035  1117 D Tethering: InitialState.processMessage what=4
09-12 13:57:19.147  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:19.147   316   893 D SoftapController: Softap fwReload - Ok
,09-12 13:57:19.153  1035  1538 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (660ms)
09-12 13:57:19.156   316   893 D CommandListener: Setting iface cfg
09-12 13:57:19.156   316   893 D CommandListener: Trying to bring down wlan0
09-12 13:57:19.157   316   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:57:19.159  1035  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-12 13:57:19.149  7170  7170 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:19.149  7170  7170 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:19.176   324  1383 V LGParserOSAL: supported mime: application/ogg
09-12 13:57:19.176   324  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-12 13:57:19.176   324  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-12 13:57:19.176   324  1383 V AwesomePlayer: mBitrate = -1 bits/sec
09-12 13:57:19.176   324  1383 V AwesomePlayer: AudioTrack Setting
09-12 13:57:19.176   324  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-12 13:57:19.176   324  1383 V AwesomePlayer: setAudioSource() 
09-12 13:57:19.176   324  1383 V MediaPlayerService: prepare
09-12 13:57:19.176   324  1383 V AwesomePlayer: prepareAsync_l() 
09-12 13:57:19.177   324  1383 V MediaPlayerService: wait for prepare
09-12 13:57:19.177  6966  6966 D UEI.SmartControl: QS Service created
,09-12 13:57:19.187   324  7171 V AwesomePlayer: onPrepareAsyncEvent() 
09-12 13:57:19.187   324  7171 V AwesomePlayer: initAudioDecoder() 
09-12 13:57:19.187   324  7171 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 13:57:19.187   324  7171 V AudioSystem: isOffloadSupported()
09-12 13:57:19.187   324  7171 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-12 13:57:19.187   324  7171 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 13:57:19.187   324  7171 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 13:57:19.187   324  7171 V AwesomePlayer: getUseOffload() = 0 
09-12 13:57:19.187   324  7171 V OMXCodec: OMXCodec::Create
09-12 13:57:19.187   324  7171 V OMXCodec: findMatchingCodecs()
09-12 13:57:19.187   324  7171 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-12 13:57:19.188   324  7171 V OMXCodec: matchingCodecs.size()=1
09-12 13:57:19.188   324  7171 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-12 13:57:19.189  7112  7112 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-12 13:57:19.194  7170  7170 I wpa_supplicant: Successfully initialized wpa_supplicant
09-12 13:57:19.196  6966  6966 I UEI.SmartControl: Service initServices...
,09-12 13:57:19.196  6966  6966 D UEI.SmartControl: QS start get config
09-12 13:57:19.200   324  7171 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-12 13:57:19.200   324  7171 V LGCodecAdapter: LG Codec Adapter start
09-12 13:57:19.200   324  7171 V OMXCodec: OMXCodec Createtor
09-12 13:57:19.200   324  7171 V OMXCodec: setComponentRole
09-12 13:57:19.200   324  7171 V OMXCodec: configureCodec protected=0
,09-12 13:57:19.200   324  7171 V LGCodecAdapter: called getLGCodecSpecificData
09-12 13:57:19.200   324  7171 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-12 13:57:19.200   324  7171 V LGCodecOSAL: Called LGconfigureCodecMETA
09-12 13:57:19.200   324  7171 V LGCodecOSAL: Called LGconfigureCodecMSG
09-12 13:57:19.200   324  7171 V LGCodecOSAL: Not support LGCodec
09-12 13:57:19.201   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-12 13:57:19.201   324  7171 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-12 13:57:19.201   324  7171 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-12 13:57:19.201   324  7171 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-12 13:57:19.201   324  7171 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 13:57:19.201   324  7171 V AudioSystem: isOffloadSupported()
09-12 13:57:19.201   324  7171 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-12 13:57:19.201   324  7171 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 13:57:19.201   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-12 13:57:19.201   324  7171 V OMXCodec: init()
09-12 13:57:19.201   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-12 13:57:19.201   324  7171 V OMXCodec: allocateBuffers
09-12 13:57:19.201   324  7171 V OMXCodec: allocateBuffersOnPort portIndex=0
09-12 13:57:19.201   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-12 13:57:19.202   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
09-12 13:57:19.202   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
09-12 13:57:19.202   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
09-12 13:57:19.202   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-12 13:57:19.202   324  7171 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 13:57:19.202   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-12 13:57:19.202   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-12 13:57:19.203   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-12 13:57:19.203   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-12 13:57:19.203   324  7171 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
09-12 13:57:19.203   324  7171 V OMXCodec: init() mAsyncCompletion wait!!! 
09-12 13:57:19.203   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-12 13:57:19.203   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 13:57:19.203   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-12 13:57:19.204   324  7171 V OMXCodec: init() mAsyncCompletion wait!!! 
09-12 13:57:19.204   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-12 13:57:19.204   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-12 13:57:19.204   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-12 13:57:19.204   324  7171 V OMXCodec: init() mAsyncCompletion wait free! 
09-12 13:57:19.204   324  7171 V AwesomePlayer: finishAsyncPrepare_l() 
09-12 13:57:19.204   324  7171 V AudioCache: notify(0xb5474600, 5, 0, 0)
09-12 13:57:19.204   324  7171 V AudioCache: ignored
09-12 13:57,:19.204   324  7171 V AudioCache: notify(0xb5474600, 1, 0, 0)
09-12 13:57:19.204   324  7171 V AudioCache: prepared
09-12 13:57:19.204   324  1383 V AudioCache: wait - success
09-12 13:57:19.204   324  1383 V MediaPlayerService: start
09-12 13:57:19.204   324  1383 V AwesomePlayer: play_l() 
09-12 13:57:19.204   324  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-12 13:57:19.204   324  1383 V AwesomePlayer: createAudioPlayer_l
09-12 13:57:19.204   324  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
09-12 13:57:19.204   324  1383 V AwesomePlayer: startAudioPlayer_l() 
09-12 13:57:19.204   324  1383 D AudioPlayer: start of Playback, useOffload 0
09-12 13:57:19.204   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 13:57:19.204   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 13:57:19.208   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-12 13:57:19.208   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-12 13:57:19.209   324  7177 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 13:57:19.209   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-12 13:57:19.210   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
,09-12 13:57:19.210   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-12 13:57:19.210   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-12 13:57:19.210   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c06f0 on output port
09-12 13:57:19.210   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-12 13:57:19.210   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-12 13:57:19.212   324  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-12 13:57:19.212   324  1383 V AudioCache: notify(0xb5474600, 6, 0, 0)
09-12 13:57:19.212   324  1383 V AudioCache: ignored
09-12 13:57:19.212   324  1383 V MediaPlayerService: wait for playback complete
09-12 13:57:19.213  7112  7112 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 13:57:19.213  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 13:57:19.219   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.219   324  7178 V AudioCache: memcpy(0xb0426000, 0xb16ed000, 4096)
,09-12 13:57:19.221   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.221   324  7178 V AudioCache: memcpy(0xb0427000, 0xb16ed000, 4096)
09-12 13:57:19.222   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.222   324  7178 V AudioCache: memcpy(0xb0428000, 0xb16ed000, 4096)
09-12 13:57:19.223   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.223   324  7178 V AudioCache: memcpy(0xb0429000, 0xb16ed000, 4096)
09-12 13:57:19.224   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.224   324  7178 V AudioCache: memcpy(0xb042a000, 0xb16ed000, 4096)
09-12 13:57:19.225   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.225   324  7178 V AudioCache: memcpy(0xb042b000, 0xb16ed000, 4096)
09-12 13:57:19.226   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.226   324  7178 V AudioCache: memcpy(0xb042c000, 0xb16ed000, 4096)
09-12 13:57:19.227   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.227   324  7178 V AudioCache: memcpy(0xb042d000, 0xb16ed000, 4096)
09-12 13:57:19.227   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.227   324  7178 V AudioCache: memcpy(0xb042e000, 0xb16ed000, 4096)
09-12 13:57:19.228   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.228   324  7178 V AudioCache: memcpy(0xb042f000, 0xb16ed000, 4096)
09-12 13:57:19.229   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.229   324  7178 V AudioCache: memcpy(0xb0430000, 0xb16ed000, 4096)
09-12 13:57:19.229  7170  7170 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 13:57:19.229  7170  7170 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-12 13:57:19.230   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.230   324  7178 V AudioCache: memcpy(0xb0431000, 0xb16ed000, 4096)
09-12 13:57:19.230   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.230   324  7178 V AudioCache: memcpy(0xb0432000, 0xb16ed000, 4096)
09-12 13:57:19.231   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.231   324  7178 V AudioCache: memcpy(0xb0433000, 0xb16ed000, 4096)
09-12 13:57:19.232   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.232   324  7178 V AudioCache: memcpy(0xb0434000, 0xb16ed000, 4096)
,09-12 13:57:19.232   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.232   324  7178 V AudioCache: memcpy(0xb0435000, 0xb16ed000, 4096)
09-12 13:57:19.233   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.233   324  7178 V AudioCache: memcpy(0xb0436000, 0xb16ed000, 4096)
09-12 13:57:19.234   324  7178 V AudioCache: write(0xb16ed000, 4096)
,09-12 13:57:19.234   324  7178 V AudioCache: memcpy(0xb0437000, 0xb16ed000, 4096)
09-12 13:57:19.235   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.235   324  7178 V AudioCache: memcpy(0xb0438000, 0xb16ed000, 4096)
09-12 13:57:19.236   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.236   324  7178 V AudioCache: memcpy(0xb0439000, 0xb16ed000, 4096)
09-12 13:57:19.236   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.236   324  7178 V AudioCache: memcpy(0xb043a000, 0xb16ed000, 4096)
09-12 13:57:19.237   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.237   324  7178 V AudioCache: memcpy(0xb043b000, 0xb16ed000, 4096)
09-12 13:57:19.238   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.238   324  7178 V AudioCache: memcpy(0xb043c000, 0xb16ed000, 4096)
09-12 13:57:19.239   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.239   324  7178 V AudioCache: memcpy(0xb043d000, 0xb16ed000, 4096)
09-12 13:57:19.239   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.240   324  7178 V AudioCache: memcpy(0xb043e000, 0xb16ed000, 4096)
09-12 13:57:19.240   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.240   324  7178 V AudioCache: memcpy(0xb043f000, 0xb16ed000, 4096)
09-12 13:57:19.240   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.240   324  7178 V AudioCache: memcpy(0xb0440000, 0xb16ed000, 4096)
09-12 13:57:19.240   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.240   324  7178 V AudioCache: memcpy(0xb0441000, 0xb16ed000, 4096)
09-12 13:57:19.240  7112  7112 V LGMDMManager: Create singleton instance
09-12 13:57:19.242   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.242   324  7178 V AudioCache: memcpy(0xb0442000, 0xb16ed000, 4096)
09-12 13:57:19.242   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.242   324  7178 V AudioCache: memcpy(0xb0443000, 0xb16ed000, 4096)
09-12 13:57:19.242   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.242   324  7178 V AudioCache: memcpy(0xb0444000, 0xb16ed000, 4096)
09-12 13:57:19.243   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.243   324  7178 V AudioCache: memcpy(0xb0445000, 0xb16ed000, 4096)
09-12 13:57:19.245   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.245   324  7178 V AudioCache: memcpy(0xb0446000, 0xb16ed000, 4096)
09-12 13:57:19.245   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.245   324  7178 V AudioCache: memcpy(0xb0447000, 0xb16ed000, 4096)
09-12 13:57:19.245   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.245   324  7178 V AudioCache: memcpy(0xb0448000, 0xb16ed000, 4096)
09-12 13:57:19.246   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.246   324  7178 V AudioCache: memcpy(0xb0449000, 0xb16ed000, 4096)
09-12 13:57:19.247   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.247   324  7178 V AudioCache: memcpy(0xb044a000, 0xb16ed000, 4096)
09-12 13:57:19.247   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.247   324  7178 V AudioCache: memcpy(0xb044b000, 0xb16ed000, 4096)
09-12 13:57:19.248   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.248   324  7178 V AudioCache: memcpy(0xb044c000, 0xb16ed000, 4096)
09-12 13:57:19.248   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.249   324  7178 V AudioCache: memcpy(0xb044d000, 0xb16ed000, 4096)
09-12 13:57:19.250   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.250   324  7178 V AudioCache: memcpy(0xb044e000, 0xb16ed000, 4096)
09-12 13:57:19.250   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.251   324  7178 V AudioCache: memcpy(0xb044f000, 0xb16ed000, 4096)
,09-12 13:57:19.252   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.252   324  7178 V AudioCache: memcpy(0xb0450000, 0xb16ed000, 4096)
09-12 13:57:19.253   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.253   324  7178 V AudioCache: memcpy(0xb0451000, 0xb16ed000, 4096)
09-12 13:57:19.254   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.254   324  7178 V AudioCache: memcpy(0xb0452000, 0xb16ed000, 4096)
09-12 13:57:19.255   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.255   324  7178 V AudioCache: memcpy(0xb0453000, 0xb16ed000, 4096)
09-12 13:57:19.256   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.256   324  7178 V AudioCache: memcpy(0xb0454000, 0xb16ed000, 4096)
09-12 13:57:19.256   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.256   324  7178 V AudioCache: memcpy(0xb0455000, 0xb16ed000, 4096)
09-12 13:57:19.257   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.257   324  7178 V AudioCache: memcpy(0xb0456000, 0xb16ed000, 4096)
09-12 13:57:19.258   324  7178 V AudioCache: write(0xb16ed000, 4096)
09-12 13:57:19.258   324  7178 V AudioCache: memcpy(0xb0457000, 0xb16ed000, 4096)
09-12 13:57:19.258   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-12 13:57:19.258   324  7178 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-12 13:57:19.258   324  7178 V AwesomePlayer: postAudioEOS() 
09-12 13:57:19.258   324  7178 V AudioCache: write(0xb16ed000, 280)
09-12 13:57:19.258   324  7178 V AudioCache: memcpy(0xb0458000, 0xb16ed000, 280)
09-12 13:57:19.260   324  7171 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-12 13:57:19.260   324  7171 V AwesomePlayer: onStreamDone
09-12 13:57:19.260   324  7171 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-12 13:57:19.260   324  7171 V AudioCache: notify(0xb5474600, 2, 0, 0)
09-12 13:57:19.260   324  7171 V AudioCache: playback complete
09-12 13:57:19.260   324  7171 V AwesomePlayer: pause_l() 
09-12 13:57:19.260   324  7171 V AudioCache: notify(0xb5474600, 7, 0, 0)
09-12 13:57:19.260   324  7171 V AudioCache: ignored
09-12 13:57:19.260   324  7171 V AwesomePlayer: cancelPlayerEvents
09-12 13:57:19.260   324  1383 V AudioCache: wait - success
09-12 13:57:19.260   324  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-12 13:57:19.260   324  7171 D AudioPlayer: Pause Playback at 1068125
09-12 13:57:19.261  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:19.261  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:19.261  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:19.261  1035  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 13:57:19.262  1035  1538 D WifiMonitor: connecting to supplicant
09-12 13:57:19.262   324  1383 V AwesomePlayer: reset_l() 
09-12 13:57:19.262   324  1383 V AudioCache: notify(0xb5474600, 8, 0, 0)
09-12 13:57:19.262   324  1383 V AudioCache: ignored
09-12 13:57:19.262   324  1383 V AwesomePlayer: cancelPlayerEvents
09-12 13:57:19.262   324  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-12 13:57:19.262   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
,09-12 13:57:19.262   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-12 13:57:19.262   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-12 13:57:19.262   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-12 13:57:19.263  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:19.263  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-12 13:57:19.266  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c06f0 on port 1
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 13:57:19.267   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-12 13:57:19.267  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:19.268   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 13:57:19.268   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-12 13:57:19.268   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-12 13:57:19.268   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-12 13:57:19.268   324  7177 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-12 13:57:19.269   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 13:57:19.269   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-12 13:57:19.269   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-12 13:57:19.269  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:19.270  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:19.270   324  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-12 13:57:19.270   324  1383 D AudioPlayer: AudioPlayer releasing audio source
09-12 13:57:19.270   324  1383 D AudioPlayer: AudioPlayer done releasing audio source
09-12 13:57:19.270   324  1383 V AwesomePlayer: reset_l() 
09-12 13:57:19.270   324  1383 V AwesomePlayer: cancelPlayerEvents
09-12 13:57:19.270   324  1383 V AwesomePlayer: ~AwesomePlayer call
09-12 13:57:19.271   324  1383 V AwesomePlayer: reset_l() 
09-12 13:57:19.271   324  1383 V AwesomePlayer: cancelPlayerEvents
09-12 13:57:19.271  7112  7168 V SoundPool: close(31)
09-12 13:57:19.271  7112  7168 V SoundPool: pointer = 0x9ffdb000, size = 205080, sampleRate = 48000, numChannels = 2
09-12 13:57:19.323  7170  7170 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 13:57:,19.323  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-12 13:57:19.329  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-12 13:57:19.332  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1142
09-12 13:57:19.334  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:19.335  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 13:57:19.335  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 13:57:19.335  7089  7089 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 13:57:19.335  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 13:57:19.336  7089  7089 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 13:57:19.336  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 13:57:19.336  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 13:57:19.336  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 13:57:19.336  7089  7089 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 13:57:19.336  7089  7089 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 13:57:19.343  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:19.346  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:19.350  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:19.356  7132  7182 W FormManager: Network not available. Please check & try again.
09-12 13:57:19.366  1035  1904 D WifiServiceImplEx: setWifiEnabled: true pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 13:57:19.366  1035  1904 D WifiService: setWifiEnabled: true pid=6796, uid=10118
,09-12 13:57:19.366  1035  1904 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:19.367  7132  7183 V FormManager: Network unavailable.
09-12 13:57:19.368  7132  7183 V FormManager: Network unavailable.
09-12 13:57:19.379  7170  7170 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-12 13:57:19.382  7170  7170 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-12 13:57:19.382  7170  7170 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-12 13:57:19.383  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-12 13:57:19.384  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-12 13:57:19.384  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-12 13:57:19.384  1035  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-12 13:57:19.385  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-12 13:57:19.385  1035  7184 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-12 13:57:19.385  1035  7184 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 13:57:19.385  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-12 13:57:19.385  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-12 13:57:19.385  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:19.385  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-12 13:57:19.385  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-12 13:57:19.385  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:19.386  1035  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-12 13:57:19.386  1035  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-12 13:57:19.386  1035  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-12 13:57:19.387  1035  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-12 13:57:19.387  1035  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-12 13:57:19.387  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:19.387  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:19.387  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:19.387  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:19.387  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:19.388  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:19.388  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:19.388  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 13:57:19.388  1035  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
09-12 13:57:19.388  1035  1538 D WifiNative-wlan0: SET update_config 1: returned true
09-12 13:57:19.389  1035  1538 D WifiConfigStore: Loading config and enabling all networks 
09-12 13:57:19.389  1035  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-12 13:57:19.389  1035  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-12 13:57:19.390  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:19.390  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-12 13:57:19.395  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-12 13:57:19.395  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-12 13:57:19.397  1035  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement, supported: NOT_SUPPORTED
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:19.398  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:19.400  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:19.404  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:19.404  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:19.405  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:19.407  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:19.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:19.409  1035  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-12 13:57:19.411  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:19.411  1035  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:57:19.412  1035  1538 D WifiStateMachine: enableVerboseLogging : level 2
09-12 13:57:19.412  1035  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-12 13:57:19.412  1035  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-12 13:57:19.412  1035  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-12 13:57:19.413  1035  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-12 13:57:19.413  1035  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-12 13:57:19.413  1035  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-12 13:57:19.413  1035  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-12 13:57:19.413  1035  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-12 13:57:19.413  1035  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-12 13:57:19.414  1035  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-12 13:57:19.414  1035  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-12 13:57:19.415  1035  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-12 13:57:19.415  1035  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-12 13:57:19.415  1035  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-12 13:57:19.416  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:57:19.416  1035  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-12 13:57:19.416  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-12 13:57:19.416  1941  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-12 13:57:19.416  1941  2316 D WfdsService: Set the WFDS Monitor: true
09-12 13:57:19.416  1941  2316 D WfdsMonitor: WfdsMonitorThread create
09-12 13:57:19.416  1035  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-12 13:57:19.416  1035  1538 D WifiNative-HAL: Setting external_sim to 1
09-12 13:57:19.416  1035  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-12 13:57:19.416  1941  2316 D WfdsMonitor: WFDS Monitor is created and started
09-12 13:57:19.416  1941  2316 D WfdsService: WiFi: Supplicant connection re-established
09-12 13:57:19.417  1035  1538 D WifiNative-wlan0: SET external_sim 1: returned true
09-12 13:57:19.417  1035  1538 I WifiNative-HAL: startHal
09-12 13:57:19.417  1035  1538 D wifi    : setting scan oui 0xaf5e2160
09-12 13:57:19.417  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:57:19.417  1035  1538 I WifiNative-HAL: startHal
09-12 13:57:19.417  1035  1538 D wifi    : setting scan oui 0xaf5e2160
09-12 13:57:19.417  1035  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-12 13:57:19.418  1035  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-12 13:57:19.418  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-12 13:57:19.418  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-12 13:57:19.418  7132  7187 V FormManager: Network unavailable.
09-12 13:57:19.419  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-12 13:57:19.419  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 13:57:19.419  1941  7188 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-12 13:57:19.419  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 13:57:19.419  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:19.419  1941  7188 E CtrlSupplicant: Succeed to open control connection
09-12 13:57:19.419  1941  7188 E CtrlSupplic,ant: Succeed to open monitor connection
09-12 13:57:19.419  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 13:57:19.419  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-12 13:57:19.419  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-12 13:57:19.420  1941  7188 D WfdsMonitor: Supplicant connection established
09-12 13:57:19.420  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-12 13:57:19.420  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 13:57:19.420  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 13:57:19.420  1941  2316 D WfdsService: Connected to the supplicant for wfds
09-12 13:57:19.420  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 13:57:19.420  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,09-12 13:57:19.421  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 13:57:19.421  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 13:57:19.421  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-12 13:57:19.421  7170  7170 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-12 13:57:19.424  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-12 13:57:19.424  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 13:57:19.424  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 13:57:19.424  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 13:57:19.425  1035  1538 E WifiNative: : [129,573,812 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-12 13:57:19.425  1035  1538 D WifiNative-wlan0: doBoolean: RECONNECT
09-12 13:57:19.425  1035  1538 D WifiNative-wlan0: RECONNECT: returned true
09-12 13:57:19.425  1035  1538 D WifiNative-wlan0: doString: [STATUS]
09-12 13:57:19.425  7132  7187 V FormManager: Network unavailable.
09-12 13:57:19.426  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 13:57:19.426  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 13:57:19.426  1035  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 13:57:19.426  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:19.426  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:19.427  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.428   316   893 D CommandListener: Setting iface cfg
09-12 13:57:19.428   316   893 D CommandListener: Trying to bring up p2p0
09-12 13:57:19.428  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 13:57:19.428  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-12 13:57:19.428  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.428  1035  1556 I WifiNative-HAL: startHal
09-12 13:57:19.428  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf5e2160
09-12 13:57:19.428  1035  1556 D wifi    : failed to get capabilities : -3
09-12 13:57:19.428  1035  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:57:19.428  1035  1556 E WifiScanningService: could not get scan capabilities
09-12 13:57:19.428  1035  1537 D LGWifiP2pService: P2pEnablingState
09-12 13:57:19.428  1035  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.428  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.428  1035  1537 D LGWifiP2pService: P2p socket connection successful
09-12 13:57:19.429  1035  1537 D LGWifiP2pService: P2pEnabledState
09-12 13:57:19.429  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-12 13:57:19.429  1035  1537 D LGWifiP2pService: sending p2p connection changed broadcast
09-12 13:57:19.429  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-12 13:57:19.429  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-12 13:57:19.429  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-12 13:57:19.430  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-12 13:57:19.430  1035  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-12 13:57:19.430  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-12 13:57:19.430  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-12 13:57:19.430  1941  1941 D WfdsService: WifiP2pState is changed : true
09-12 13:57:19.430  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-12 13:57:19.430  1941  2316 D WfdsService: Receive the WFDS_ENABLE Method
09-12 13:57:19.430  1941  2316 D WfdsService: Set the WFDS Monitor: true
09-12 13:57:19.430  1941  2316 D WfdsService: Connected to the supplicant for wfds
09-12 13:57:19.430  1941  2316 D WfdsJNI : doCommand: WFDS_SET TRUE
09-12 13:57:19.430  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-12 13:57:19.430  7170  7170 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,09-12 13:57:19.431  1941  2316 D WfdsService: selectPreferredScanChannel [36]
09-12 13:57:19.431  1941  2316 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-12 13:57:19.431  1035  1538 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-12 13:57:19.431  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-12 13:57:19.431  1035  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-12 13:57:19.431  1035  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-12 13:57:19.431  1941  1941 D WfdsService: isConnected: false
09-12 13:57:19.432  1035  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-12 13:57:19.432  1035  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
09-12 13:57:19.432  1035  1537 D WifiNative-p2p0: SET device_name G3: returned true
09-12 13:57:19.432  1035  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-12 13:57:19.433  1035  1537 D LGWifiP2pService: before postfix = G3
09-12 13:57:19.433  1035  1537 D WifiServerServiceExt: postfix byte check : 2
09-12 13:57:19.433  1035  1537 D LGWifiP2pService: after postfix = G3
09-12 13:57:19.433  1035  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-12 13:57:19.433  7132  7186 W FormManager: Network not available. Please check & try again.
09-12 13:57:19.433  1035  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-12 13:57:19.433  1035  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-12 13:57:19.433  1035  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-12 13:57:19.433  1035  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-12 13:57:19.433  7170  7170 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-12 13:57:19.433  1035  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-12 13:57:19.434  1035  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-12 13:57:19.434  1035  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-12 13:57:19.434  1035  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-12 13:57:19.434  1035  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-12 13:57:19.434  1035  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-12 13:57:19.434  7170  7170 E wpa_supplicant: disconnect_rssi_lvl: -100
09-12 13:57:19.434  1035  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-12 13:57:19.434  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-12 13:57:19.435  1035  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-12 13:57:19.435  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress
09-12 13:57:19.435  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-12 13:57:19.435  1035  1537 D LGWifiP2pService: DeviceAddress: 
09-12 13:57:19.435  1035  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-12 13:57:19.436  1035  1537 D WifiNative-p2p0: P2P_FLUSH: returned false
09-12 13:57:19.436  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-12 13:57:19.436  1035  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-12 13:57:19.436  1035  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,09-12 13:57:19.438  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-12 13:57:19.438  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-12 13:57:19.438  1941  1941 D WfdsService: Update P2p Interface State: 3
09-12 13:57:19.438  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 13:57:19.438  1035  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-12 13:57:19.439  1035  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-12 13:57:19.439  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 13:57:19.439  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 13:57:19.439  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-12 13:57:19.444  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 13:57:19.444  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:19.445  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:19.447  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:19.449  5613  5613 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:57:19.449  5613  5613 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-12 13:57:19.451  5613  5613 V [BNRBootReceiver]: Boot Receiver Return
,09-12 13:57:19.451  4834  7189 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:19.454  4834  7190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 13:57:19.454  4834  7190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:19.460  1035  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-12 13:57:19.460  1035  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-12 13:57:19.460  1035  1537 D LGWifiP2pService: InactiveState
09-12 13:57:19.460  1035  1537 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.460  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.460  1035  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-12 13:57:19.460  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 13:57:19.461  7170  7170 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.461  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 13:57:19.461  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.461  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.461  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.461  7170  7170 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 13:57:19.461  7170  7170 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.461  1941  7188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-12 13:57:19.462  1035  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-12 13:57:19.462  7170  7170 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.462  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-12 13:57:19.462  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-12 13:57:19.462  1941  7188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:19.462  1035  7184 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:19.462  1035  7184 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.463  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-12 13:57:19.463  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.463  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-12 13:57:19.463  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.463  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-12 13:57:19.463  7170  7170 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:19.463  1035  7184 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:19.463  1035  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-12 13:57:19.463  1035  7184 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.463  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.463  1035  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-12 13:57:19.464  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.464  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-12 13:57:19.464  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:19.464  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:19.464  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:19.464  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 13:57:19.464  7170  7170 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.465  7170  7170 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 13:57:19.465  7170  7170 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.465  1035  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.465  7170  7170 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3, target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.465  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.466  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.466  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.466  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.466  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.466  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.466  1035  1035 E WifiServerServiceExt: No p2p device connected
09-12 13:57:19.466  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:19.466  1941  2316 W WfdsService: DefaultState - msg [9441285] is not handled
09-12 13:57:19.466  1035  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-12 13:57:19.466  1035  1538 D WifiNative-wlan0: doBoolean: SCAN
09-12 13:57:19.467  1941  7188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 13:57:19.467  1035  1538 D WifiNative-wlan0: SCAN: returned false
09-12 13:57:19.467  1941  7188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:19.467  1941  7188 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:19.467  1035  7184 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 13:57:19.467  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=129616  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 13:57:19.467  1035  7184 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.467  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.467  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:19.467  1035  7184 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:19.467  1035  7184 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.467  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.467  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.467  1035  7184 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:19.467  1035  7184 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.467  1035  7184 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.467  1035  7184 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:19.468  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=129617  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 13:57:19.468  1035  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:19.468  1035  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:19.469  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: ,false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:19.469  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:19.469  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:19.470  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:19.470  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 13:57:19.470  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:19.471  1035  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:19.471  1035  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:19.471  1035  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:19.472  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:19.472  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:19.472  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 13:57:19.476  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:19.482  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:19.486  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:19.486  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:19.488  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 13:57:19.683  6966  6966 I UEI.SmartControl: Supports setup maps: true
,09-12 13:57:19.690  6966  6966 D UEI.SmartControl: QS start statue = true Error code = 0
,09-12 13:57:19.690  6966  6966 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-12 13:57:19.690  6966  6966 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-12 13:57:19.690  6966  6966 I UEI.SmartControl: ### init IR Blaster...
09-12 13:57:19.694  6966  6966 D serial_port: Configuring serial port
09-12 13:57:19.695  6966  6966 E UEI.SmartControl: UEIBLaster setting for 616
09-12 13:57:19.695  6966  6966 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 13:57:19.695  6966  6966 I UEI.SmartControl: configuring settings for MAXQ616
09-12 13:57:19.695  6966  6966 I UEI.SmartControl: Get version...
09-12 13:57:19.715  6966  7191 D UEI.SmartControl: serial port data available: 21
,09-12 13:57:19.742  6966  6966 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-12 13:57:19.742  6966  6966 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 13:57:19.742  6966  6966 I UEI.SmartControl: QS saving settings...
09-12 13:57:19.744  6966  6966 D UEI.SmartControl: IR Blaster version: 25672567
,09-12 13:57:19.766  6966  7191 D UEI.SmartControl: serial port data available: 4
,09-12 13:57:19.800  6966  7200 I UEI.SmartControl: Device manager: loading config....
,09-12 13:57:19.805  6966  7200 D UEI.SmartControl: ----------- loading internal config...
09-12 13:57:19.806  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-12 13:57:19.810  6966  6966 E UEI.SmartControl: Services init done
09-12 13:57:19.810  6966  6966 D UEI.SmartControl: QS Service init finished
,09-12 13:57:19.814  6966  6966 D UEI.SmartControl: QS Service version name: 2.1.91
,09-12 13:57:19.814  6966  6966 D UEI.SmartControl: QS Service version code: 201091
09-12 13:57:19.817  6966  6966 D UEI.SmartControl: Service requested: Control
09-12 13:57:19.831  6966  7200 E UEI.SmartControl: Loading SETTINGS...
,09-12 13:57:19.835  6966  6966 D UEI.SmartControl: Request IControl service: devices are loaded...
09-12 13:57:19.837  7112  7112 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-12 13:57:19.839  6966  6981 I UEI.SmartControl: ------ IControl API: 11
09-12 13:57:19.839  6966  6981 D UEI.SmartControl: File observer start...
09-12 13:57:19.839  6966  6981 E UEI.SmartControl: IR Port is disabled: false
09-12 13:57:19.840  6966  6981 D UEI.SmartControl: Starting file observer...
09-12 13:57:19.841  6966  6981 I UEI.SmartControl: Registering callback...
09-12 13:57:19.842  6966  6982 I UEI.SmartControl: ------ IControl API: 19
09-12 13:57:19.842  6966  6982 I UEI.SmartControl: Registering Services Ready callback...
09-12 13:57:19.843  6966  6966 D UEI.SmartControl: Internal service binding...
,09-12 13:57:19.849  1035  1426 V AlarmManager: RTC_WAKEUP set : Alarm{29159ce0 type 0 when 1473681439628 android} when 1473681439628
09-12 13:57:19.850  1035  1426 V AlarmManager: ELAPSED_WAKEUP set : Alarm{9403b99 type 2 when 129994 com.google.android.gms} when 129994
09-12 13:57:19.856  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 full rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:83176] from screen [on:0 period:507657328]
09-12 13:57:19.856  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):9 full rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:507657328]
,09-12 13:57:19.859  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):12 full rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:507657331]
09-12 13:57:19.859  1035  1538 D WifiNative-wlan0: doBoolean: SCAN
09-12 13:57:19.860  1035  1538 D WifiNative-wlan0: SCAN: returned false
09-12 13:57:19.864   316  7206 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-12 13:57:19.866  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-12 13:57:19.879  1035  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:19.882  1035  2006 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:19.884  6966  7200 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-12 13:57:19.892  6966  7199 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-12 13:57:19.894  7112  7127 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-12 13:57:19.896  6966  7199 D UEI.SmartControl: -----service ready thread exits
09-12 13:57:19.896  7112  7166 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-12 13:57:19.896  7112  7166 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-12 13:57:19.897  7112  7112 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-12 13:57:19.897  7112  7112 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-12 13:57:19.897  6966  6981 I UEI.SmartControl: ------ IControl API: 8
09-12 13:57:19.900  7112  7112 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-12 13:57:19.900  7112  7112 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-12 13:57:19.900  7112  7112 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-12 13:57:19.901  7112  7112 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-12 13:57:19.902  7112  7112 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-12 13:57:19.902  7112  7112 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-12 13:57:19.907  7112  7112 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-12 13:57:19.909  7112  7112 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-12 13:57:19.915  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 13:57:19.915  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 13:57:19.915  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-12 13:57:19.915  1035  1117 D BluetoothManagerService: Message: 2
09-12 13:57:19.920  1035  1117 D BluetoothManagerService: Sending off request.
09-12 13:57:19.920  4342  4364 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-12 13:57:19.921  4342  4435 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-12 13:57:19.921  4342  4435 D BluetoothAdapterProperties: Setting state to 13
09-12 13:57:19.921  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 13:57:19.923  4342  4435 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:57:19.924  4342  4435 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-12 13:57:19.927  4342  4439 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:57:19.928  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 13:57:19.929  4342  4435 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 13:57:19.930  4342  4757 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:19.931  4342  4829 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:19.931  4342  4796 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:19.932  4342  4799 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-12 13:57:19.932  4342  4756 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-12 13:57:19.933  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,09-12 13:57:19.935  4342  4555 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-12 13:57:19.937  1035  1117 D BluetoothManagerService: Message: 60
09-12 13:57:19.937  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-12 13:57:19.937  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-12 13:57:19.938  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-12 13:57:19.940  4342  4555 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-12 13:57:19.941  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:19.941  4342  4342 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:19.941  4342  4342 D BluetoothMapService: STATE_TURNING_OFF
09-12 13:57:19.942  4342  4342 V BtOppService: Receiver DISABLED_ACTION 
09-12 13:57:19.942  4342  4342 V BluetoothMapService: Handler(): got msg=4
09-12 13:57:19.942  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-12 13:57:19.942  4342  4342 D BluetoothMapService: MAP Service closeService in
09-12 13:57:19.943  4342  4342 D BluetoothMapMasInstance: MAP Service shutdown
,09-12 13:57:19.943  4342  4342 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 13:57:19.943  4342  4342 V BluetoothMapService: MAP Service closeService out
09-12 13:57:19.943  4342  4342 I BtOppRfcommListener: stopping Accept Thread
09-12 13:57:19.943  4342  4342 V BtOppRfcommListener: close mBtServerSocket
09-12 13:57:19.943  4342  4342 V BtOppRfcommListener: waiting for thread to terminate
,09-12 13:57:19.944  4342  4796 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:57:19.951  4342  4342 V BtOppRfcommListener: done waiting for thread to terminate
09-12 13:57:19.954  4342  4342 V BtOppService: onDestroy
,09-12 13:57:19.955  4342  4342 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-12 13:57:19.957  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:19.957  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:19.957  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:19.957  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:19.962  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:19.962  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:19.963  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:19.963  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:19.965  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:19.965  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:19.966  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-12 13:57:19.966  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:19.966  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:19.967  7089  7089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 13:57:19.973  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:19.973  7112  7112 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 13:57:19.973  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 13:57:19.974  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-12 13:57:19.975  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:19.975  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:19.975  4342  4342 V BluetoothPbapReceiver: ***********state = 13
,09-12 13:57:19.978  4342  4342 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-12 13:57:19.979  4342  4342 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:19.979  4342  4342 V BluetoothPbapService: state: 13
09-12 13:57:19.979  4342  4342 V BluetoothPbapService: Pbap Service closeService in
09-12 13:57:19.980  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:19.980  4342  4342 V BluetoothPbapService: successfully stopped pbap service
09-12 13:57:19.980  4342  4342 V BluetoothPbapService: Pbap Service closeService out
09-12 13:57:19.981  4342  4342 V BluetoothPbapService: Pbap Service onDestroy
09-12 13:57:19.981  4342  4342 V BluetoothPbapService: Pbap Service closeService in
09-12 13:57:19.981  4342  4342 V BluetoothPbapService: Pbap Service closeService out
09-12 13:57:19.981  4342  4342 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-12 13:57:19.981  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:19.987  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:19.987  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,09-12 13:57:19.992  1035  1117 D BluetoothManagerService: Message: 20
09-12 13:57:19.992  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34cff855:true
09-12 13:57:19.999  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-12 13:57:20.000  7112  7112 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473681439999]
09-12 13:57:20.001  7112  7112 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-12 13:57:20.035  1035  1867 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7226 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:20.047  1035  1117 D BluetoothManagerService: Message: 30
09-12 13:57:20.049  7112  7225 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-12 13:57:20.051  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-12 13:57:20.051  1035  7184 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-12 13:57:20.051  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-12 13:57:20.051  7170  7170 E wpa_supplicant: USIM:  scard_init function
09-12 13:57:20.051  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-12 13:57:20.051  1035  7184 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-12 13:57:20.052  7170  7170 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-12 13:57:20.052  1035  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-12 13:57:20.052  1035  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-12 13:57:20.053  1035  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-12 13:57:20.053  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-12 13:57:20.054  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-12 13:57:20.054  1035  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-12 13:57:20.054  1035  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-12 13:57:20.055  1035  1117 D BluetoothManagerService: Message: 30
09-12 13:57:20.058  7089  7089 D LocalBluetoothProfileManager: Adding local MAP profile
09-12 13:57:20.059  7089  7089 D BluetoothMap: Create BluetoothMap proxy object
09-12 13:57:20.060  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=130209  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 13:57:20.061  1035  1117 D BluetoothManagerService: Message: 30
09-12 13:57:20.062  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.062  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-12 13:57:20.063  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.063  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.063  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 13:57:20.065  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.067  1035  1117 D BluetoothManagerService: Message: 30
09-12 13:57:20.068  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=130217  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 13:57:20.070  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.070  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.070  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 13:57:20.071  7089  7089 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-12 13:57:20.071  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:20.071  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-12 13:57:20.072  7089  7089 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-12 13:57:20.083  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:57:20.083  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:20.083  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.088  7089  7089 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-12 13:57:20.090  7089  7089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-12 13:57:20.098  7089  7089 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:20.099  7089  7089 D BluetoothInputDevice: Proxy object connected
09-12 13:57:20.100  7089  7089 D HidProfile: Bluetooth service connected
09-12 13:57:20.100  7089  7089 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:57:20.101  7089  7089 D PanProfile: Bluetooth service connected
09-12 13:57:20.104  7089  7089 D BluetoothMap: Proxy object connected
,09-12 13:57:20.104  7089  7089 D MapProfile: Bluetooth service connected
09-12 13:57:20.104  7089  7089 D BluetoothMap: getConnectedDevices()
09-12 13:57:20.105  7089  7089 D BluetoothMap: Bluetooth is Not enabled
09-12 13:57:20.106  7089  7089 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-12 13:57:20.107  1035  1576 I ActivityManager: Killing 6624:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-12 13:57:20.159  7170  7170 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-12 13:57:20.159  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-12 13:57:20.159  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-12 13:57:20.160  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-12 13:57:20.160  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-12 13:57:20.160  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=130309  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-12 13:57:20.161  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:20.161  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:20.162  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=130311  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 13:57:20.163  1035  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130312
09-12 13:57:20.163  1035  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130312
09-12 13:57:20.164  1035  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130313
09-12 13:57:20.164  1035  1751 W libprocessgroup: failed to open /acct/uid_10011/pid_6624/cgroup.procs: No such file or directory
09-12 13:57:20.165  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130314
09-12 13:57:20.165  1035  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130314
09-12 13:57:20.166  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=130315  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 13:57:20.167  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:57:20.168  7170  7170 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:57:20.168  7170  7170 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 13:57:20.168  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:20.168  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:20.169  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-12 13:57:20.169  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:57:20.169  1035  7184 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:57:20.169  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-12 13:57:20.169  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 13:57:20.169  1035  7184 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 13:57:20.171  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:20.171  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-12 13:57:20.175  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.175  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:20.176  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.176  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.176  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 13:57:20.177  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=130326  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 13:57:20.178  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.179  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.180  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.180  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-12 13:57:20.180  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.180  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:20.180  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:20.180  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-12 13:57:20.181  7226  7226 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-12 13:57:20.181  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.181  7226  7226 W LG Account v2.2: No ProfileInfo entries
09-12 13:57:20.182  7226  7226 I LG Account v2.2: isEnabled: false
09-12 13:57:20.182  7226  7226 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-12 13:57:20.182  7226  7226 I Feature : [Lifetracker]Country: EU
09-12 13:57:20.182  7226  7226 I Feature : [Lifetracker]Operator: OPEN
09-12 13:57:20.182  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=130331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 13:57:20.182  7226  7226 I Feature : [Lifetracker]Ranking support: false
09-12 13:57:20.182  7226  7226 I Feature : [Lifetracker]Comfort support: false
09-12 13:57:20.182  7226  7226 I Feature : [Lifetracker]Accessory: true
09-12 13:57:20.183  7226  7226 I Feature : [Lifetracker]Health device: true
09-12 13:57:20.183  7226  7226 I Feature : [Lifetracker]Extra Pedometer: false
09-12 13:57:20.183  7226  7226 I Feature : [Lifetracker]Blood glucose device: false
09-12 13:57:20.183  7226  7226 I Feature : [Lifetracker]Device Number: 3
09-12 13:57:20.183  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=130332  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,09-12 13:57:20.184  1035  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=130333
09-12 13:57:20.184  1035  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=130333
09-12 13:57:20.185  1035  1538 D WifiNative-wlan0: doString: [STATUS]
09-12 13:57:20.186  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:20.186  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:20.186  1035  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 13:57:20.188  1035  1538 I WifiServiceExtension: setVHTCapabilityType  : false
09-12 13:57:20.195  1035  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-12 13:57:20.195  1035  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-12 13:57:20.197  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.198  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.198  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 13:57:20.201  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.201  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.201  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 13:57:20.202  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.202  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:20.202  7112  7112 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-12 13:57:20.203  7089  7089 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-12 13:57:20.204  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:20.205  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.205  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:20.206  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:20.209  7112  7112 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 13:57:20.210  1035  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-12 13:57:20.210  1035  1545 D ConnectivityService: Got NetworkAgent Messenger
09-12 13:57:20.210  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-12 13:57:20.210  7089  7089 D BluetoothPermissionRequest: onReceive
09-12 13:57:20.210  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-12 13:57:20.210  1035  1545 D ConnectivityService: NetworkAgent connected
09-12 13:57:20.210  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-12 13:57:20.210  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:57:20.210  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 13:57:20.210  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-12 13:57:20.211  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-12 13:57:20.211  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-12 13:57:20.212  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 13:57:20.212  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 13:57:20.213  7089  7089 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-12 13:57:20.219  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 13:57:20.219  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:57:20.219  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-12 13:57:20.219  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 13:57:20.220  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 13:57:20.223  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-12 13:57:20.223  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:20.223  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 13:57:20.225   316   893 D CommandListener: Setting iface cfg
09-12 13:57:20.227  4342  4342 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-12 13:57:20.227  4342  4342 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-12 13:57:20.228  4342  4342 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-12 13:57:20.231  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-12 13:57:20.231  1035  1538 E WifiStateMachine: Start Dhcp Watchdog 2
09-12 13:57:20.231  1035  7255 D DhcpStateMachine: StoppedState
09-12 13:57:20.231  1035  7255 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.231  1035  7255 D DhcpStateMachine: WaitBeforeStartState
09-12 13:57:20.232  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:20.232  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,09-12 13:57:20.232  1035  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:20.232  1035  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:20.233  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:20.233  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:20.234  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:20.234  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:20.234  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:20.235  7089  7089 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-12 13:57:20.242  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.244  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:20.244  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 13:57:20.244  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130393  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:20.244  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:20.244  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-12 13:57:20.244  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130393  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:20.244  4342  4342 V BluetoothFtpService: Ftp Service onStartCommand
09-12 13:57:20.245  4342  4342 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:20.245  4342  4342 V BluetoothFtpService: Ftp Service closeService
09-12 13:57:20.245  4342  4342 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-12 13:57:20.245  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:20.246  4342  4342 V BluetoothFtpService: successfully stopped ftp service
09-12 13:57:20.246  4342  4342 V BluetoothFtpService: Ftp Service onDestroy
09-12 13:57:20.246  4342  4342 V BluetoothFtpService: Ftp Service closeService
09-12 13:57:20.247  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:387] from screen [on:0 period:507657719] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:20.248  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:507657720] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:20.248  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-12 13:57:20.251  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 13:57:20.251  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:20.251  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 13:57:20.251  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:20.251  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-12 13:57:20.251  4342  4342 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 13:57:20.252  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.253  4342  4342 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:20.253  4342  4342 V BluetoothSapService: state: 13
09-12 13:57:20.253  4342  4342 V BluetoothSapService: Stopping SAP server process
09-12 13:57:20.254  4342  4342 V BluetoothSapService: Sap Service closeSapService in
09-12 13:57:20.254  4342  4342 V BluetoothSapService: Close listen Socket : 
09-12 13:57:20.254  4342  4342 V BluetoothSapService: Close rfcomm Socket : 
09-12 13:57:20.254  4342  4342 V BluetoothSapService: Close sapd  Socket : 
09-12 13:57:20.255  1035  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-12 13:57:20.255  4342  4342 V BluetoothSapService: Sap Service closeSapService out
,09-12 13:57:20.255  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.255  4342  4342 V BluetoothSapService: Sap Service onDestroy
09-12 13:57:20.255  4342  4342 V BluetoothSapService: Sap Service closeSapService in
09-12 13:57:20.255  4342  4342 V BluetoothSapService: Close listen Socket : 
09-12 13:57:20.255  4342  4342 V BluetoothSapService: Close rfcomm Socket : 
09-12 13:57:20.255  4342  4342 V BluetoothSapService: Close sapd  Socket : 
09-12 13:57:20.255  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.256  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.256  4342  4342 V BluetoothSapService: Sap Service closeSapService out
09-12 13:57:20.257  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.257  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.258  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.258  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 13:57:20.259  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
09-12 13:57:20.259  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:20.260  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
09-12 13:57:20.260  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-12 13:57:20.260  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-12 13:57:20.260  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-12 13:57:20.260  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 0
09-12 13:57:20.261  1035  1538 D WifiNative-wlan0: SET ps 0: returned true
09-12 13:57:20.261  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-12 13:57:20.261  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-12 13:57:20.261  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-12 13:57:20.261  1035  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-12 13:57:20.261  1035  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 13:57:20.262  1035  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 13:57:20.262  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1641b188 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.262  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1641b188 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.262   316   893 D CommandListener: Setting iface cfg
09-12 13:57:20.262  1035  7255 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.262  1035  7255 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-12 13:57:20.263   316   893 D CommandListener: Trying to bring up wlan0
09-12 13:57:20.264  1035  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,09-12 13:57:20.273  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.299  1035  1051 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7256 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 13:57:20.300  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:20.301  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 13:57:20.302  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.303  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.304  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.304  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.305  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.306  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:20.307  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:20.307  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 13:57:20.308  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 13:57:20.309  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-12 13:57:20.310  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-12 13:57:20.310  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.311  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.311  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,09-12 13:57:20.311  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 13:57:20.312  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 13:57:20.312  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-12 13:57:20.314  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-12 13:57:20.314  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-12 13:57:20.314  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:20.319  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:20.319  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:20.321   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 581us total 22.065ms
09-12 13:57:20.323  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 13:57:20.326  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.330  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:20.330  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 13:57:20.331  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 13:57:20.331  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 13:57:20.331  1035  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 13:57:20.332  1035  1545 D ConnectivityService: ignoring duplicate network state non-change
09-12 13:57:20.334  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.336  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 13:57:20.337  1035  1545 D ConnectivityService: Adding iface wlan0 to network 101
09-12 13:57:20.338  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.338  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:20.343  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.343  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.343  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 13:57:20.344  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.344   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 22.455ms
,09-12 13:57:20.360  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.360  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.360  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-12 13:57:20.361  1035  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 13:57:20.362  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 13:57:20.365   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 19.591ms
09-12 13:57:20.366  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-12 13:57:20.366  1035  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 13:57:20.367  1035  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-12 13:57:20.368  1035  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-12 13:57:20.368   316   893 E Netd    : netlink response contains error (File exists)
09-12 13:57:20.369  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.369  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.369  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 13:57:20.369  1035  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-12 13:57:20.370  1035  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-12 13:57:20.370  1035  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-12 13:57:20.370  1035  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-12 13:57:20.370  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 13:57:20.370  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.370  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:20.372  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:20.374  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.374  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 13:57:20.375  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.376  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.377  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.377  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:20.377  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 13:57:20.377  1035  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 13:57:20.377  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 13:57:20.377  1035  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-12 13:57:20.378  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 13:57:20.378  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.378  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-12 13:57:20.378  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.378  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 13:57:20.378  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:20.381  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:20.381  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:20.381  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.381  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-12 13:57:20.381  1035  1545 D ConnectivityService: currentScore = 0, newScore = 20
09-12 13:57:20.381  1035  1545 D ConnectivityService:    accepting network in place of null
09-12 13:57:20.381  1035  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.382  1035  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 13:57:20.382  1035  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 13:57:20.383  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 13:57:20.383  1035  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.383  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:20.384  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.384  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 13:57:20.384   316  7276 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, ,type = 28
09-12 13:57:20.387  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:20.387  1035  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-12 13:57:20.387  1035  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-12 13:57:20.388  1035  1545 D ConnectivityService: validation of new default Network = false
09-12 13:57:20.388  1035  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-12 13:57:20.388  1035  1545 D DSQN    : enableDataServiceNotify 
09-12 13:57:20.388  1035  1545 D DSQN    : start dsqn bin
09-12 13:57:20.394  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-12 13:57:20.394  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 13:57:20.394  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 13:57:20.394  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 13:57:20.395  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:20.396  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 13:57:20.396  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.396  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 13:57:20.397  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.397  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:20.397  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:20.397  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:57:20.389  7277  7277 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:20.389  7277  7277 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:20.401  7256  7256 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 13:57:20.411  7277  7277 E DSQN    : DSQN ssw
09-12 13:57:20.412  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:20.412  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:20.412  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:20.416  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:20.416  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 13:57:20.416  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 13:57:20.416  7089  7089 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 13:57:20.417  1035  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-12 13:57:20.417  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-12 13:57:20.419  7089  7089 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 13:57:20.419  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-12 13:57:20.419  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 13:57:20.419  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 13:57:20.419  7089  7089 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 13:57:20.419  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-12 13:57:20.419  7089  7089 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 13:57:20.422  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.424  1035  2031 I ActivityManager: Killing 6111:com.android.contacts/u0a19 (adj 15): empty #17
09-12 13:57:20.466  1035  7255 D DhcpStateMachine: DHCPV4 request on wlan0
09-12 13:57:20.467  1035  7255 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-12 13:57:20.468  1035  7255 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-12 13:57:20.476   316  7276 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-12 13:57:20.459  7282  7282 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:20.459  7282  7282 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:20.487  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:20.488  1035  1051 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:20.488  1035  1992 W libprocessgroup: failed to open /acct/uid_10019/pid_6111/cgroup.procs: No such file or directory
,09-12 13:57:20.492  1035  1992 I ActivityManager: Killing 6647:com.lge.email/u0a23 (adj 15): empty #17
09-12 13:57:20.502  7282  7282 I dhcpcd  : version 5.5.6 starting
09-12 13:57:20.504  1035  1117 D BluetoothManagerService: Message: 1
09-12 13:57:20.504  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
09-12 13:57:20.505  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-12 13:57:20.506  7282  7282 E dhcpcd  : get_duid: m
09-12 13:57:20.506  7282  7282 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-12 13:57:20.506  7282  7282 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-12 13:57:20.506  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 13:57:20.507  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-12 13:57:20.510  4342  4364 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-12 13:57:20.510  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-12 13:57:20.516   316  7276 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-12 13:57:20.554   316   892 D LGDataListener: argv[0]=dsqncommand
09-12 13:57:20.554   316   892 D LGDataListener: argv[1]=wlan0
09-12 13:57:20.554   316   892 D LGDataListener: argv[2]=1
09-12 13:57:20.554   316   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-12 13:57:20.555  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-12 13:57:20.555  1035  1115 D DSQN    : start to monitor internet connection
,09-12 13:57:20.564  1035  1050 W libprocessgroup: failed to open /acct/uid_10023/pid_6647/cgroup.procs: No such file or directory
09-12 13:57:20.576  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.584  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 13:57:20.586  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.588  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.588  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.589  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:20 GMT], X-Android-Received-Millis=[1473681440588], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681440553]}
09-12 13:57:20.589  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:20.589  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 13:57:20.589  1035  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-12 13:57:20.589  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 13:57:20.589  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:20.589  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:20.589  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:20.589  1035  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-12 13:57:20.589  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 13:57:20.590  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.590  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:20.590  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:20.590  1035  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.590  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:57:20.593  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:57:20.593  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.593  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 13:57:20.594  1035  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:20.594  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:20.594  7282  7282 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 13:57:20.595  7282  7282 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 13:57:20.595  7282  7282 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 13:57:20.595  7282  7282 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-12 13:57:20.595  7282  7282 D dhcpcd  : wlan0: sending REQUEST (xid 0x4b424c0c), next in 4.93 seconds
09-12 13:57:20.602  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:20.603  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:20.603  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 13:57:20.611  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.623  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.631  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.638  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:20.639  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:20.640  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:20.643  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.645  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 13:57:20.647  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.647  7282  7282 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-12 13:57:20.648  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:20.650  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.658  7282  7282 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-12 13:57:20.658  7282  7282 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-12 13:57:20.658  7282  7282 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-12 13:57:20.658  7282  7282 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-12 13:57:20.659  7282  7282 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 13:57:20.659  7282  7282 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 13:57:20.659  7282  7282 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 13:57:20.659  7282  7282 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-12 13:57:20.659  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.667  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:20.668  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:20.669  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:20.675  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.684  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.692  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.699  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:20.700  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:20.700  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 13:57:20.708  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.723  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.734  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 13:57:20.747  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:20.748  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:20.753  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 13:57:20.758  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.768  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.780  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.788  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:20.789  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:20.789  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:20.794  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.799  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-12 13:57:20.803  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 13:57:20.807  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:20.812  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.819  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:20.820  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:20.821  7112  7112 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 13:57:20.822  7112  7112 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 13:57:20.823  7112  7112 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 13:57:20.828  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:20.833  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 13:57:20.834  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:20.842  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:20.848  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:20.856  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:20.856  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:20.857  7112  7112 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-12 13:57:20.859  7112  7112 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-12 13:57:20.860  7112  7112 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 13:57:20.941  4342  4555 W bt-btif : ag scb idx 1 not allocated
09-12 13:57:20.941  4342  4439 D bt_hci_bdroid: cleanup
09-12 13:57:20.941  4342  4555 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 13:57:20.941  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:20.942  4342  4557 I bt_lpm  : LPM is already off!!!
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:20.942  4342  4743 I bt_userial_mct: exiting userial_read_thread
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:20.942  4342  4743 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:20.942  4342  4555 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:20.942  4342  4555 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 13:57:20.943  4342  4439 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 13:57:20.943  4342  4557 I bt_vendor: hw_epilog_process
09-12 13:57:20.943  4342  4439 D bt_hci_bdroid: cleanup Finalizing cleanup
09-12 13:57:20.943  4342  4439 D bt_userial_mct: userial_close
09-12 13:57:20.943  4342  4439 E bt_userial_mct: pthread_join() FAILED result:3
09-12 13:57:20.943  4342  4439 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 13:57:21.007  1035  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 13:57:21.007  1035  1904 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
,09-12 13:57:21.008  1035  1117 D BluetoothManagerService: Message: 1
09-12 13:57:21.009  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
,09-12 13:57:21.012  4342  4359 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
,09-12 13:57:21.012  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-12 13:57:21.015  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:21.019  4342  4439 D bt_hci_bdroid: set_power 0
09-12 13:57:21.019  4342  4439 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 13:57:21.019  4342  4439 I bt_vendor: bluetooth satus is on
09-12 13:57:21.019  4342  4439 I bt_vendor: bt-vendor : resetting BT status
09-12 13:57:21.019  4342  4439 I bt_vendor: Starting hciattach daemon
09-12 13:57:21.019  4342  4439 I bt_vendor: try to set false
09-12 13:57:21.020  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:21.021  4342  4439 I bt_vendor: Starting hciattach daemon
09-12 13:57:21.021  4342  4439 I bt_vendor: try to set false
09-12 13:57:21.023  4342  4439 I bt_vendor: cleanup
09-12 13:57:21.024  4342  4555 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-12 13:57:21.025  4342  4439 I GKI_LINUX: GKI_exit_task 0 done
09-12 13:57:21.025  4342  4439 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 13:57:21.026  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 13:57:21.032  4342  4342 D HeadsetService: Received stop request...Stopping profile...
09-12 13:57:21.034  4342  4342 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 13:57:21.034  4342  4342 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:57:21.034  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.035  4342  4508 D HeadsetStateMachine: Exit Disconnected: -1
09-12 13:57:21.036  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:21.037  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:21.037  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:21.038  4342  4342 D A2dpService: Received stop request...Stopping profile...
09-12 13:57:21.038  4342  4530 D A2dpStateMachine: Exit Disconnected: -1
09-12 13:57:21.039  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-12 13:57:21.042  4342  4435 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 13:57:21.042  4342  4342 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-12 13:57:21.042  4342  4342 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:57:21.042  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
,09-12 13:57:21.044  4342  4342 D HidService: Received stop request...Stopping profile...
09-12 13:57:21.044  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.046  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:21.046  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 13:57:21.046  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-12 13:57:21.046  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 13:57:21.047  4342  4342 D HealthService: Received stop request...Stopping profile...
09-12 13:57:21.048  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.048  7089  7089 D BluetoothInputDevice: Proxy object disconnected
09-12 13:57:21.049  7089  7089 D HidProfile: Bluetooth service disconnected
09-12 13:57:21.051  4342  4342 D PanService: Received stop request...Stopping profile...
09-12 13:57:21.051  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
,09-12 13:57:21.053  4342  4342 D HeadsetStateMachine: Unbinding service...
09-12 13:57:21.053  7089  7089 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:57:21.054  7089  7089 D PanProfile: Bluetooth service disconnected
,09-12 13:57:21.055  4342  4342 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 13:57:21.055  4342  4342 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,09-12 13:57:21.055  4342  4342 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 13:57:21.055  4342  4342 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,09-12 13:57:21.055  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:21.055  4342  4342 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:57:21.055  4342  4342 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:57:21.055  4342  4342 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 13:57:21.056  4342  4342 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:57:21.057  1035  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:21.057  4342  4342 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:57:21.057  4342  4342 D BtGatt.GattService: stop()
09-12 13:57:21.057  4342  4342 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 13:57:21.058  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:21.058  1035  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:21.062  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-12 13:57:21.062  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-12 13:57:21.068  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:21.068  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:21.070  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:21.070  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:21.073  5865  5865 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-12 13:57:21.073  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.074  1035  7255 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-12 13:57:21.076  4342  4342 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:57:21.076  4342  4342 D BluetoothMapService: stop()
09-12 13:57:21.076  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:21.076  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:21.076  4342  4342 D BluetoothMapEmailAppObserver: deinitObservers()
09-12 13:57:21.076  4342  4342 D BluetoothMapEmailAppObserver: removeReceiver()
09-12 13:57:21.077  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.078  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:21.078  1035  7255 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-12 13:57:21.078  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:21.078  1035  7255 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 13:57:21.078  1035  7255 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-12 13:57:21.078  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 13:57:21.078  1035  7255 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-12 13:57:21.078  1035  7255 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 13:57:21.078  1035  7255 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-12 13:57:21.078  4342  4342 I BluetoothA2dpServiceJni: cleanupNative
09-12 13:57:21.078  4342  4531 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 13:57:21.079  1035  7255 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-12 13:57:21.079  4342  4342 I GKI_LINUX: GKI_exit_task 2 done
09-12 13:57:21.079  4342  4342 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 13:57:21.079  7089  7089 D BluetoothMap: Proxy object disconnected
09-12 13:57:21.079  7089  7089 D MapProfile: Bluetooth service disconnected
09-12 13:57:,21.079  4342  4342 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:57:21.079  4342  4342 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:57:21.080  4342  4342 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:57:21.080  4342  4342 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:57:21.080  4342  4342 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:57:21.080  4342  4342 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:57:21.080  4342  4342 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:57:21.081  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:21.081  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:21.082  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:21.082  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:21.082  1035  7255 D DhcpStateMachine: RunningState
09-12 13:57:21.084  4342  4342 V BluetoothMapService: Handler(): got msg=4
09-12 13:57:21.084  4342  4342 D BluetoothMapService: MAP Service closeService in
09-12 13:57:21.084  4342  4342 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 13:57:21.084  4342  4342 V BluetoothMapService: MAP Service closeService out
09-12 13:57:21.084  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.084  4342  4342 D BluetoothMapService: cleanup()
09-12 13:57:21.084  4342  4342 D BluetoothMapService: MAP Service closeService in
09-12 13:57:21.084  4342  4342 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 13:57:21.084  4342  4342 V BluetoothMapService: MAP Service closeService out
09-12 13:57:21.085  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-12 13:57:21.085  4342  4435 D BluetoothAdapterProperties: Setting state to 10
09-12 13:57:21.085  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 13:57:21.085  1035  1117 D BluetoothManagerService: Message: 60
09-12 13:57:21.085  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-12 13:57:21.085  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-12 13:57:21.086  4342  4435 I BluetoothAdapterState: Entering OffState
09-12 13:57:21.086  7089  7105 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:57:21.087  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.088  1850  4449 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:57:21.089  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.089  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:57:21.089  7089  7104 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:57:21.090  6537  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 13:57:21.090  7089  7105 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:57:21.091  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:57:21.091  5865  5865 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-12 13:57:21.094  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:57:21.094  7089  7104 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:57:21.094  1850  4449 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:57:21.095  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-12 13:57:21.097  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 13:57:21.098  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:21.098  1941  2125 D LGBluetoothAPIService: Message: 2
09-12 13:57:21.098  1941  2125 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1b362c56 mBinding = false
09-12 13:57:21.098  1941  2125 D LGBluetoothAPIService: Sending unbind request.
09-12 13:57:21.100  7089  7089 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 13:57:21.100  7089  7089 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-12 13:57:21.101  7089  7089 D LGBluetoothEventManager: [BTUI] clear device connection state
09-12 13:57:21.103  4342  4342 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-12 13:57:21.103  4342  4342 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-12 13:57:21.103  4342  4342 D LGBluetoothAPIServer: [BTUI] onDestroy()
,09-12 13:57:21.103  7089  7089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 13:57:21.104  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.108  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.108  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:21.109  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:21.109  4342  4342 V BluetoothPbapReceiver: ***********state = 10
,09-12 13:57:21.111  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.112  7089  7089 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:21.115  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:21.124  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:21.129   316  7321 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:21.129   316  7321 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-12 13:57:21.133  1035  1867 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-12 13:57:21.133  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:21.133  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:21.133  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:57:21.133  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:21.133  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 13:57:21.135  7089  7089 D BluetoothPermissionRequest: onReceive
09-12 13:57:21.139  7089  7089 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 13:57:21.139  7089  7089 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-12 13:57:21.157  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:21 GMT], X-Android-Received-Millis=[1473681441156], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681441134]}
09-12 13:57:21.157  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:21.157  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 13:57:21.157  1035  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-12 13:57:21.157  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 13:57:21.157  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 13:57:21.157  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:21.157  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:21.157  1035  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,09-12 13:57:21.157  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 13:57:21.157  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:21.157  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:21.158  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:21.158  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:57:21.161   316  7321 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-12 13:57:21.182  1035  1903 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7322 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-12 13:57:21.184  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:21.191  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:21.193  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 13:57:21.193  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:21.193  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 13:57:21.193  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:21.193  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-12 13:57:21.199  7256  7256 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-12 13:57:21.267  7322  7322 I AppUp4:AppBoxCP: onCreate
,09-12 13:57:21.267  7322  7322 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-12 13:57:21.276  7322  7322 I AppUp4:DB:  setFingerPrint start
09-12 13:57:21.276  7322  7322 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-12 13:57:21.284  7322  7322 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-12 13:57:21.284  7322  7322 I AppUp4:DB:  SDK version = 21
,09-12 13:57:21.284  7322  7322 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-12 13:57:21.285  7322  7322 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-12 13:57:21.286  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 13:57:21.286  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:21.288  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 13:57:21.288  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 13:57:21.297  7322  7322 I AppUp4:CustModeStarterReceiver: onReceive
,09-12 13:57:21.357  7322  7322 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:57:21.358  7322  7322 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:57:21.370  7322  7322 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c445186
09-12 13:57:21.370  7322  7322 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 13:57:21.370  7322  7322 D AppUp4:CustFacade: isPhone : true
09-12 13:57:21.372  7322  7322 D AppUp4:CustModeStarterReceiver: begin check event
09-12 13:57:21.373  7322  7322 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-12 13:57:21.373  7322  7322 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-12 13:57:21.374  7322  7340 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-12 13:57:21.374  7322  7340 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-12 13:57:21.375  7322  7340 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-12 13:57:21.376  1035  1940 I ActivityManager: Killing 6680:com.android.gallery3d/u0a27 (adj 15): empty #17
09-12 13:57:21.399  1035  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 13:57:21.432  1035  1867 W libprocessgroup: failed to open /acct/uid_10027/pid_6680/cgroup.procs: No such file or directory
,09-12 13:57:21.434  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:21.435  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:21.438  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:21.441  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:21.446  3388  3388 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:21.447  4834  7346 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:21.452  4834  7346 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-12 13:57:21.453  3388  3388 V DownloadManager: DownloadService onCreate
09-12 13:57:21.454  3388  7348 I DownloadManager: in removeSpuriousFiles
09-12 13:57:21.456  3388  7348 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-12 13:57:21.458  3388  7348 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@bbe843b on behalf of 3388
09-12 13:57:21.460  1035  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-12 13:57:21.460  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-12 13:57:21.460  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-12 13:57:21.460  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:21.460  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-12 13:57:21.460  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,09-12 13:57:21.460  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
,09-12 13:57:21.460  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-12 13:57:21.461  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-12 13:57:21.461  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-12 13:57:21.461  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:21.461  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-12 13:57:21.461  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-12 13:57:21.461  3388  7348 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-12 13:57:21.461  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:21.462  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:21.462  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:21.463  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-12 13:57:21.463  1035  1545 D ConnectivityService: identical MTU - not setting
09-12 13:57:21.463  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 13:57:21.463  1035  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 13:57:21.463  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:21.464  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:21.464  3388  7348 I DownloadManager: in trimDatabase
09-12 13:57:21.464  3388  7348 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-12 13:57:21.465  1035  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:21.467  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-12 13:57:21.469  3388  7348 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@d0a7758 on behalf of 3388
09-12 13:57:21.468  4834  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:21.470  4834  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:21.509  1035  1050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7352 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-12 13:57:21.511  1035  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:21.511  1035  1904 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:21.511  1035  1117 D BluetoothManagerService: Message: 1
09-12 13:57:21.511  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
09-12 13:57:21.512  3388  3388 V DownloadManager: DownloadService onStartCommand
09-12 13:57:21.513  4834  7346 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-12 13:57:21.514  4342  4435 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-12 13:57:21.514  4342  4435 D BluetoothAdapterProperties: Setting state to 11
09-12 13:57:21.514  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 13:57:21.515  1035  1117 D BluetoothManagerService: Message: 60
09-12 13:57:21.515  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-12 13:57:21.515  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-12 13:57:21.515  4342  4435 D BluetoothBondStateMachine: make
09-12 13:57:21.517  4342  4435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.517  4342  7361 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 13:57:21.517  4342  4435 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-12 13:57:21.517  4342  4435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.517  4342  4435 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-12 13:57:21.517  4342  4435 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-12 13:57:21.519  4834  4834 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-12 13:57:21.519  4834  4834 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-12 13:57:21.520  4834  4834 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-12 13:57:21.520  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:21.522  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:21.523  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 13:57:21.523  4834  4834 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-12 13:57:21.527  7089  7089 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-12 13:57:21.536  3388  7349 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-12 13:57:21.540  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:21.544  4834  4834 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-12 13:57:21.545  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.550  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:21.551  3388  7349 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@15072917 on behalf of 3388
09-12 13:57:21.554  3388  7349 V DownloadManager: processing inserted download 1
09-12 13:57:21.555  3388  7349 V DownloadManager: processing inserted download 4
09-12 13:57:21.556  3388  7349 V DownloadManager: processing inserted download 7
09-12 13:57:21.557  3388  7349 V DownloadManager: processing inserted download 8
,09-12 13:57:21.560  3388  7349 V DownloadManager: processing inserted download 9
09-12 13:57:21.562  3388  7349 V DownloadManager: processing inserted download 10
09-12 13:57:21.563  3388  7349 V DownloadManager: processing inserted download 11
09-12 13:57:21.564  3388  7349 V DownloadManager: processing inserted download 12
09-12 13:57:21.565  3388  7349 V DownloadManager: processing inserted download 13
09-12 13:57:21.566  3388  7349 V DownloadManager: processing inserted download 14
09-12 13:57:21.568  3388  7349 V DownloadManager: processing inserted download 16
09-12 13:57:21.697  1035  1051 I art     : Explicit concurrent mark sweep GC freed 118221(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.724ms total 166.924ms
,09-12 13:57:21.707  4342  4342 D HeadsetService: Received start request. Starting profile...
09-12 13:57:21.707  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:21.707  4342  4342 D HeadsetStateMachine: make
09-12 13:57:21.718  3388  3388 V DownloadManager: DownloadService onDestroy
,09-12 13:57:21.729  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:21.729  4342  4342 D HeadsetStateMachine: max_hf_connections = 1
09-12 13:57:21.729  4342  4342 I bluedroid-qcom: get_profile_interface handsfree
09-12 13:57:21.729  4342  4342 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-12 13:57:21.729  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.730  4342  7370 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-12 13:57:21.730  4342  7370 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 13:57:21.730  4342  7370 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 13:57:21.730  4342  7370 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-12 13:57:21.730   324  2149 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 4342
09-12 13:57:21.731  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:21.731  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:21.732  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:21.732  4342  4342 V BluetoothPbapReceiver: ***********state = 11
,09-12 13:57:21.734   324  2149 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-12 13:57:21.734   324  2149 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-12 13:57:21.734   324  2149 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-12 13:57:21.734   324  2149 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-12 13:57:21.734   324  2149 V voice   : voice_set_parameters: exit with code(0)
09-12 13:57:21.734   324  2149 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-12 13:57:21.734   324  2149 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-12 13:57:21.735   324  2149 V msm8974_platform: platform_set_parameters: exit with code(0)
09-12 13:57:21.735   324  2149 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-12 13:57:21.735   324  2149 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-12 13:57:21.735   324  2149 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-12 13:57:21.737  4342  4342 D A2dpService: Received start request. Starting profile...
09-12 13:57:21.737  4342  4342 V Avrcp   : make
09-12 13:57:21.737  4342  4342 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-12 13:57:21.737  4342  4342 I bluedroid-qcom: get_profile_interface avrcp
09-12 13:57:21.740  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:21.741  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:21.743  4342  4342 V AudioManager: registerRemoteController: size of Media player list: 0
09-12 13:57:21.745  4342  4342 E AudioManager: No RCC entry present to update
09-12 13:57:21.745  4342  4342 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 13:57:21.745  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-12 13:57:21.745  4342  4342 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-12 13:57:21.762  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-12 13:57:21.768  7352  7352 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:21.768  7352  7352 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 13:57:21.770  7352  7352 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 13:57:21.770  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:21.770  7352  7352 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 13:57:21.852  7089  7089 D BluetoothPermissionRequest: onReceive
09-12 13:57:21.852  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 13:57:21.868  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:21.873  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 13:57:21.880  4342  4435 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 13:57:21.929  1035  2031 V SIM_STK : Menu title from STK is T-Mobile
09-12 13:57:21.929  1035  2031 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:57:21.949  7352  7352 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-12 13:57:21.963  7352  7352 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-12 13:57:22.005  7352  7352 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 13:57:22.014  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:22.014  1035  1973 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:22.014  1035  1117 D BluetoothManagerService: Message: 1
09-12 13:57:22.014  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
09-12 13:57:22.016  4342  7314 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-12 13:57:22.017  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-12 13:57:22.062  1035  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 13:57:22.063  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-12 13:57:22.063  4342  4342 D A2dpStateMachine: make
09-12 13:57:22.065  7352  7352 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 13:57:22.065  7352  7352 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 13:57:22.067  4342  4342 I bluedroid-qcom: get_profile_interface a2dp
,09-12 13:57:22.067  4342  7381 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 13:57:22.069  4342  4342 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-12 13:57:22.070  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:22.070  4342  7380 D A2dpStateMachine: Enter Disconnected: -2
09-12 13:57:22.070  4342  4342 D HeadsetStateMachine: Proxy object connected
09-12 13:57:22.071  4342  4342 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-12 13:57:22.071  4342  4342 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-12 13:57:22.078  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 13:57:22.078  4342  7370 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-12 13:57:22.079  4342  7370 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:57:22.079  4342  7370 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-12 13:57:22.081  4342  4342 D HidService: Received start request. Starting profile...
09-12 13:57:22.081  4342  4342 I bluedroid-qcom: get_profile_interface hidhost
09-12 13:57:22.081  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
,09-12 13:57:22.083  4342  4342 D HealthService: Received start request. Starting profile...
09-12 13:57:22.087  4342  4342 I bluedroid-qcom: get_profile_interface health
09-12 13:57:22.087  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:22.089  4342  4342 D PanService: Received start request. Starting profile...
09-12 13:57:22.089  4342  4342 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:57:22.089  4342  4342 I bluedroid-qcom: get_profile_interface pan
,09-12 13:57:22.091  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:22.091  4342  4342 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:57:22.092  4342  4342 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:57:22.092  4342  4342 D BtGatt.GattService: start()
09-12 13:57:22.092  4342  4342 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:57:22.100  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:22.101  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
,09-12 13:57:22.101  4342  4342 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-12 13:57:22.101  4342  4342 V BluetoothMapService: BluetoothMapBinder()
09-12 13:57:22.102  4342  4342 D BluetoothMapService: Received start request. Starting profile...
09-12 13:57:22.102  4342  4342 D BluetoothMapService: start()
09-12 13:57:22.107  4342  4342 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-12 13:57:22.107  4342  4342 D BluetoothMapEmailAppObserver: createReceiver()
09-12 13:57:22.109  4342  4342 D BluetoothMapEmailAppObserver: initObservers()
09-12 13:57:22.109  4342  4342 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-12 13:57:22.109  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
,09-12 13:57:22.112  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService,
09-12 13:57:22.116  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 13:57:22.120  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-12 13:57:22.123  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 13:57:22.124  4342  4342 V PanService: [BTUI] SIM Extra State :ABSENT
09-12 13:57:22.128  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-12 13:57:22.131  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.131  4342  4342 V BluetoothMapService: Handler(): got msg=1
09-12 13:57:22.133  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-12 13:57:22.133  4342  4435 I bluedroid-qcom: enable
,09-12 13:57:22.133  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-12 13:57:22.134  4342  4435 I bt_hci_bdroid: init
09-12 13:57:22.134  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:22.134  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 13:57:22.134  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.134  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-12 13:57:22.137  4342  4435 I bt_vendor: bt-vendor : init
09-12 13:57:22.137  4342  4435 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 13:57:22.137  4342  4435 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 13:57:22.137  4342  4435 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-12 13:57:22.137  4342  4435 D bt_userial_mct: userial_init
09-12 13:57:22.137  4342  7389 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-12 13:57:22.137  4342  7389 I bt-btu  : btu_task pending for preload complete event
09-12 13:57:22.138  4342  4435 D bt_hci_bdroid: set_power 1
09-12 13:57:22.138  4342  4435 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 13:57:22.138  4342  4435 I bt_vendor: Starting hciattach daemon
09-12 13:57:22.138  4342  4435 I bt_vendor: try to set true
09-12 13:57:22.129  7393  7393 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:22.129  7393  7393 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:22.173  7394  7394 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-12 13:57:22.220  7352  7352 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-12 13:57:22.260  7352  7352 I HubEmail: JNI_OnLoad()
09-12 13:57:22.260  7352  7352 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 13:57:22.260  7352  7352 I HubEmail: registerNatives()
09-12 13:57:22.261  7352  7352 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 13:57:22.261  7352  7352 I HubEmail: registerNativeMethods()
09-12 13:57:22.261  7352  7352 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 13:57:22.261  7352  7352 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-12 13:57:22.267  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 13:57:22.267  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:22.267  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 13:57:22.278  7405  7405 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-12 13:57:22.289  7406  7406 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-12 13:57:22.290   316  7408 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:22.291   316  7408 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-12 13:57:22.312  7410  7410 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-12 13:57:22.323  1035  1576 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7412 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-12 13:57:22.324  7411  7411 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-12 13:57:22.327  7352  7404 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:22.335  7422  7422 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-12 13:57:22.343   316  7408 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-12 13:57:22.346  7428  7428 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-12 13:57:22.362  7432  7432 I libmdmdetect: ESOC framework not supported
,09-12 13:57:22.363  7432  7432 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-12 13:57:22.368  7432  7432 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-12 13:57:22.368  7432  7432 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-12 13:57:22.368  7432  7432 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-12 13:57:22.368  7432  7432 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-12 13:57:22.368  7432  7432 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-12 13:57:22.368  7432  7432 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-12 13:57:22.368  7432  7432 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-12 13:57:22.387  7132  7402 V FormManager: There are no updated forms. The schedule will be deleted.
,09-12 13:57:22.391  7132  7402 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-12 13:57:22.403  7432  7433 E QC-QMI  : qmi_client [7432] 14: failed to locate client data
,09-12 13:57:22.404   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-12 13:57:22.404   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-12 13:57:22.418  1035  1576 I ActivityManager: Killing 6745:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-12 13:57:22.436  7412  7412 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 13:57:22.437  7412  7412 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:57:22.441  7412  7412 D PhoneMonitor: Register our PhoneStateListener
09-12 13:57:22.475  7434  7434 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-12 13:57:22.480  1035  1940 W libprocessgroup: failed to open /acct/uid_10061/pid_6745/cgroup.procs: No such file or directory
,09-12 13:57:22.495  7435  7435 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 13:57:22.501  7412  7412 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 13:57:22.505  7412  7412 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-12 13:57:22.528  7412  7412 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-12 13:57:22.529  7412  7412 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-12 13:57:22.530  7412  7412 D TelephonyAutoProfiling: [parse] Load xml
,09-12 13:57:22.533  7412  7412 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-12 13:57:22.533  7412  7412 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-12 13:57:22.534  7412  7412 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-12 13:57:22.541  7412  7412 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-12 13:57:22.542  4342  4435 I bt_vendor: bluetooth satus is on
09-12 13:57:22.542  4342  4435 D bt_hci_bdroid: preload
09-12 13:57:22.543  4342  7392 D bt_userial_mct: userial_open(port:0)
09-12 13:57:22.543  4342  7392 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-12 13:57:22.543  4342  7392 I bt_vendor: Done intiailizing UART
09-12 13:57:22.544  4342  7392 I bt_vendor: Done intiailizing UART
,09-12 13:57:22.544  4342  7392 I bt_userial_mct: CMD=82, EVT=82, ACL_Out=83, ACL_In=83
09-12 13:57:22.544  4342  7392 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-12 13:57:22.545  4342  7439 D bt_userial_mct: Entering userial_read_thread()
09-12 13:57:22.545  4342  7389 I bt-btu  : btu_task received preload complete event
09-12 13:57:22.545  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-12 13:57:22.545  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-12 13:57:22.545  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:57:22.549  4342  7389 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:57:22.550  4342  7389 I         : BTE_InitTraceLevels -- TRC_BTIF
09-12 13:57:22.573  1035  2006 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7440 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:22.576  1035  2006 I ActivityManager: Killing 6870:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-12 13:57:22.588  4342  7389 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-12 13:57:22.588  4342  7389 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e9061 
,09-12 13:57:22.588  4342  7389 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e9061 
,09-12 13:57:22.595  4342  4439 E bt-btif : Calling BTA_HhEnable
09-12 13:57:22.595  4342  4439 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-12 13:57:22.595  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-12 13:57:22.595  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-12 13:57:22.595  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-12 13:57:22.595  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-12 13:57:22.595  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-12 13:57:22.595  4342  4439 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-12 13:57:22.602  4342  7389 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 13:57:22.602  4342  7389 W bt-smp  : Plain text(LSB ~ MSB) = af c1 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 13:57:22.602  4342  7389 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 8a 99 5d d2 9f 84 cb 6c 13 ce 2e d4 0a 45 47 
09-12 13:57:22.602  4342  7389 W bt-btm  : Stopping oneshot timer
,09-12 13:57:22.683  4342  4439 D BluetoothAdapterProperties: Name is: G3
09-12 13:57:22.683  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 13:57:22.684  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-12 13:57:22.697  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:22.698  1035  1973 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:22.699  1035  1751 W libprocessgroup: failed to open /acct/uid_10080/pid_6870/cgroup.procs: No such file or directory
09-12 13:57:22.699  1035  1117 D BluetoothManagerService: Message: 1
09-12 13:57:22.699  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
,09-12 13:57:22.704  4342  4439 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:57:22.704  4342  4439 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:57:22.704  4342  4439 D bt_hci_bdroid: postload
09-12 13:57:22.705  4342  7389 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-12 13:57:22.705  4342  7392 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 13:57:22.706  4342  7439 E bt_mct  : hci lib postload completed
09-12 13:57:22.706  4342  4439 D bte_conf: Device ID record 1 : primary
09-12 13:57:22.706  4342  4439 D bte_conf:   vendorId            = 00c4
09-12 13:57:22.706  4342  4439 D bte_conf:   vendorIdSource      = 0001
09-12 13:57:22.706  4342  4439 D bte_conf:   product             = 13a1
09-12 13:57:22.706  4342  4439 D bte_conf:   version             = 1000
09-12 13:57:22.706  4342  4439 D bte_conf:   clientExecutableURL = 
09-12 13:57:22.706  4342  4439 D bte_conf:   serviceDescription  = 
09-12 13:57:22.706  4342  4439 D bte_conf:   documentationURL    = 
09-12 13:57:22.706  4342  4439 D bte_conf: bte_load_did_conf no section named DID2.
09-12 13:57:22.709  4342  7314 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-12 13:57:22.710  4342  4439 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 13:57:22.710  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 13:57:22.710  4342  4435 D BluetoothAdapterProperties: ScanMode =  20
09-12 13:57:22.710  4342  4435 D BluetoothAdapterProperties: State =  11
09-12 13:57:22.710  4342  4435 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-12 13:57:22.711  4342  4435 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-12 13:57:22.711  4342  4435 D BluetoothAdapterProperties: Setting state to 12
09-12 13:57:22.711  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:57:22.712  4342  4439 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 13:57:22.699  7458  7458 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:22.699  7458  7458 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:22.714  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-12 13:57:22.714  1035  1117 D BluetoothManagerService: Message: 60
,09-12 13:57:22.714  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-12 13:57:22.714  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-12 13:57:22.719  4342  4435 I BluetoothAdapterState: Entering On State
09-12 13:57:22.721  4342  4435 D LGBluetoothServiceAdapter: [BTUI] OnState
09-12 13:57:22.721  4342  4435 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-12 13:57:22.721  4342  4435 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-12 13:57:22.723  4342  4435 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-12 13:57:22.723  7089  7105 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:22.727  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:22.730  4342  4439 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:57:22.730  4342  4439 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-12 13:57:22.730  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:22.731  7089  7089 D BluetoothMap: Proxy object connected
09-12 13:57:22.731  7089  7089 D MapProfile: Bluetooth service connected
09-12 13:57:22.731  7089  7089 D BluetoothMap: getConnectedDevices()
09-12 13:57:22.732  1850  2451 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:22.733  4342  7314 V BluetoothMapService: getConnectedDevices()
09-12 13:57:22.736  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:22.736  1850  1850 D BluetoothHeadset: Proxy object connected
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:22.737  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:22.738  1035  1035 D BluetoothHeadset: Proxy object connected
09-12 13:57:22.739  7089  7105 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:57:22.742  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:22.746  7089  7104 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:57:22.746  7089  7104 D BluetoothPan: onBluetoothStateChange call bindService
09-12 13:57:22.746  7089  7089 D BluetoothInputDevice: Proxy object connected
09-12 13:57:22.746  7089  7089 D HidProfile: Bluetooth service connected
09-12 13:57:22.749  1850  4449 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:22.750  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:22.752  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:22.755  1850  1850 D BluetoothHeadset: Proxy object connected
09-12 13:57:22.756  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:57:22.756  7089  7089 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:57:22.756  7089  7089 D PanProfile: Bluetooth service connected
,09-12 13:57:22.758  1035  1035 D BluetoothA2dp: Proxy object connected
09-12 13:57:22.758  7089  7462 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:57:22.761  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:22.762  1815  7460 I CheckinService: active receiver: enabled
09-12 13:57:22.763  1850  1850 D BluetoothHeadset: Proxy object connected
09-12 13:57:22.768  4342  4435 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-12 13:57:22.773  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-12 13:57:22.773  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-12 13:57:22.774  1815  7460 I CheckinService: Preparing to send checkin request
09-12 13:57:22.774  1815  7460 I EventLogService: Accumulating logs since 1473681353036
09-12 13:57:22.775  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.776  1941  2125 D LGBluetoothAPIService: Message: 1
09-12 13:57:22.776  1941  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-12 13:57:22.778  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 13:57:22.780  7465  7465 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-12 13:57:22.789  6796  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-12 13:57:22.791  1941  2125 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-12 13:57:22.793  4342  4342 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.793  4342  4342 D BluetoothMapService: STATE_ON
09-12 13:57:22.793  4342  4342 V BluetoothMapService: Handler(): got msg=1
09-12 13:57:22.793  4342  4342 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-12 13:57:22.794  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:22.794  4342  4342 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-12 13:57:22.795  4342  7467 D BluetoothMapMasInstance: MAS initSocket()
09-12 13:57:22.796  4342  7467 D BluetoothMapMasInstance:   masId = 00
09-12 13:57:22.796  4342  7467 D BluetoothMapMasInstance:   msgTypes = 0e
09-12 13:57:22.796  4342  7467 D BluetoothMapMasInstance:   masName = SMS/MMS
09-12 13:57:22.796  4342  7467 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-12 13:57:22.796  4342  4342 D LGBluetoothAPIServer: [BTUI] onBind()
09-12 13:57:22.797  7089  7089 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 13:57:22.797  1035  1751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:22.799  1035  1117 D BluetoothManagerService: Message: 30
09-12 13:57:22.799  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-12 13:57:22.799  1941  2125 D LGBluetoothAPIService: Message: 100
09-12 13:57:22.799  1941  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-12 13:57:22.799  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:22.799  4342  4342 V BluetoothPbapService: Pbap Service onCreate
09-12 13:57:22.799  4342  4342 V BluetoothPbapService: Starting PBAP service
09-12 13:57:22.800  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:22.800  4342  7467 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:22.800  4342  4342 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-12 13:57:22.801  4342  4342 V BluetoothPbapService: Pbap Service onBind
09-12 13:57:22.802  4342  4342 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.802  4342  4342 V BluetoothPbapService: state: 12
09-12 13:57:22.802  4342  4342 V BluetoothPbapService: Handler(): got msg=1
09-12 13:57:22.803  4342  4342 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-12 13:57:22.803  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:22.804  7089  7089 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 13:57:22.806  4342  7467 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=88 mFd=84
09-12 13:57:22.806  4342  7467 V BluetoothMapMasInstance: Succeed to create listening socket 
09-12 13:57:22.806  4342  7468 V BluetoothPbapService: Pbap Service initSocket
09-12 13:57:22.806  4342  7467 D BluetoothMapMasInstance: Accepting socket connection...
09-12 13:57:22.807  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:22.807  4342  4439 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:57:22.807  4342  4439 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-12 13:57:22.808  4342  7468 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:22.810  1035  1117 D BluetoothManagerService: Message: 30
09-12 13:57:22.810  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:22.810  4342  7468 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=89 mFd=88
09-12 13:57:22.811  4342  7468 V BluetoothPbapService: Succeed to create listening socket 
09-12 13:57:22.811  4342  7468 V BluetoothPbapService: Accepting socket connection...
09-12 13:57:22.812  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:22.813  7089  7089 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-12 13:57:22.814  7089  7089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 13:57:22.815  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:22.817  7089  7089 D BluetoothPbap: Proxy object connected
09-12 13:57:22.817  7089  7089 D PbapServerProfile: Bluetooth service connected
09-12 13:57:22.817  7089  7089 D BluetoothA2dp: Proxy object connected
09-12 13:57:22.818  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:22.818  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.818  4342  4342 V BluetoothPbapReceiver: ***********state = 12
09-12 13:57:22.819  7089  7089 D A2dpProfile: Bluetooth service connected
09-12 13:57:22.820  7089  7089 D BluetoothHeadset: Proxy object connected
09-12 13:57:22.820  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:57:22.821  2206  2206 D c       : Getting all permits...
09-12 13:57:22.821  2206  2206 D a       : Opening database...
09-12 13:57:22.822  7089  7089 D HeadsetProfile: Bluetooth service connected
09-12 13:57:22.825  2206  2206 D a       : Opening database auth.proximity.permit_store...
09-12 13:57:22.825  2206  2206 D a       : Closing database...
09-12 13:57:22.829  7089  7089 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:22.834  1815  7460 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-12 13:57:22.837  7089  7089 D BluetoothPermissionRequest: onReceive
09-12 13:57:22.839  7089  7089 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 13:57:22.840  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:22.843  4342  4342 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-12 13:57:22.848  4342  4342 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-12 13:57:22.851  4342  4342 V BtOppService: onCreate
09-12 13:57:22.851  4342  4342 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-12 13:57:22.852  4342  4342 V BluetoothOppNotification: send message
09-12 13:57:22.854  4342  7471 V BtOppService: Deleted complete outbound shares, number =  0
09-12 13:57:22.854  4342  4342 V BtOppService: Starting RfcommListener
09-12 13:57:22.854  4342  4342 D BluetoothOppPreference: Dumping Names:  
09-12 13:57:22.855  4342  4342 D BluetoothOppPreference: {}
09-12 13:57:22.855  4342  4342 D BluetoothOppPreference: Dumping Channels:  
,09-12 13:57:22.855  4342  4342 D BluetoothOppPreference: {}
09-12 13:57:22.855  4342  4342 V BtOppService: onStartCommand
09-12 13:57:22.855  4342  7471 V BtOppService: Deleted complete inbound failed shares, number = 0
09-12 13:57:22.856  4342  7471 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-12 13:57:22.857  4342  7472 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 13:57:22.857  4342  7472 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 13:57:22.857  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.857  4342  7471 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ec97630 on behalf of 
09-12 13:57:22.857  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 13:57:22.860  4342  4342 V BluetoothOppNotification: new notify threadi!
09-12 13:57:22.860  4342  7472 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16ea22a9 on behalf of 
09-12 13:57:22.860  4342  4342 V BluetoothOppNotification: send delay message
09-12 13:57:22.860  4342  4342 V BtOppService: ContentObserver received notification
09-12 13:57:22.860  4342  4342 V BtOppService: start RfcommListener
,09-12 13:57:22.862  4342  4342 V BtOppService: RfcommListener started
09-12 13:57:22.862  4342  4342 V BtOppService: ContentObserver received notification
09-12 13:57:22.862  4342  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 13:57:22.863  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:22.863  4342  4342 V BluetoothFtpService: Ftp Service onCreate
09-12 13:57:22.863  4342  4342 I BluetoothFtpService: Ftp Service onCreate
09-12 13:57:22.863  4342  7474 V BtOppRfcommListener: Starting RFCOMM listener....
09-12 13:57:22.868  4342  4342 V BluetoothFtpService: Ftp Service onStartCommand
09-12 13:57:22.868  4342  4342 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.868  4342  4342 V BluetoothFtpService: Starting Listening on sockets
09-12 13:57:22.868  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 13:57:22.868  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:22.868  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 13:57:22.868  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.868  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-12 13:57:22.868  4342  4342 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 13:57:22.869  4342  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13aff7cf on behalf of 
09-12 13:57:22.869  4342  7473 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 13:57:22.870  1035  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:22.870  4342  4342 V BluetoothFtpService: Handler(): got msg=1
09-12 13:57:22.871  4342  4342 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-12 13:57:22.871  4342  4342 V BluetoothFtpService: Ftp Service initSocket
09-12 13:57:22.871  4342  7474 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:22.871  4342  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 13:57:22.872  4342  7472 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 13:57:22.872  4342  7472 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 13:57:22.873  4342  7474 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=91 mFd=89
09-12 13:57:22.874  4342  7474 V BtOppRfcommListener: Started RFCOMM listener....
09-12 13:57:22.874  4342  7474 I BtOppRfcommListener: Accept thread started.
09-12 13:57:22.874  4342  7474 V BtOppRfcommListener: Accepting connection...
09-12 13:57:22.875  4342  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3887c55c on behalf of 
09-12 13:57:22.875  4342  7472 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31194065 on behalf of 
09-12 13:57:22.875  4342  7473 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 13:57:22.875  1035  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:22.876  4342  4342 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:22.876  4342  7472 V BluetoothOppNotification: update too frequent, put in queue
09-12 13:57:22.877  4342  4342 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=95 mFd=91
09-12 13:57:22.877  4342  43,42 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-12 13:57:22.877  4342  7472 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 13:57:22.877  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:22.877  4342  4342 V BluetoothSapService: Sap Service onCreate
09-12 13:57:22.878  4342  4342 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:22.879  4342  4342 V BluetoothSapService: state: 12
09-12 13:57:22.879  4342  4342 V BluetoothSapService: Starting SAP server process
09-12 13:57:22.880  4342  7475 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-12 13:57:22.880  4342  4342 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-12 13:57:22.869  7476  7476 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:22.869  7476  7476 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:22.883  4342  7477 V BluetoothSapService: Sap Service initRfcommSocket
09-12 13:57:22.888  4342  7473 V BluetoothOppNotification: outbound notification was removed.
09-12 13:57:22.888  4342  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 13:57:22.888  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:22.889  7476  7476 V BT_SAP  : Event pipe created
09-12 13:57:22.889  7476  7476 V BT_SAP  : create_server_socket qcom.sap.server
09-12 13:57:22.889  7476  7476 V BT_SAP  : created socket fd 6
09-12 13:57:22.889  4342  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8627de1 on behalf of 
09-12 13:57:22.890  4342  7477 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:22.890  4342  7473 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 13:57:22.890  4342  7477 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=96 mFd=95
09-12 13:57:22.891  4342  7477 V BluetoothSapService: Succeed to create listening socket 
,09-12 13:57:22.891  4342  7477 V BluetoothSapService: Accepting socket connection...
09-12 13:57:22.891  4342  7473 V BluetoothOppNotification: inbound notification was removed.
09-12 13:57:22.892  4342  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 13:57:22.892  4342  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11505706 on behalf of 
09-12 13:57:22.954  1035  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:22.955  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:22.955  1035  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:22.964  1035  1867 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7478 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-12 13:57:22.975  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 13:57:22.976  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 13:57:22.976  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 13:57:22.976  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 13:57:22.977  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-12 13:57:22.977  1035  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 13:57:23.021  1035  1903 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7495 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-12 13:57:23.022  1035  1903 I ActivityManager: Killing 6891:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-12 13:57:23.153  1035  1051 W libprocessgroup: failed to open /acct/uid_10097/pid_6891/cgroup.procs: No such file or directory
,09-12 13:57:23.183  7478  7478 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-12 13:57:23.184  7478  7478 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 13:57:23.202  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:23.202  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:23.212  1035  1867 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:23.213  1035  1867 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:23.222  7478  7478 I MultiDex: VM with version 2.1.0 has multidex support
09-12 13:57:23.222  1035  1117 D BluetoothManagerService: Message: 2
,09-12 13:57:23.222  7478  7478 I MultiDex: install
09-12 13:57:23.223  7478  7478 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-12 13:57:23.228  1035  1117 D BluetoothManagerService: Sending off request.
09-12 13:57:23.228  4342  7318 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-12 13:57:23.230  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 13:57:23.230  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 13:57:23.230  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-12 13:57:23.231  4342  4435 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-12 13:57:23.231  4342  4435 D BluetoothAdapterProperties: Setting state to 13
09-12 13:57:23.231  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:57:23.232  4342  4435 D BluetoothAdapterProperties: onBluetoothDisable(),
09-12 13:57:23.232  4342  4435 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-12 13:57:23.234  4342  4439 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:57:23.239  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 13:57:23.240  4342  7474 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:23.240  4342  4435 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-12 13:57:23.242  4342  7467 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-12 13:57:23.242  4342  7468 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:23.243  4342  7475 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:23.243  4342  7477 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:57:23.243  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-12 13:57:23.243  4342  7389 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-12 13:57:23.246  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:23.246  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:23.249  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:57:23.249  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:23.252  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:23.252  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:23.253  6796  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:23.253  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:23.253  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-12 13:57:23.254  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-12 13:57:23.254  4342  7389 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 13:57:23.254  7478  7478 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-12 13:57:23.256  1035  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=65.5, 0.0, 0.0  rx=66.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:507660728] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:23.257  1035  1117 D BluetoothManagerService: Message: 60
09-12 13:57:23.257  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-12 13:57:23.257  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-12 13:57:23.258  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.258  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=65.5, 0.0, 0.0  rx=66.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:507660729] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:23.258  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-12 13:57:23.262  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 13:57:23.264  4342  4342 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.264  4342  4342 D BluetoothMapService: STATE_TURNING_OFF
09-12 13:57:23.264  4342  4342 V BluetoothMapService: Handler(): got msg=4
09-12 13:57:23.265  4342  4342 D BluetoothMapService: MAP Service closeService in
09-12 13:57:23.265  4342  4342 D BluetoothMapMasInstance: MAP Service shutdown
09-12 13:57:23.265  4342  4342 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 13:57:23.265  4342  4342 V BluetoothMapService: MAP Service closeService out
09-12 13:57:23.265  4342  4342 V BtOppService: Receiver DISABLED_ACTION 
09-12 13:57:23.265  4342  4342 I BtOppRfcommListener: stopping Accept Thread
09-12 13:57:23.265  4342  4342 V BtOppRfcommListener: close mBtServerSocket
09-12 13:57:23.265  4342  4342 V BtOppRfcommListener: waiting for thread to terminate
09-12 13:57:23.265  4342  7474 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 13:57:23.266  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:23.266  4342  4342 V BtOppRfcommListener: done waiting for thread to terminate
09-12 13:57:23.267  4342  4342 V BtOppService: onDestroy
09-12 13:57:23.270  4342  4342 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-12 13:57:23.271  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:23.286  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:23.295  7089  7089 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-12 13:57:23.297  7089  7089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 13:57:23.301  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:23.302  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.302  4342  4342 V BluetoothPbapReceiver: ***********state = 13
,09-12 13:57:23.303  4342  4342 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-12 13:57:23.305  4342  4342 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.305  4342  4342 V BluetoothPbapService: state: 13
09-12 13:57:23.306  4342  4342 V BluetoothPbapService: Pbap Service closeService in
09-12 13:57:23.307  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:23.308  4342  4342 V BluetoothPbapService: successfully stopped pbap service
09-12 13:57:23.308  4342  4342 V BluetoothPbapService: Pbap Service closeService out
09-12 13:57:23.309  4342  4342 V BluetoothPbapService: Pbap Service onDestroy
09-12 13:57:23.309  4342  4342 V BluetoothPbapService: Pbap Service closeService in
09-12 13:57:23.309  4342  4342 V BluetoothPbapService: Pbap Service closeService out
09-12 13:57:23.309  4342  4342 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-12 13:57:23.310  7089  7089 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:23.311  7089  7089 D BluetoothPbap: Proxy object disconnected
09-12 13:57:23.311  7089  7089 D PbapServerProfile: Bluetooth service disconnected
09-12 13:57:23.325  7089  7089 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-12 13:57:23.332  7089  7089 D BluetoothPermissionRequest: onReceive
09-12 13:57:23.332  7089  7089 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-12 13:57:23.364  1035  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-12 13:57:23.377  1035  1992 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7535 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:23.384  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:23.388  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:23.389  1035  2030 I ActivityManager: Killing 6920:com.lge.eula/1000 (adj 15): empty #17
09-12 13:57:23.481  4342  4342 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-12 13:57:23.481  4342  4342 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-12 13:57:23.482  4342  4342 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-12 13:57:23.484  1035  2006 W libprocessgroup: failed to open /acct/uid_1000/pid_6920/cgroup.procs: No such file or directory
09-12 13:57:23.499  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:57:23.508  5865  5865 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-12 13:57:23.513  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:23.516  1035  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:23.519  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.519  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 13:57:23.521  4342  4342 V BluetoothFtpService: Ftp Service onStartCommand
09-12 13:57:23.521  4342  4342 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.521  4342  4342 V BluetoothFtpService: Ftp Service closeService
09-12 13:57:23.521  4342  4342 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-12 13:57:23.522  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:23.522  4342  4342 V BluetoothFtpService: successfully stopped ftp service
09-12 13:57:23.522  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 13:57:23.522  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:23.522  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 13:57:23.522  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.522  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-12 13:57:23.522  4342  4342 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 13:57:23.523  4342  4342 V BluetoothFtpService: Ftp Service onDestroy
09-12 13:57:23.523  4342  4342 V BluetoothFtpService: Ftp Service closeService
09-12 13:57:23.526  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:23.527  4342  4342 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:23.527  4342  4342 V BluetoothSapService: state: 13
09-12 13:57:23.527  4342  4342 V BluetoothSapService: Stopping SAP server process
,09-12 13:57:23.528  4342  4342 V BluetoothSapService: Sap Service closeSapService in
09-12 13:57:23.528  4342  4342 V BluetoothSapService: Close listen Socket : 
09-12 13:57:23.528  4342  4342 V BluetoothSapService: Close rfcomm Socket : 
09-12 13:57:23.528  4342  4342 V BluetoothSapService: Close sapd  Socket : 
09-12 13:57:23.532  4342  4342 V BluetoothSapService: Sap Service closeSapService out
09-12 13:57:23.532  4342  4342 V BluetoothSapService: Sap Service onDestroy
09-12 13:57:23.532  4342  4342 V BluetoothSapService: Sap Service closeSapService in
09-12 13:57:23.532  4342  4342 V BluetoothSapService: Close listen Socket : 
09-12 13:57:23.532  4342  4342 V BluetoothSapService: Close rfcomm Socket : 
09-12 13:57:23.532  4342  4342 V BluetoothSapService: Close sapd  Socket : 
09-12 13:57:23.533  4342  4342 V BluetoothSapService: Sap Service closeSapService out
09-12 13:57:23.538  7535  7535 I art     : Almond Protected OAT
,09-12 13:57:23.590  7535  7535 D WeatherApplication: removeAccount
,09-12 13:57:23.591  7535  7535 D WeatherApplication: Account.length = 0
,09-12 13:57:23.591  7535  7535 E WeatherApplication: OPERATOR:OPEN
09-12 13:57:23.595  7535  7535 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:23
09-12 13:57:23.598  7535  7535 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 13:57:23.599  7535  7535 D Weather.Utils: 2 : All the weather widget is gone.
09-12 13:57:23.600  7535  7535 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 13:57:23.603  7535  7535 D WeatherAncestor: connectivity changed - connection : true
09-12 13:57:23.603  7535  7535 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-12 13:57:23.615  7535  7535 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 13:57:23.615  7535  7535 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 13:57:23.616  7535  7535 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-12 13:57:23.633  7535  7535 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 13:57:23.633  7535  7535 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:23
,09-12 13:57:23.710  1035  2006 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7553 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:23.712  1035  2006 I ActivityManager: Killing 2126:com.lge.music/u0a34 (adj 15): empty #17
,09-12 13:57:23.730  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:23.730  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:23.732  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:23.732  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:23.740   324  2148 V AudioFlinger: 2126 died, releasing its sessions
,09-12 13:57:23.740   324  2148 V AudioFlinger:  pid 1850 @ 0
09-12 13:57:23.740   324  2148 V AudioFlinger:  pid 3219 @ 1
09-12 13:57:23.740   324  2148 V AudioFlinger:  pid 3219 @ 2
09-12 13:57:23.790  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:23.790  1035  1904 W libprocessgroup: failed to open /acct/uid_10034/pid_2126/cgroup.procs: No such file or directory
09-12 13:57:23.790  1035  2030 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
,09-12 13:57:23.813  1035  1117 D BluetoothManagerService: Message: 1
,09-12 13:57:23.814  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
09-12 13:57:23.815  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 13:57:23.816  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 13:57:23.816  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-12 13:57:23.817  4342  4359 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-12 13:57:23.817  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
,09-12 13:57:23.860  4342  4342 V BluetoothOppNotification: previous thread is not finished yet
,09-12 13:57:23.906  7576  7576 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-12 13:57:23.928   281   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 13:57:23.928   281   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-12 13:57:23.928   281   354 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 13:57:23.930  7553  7579 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-12 13:57:23.962   281   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 13:57:23.962   281   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-12 13:57:23.962   281   354 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:23.962  7553  7579 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-12 13:57:23.969   281   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 13:57:23.969   281   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-12 13:57:23.969   281   354 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 13:57:23.970  7553  7586 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-12 13:57:23.972   281   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 13:57:23.972   281   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-12 13:57:23.972   281   354 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 13:57:23.973  7553  7586 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-12 13:57:23.974  7576  7576 I dex2oat : dex2oat took 68.121ms (threads: 4)
09-12 13:57:23.991  7478  7493 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 13:57:23.991  7478  7493 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 13:57:23.991  7478  7493 I Adreno-EGL: Build Date: 12/12/14 금
09-12 13:57:23.991  7478  7493 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 13:57:23.991  7478  7493 I Adreno-EGL: Remote Branch: 
09-12 13:57:23.991  7478  7493 I Adreno-EGL: Local Patches: 
09-12 13:57:23.991  7478  7493 I Adreno-EGL: Reconstruct Branch: 
,09-12 13:57:24.127  7478  7493 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 13:57:24.127  7478  7493 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 13:57:24.127  7478  7493 I Adreno-EGL: Build Date: 12/12/14 금
09-12 13:57:24.127  7478  7493 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 13:57:24.127  7478  7493 I Adreno-EGL: Remote Branch: 
09-12 13:57:24.127  7478  7493 I Adreno-EGL: Local Patches: 
09-12 13:57:24.127  7478  7493 I Adreno-EGL: Reconstruct Branch: 
,09-12 13:57:24.221  7553  7553 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-12 13:57:24.225  7478  7493 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:57:24.226  7478  7493 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:57:24.231  7553  7553 I LibraryLoader: Loading: webviewchromium
09-12 13:57:24.234  7553  7553 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 4391-4396)
09-12 13:57:24.234  7553  7553 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:57:24.239  7553  7553 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3797ae09}
,09-12 13:57:24.243  7553  7553 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:57:24.243  7553  7553 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:57:24.251  4342  4439 D bt_hci_bdroid: cleanup
09-12 13:57:24.251  4342  7392 I bt_lpm  : LPM is already off!!!
,09-12 13:57:24.252  4342  7439 I bt_userial_mct: exiting userial_read_thread
09-12 13:57:24.252  4342  7439 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 13:57:24.252  4342  7389 W bt-btif : ag scb idx 1 not allocated
09-12 13:57:24.252  4342  7389 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 13:57:24.252  4342  7389 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:24.252  4342  7389 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 13:57:24.252  4342  4439 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 13:57:24.253  4342  7392 I bt_vendor: hw_epilog_process
09-12 13:57:24.253  4342  4439 D bt_hci_bdroid: cleanup Finalizing cleanup
09-12 13:57:24.253  4342  4439 D bt_userial_mct: userial_close
09-12 13:57:24.253  4342  4439 E bt_userial_mct: pthread_join() FAILED result:3
09-12 13:57:24.253  4342  4439 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-12 13:57:24.256  7553  7553 I BrowserStartupController: Initializing chromium process, renderers=0
09-12 13:57:24.257  7553  7553 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:57:24.266  7553  7553 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-12 13:57:24.266  7553  7553 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-12 13:57:24.267  7553  7553 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-12 13:57:24.287  7553  7553 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 13:57:24.287  7553  7553 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 13:57:24.287  7553  7553 I Adreno-EGL: Build Date: 12/12/14 금
09-12 13:57:24.287  7553  7553 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 13:57:24.287  7553  7553 I Adreno-EGL: Remote Branch: 
09-12 13:57:24.287  7553  7553 I Adreno-EGL: Local Patches: 
09-12 13:57:24.287  7553  7553 I Adreno-EGL: Reconstruct Branch: 
,09-12 13:57:24.289   324   324 V AudioPolicyService: registerClient() client 0xb57d3be0, uid 10093
09-12 13:57:24.290  7553  7612 W AudioManagerAndroid: Requires BLUETOOTH permission
09-12 13:57:24.317  1035  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:24.317  1035  2006 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
,09-12 13:57:24.318  1035  1117 D BluetoothManagerService: Message: 1
09-12 13:57:24.318  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
09-12 13:57:24.321  4342  7314 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-12 13:57:24.321  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-12 13:57:24.386  7553  7553 I NSApplication: Starting up...
,09-12 13:57:24.388  4342  4439 D bt_hci_bdroid: set_power 0
09-12 13:57:24.388  4342  4439 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 13:57:24.388  4342  4439 I bt_vendor: bluetooth satus is on
09-12 13:57:24.388  4342  4439 I bt_vendor: bt-vendor : resetting BT status
09-12 13:57:24.388  4342  4439 I bt_vendor: Starting hciattach daemon
09-12 13:57:24.388  4342  4439 I bt_vendor: try to set false
09-12 13:57:24.388  4342  4439 I bt_vendor: Starting hciattach daemon
09-12 13:57:24.388  4342  4439 I bt_vendor: try to set false
09-12 13:57:24.389  4342  4439 I bt_vendor: cleanup
09-12 13:57:24.389  4342  7389 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-12 13:57:24.389  4342  4439 I GKI_LINUX: GKI_exit_task 0 done
09-12 13:57:24.389  4342  4439 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 13:57:24.390  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 13:57:24.393  4342  4342 D HeadsetService: Received stop request...Stopping profile...
09-12 13:57:24.393  4342  4342 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 13:57:24.393  4342  4342 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:57:24.393  4342  7370 D HeadsetStateMachine: Exit Disconnected: -1
09-12 13:57:24.393  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.395  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:24.395  4342  4435 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 13:57:24.395  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:24.395  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 13:57:24.395  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:24.395  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:24.396  4342  4342 D A2dpService: Received stop request...Stopping profile...
09-12 13:57:24.396  7089  7089 D BluetoothHeadset: Proxy object disconnected
09-12 13:57:24.396  7089  7089 D HeadsetProfile: Bluetooth service disconnected
09-12 13:57:24.396  4342  7380 D A2dpStateMachine: Exit Disconnected: -1
09-12 13:57:24.396  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-12 13:57:24.397  4342  4342 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-12 13:57:24.397  4342  4342 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:57:24.397  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.398  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-12 13:57:24.398  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 13:57:24.398  7089  7089 D BluetoothA2dp: Proxy object disconnected
,09-12 13:57:24.398  7089  7089 D A2dpProfile: Bluetooth service disconnected
09-12 13:57:24.399  4342  4342 D HidService: Received stop request...Stopping profile...
09-12 13:57:24.399  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.401  7089  7089 D BluetoothInputDevice: Proxy object disconnected
09-12 13:57:24.401  7089  7089 D HidProfile: Bluetooth service disconnected
09-12 13:57:24.403  4342  4342 D HealthService: Received stop request...Stopping profile...
09-12 13:57:24.403  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.404  4342  4342 D PanService: Received stop request...Stopping profile...
09-12 13:57:24.405  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.406  7089  7089 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:57:24.406  7089  7089 D PanProfile: Bluetooth service disconnected
09-12 13:57:24.406  4342  4342 D HeadsetStateMachine: Unbinding service...
09-12 13:57:24.406  4342  4342 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 13:57:24.406  4342  4342 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 13:57:24.406  4342  4342 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 13:57:24.406  4342  4342 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 13:57:24.406  4342  4342 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:57:24.406  4342  4342 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:57:24.406  4342  4342 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 13:57:24.406  4342  4342 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:57:24.407  4342  4342 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:57:24.407  4342  4342 D BtGatt.GattService: stop()
09-12 13:57:24.407  4342  4342 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 13:57:24.407  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.409  7478  7493 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 13:57:24.409  7478  7493 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 13:57:24.409  7478  7493 I Adreno-EGL: Build Date: 12/12/14 금
09-12 13:57:24.409  7478  7493 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 13:57:24.409  7478  7493 I Adreno-EGL: Remote Branch: 
09-12 13:57:24.409  7478  7493 I Adreno-EGL: Local Patches: 
09-12 13:57:24.409  7478  7493 I Adreno-EGL: Reconstruct Branch: 
09-12 13:57:24.409  4342  4342 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:57:24.409  4342  4342 D BluetoothMapService: stop()
09-12 13:57:24.409  4342  4342 D BluetoothMapEmailAppObserver: deinitObservers()
09-12 13:57:24.409  4342  4342 D BluetoothMapEmailAppObserver: removeReceiver()
09-12 13:57:24.410  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.410  7089  7089 D BluetoothMap: Proxy object disconnected
09-12 13:57:24.410  7089  7089 D MapProfile: Bluetooth service disconnected
09-12 13:57:24.411  4342  4342 I BluetoothA2dpServiceJni: cleanupNative
09-12 13:57:24.411  4342  7381 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 13:57:24.411  4342  4342 I GKI_LINUX: GKI_exit_task 2 done
09-12 13:57:24.411  4342  4342 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 13:57:24.412  4342  4342 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:57:24.412  4342  4342 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 13:57:24.412  4342  4342 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:57:24.412  4342  4342 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:57:24.412  4342  4342 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:57:24.412  4342  4342 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:57:24.412  4342  4342 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:57:24.413  4342  4342 V BluetoothMapService: Handler(): got msg=4
09-12 13:57:24.413  4342  4342 D BluetoothMapService: MAP Service closeService in
09-12 13:57:24.413  4342  4342 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 13:57:24.413  4342  4342 V BluetoothMapService: MAP Service closeService out
09-12 13:57:24.413  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-12 13:57:24.413  4342  4435 D BluetoothAdapterProperties: Setting state to 10
09-12 13:57:24.414  4342  4342 D BluetoothMapService: cleanup()
09-12 13:57:24.414  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 13:57:24.414  4342  4342 D BluetoothMapService: MAP Service closeService in
09-12 13:57:24.414  4342  4342 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 13:57:24.414  4342  4342 V BluetoothMapService: MAP Service closeService out
09-12 13:57:24.414  1035  1117 D BluetoothManagerService: Message: 60
09-12 13:57:24.414  4342  4435 I BluetoothAdapterState: Entering OffState
09-12 13:57:24.414  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-12 13:57:24.414  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-12 13:57:24.415  7089  7462 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:57:24.465  1035  1940 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7627 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-12 13:57:24.466  1035  1940 I ActivityManager: Killing 6703:com.android.vending/u0a44 (adj 15): empty #17
,09-12 13:57:24.562  1035  1903 W libprocessgroup: failed to open /acct/uid_10044/pid_6703/cgroup.procs: No such file or directory
,09-12 13:57:24.563  1850  4449 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:57:24.577   316  7644 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-12 13:57:24.578   316  7644 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-12 13:57:24.581  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:57:24.582  7089  7105 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:57:24.583  7089  7104 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:57:24.584  7089  7462 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:57:24.585  1850  2451 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:57:24.586  7089  7105 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:57:24.588  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:57:24.589  7089  7104 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:57:24.590  1850  4449 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:57:24.591  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-12 13:57:24.593  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:24.593  1941  2125 D LGBluetoothAPIService: Message: 2
09-12 13:57:24.593  1941  2125 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@381744d7 mBinding = false
09-12 13:57:24.593  1941  2125 D LGBluetoothAPIService: Sending unbind request.
09-12 13:57:24.596  7089  7089 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-12 13:57:24.596  7089  7089 D LGBluetoothEventManager: [BTUI] clear device connection state
09-12 13:57:24.598  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 13:57:24.605  4342  4342 D LGBluetoothAPIServer: [BTUI] onUnbind()
,09-12 13:57:24.605  4342  4342 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-12 13:57:24.606  4342  4342 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-12 13:57:24.607  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:24.610  7089  7089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 13:57:24.611  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:24.615  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:24.615  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:24.615  4342  4342 V BluetoothPbapReceiver: ***********state = 10
09-12 13:57:24.616   316  7644 D libc-netbsd: res_queryN name = www.google.com succeed
09-12 13:57:24.617  7089  7089 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:24.621   316  7647 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:24.621  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:24.621   316  7647 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-12 13:57:24.621   316  7647 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-12 13:57:24.634   316  7649 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:24.635   316  7649 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-12 13:57:24.636  7089  7089 D BluetoothPermissionRequest: onReceive
09-12 13:57:24.636  7627  7627 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:57:24.639  7089  7089 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 13:57:24.639  7089  7089 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-12 13:57:24.641  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:24.649  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:24.650  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 13:57:24.651  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:24.651  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 13:57:24.651  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:24.651  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-12 13:57:24.653  7256  7256 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-12 13:57:24.669   316  7649 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-12 13:57:24.669  1035  1541 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-12 13:57:24.798  1815  7460 I CheckinTask: Sending checkin request (7926 bytes)
,09-12 13:57:24.802  6966  7201 D UEI.SmartControl: Internal timer expired: 2
09-12 13:57:24.802  6966  7201 D UEI.SmartControl: unbind internal service
09-12 13:57:24.820  1035  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:24.820  1035  1992 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:24.821  1035  1117 D BluetoothManagerService: Message: 1
,09-12 13:57:24.821  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
09-12 13:57:24.827  4342  4435 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-12 13:57:24.827  4342  4435 D BluetoothAdapterProperties: Setting state to 11
09-12 13:57:24.827  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-12 13:57:24.828  4342  4435 D BluetoothBondStateMachine: make
09-12 13:57:24.829  6966  7195 D serial_port: close(fd = 24)
09-12 13:57:24.830  1035  1117 D BluetoothManagerService: Message: 60
09-12 13:57:24.831  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-12 13:57:24.831  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-12 13:57:24.833  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 13:57:24.833  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:24.837  6966  7195 I UEI.SmartControl: Serial port is closed.
09-12 13:57:24.837  7089  7089 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-12 13:57:24.837  4342  4435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.838  4342  4435 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-12 13:57:24.838  4342  4435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.838  4342  4435 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-12 13:57:24.838  4342  4435 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-12 13:57:24.838  4342  7653 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:57:24.846  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:24.846  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:24.846  4342  4342 V BluetoothPbapReceiver: ***********state = 11
09-12 13:57:24.847  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:24.847  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:24.850  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:24.853  4342  4342 D HeadsetService: Received start request. Starting profile...
09-12 13:57:24.854  4342  4342 D HeadsetStateMachine: make
,09-12 13:57:24.854  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:24.854  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:24.862  4342  4342 D HeadsetStateMachine: max_hf_connections = 1
09-12 13:57:24.862  4342  4342 I bluedroid-qcom: get_profile_interface handsfree
09-12 13:57:24.862  4342  4342 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-12 13:57:24.862  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:24.863  4342  7654 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-12 13:57:24.863  4342  7654 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 13:57:24.863  4342  7654 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 13:57:24.863  4342  7654 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,09-12 13:57:24.863   324  2149 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 4342
09-12 13:57:24.864  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
,09-12 13:57:24.864   324  2149 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-12 13:57:24.864   324  2149 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-12 13:57:24.864   324  2149 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-12 13:57:24.864   324  2149 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-12 13:57:24.864   324  2149 V voice   : voice_set_parameters: exit with code(0)
09-12 13:57:24.864   324  2149 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-12 13:57:24.865   324  2149 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-12 13:57:24.865   324  2149 V msm8974_platform: platform_set_parameters: exit with code(0)
09-12 13:57:24.865   324  2149 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-12 13:57:24.865   324  2149 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-12 13:57:24.865   324  2149 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-12 13:57:24.865  4342  4342 V BluetoothOppNotification: previous thread is not finished yet
09-12 13:57:24.866  4342  4342 D HeadsetStateMachine: Proxy object connected
09-12 13:57:24.866  4342  4342 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-12 13:57:24.866  4342  4342 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-12 13:57:24.868  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 13:57:24.872  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 13:57:24.872  4342  4342 D A2dpService: Received start request. Starting profile...
09-12 13:57:24.873  4342  4342 V Avrcp   : make
09-12 13:57:24.873  4342  4342 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-12 13:57:24.873  4342  4342 I bluedroid-qcom: get_profile_interface avrcp
09-12 13:57:24.875  7089  7089 D BluetoothPermissionRequest: onReceive
09-12 13:57:24.878  4342  4342 V AudioManager: registerRemoteController: size of Media player list: 0
09-12 13:57:24.879  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:24.880  4342  4342 E AudioManager: No RCC entry present to update
09-12 13:57:24.880  4342  4342 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 13:57:24.880  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-12 13:57:24.880  4342  4342 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-12 13:57:24.884  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-12 13:57:24.884  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:24.885  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
09-12 13:57:24.956  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 13:57:24.965  4342  4435 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 13:57:24.975  4342  4435 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-12 13:57:25.033  1815  7460 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-12 13:57:25.040  1815  7460 I CheckinService: active receiver: disabled
09-12 13:57:25.043  1035  1693 V SIM_STK : Menu title from STK is T-Mobile
09-12 13:57:25.043  1035  1693 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:57:25.128  1035  1973 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 13:57:25.130  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-12 13:57:25.130  4342  4342 D A2dpStateMachine: make
09-12 13:57:25.132  4342  4342 I bluedroid-qcom: get_profile_interface a2dp
09-12 13:57:25.132  4342  7658 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 13:57:25.132  4342  4342 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-12 13:57:25.132  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.132  4342  7657 D A2dpStateMachine: Enter Disconnected: -2
09-12 13:57:25.133  4342  7654 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-12 13:57:25.133  4342  7654 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:57:25.133  4342  7654 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-12 13:57:25.133  4342  4342 D HidService: Received start request. Starting profile...
09-12 13:57:25.133  4342  4342 I bluedroid-qcom: get_profile_interface hidhost
09-12 13:57:25.133  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.135  4342  4342 D HealthService: Received start request. Starting profile...
09-12 13:57:25.136  4342  4342 I bluedroid-qcom: get_profile_interface health
09-12 13:57:25.136  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.137  4342  4342 D PanService: Received start request. Starting profile...
09-12 13:57:25.137  4342  4342 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:57:25.137  4342  4342 I bluedroid-qcom: get_profile_interface pan
09-12 13:57:25.139  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.139  4342  4342 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:57:25.140  4342  4342 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:57:25.140  4342  4342 D BtGatt.GattService: start()
09-12 13:57:25.140  4342  4342 D BtGatt.AdvertiseManager: advertise manager created
09-12 13:57:25.144  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.144  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.144  4342  4342 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-12 13:57:25.144  4342  4342 V BluetoothMapService: BluetoothMapBinder()
09-12 13:57:25.145  4342  4342 D BluetoothMapService: Received start request. Starting profile...
,09-12 13:57:25.145  4342  4342 D BluetoothMapService: start()
09-12 13:57:25.150  4342  4342 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-12 13:57:25.150  4342  4342 D BluetoothMapEmailAppObserver: createReceiver()
09-12 13:57:25.152  4342  4342 D BluetoothMapEmailAppObserver: initObservers()
09-12 13:57:25.152  4342  4342 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-12 13:57:25.153  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.158  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-12 13:57:25.161  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 13:57:25.164  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 13:57:25.166  1035  1050 I art     : Explicit concurrent mark sweep GC freed 22896(1314KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.808ms total 156.781ms
09-12 13:57:25.166  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.171  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 13:57:25.171  4342  4342 V PanService: [BTUI] SIM Extra State :ABSENT
,09-12 13:57:25.175  4342  4342 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-12 13:57:25.175  4342  4342 V BluetoothMapService: Handler(): got msg=1
09-12 13:57:25.175  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-12 13:57:25.175  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 13:57:25.175  4342  4435 I bluedroid-qcom: enable
09-12 13:57:25.175  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:25.175  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 13:57:25.176  4342  4435 I bt_hci_bdroid: init
09-12 13:57:25.176  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.176  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-12 13:57:25.176  4342  7665 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-12 13:57:25.176  4342  7665 I bt-btu  : btu_task pending for preload complete event
09-12 13:57:25.177  4342  4435 I bt_vendor: bt-vendor : init
09-12 13:57:25.177  4342  4435 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 13:57:25.177  4342  4435 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 13:57:25.177  4342  4435 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-12 13:57:25.177  4342  4435 D bt_userial_mct: userial_init
09-12 13:57:25.177  4342  4435 D bt_hci_bdroid: set_power 1
09-12 13:57:25.177  4342  4435 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 13:57:25.177  4342  4435 I bt_vendor: Starting hciattach daemon
09-12 13:57:25.177  4342  4435 I bt_vendor: try to set true
09-12 13:57:25.169  7669  7669 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:25.169  7669  7669 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:25.194  7670  7670 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-12 13:57:25.219  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 13:57:25.225  6537  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 13:57:25.229  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.234   316  7680 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:25.235   316  7680 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-12 13:57:25.235   316  7680 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-12 13:57:25.238  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 13:57:25.238  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.239  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 13:57:25.239  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 13:57:25.240  7322  7322 I AppUp4:CustModeStarterReceiver: onReceive
09-12 13:57:25.242  7322  7322 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c445186
09-12 13:57:25.242  7322  7322 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 13:57:25.242  7322  7322 D AppUp4:CustFacade: isPhone : true
09-12 13:57:25.242  7322  7322 D AppUp4:CustModeStarterReceiver: begin check event
09-12 13:57:25.243  7322  7322 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 13:57:25.248  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.248  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:25.249  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 13:57:25.250  7681  7681 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
09-12 13:57:25.251  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:25.254  3388  3388 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.255  4834  7685 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:25.256  3388  3388 V DownloadManager: DownloadService onCreate
09-12 13:57:25.257  3388  7687 I DownloadManager: in removeSpuriousFiles
09-12 13:57:25.257  4834  7685 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-12 13:57:25.257  3388  7687 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-12 13:57:25.258  4834  7686 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.258  4834  7686 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:25.259  3388  7687 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3111c6ed on behalf of 3388
09-12 13:57:25.260  7684  7684 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-12 13:57:25.260  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-12 13:57:25.261  3388  7687 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-12 13:57:25.262  3388  7687 I DownloadManager: in trimDatabase
,09-12 13:57:25.263  3388  7687 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-12 13:57:25.263  3388  7687 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@177c1922 on behalf of 3388
09-12 13:57:25.263  4834  7685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-12 13:57:25.265  4834  4834 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-12 13:57:25.265  4834  4834 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-12 13:57:25.265  4834  4834 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-12 13:57:25.266  4834  4834 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-12 13:57:25.270  4834  4834 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-12 13:57:25.275  7690  7690 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-12 13:57:25.275  3388  3388 V DownloadManager: DownloadService onStartCommand
09-12 13:57:25.275  3388  7688 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-12 13:57:25.279  3388  7688 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29d0e4e9 on behalf of 3388
09-12 13:57:25.281  3388  7688 V DownloadManager: processing inserted download 1
09-12 13:57:25.282  3388  7688 V DownloadManager: processing inserted download 4
09-12 13:57:25.283  7694  7694 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-12 13:57:25.283  3388  7688 V DownloadManager: processing inserted download 7
09-12 13:57:25.284  3388  7688 V DownloadManager: processing inserted download 8
09-12 13:57:25.287  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 13:57:25.287  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.287  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-12 13:57:25.287  3388  7688 V DownloadManager: processing inserted download 9
09-12 13:57:25.288  3388  7688 V DownloadManager: processing inserted download 10
09-12 13:57:25.289  3388  7688 V DownloadManager: processing inserted download 11
09-12 13:57:25.289  3388  7688 V DownloadManager: processing inserted download 12
09-12 13:57:25.290  7352  7692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.290  3388  7688 V DownloadManager: processing inserted download 13
09-12 13:57:25.291  3388  7688 V DownloadManager: processing inserted download 14
09-12 13:57:25.291  3388  7688 V DownloadManager: processing inserted download 16
09-12 13:57:25.292  7412  7412 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 13:57:25.292  7412  7412 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 13:57:25.292  7698  7698 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-12 13:57:25.298  7701  7701 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-12 13:57:25.302  7535  7535 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:25
09-12 13:57:25.303  3388  3388 V DownloadManager: DownloadService onDestroy
09-12 13:57:25.306  7535  7535 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 13:57:25.306  7535  7535 D Weather.Utils: 2 : All the weather widget is gone.
09-12 13:57:25.306  7535  7535 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 13:57:25.306  7535  7535 D WeatherAncestor: connectivity changed - connection : true
09-12 13:57:25.307  7535  7535 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27b82274
09-12 13:57:25.307  7535  7535 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 13:57:25.307  7535  7535 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 13:57:25.307  7535  7535 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 13:57:25.307  7535  7535 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 13:57:25.307  7535  7535 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:25
09-12 13:57:25.312  7704  7704 I libmdmdetect: ESOC framework not supported
09-12 13:57:25.312  7704  7704 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-12 13:57:25.316  7704  7704 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-12 13:57:25.316  7704  7704 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-12 13:57:25.316  7704  7704 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-12 13:57:25.316  7704  7704 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-12 13:57:25.316  7704  7704 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-12 13:57:25.316  7704  7704 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-12 13:57:25.316  7704  7704 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-12 13:57:25.322  1035  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 13:57:25.322  1035  2006 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e mBinding = false
09-12 13:57:25.322  1035  1117 D BluetoothManagerService: Message: 1
09-12 13:57:25.322  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33d82e5e
09-12 13:57:25.323  4342  4359 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-12 13:57:25.323  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-12 13:57:25.330  2206  2206 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-12 13:57:25.335  2206  2206 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-12 13:57:25.335  2206  2206 D c       : Getting all permits...
09-12 13:57:25.335  2206  2206 D a       : Opening database...
09-12 13:57:25.338  2206  2206 D a       : Opening database auth.proximity.permit_store...
09-12 13:57:25.338  2206  2206 D a       : Closing database...
09-12 13:57:25.346  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 13:57:25.347  6537  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 13:57:25.347  7704  7705 E QC-QMI  : qmi_client [7704] 15: failed to locate client data
09-12 13:57:25.347   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-12 13:57:25.347   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-12 13:57:25.364  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:25.365  1815  7710 I CheckinService: active receiver: disabled
09-12 13:57:25.370  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 13:57:25.370  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.370  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 13:57:25.370  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 13:57:25.371  7322  7322 I AppUp4:CustModeStarterReceiver: onReceive
09-12 13:57:25.377  7322  7322 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c445186
09-12 13:57:25.377  7322  7322 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 13:57:25.377  7322  7322 D AppUp4:CustFacade: isPhone : true
09-12 13:57:25.378  7322  7322 D AppUp4:CustModeStarterReceiver: begin check event
09-12 13:57:25.378  7322  7322 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-12 13:57:25.379  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.379  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:25.380  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:25.382  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 13:57:25.384  3388  3388 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.385  4834  7711 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:25.386  4834  7711 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-12 13:57:25.387  3388  3388 V DownloadManager: DownloadService onCreate
09-12 13:57:25.387  4834  7712 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.387  4834  7712 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:25.390  3388  7713 I DownloadManager: in removeSpuriousFiles
09-12 13:57:25.391  3388  7713 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-12 13:57:25.392  3388  7713 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@11b0240f on behalf of 3388
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-12 13:57:25.392  3388  7713 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-12 13:57:25.396  4834  7711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-12 13:57:25.398  7715  7715 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
09-12 13:57:25.396  3388  7713 I DownloadManager: in trimDatabase
09-12 13:57:25.399  3388  3388 V DownloadManager: DownloadService onStartCommand
09-12 13:57:25.399  4834  4834 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-12 13:57:25.399  4834  4834 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-12 13:57:25.399  3388  7713 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-12 13:57:25.399  4834  4834 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-12 13:57:25.400  3388  7713 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1e5baa7a on behalf of 3388
09-12 13:57:25.401  3388  7714 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-12 13:57:25.402  4834  4834 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-12 13:57:25.404  4834  4834 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-12 13:57:25.405  7718  7718 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-12 13:57:25.407  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 13:57:25.407  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.407  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = true
09-12 13:57:25.407  3219  3219 D PhoneState: setPdpRejectCasuse : false
09-12 13:57:25.410  7412  7412 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 13:57:25.410  7412  7412 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 13:57:25.410  3388  7714 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f54f22b on behalf of 3388
09-12 13:57:25.413  3388  7714 V DownloadManager: processing inserted download 1
09-12 13:57:25.414  7352  7717 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.414  3388  7714 V DownloadManager: processing inserted download 4
09-12 13:57:25.415  3388  7714 V DownloadManager: processing inserted download 7
,09-12 13:57:25.416  3388  7714 V DownloadManager: processing inserted download 8
09-12 13:57:25.416  3388  7714 V DownloadManager: processing inserted download 9
09-12 13:57:25.417  3388  7714 V DownloadManager: processing inserted download 10
09-12 13:57:25.418  3388  7714 V DownloadManager: processing inserted download 11
09-12 13:57:25.419  7535  7535 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:25
09-12 13:57:25.419  7535  7535 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 13:57:25.419  7535  7535 D Weather.Utils: 2 : All the weather widget is gone.
09-12 13:57:25.420  7535  7535 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 13:57:25.420  7535  7535 D WeatherAncestor: connectivity changed - connection : true
09-12 13:57:25.420  7535  7535 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27b82274
09-12 13:57:25.420  7535  7535 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 13:57:25.420  7535  7535 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 13:57:25.420  7535  7535 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 13:57:25.421  7535  7535 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 13:57:25.421  7535  7535 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:25
09-12 13:57:25.421  3388  7714 V DownloadManager: processing inserted download 12
09-12 13:57:25.422  3388  7714 V DownloadManager: processing inserted download 13
09-12 13:57:25.422  3388  7714 V DownloadManager: processing inserted download 14
09-12 13:57:25.423  3388  7714 V DownloadManager: processing inserted download 16
09-12 13:57:25.429  4342  4435 I bt_vendor: bluetooth satus is on
09-12 13:57:25.429  4342  4435 D bt_hci_bdroid: preload
09-12 13:57:25.429  4342  7668 D bt_userial_mct: userial_open(port:0)
09-12 13:57:25.429  4342  7668 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 13:57:25.429  4342  7668 I bt_vendor: Done intiailizing UART
09-12 13:57:25.429  4342  7668 I bt_vendor: Done intiailizing UART
09-12 13:57:25.429  4342  7668 I bt_userial_mct: CMD=94, EVT=94, ACL_Out=96, ACL_In=96
09-12 13:57:25.430  4342  7668 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-12 13:57:25.430  4342  7721 D bt_userial_mct: Entering userial_read_thread()
09-12 13:57:25.430  4342  7665 I bt-btu  : btu_task received preload complete event
09-12 13:57:25.430  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-12 13:57:25.430  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-12 13:57:25.430  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-12 13:57:25.430  3388  3388 V DownloadManager: DownloadService onDestroy
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:57:25.431  4342  7665 I         : BTE_InitTraceLevels -- TRC_BTIF
09-12 13:57:25.440  2206  2206 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-12 13:57:25.449  2206  2206 I GCM     : GCM config loaded
,09-12 13:57:25.462  7412  7412 V SetupWizard: Connected to Gservices successfully
,09-12 13:57:25.466  4342  7665 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-12 13:57:25.466  4342  7665 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e9061 
09-12 13:57:25.466  4342  7665 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e9061 
,09-12 13:57:25.467  2206  2206 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-12 13:57:25.472  4342  4439 E bt-btif : Calling BTA_HhEnable
09-12 13:57:25.472  4342  4439 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-12 13:57:25.472  4342  4439 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-12 13:57:25.472  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-12 13:57:25.472  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-12 13:57:25.472  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-12 13:57:25.472  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-12 13:57:25.472  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-12 13:57:25.473  4342  4439 D BluetoothAdapterProperties: Name is: G3
09-12 13:57:25.473  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 13:57:25.473  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-12 13:57:25.477  4342  4439 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:57:25.477  4342  4439 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:57:25.477  4342  4439 D bt_hci_bdroid: postload
09-12 13:57:25.477  4342  4439 D bte_conf: Device ID record 1 : primary
09-12 13:57:25.477  4342  4439 D bte_conf:   vendorId            = 00c4
09-12 13:57:25.478  4342  4439 D bte_conf:   vendorIdSource      = 0001
09-12 13:57:25.478  4342  4439 D bte_conf:   product             = 13a1
09-12 13:57:25.478  4342  4439 D bte_conf:   version             = 1000
09-12 13:57:25.478  4342  4439 D bte_conf:   clientExecutableURL = 
09-12 13:57:25.478  4342  4439 D bte_conf:   serviceDescription  = 
09-12 13:57:25.478  4342  4439 D bte_conf:   documentationURL    = 
09-12 13:57:25.478  4342  4439 D bte_conf: bte_load_did_conf no section named DID2.
09-12 13:57:25.478  4342  7668 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 13:57:25.478  4342  7665 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-12 13:57:25.479  4342  4439 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 13:57:25.479  4342  4435 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 13:57:25.479  4342  4435 D BluetoothAdapterProperties: ScanMode =  20
09-12 13:57:25.479  4342  4435 D BluetoothAdapterProperties: State =  11
09-12 13:57:25.479  4342  4435 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-12 13:57:25.479  4342  4435 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-12 13:57:25.479  4342  4435 D BluetoothAdapterProperties: Setting state to 12
09-12 13:57:25.479  4342  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:57:25.479  4342  4439 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 13:57:25.480  4342  7665 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 13:57:25.480  4342  7665 W bt-smp  : Plain text(LSB ~ MSB) = e7 00 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 13:57:25.480  4342  7665 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 48 5b fc 9d 4e 3c fb d0 3d cf b9 d4 2d 1f e7 
09-12 13:57:25.480  4342  7665 W bt-btm  : Stopping oneshot timer
09-12 13:57:25.480  4342  7668 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 13:57:25.469  7725  7725 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:25.469  7725  7725 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:25.481  1035  1117 D BluetoothManagerService: Message: 60
09-12 13:57:25.481  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-12 13:57:25.481  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-12 13:57:25.481  4342  4435 I BluetoothAdapterState: Entering On State
09-12 13:57:25.481  4342  7721 E bt_mct  : hci lib postload completed
09-12 13:57:25.481  7089  7104 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:57:25.482  4342  4435 D LGBluetoothServiceAdapter: [BTUI] OnState
09-12 13:57:25.482  4342  4435 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-12 13:57:25.482  4342  4435 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-12 13:57:25.483  4342  4435 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-12 13:57:25.488  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:57:25.491  4342  7665 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 13:57:25.491  4342  7665 W bt-smp  : Plain text(LSB ~ MSB) = 5d 2a 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 13:57:25.491  4342  7665 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 40 db 26 12 ff 08 b4 92 d8 f7 15 71 8e 6e 14 
,09-12 13:57:25.491  4342  7665 W bt-btm  : Stopping oneshot timer
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:25.492  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:25.494  7089  7089 D BluetoothMap: Proxy object connected
09-12 13:57:25.494  7089  7089 D MapProfile: Bluetooth service connected
09-12 13:57:25.494  7089  7089 D BluetoothMap: getConnectedDevices()
09-12 13:57:25.495  2206  7709 D GCM     : Connected
09-12 13:57:25.495  4342  4364 V BluetoothMapService: getConnectedDevices()
09-12 13:57:25.496  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:25.497  7089  7104 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:57:25.497  1035  1035 D BluetoothHeadset: Proxy object connected
09-12 13:57:25.499  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:25.503  4342  7665 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 13:57:25.503  4342  7665 W bt-smp  : Plain text(LSB ~ MSB) = 41 23 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 13:57:25.503  4342  7665 W bt-smp  : Encrypted text(LSB ~ MSB) = f5 6e e6 14 6a c2 9e a1 41 11 c8 85 a6 c8 1b 20 
09-12 13:57:25.503  4342  7665 W bt-btm  : Stopping oneshot timer
09-12 13:57:25.503  1850  1850 D BluetoothHeadset: Proxy object connected
,09-12 13:57:25.507  7089  7462 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:57:25.507  7089  7089 D BluetoothA2dp: Proxy object connected
09-12 13:57:25.507  7089  7089 D A2dpProfile: Bluetooth service connected
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:25.508  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:25.509  7089  7104 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:57:25.509  7089  7104 D BluetoothPan: onBluetoothStateChange call bindService
09-12 13:57:25.509  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:25.511  4342  7665 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 13:57:25.511  4342  7665 W bt-smp  : Plain text(LSB ~ MSB) = 2d 95 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 13:57:25.511  4342  7665 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 d9 2b 56 54 9c 16 9d 52 fe b4 2e 4d a8 d9 f2 
09-12 13:57:25.511  4342  7665 W bt-btm  : Stopping oneshot timer
09-12 13:57:25.511  1850  2451 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:25.513  1850  1850 D BluetoothHeadset: Proxy object connected
09-12 13:57:25.513  7089  7105 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:25.515  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:57:25.515  7089  7462 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:57:25.515  1035  1035 D BluetoothA2dp: Proxy object connected
,09-12 13:57:25.518  7089  7089 D BluetoothInputDevice: Proxy object connected
09-12 13:57:25.518  7089  7089 D HidProfile: Bluetooth service connected
09-12 13:57:25.518  1850  4449 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:57:25.520  1850  1850 D BluetoothHeadset: Proxy object connected
09-12 13:57:25.520  4342  7665 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 13:57:25.520  4342  7665 W bt-smp  : Plain text(LSB ~ MSB) = 0c 91 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 13:57:25.520  4342  7665 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 4f c9 52 e3 ae b8 33 77 46 f4 5c b1 7a aa e6 
09-12 13:57:25.520  4342  7665 W bt-btm  : Stopping oneshot timer
09-12 13:57:25.520  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-12 13:57:25.520  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-12 13:57:25.520  7089  7089 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:57:25.520  7089  7089 D PanProfile: Bluetooth service connected
09-12 13:57:25.522  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.522  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 13:57:25.522  1941  2125 D LGBluetoothAPIService: Message: 1
09-12 13:57:25.522  1941  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-12 13:57:25.527  7089  7089 D BluetoothHeadset: Proxy object connected
09-12 13:57:25.527  7089  7089 D HeadsetProfile: Bluetooth service connected
,09-12 13:57:25.530  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:25.532  4342  4435 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-12 13:57:25.532  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:25.533  1941  2125 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-12 13:57:25.534  4342  4342 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.534  4342  4342 D BluetoothMapService: STATE_ON
09-12 13:57:25.534  4342  4342 D LGBluetoothAPIServer: [BTUI] onCreate()
09-12 13:57:25.534  4342  4342 D LGBluetoothAPIServer: [BTUI] onBind()
,09-12 13:57:25.535  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-12 13:57:25.535  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.535  4342  4342 V BluetoothPbapService: Pbap Service onCreate
09-12 13:57:25.535  4342  4342 V BluetoothPbapService: Starting PBAP service
09-12 13:57:25.535  1941  2125 D LGBluetoothAPIService: Message: 100
09-12 13:57:25.535  1941  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-12 13:57:25.535  4342  4342 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-12 13:57:25.535  4342  4342 V BluetoothMapService: Handler(): got msg=1
09-12 13:57:25.536  4342  4342 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-12 13:57:25.536  4342  4342 V BluetoothPbapService: Pbap Service onBind
09-12 13:57:25.536  4342  4342 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.536  4342  4342 V BluetoothPbapService: state: 12
09-12 13:57:25.537  4342  4342 V BluetoothPbapService: Handler(): got msg=1
09-12 13:57:25.537  4342  4342 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-12 13:57:25.538  7730  7730 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-12 13:57:25.538  4342  7731 D BluetoothMapMasInstance: MAS initSocket()
09-12 13:57:25.538  4342  7731 D BluetoothMapMasInstance:   masId = 00
09-12 13:57:25.538  4342  7731 D BluetoothMapMasInstance:   msgTypes = 0e
09-12 13:57:25.538  4342  7731 D BluetoothMapMasInstance:   masName = SMS/MMS
09-12 13:57:25.538  4342  7731 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-12 13:57:25.538  1035  2359 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:25.538  4342  7732 V BluetoothPbapService: Pbap Service initSocket
09-12 13:57:25.539  4342  7731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:25.540  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:25.541  4342  7731 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=100 mFd=96
09-12 13:57:25.542  4342  7731 V BluetoothMapMasInstance: Succeed to create listening socket 
09-12 13:57:25.542  4342  7731 D BluetoothMapMasInstance: Accepting socket connection...
09-12 13:57:25.542  4342  7732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:25.543  7089  7089 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-12 13:57:25.543  4342  7732 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=102 mFd=100
09-12 13:57:25.543  4342  7732 V BluetoothPbapService: Succeed to create listening socket 
09-12 13:57:25.543  4342  7732 V BluetoothPbapService: Accepting socket connection...
09-12 13:57:25.544  7089  7089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 13:57:25.544  2206  7709 D GCM     : Message class com.google.e.a.a.q
09-12 13:57:25.545  7089  7089 D BluetoothPbap: Proxy object connected
09-12 13:57:25.545  7089  7089 D PbapServerProfile: Bluetooth service connected
09-12 13:57:25.547  4342  4342 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 13:57:25.547  4342  4342 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.547  4342  4342 V BluetoothPbapReceiver: ***********state = 12
09-12 13:57:25.551  7089  7089 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:25.551  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:25.551  2206  2206 D c       : Getting all permits...
09-12 13:57:25.551  2206  2206 D a       : Opening database...
,09-12 13:57:25.555  2206  2206 D a       : Opening database auth.proximity.permit_store...
09-12 13:57:25.556  2206  2206 D a       : Closing database...
09-12 13:57:25.566  7089  7089 D BluetoothPermissionRequest: onReceive
,09-12 13:57:25.567  4342  4439 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:57:25.567  4342  4439 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-12 13:57:25.568  7089  7089 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 13:57:25.568  4342  4439 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:57:25.568  4342  4439 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-12 13:57:25.570  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:25.571  7089  7089 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 13:57:25.574  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:25.575  4342  4342 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-12 13:57:25.576  4342  4342 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-12 13:57:25.577  4342  4342 V BtOppService: onCreate
09-12 13:57:25.577  4342  4342 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-12 13:57:25.578  4342  4342 V BluetoothOppNotification: send message
09-12 13:57:25.580  4342  4342 V BtOppService: Starting RfcommListener
09-12 13:57:25.580  4342  4342 D BluetoothOppPreference: Dumping Names:  
09-12 13:57:25.580  4342  4342 D BluetoothOppPreference: {}
09-12 13:57:25.581  4342  4342 D BluetoothOppPreference: Dumping Channels:  
09-12 13:57:25.581  4342  4342 D BluetoothOppPreference: {}
09-12 13:57:25.581  4342  4342 V BtOppService: onStartCommand
09-12 13:57:25.581  4342  7734 V BtOppService: Deleted complete outbound shares, number =  0
09-12 13:57:25.581  4342  7735 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 13:57:25.582  4342  7735 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 13:57:25.582  4342  7734 V BtOppService: Deleted complete inbound failed shares, number = 0
09-12 13:57:25.582  4342  7734 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-12 13:57:25.583  4342  7735 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a1a1c31 on behalf of 
09-12 13:57:25.583  4342  7734 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@109b1f16 on behalf of 
09-12 13:57:25.583  4342  7735 V BluetoothOppNotification: update too frequent, put in queue
09-12 13:57:25.584  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.584  4342  4342 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 13:57:25.584  4342  7735 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 13:57:25.584  4342  7735 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 13:57:25.586  4342  4342 V BluetoothOppNotification: new notify threadi!
09-12 13:57:25.586  4342  7735 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36892097 on behalf of 
09-12 13:57:25.586  4342  4342 V BluetoothOppNotification: send delay message
09-12 13:57:25.587  4342  4342 V BtOppService: start RfcommListener
09-12 13:57:25.587  4342  7735 V BluetoothOppNotification: update too frequent, put in queue
09-12 13:57:25.588  4342  7735 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 13:57:25.588  4342  4342 V BtOppService: RfcommListener started
09-12 13:57:25.588  4342  4342 V BtOppService: ContentObserver received notification
09-12 13:57:25.588  4342  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 13:57:25.588  4342  7737 V BtOppRfcommListener: Starting RFCOMM listener....
09-12 13:57:25.589  4342  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c1b1284 on behalf of 
09-12 13:57:25.589  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 13:57:25.589  4342  7736 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 13:57:25.589  4342  4342 V BtOppService: ContentObserver received notification
09-12 13:57:25.590  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.590  4342  4342 V BluetoothFtpService: Ftp Service onCreate
09-12 13:57:25.590  4342  4342 I BluetoothFtpService: Ftp Service onCreate
09-12 13:57:25.590  4342  4342 V BluetoothFtpService: Ftp Service onStartCommand
09-12 13:57:25.590  4342  4342 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.590  4342  4342 V BluetoothFtpService: Starting Listening on sockets
09-12 13:57:25.590  4342  4342 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 13:57:25.590  4342  4342 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 13:57:25.590  4342  4342 V BluetoothSapReceiver: SapReceiver onReceive 
,09-12 13:57:25.590  4342  4342 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.591  4342  4342 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-12 13:57:25.591  4342  4342 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 13:57:25.592  4342  4342 V BluetoothFtpService: Handler(): got msg=1
09-12 13:57:25.592  4342  4342 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-12 13:57:25.592  4342  4342 V BluetoothFtpService: Ftp Service initSocket
09-12 13:57:25.592  4342  7738 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 13:57:25.593  4342  7737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:25.593  4342  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 13:57:25.593  4342  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 13:57:25.594  1035  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:25.595  4342  7737 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=104 mFd=102
09-12 13:57:25.595  4342  4342 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:25.595  4342  7737 V BtOppRfcommListener: Started RFCOMM listener....
09-12 13:57:25.595  4342  7737 I BtOppRfcommListener: Accept thread started.
09-12 13:57:25.595  4342  7737 V BtOppRfcommListener: Accepting connection...
09-12 13:57:25.595  4342  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13a216a2 on behalf of 
09-12 13:57:25.595  4342  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22352f33 on behalf of 
09-12 13:57:25.596  4342  7736 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 13:57:25.597  4342  7738 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-12 13:57:25.597  4342  7736 V BluetoothOppNotification: outbound notification was removed.
09-12 13:57:25.598  4342  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 13:57:25.599  4342  4342 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=106 mFd=104
09-12 13:57:25.599  4342  4342 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-12 13:57:25.599  4342  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d91ba47
09-12 13:57:25.599  4342  4342 V BluetoothSapService: Sap Service onCreate
09-12 13:57:25.600  4342  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3978d2f0 on behalf of 
09-12 13:57:25.599  4342  7739 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-12 13:57:25.600  4342  4342 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:25.600  4342  4342 V BluetoothSapService: state: 12
09-12 13:57:25.600  4342  4342 V BluetoothSapService: Starting SAP server process
09-12 13:57:25.601  4342  4342 V BluetoothSapService: SAP Service startRfcommListenerThread
09-12 13:57:25.602  4342  7736 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 13:57:25.589  7740  7740 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:25.602  4342  7741 V BluetoothSapService: Sap Service initRfcommSocket
,09-12 13:57:25.589  7740  7740 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:25.603  1035  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:25.589  7740  7740 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:25.603  4342  7741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:25.603  4342  7736 V BluetoothOppNotification: inbound notification was removed.
09-12 13:57:25.604  4342  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 13:57:25.605  4342  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29b02e1c on behalf of 
09-12 13:57:25.605  4342  7741 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=109 mFd=106
09-12 13:57:25.605  4342  7741 V BluetoothSapService: Succeed to create listening socket 
09-12 13:57:25.605  4342  7741 V BluetoothSapService: Accepting socket connection...
09-12 13:57:25.613  7740  7740 V BT_SAP  : Event pipe created
09-12 13:57:25.613  7740  7740 V BT_SAP  : create_server_socket qcom.sap.server
09-12 13:57:25.613  7740  7740 V BT_SAP  : created socket fd 6
,09-12 13:57:25.704  7132  7700 V FormManager: There are no updated forms. The schedule will be deleted.
,09-12 13:57:25.707  7132  7700 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-12 13:57:25.763  7132  7743 V FormManager: There are no updated forms. The schedule will be deleted.
,09-12 13:57:25.767  7132  7743 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:25.835  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:25.841  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:25.847  1035  1939 D WifiServiceImplEx: setWifiEnabled: false pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 13:57:25.847  1035  1939 D WifiService: setWifiEnabled: false pid=6796, uid=10118
09-12 13:57:25.847  1035  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:57:25.867  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 13:57:25.869  4342  4342 V BluetoothOppNotification: new notify threadi!
09-12 13:57:25.869  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 13:57:25.869  4342  4342 V BluetoothOppNotification: send delay message
09-12 13:57:25.871  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:25.872  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:25.873  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:25.873  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-12 13:57:25.875  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:25.876  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-12 13:57:25.876  1035  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 13:57:25.876  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:57:25.877  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 13:57:25.878  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 13:57:25.879  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 13:57:25.879  4342  7745 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 13:57:25.879  1035  1867 D WifiServiceImplEx: setWifiEnabled: false pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 13:57:25.880  1035  1867 D WifiService: setWifiEnabled: false pid=6796, uid=10118
09-12 13:57:25.880  1035  1867 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:25.881  4342  7745 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33b85a25 on behalf of 
09-12 13:57:25.882  4342  7745 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-12 13:57:25.884  4342  7745 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 13:57:25.886  4342  7745 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e93d7fa on behalf of 
09-12 13:57:25.887  4342  7745 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 13:57:25.888  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 13:57:25.888  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 13:57:25.888  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.888  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.889  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 13:57:25.889  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 13:57:25.889  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:25.889  4342  7745 V BluetoothOppNotification: outbound notification was removed.
09-12 13:57:25.889  4342  7745 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 13:57:25.890  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:25.890  1035  7255 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.890   316   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:57:25.900  4342  7745 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@61d51ab on behalf of 
09-12 13:57:25.902  4342  7745 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 13:57:25.903  4342  7745 V BluetoothOppNotification: inbound notification was removed.
,09-12 13:57:25.903  4342  7745 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 13:57:25.908  1035  1576 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-12 13:57:25.908  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.908  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.908  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:57:25.908  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.908  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 13:57:25.909  4342  7745 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ea01008 on behalf of 
09-12 13:57:25.911   316  7747 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-12 13:57:25.912  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-12 13:57:25.912  1035  1115 D DSQN    : Dns fail occured do internet check.
09-12 13:57:25.912  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-12 13:57:25.913  1035  1035 D DSQN    : try Internet connection check
09-12 13:57:25.918  1035  7749 D DSQN    : ThreadTCPConnectionCheck connect try to216.58.214.206
,09-12 13:57:25.919  1035  7749 D DSQN    : ThreadTCPConnectionCheck conn fail internet is not possible
09-12 13:57:25.919  1035  7748 D DSQN    : ThreadInternetCheck internet check NOK 
09-12 13:57:25.920  1035  7748 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
09-12 13:57:25.920  1035  7748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
09-12 13:57:25.921  1035  1035 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
09-12 13:57:25.924  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 13:57:25.924  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-12 13:57:25.926  1941  1956 D WifiServiceExtension: isInternetCheckAvailable return false
09-12 13:57:25.928  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-12 13:57:25.929  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:25.929  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:25.930  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-12 13:57:25.931  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:25.933  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:25.935  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.935  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 13:57:25.937  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-12 13:57:25.938  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:25.942  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.942  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.942  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 13:57:25.946  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 13:57:25.946  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-12 13:57:25.946  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.946  1035  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:25.950  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.950  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:25.950  1035  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@27ccd994
09-12 13:57:25.951  1035  1537 D LGWifiP2pService: P2pDisablingState
09-12 13:57:25.951  1035  1537 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.951  1035  1537 D LGWifiP2pService: p2p socket connection lost
09-12 13:57:25.951  1035  1537 D LGWifiP2pService: P2pDisabledState
09-12 13:57:25.953  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 13:57:25.953  1941  1941 D WfdsService: WifiP2pState is changed : false
09-12 13:57:25.954  1941  2316 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-12 13:57:25.954  1941  2316 D WfdsService: Set the WFDS Monitor: false
09-12 13:57:25.955  1941  2316 D WfdsMonitor: WFDS Monitor is stopped
,09-12 13:57:25.955  1941  2316 D WfdsService: STATE : WfdsDisabledState - enter
09-12 13:57:25.955  1941  7188 D CtrlSupplicant: Received on exit socket, terminate
09-12 13:57:25.955  1941  7188 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-12 13:57:25.955  1941  7188 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-12 13:57:25.955  1941  7188 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-12 13:57:25.956  1941  2320 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-12 13:57:25.956  1941  2316 W WfdsService: DefaultState - msg [9445378] is not handled
09-12 13:57:25.957  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:25.957  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:25.957  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:25.957  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:25.958  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:25.958  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:25.958  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 13:57:25.958  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:25.958  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:25.959  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:25.960  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:25.960  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:25.960  1035  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:57:25.961  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-12 13:57:25.961  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.961  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.961  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 13:57:25.961  7170  7170 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 13:57:25.962  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 13:57:25.962  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:25.962  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:25.963  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:25.971  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:25.978  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:25.979  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:25.980  1035  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-12 13:57:25.980   316   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:57:25.980  1035  1545 D DSQN    : disableDataServiceNotify
09-12 13:57:25.980  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 13:57:25.980  1035  1545 D DSQN    : stop dsqn bin
09-12 13:57:25.983  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:25.986  1035  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-12 13:57:25.986  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:25.986  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:25.987  1035  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:25.987  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 13:57:25.987  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:25.987  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-12 13:57:25.987  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:25.987  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.987  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:25.987  1035  7252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 13:57:25.987  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 13:57:25.988  1035  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-12 13:57:25.988  1035  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 13:57:25.988  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 13:57:25.988  1035  1538 D WifiNative-p2p0: doBoolean: TERMINATE
09-12 13:57:25.989  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.989  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 13:57:25.989  1035  1538 D WifiNative-p2p0: TERMINATE: returned true
09-12 13:57:25.989  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:25.989  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:25.989  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:25.990  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspe,cified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 13:57:25.990  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:25.990  1035  1035 D WifiHS20: hidePasspointNotification off =false
,09-12 13:57:25.991  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:25.992  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 13:57:25.993  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.993  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.993  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 13:57:25.993  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 13:57:25.993  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 13:57:25.993  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 13:57:25.993  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 13:57:25.998  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:25.998  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:25.998  1035  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:25.999  1035  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:25.999  1035  1545 D NetworkManagementService: Removing idletimer
09-12 13:57:25.999  1035  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:25.999  1035  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 13:57:26.000  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 13:57:26.000  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 13:57:26.000  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 13:57:26.000  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:26.000  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 13:57:26.000  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 13:57:26.000  1035  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:26.000  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:26.000  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 13:57:26.002  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-12 13:57:26.003  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-12 13:57:26.003  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:26.003  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:26.007  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:26.009  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:26.009  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:26.014  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:26.016  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:26.020  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:26.020  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:26.021  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 13:57:26.026  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 13:57:26.031  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 13:57:26.032  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:26.032  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:26.037  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:26.042  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:26.047  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:26.048  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:26.049  7170  7170 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 13:57:26.049  7170  7170 I wpa_supplicant: monitor socket send errors count : 1
09-12 13:57:26.049  7170  7170 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
,09-12 13:57:26.050  1035  7184 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-12 13:57:26.050  1035  7184 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 13:57:26.050  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 13:57:26.053  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 13:57:26.054  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:26.054  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:26.056  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:26.058  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:26.064  7132  7755 W FormManager: Network not available. Please check & try again.
09-12 13:57:26.065  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:26.076  7132  7756 V FormManager: Network unavailable.
,09-12 13:57:26.079  7132  7756 V FormManager: Network unavailable.
09-12 13:57:26.081  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 13:57:26.082  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:26.083  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:26.083  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:26.084  7170  7170 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:57:26.085  7170  7170 W wpa_supplicant: USIM:  scard_deinit function
09-12 13:57:26.085  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-12 13:57:26.085  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:57:26.085  1035  7184 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:57:26.086  1035  7184 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-12 13:57:26.086  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:26.086  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:26.086  1035  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=136235
09-12 13:57:26.086  1035  1117 D Tethering: InitialState.processMessage what=4
09-12 13:57:26.087  1035  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=136236
09-12 13:57:26.087  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:26.087  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=136236  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 13:57:26.088  1035  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=136236  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-12 13:57:26.090  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:26.091  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:26.091  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-12 13:57:26.091  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 13:57:26.091  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 13:57:26.092  7089  7089 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 13:57:26.092  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 13:57:26.092  7089  7089 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 13:57:26.092  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 13:57:26.092  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 13:57:26.092  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 13:57:26.093  7089  7089 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 13:57:26.093  7089  7089 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 13:57:26.098  1035  7255 D DhcpStateMachine: StoppedState
09-12 13:57:26.098  1035  7255 D DhcpStateMachine: StoppedState{ when=-136ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:26.099  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-12 13:57:26.099  1035  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-12 13:57:26.119  7170  7170 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 13:57:26.119  1035  7184 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-12 13:57:26.119  1035  7184 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-12 13:57:26.120  1035  7184 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-12 13:57:26.123  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-12 13:57:26.127  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-12 13:57:26.127  1941  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-12 13:57:26.127  1941  2316 D WfdsService: Set the WFDS Monitor: false
09-12 13:57:26.127  1941  2316 D WfdsMonitor: WFDS Monitor is stopped
09-12 13:57:26.131  1035  1538 D WifiOffDelayIfNotUsed: stopMonitoring
09-12 13:57:26.131  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:26.131  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:26.131  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:26.132  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 13:57:26.133  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:26.136  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:26.136  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-12 13:57:26.137  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:26.141  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-12 13:57:26.141  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-12 13:57:26.141  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-12 13:57:26.143  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:26.143  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:26.146  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:26.151  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 13:57:26.164  7068  7068 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-12 13:57:26.164  7068  7068 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 13:57:26.164  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:26.164  4834  7757 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 13:57:26.168  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:26.170  4834  7760 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 13:57:26.170  4834  7760 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:26.171  7132  7759 W FormManager: Network not available. Please check & try again.
09-12 13:57:26.176  7132  7761 V FormManager: Network unavailable.
,09-12 13:57:26.177  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:26.183  7132  7761 V FormManager: Network unavailable.
09-12 13:57:26.341  1035  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3065] from screen [on:0 period:507663813] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-12 13:57:26.343  1035  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:507663815] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:26.391  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:26.394  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:26.397  1035  2030 D WifiServiceImplEx: setWifiEnabled: true pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-12 13:57:26.399  1035  2030 D WifiService: setWifiEnabled: true pid=6796, uid=10118
,09-12 13:57:26.399  1035  2030 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:57:26.421  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-12 13:57:26.421  1035  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-12 13:57:26.421  1035  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-12 13:57:26.421  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-12 13:57:26.421  1035  1035 D Ulp_jni : JNI:system_update. Event-4,
09-12 13:57:26.425  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-12 13:57:26.425  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 13:57:26.426  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-12 13:57:26.426  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
09-12 13:57:26.426  1035  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
,09-12 13:57:26.426  1035  1538 E WifiHW  : unknown target_country: EU , set to default,
09-12 13:57:26.426  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-12 13:57:26.426  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-12 13:57:26.427  1035  1538 I WifiUtil: gEnableBmps=1
,09-12 13:57:26.428  1035  1903 D WifiServiceImplEx: setWifiEnabled: true pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 13:57:26.430  1035  1903 D WifiService: setWifiEnabled: true pid=6796, uid=10118
09-12 13:57:26.430  1035  1903 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:26.432  1035  1544 D WifiController: Mismatch in the state 1
,09-12 13:57:26.589  4342  4342 V BluetoothOppNotification: new notify threadi!
09-12 13:57:26.590  4342  4342 V BluetoothOppNotification: send delay message
,09-12 13:57:26.613  4342  7773 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 13:57:26.616  4342  7773 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d3973a1 on behalf of 
09-12 13:57:26.617  4342  7773 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 13:57:26.618  4342  7773 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-12 13:57:26.621  4342  7773 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@223779c6 on behalf of 
09-12 13:57:26.622  4342  7773 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 13:57:26.624  4342  7773 V BluetoothOppNotification: outbound notification was removed.
09-12 13:57:26.624  4342  7773 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 13:57:26.625  4342  7773 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ddd5d87 on behalf of 
09-12 13:57:26.626  4342  7773 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 13:57:26.629  4342  7773 V BluetoothOppNotification: inbound notification was removed.
09-12 13:57:26.629  4342  7773 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 13:57:26.630  4342  7773 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@172a24b4 on behalf of 
,09-12 13:57:26.937  1035  1903 D WifiServiceImplEx: setWifiEnabled: true pid=6796, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-12 13:57:26.946  1035  1903 D WifiService: setWifiEnabled: true pid=6796, uid=10118
,09-12 13:57:26.946  1035  1903 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:57:26.950  1035  1544 D WifiController: Mismatch in the state 1
09-12 13:57:27.067   316   893 D SoftapController: Softap fwReload - Ok
,09-12 13:57:27.080  1035  1538 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (645ms)
09-12 13:57:27.088   316   893 D CommandListener: Setting iface cfg
09-12 13:57:27.089   316   893 D CommandListener: Trying to bring down wlan0
,09-12 13:57:27.092  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:27.092  1035  1117 D Tethering: InitialState.processMessage what=4
09-12 13:57:27.101   316   893 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:57:27.105  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-12 13:57:27.122  1035  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-12 13:57:27.109  7781  7781 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 13:57:27.133  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:27.133  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:27.133  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:27.119  7781  7781 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:27.140  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:27.153  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-12 13:57:27.180  1035  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-12 13:57:27.181  1035  1538 D WifiMonitor: connecting to supplicant
,09-12 13:57:27.185  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:27.185  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 13:57:27.186  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 13:57:27.186  7089  7089 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 13:57:27.188  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-12 13:57:27.194  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 13:57:27.194  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:27.195  7089  7089 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 13:57:27.195  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 13:57:27.195  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 13:57:27.195  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 13:57:27.195  7089  7089 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 13:57:27.195  7089  7089 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 13:57:27.195  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:27.197  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:27.197  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 13:57:27.198  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 13:57:27.198  7089  7089 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-12 13:57:27.199  7781  7781 I wpa_supplicant: Successfully initialized wpa_supplicant
09-12 13:57:27.201  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 13:57:27.202  7089  7089 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 13:57:27.202  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 13:57:27.202  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 13:57:27.202  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 13:57:27.202  7089  7089 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 13:57:27.203  7089  7089 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 13:57:27.212  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 13:57:27.217  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:27.222  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:27.233  7781  7781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 13:57:27.234  7781  7781 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-12 13:57:27.237  7132  7798 W FormManager: Network not available. Please check & try again.
,09-12 13:57:27.238  7132  7799 V FormManager: Network unavailable.
09-12 13:57:27.240  7132  7799 V FormManager: Network unavailable.
09-12 13:57:27.341  7781  7781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 13:57:27.361  7781  7781 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-12 13:57:27.370  7781  7781 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-12 13:57:27.371  7781  7781 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-12 13:57:27.375  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-12 13:57:27.377  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-12 13:57:27.377  1035  7803 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-12 13:57:27.377  1035  7803 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 13:57:27.377  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-12 13:57:27.377  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,09-12 13:57:27.378  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,09-12 13:57:27.378  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-12 13:57:27.379  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-12 13:57:27.380  1035  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-12 13:57:27.381  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.383  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.384  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:27.386  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:27.388  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:27.389  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:27.390  1035  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-12 13:57:27.391  1035  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-12 13:57:27.392  1035  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-12 13:57:27.392  1035  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-12 13:57:27.392  1035  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-12 13:57:27.393  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 13:57:27.393  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-12 13:57:27.393  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 13:57:27.394  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:27.394  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:27.395  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:27.395  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:27.396  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 13:57:27.396  1035  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
09-12 13:57:27.396  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:27.397  1035  1538 D WifiNative-wlan0: SET update_config 1: returned true
09-12 13:57:27.397  1035  1538 D WifiConfigStore: Loading config and enabling all networks 
09-12 13:57:27.397  1035  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-12 13:57:27.397  1941  1941 D WfdService: Waiting for WifiP2p enabling
,09-12 13:57:27.398  1035  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-12 13:57:27.406  1035  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-12 13:57:27.407  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-12 13:57:27.407  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:27.409  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:27.414  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:27.416  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:27.416  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:27.420  1035  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-12 13:57:27.420  1035  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:57:27.421  1035  1538 D WifiStateMachine: enableVerboseLogging : level 2
,09-12 13:57:27.421  1035  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-12 13:57:27.421  1035  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-12 13:57:27.421  1035  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:27.422  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:27.422  1035  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-12 13:57:27.422  1035  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-12 13:57:27.422  1035  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-12 13:57:27.422  1035  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,09-12 13:57:27.423  1035  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
,09-12 13:57:27.423  1035  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-12 13:57:27.423  1035  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-12 13:57:27.423  1035  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-12 13:57:27.423  1035  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-12 13:57:27.424  1035  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-12 13:57:27.424  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:27.424  1035  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-12 13:57:27.424  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:57:27.424  1035  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-12 13:57:27.425  1035  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-12 13:57:27.425  1035  1538 D WifiNative-HAL: Setting external_sim to 1
09-12 13:57:27.425  1035  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-12 13:57:27.425  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-12 13:57:27.425  1035  1538 D WifiNative-wlan0: SET external_sim 1: returned true
09-12 13:57:27.425  1035  1538 I WifiNative-HAL: startHal
09-12 13:57:27.425  1035  1538 D wifi    : setting scan oui 0xaf5e2160
09-12 13:57:27.425  1941  2316 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-12 13:57:27.426  1941  2316 D WfdsService: Set the WFDS Monitor: true
09-12 13:57:27.426  1941  2316 D WfdsMonitor: WfdsMonitorThread create
09-12 13:57:27.426  7132  7805 W FormManager: Network not available. Please check & try again.
09-12 13:57:27.426  1941  2316 D WfdsMonitor: WFDS Monitor is created and started
09-12 13:57:27.426  1941  2316 D WfdsService: WiFi: Supplicant connection re-established
09-12 13:57:27.426  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:57:27.426  1035  1538 I WifiNative-HAL: startHal
09-12 13:57:27.426  1035  1538 D wifi    : setting scan oui 0xaf5e2160
09-12 13:57:27.427  1941  7807 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-12 13:57:27.427  1035  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-12 13:57:27.427  1035  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-12 13:57:27.427  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-12 13:57:27.428  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-12 13:57:27.428  7132  7806 V FormManager: Network unavailable.
09-12 13:57:27.428  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-12 13:57:27.428  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 13:57:27.428  1941  7807 E CtrlSupplicant: Succeed to open control connection
09-12 13:57:27.428  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 13:57:27.429  1941  7807 E CtrlSupplicant: Succeed to open monitor connection
09-12 13:57:27.429  1941  7807 D WfdsMonitor: Supplicant connection established
09-12 13:57:27.429  1941  2316 D WfdsService: Connected to the supplicant for wfds
09-12 13:57:27.429  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 13:57:27.429  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-12 13:57:27.429  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-12 13:57:27.429  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-12 13:57:27.430  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 13:57:27.430  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 13:57:27.430  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 13:57:27.430  7132  7806 V FormManager: Network unavailable.
09-12 13:57:27.430  1035  1538 D WifiNative-wlan0: doBoolean,: DRIVER RXFILTER-STOP
09-12 13:57:27.430  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 13:57:27.430  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 13:57:27.430  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-12 13:57:27.431  7781  7781 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-12 13:57:27.431  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-12 13:57:27.431  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 13:57:27.431  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 13:57:27.432  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 13:57:27.432  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:27.433  1035  1538 E WifiNative: : [137,581,290 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-12 13:57:27.433  1035  1538 D WifiNative-wlan0: doBoolean: RECONNECT
09-12 13:57:27.433  1035  1538 D WifiNative-wlan0: RECONNECT: returned true
09-12 13:57:27.433  1035  1538 D WifiNative-wlan0: doString: [STATUS]
09-12 13:57:27.434  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 13:57:27.434  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 13:57:27.434  1035  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 13:57:27.434  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:27.435  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:27.435  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:27.437   316   893 D CommandListener: Setting iface cfg
,09-12 13:57:27.437   316   893 D CommandListener: Trying to bring up p2p0
09-12 13:57:27.437  1035  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 13:57:27.437  1035  1537 D LGWifiP2pService: P2pEnablingState
09-12 13:57:27.438  1035  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.438  1035  1537 D LGWifiP2pService: P2p socket connection successful
09-12 13:57:27.438  1035  1537 D LGWifiP2pService: P2pEnabledState
09-12 13:57:27.438  1035  1537 D LGWifiP2pService: sending p2p connection changed broadcast
09-12 13:57:27.439  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-12 13:57:27.439  1941  1941 D WfdsService: WifiP2pState is changed : true
09-12 13:57:27.440  1941  2316 D WfdsService: Receive the WFDS_ENABLE Method
09-12 13:57:27.440  1941  2316 D WfdsService: Set the WFDS Monitor: true
09-12 13:57:27.440  1941  2316 D WfdsService: Connected to the supplicant for wfds
09-12 13:57:27.440  1941  2316 D WfdsJNI : doCommand: WFDS_SET TRUE
09-12 13:57:27.440  1035  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-12 13:57:27.440  7781  7781 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-12 13:57:27.440  1941  2316 D WfdsService: selectPreferredScanChannel [36]
,09-12 13:57:27.440  1941  2316 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-12 13:57:27.440  1035  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-12 13:57:27.441  1035  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
09-12 13:57:27.441  1035  1537 D WifiNative-p2p0: SET device_name G3: returned true
09-12 13:57:27.441  1035  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-12 13:57:27.441  1035  1537 D LGWifiP2pService: before postfix = G3
09-12 13:57:27.441  1035  1537 D WifiServerServiceExt: postfix byte check : 2
09-12 13:57:27.441  1035  1537 D LGWifiP2pService: after postfix = G3
09-12 13:57:27.441  1035  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-12 13:57:27.442  1035  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-12 13:57:27.442  1035  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-12 13:57:27.442  1035  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-12 13:57:27.442  1035  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-12 13:57:27.443  1035  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-12 13:57:27.443  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-12 13:57:27.443  1035  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-12 13:57:27.443  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress
09-12 13:57:27.444  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-12 13:57:27.444  1035  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-12 13:57:27.444  1035  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-12 13:57:27.445  1035  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
09-12 13:57:27.445  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-12 13:57:27.445  1035  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-12 13:57:27.445  1035  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-12 13:57:27.446  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-12 13:57:27.446  1035  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-12 13:57:27.446  1035  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-12 13:57:27.446  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-12 13:57:27.446  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-12 13:57:27.448  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-12 13:57:27.448  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 13:57:27.448  1941  1941 D WfdsService: isConnected: false
09-12 13:57:27.448  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.448  1035  1556 I WifiNative-HAL: startHal
09-12 13:57:27.449  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-12 13:57:27.449  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-12 13:57:27.449  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-12 13:57:27.449  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.449  1941  1941 D WfdsService: Update P2p Interface State: 3
,09-12 13:57:27.453  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-12 13:57:27.453  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.454  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
,09-12 13:57:27.454  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.454  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.454  1035  1538 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.455  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.455  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.455  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.455  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.456  1035  1538 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-12 13:57:27.456  1035  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-12 13:57:27.456  1035  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-12 13:57:27.457  1035  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-12 13:57:27.457  1035  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-12 13:57:27.457  7781  7781 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-12 13:57:27.457  1035  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-12 13:57:27.457  1035  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-12 13:57:27.457  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf5e2160
09-12 13:57:27.457  1035  1556 D wifi    : failed to get capabilities : -3
09-12 13:57:27.457  1035  1556 E WifiScanningService: could not get scan capabilities
09-12 13:57:27.457  1035  1537 D LGWifiP2pService: InactiveState
09-12 13:57:27.458  1035  1537 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.458  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 13:57:27.458  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.458  1035  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-12 13:57:27.458  1035  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-12 13:57:27.458  1035  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-12 13:57:27.458  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 13:57:27.459  1035  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,09-12 13:57:27.459  1035  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:27.459  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:27.459  7781  7781 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:27.459  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:27.459  1035  7803 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 13:57:27.459  7781  7781 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 13:57:27.459  1035  7803 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:27.459  7781  7781 E wpa_supplicant: disconnect_rssi_lvl: -100
09-12 13:57:27.459  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:27.460  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:27.460  7781  7781 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.460  1035  7803 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.460  1035  7803 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.460  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.460  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.460  7781  7781 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.460  1035  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-12 13:57:27.460  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.460  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1941  7807 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 13:57:27.461  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57,:27.461  1941  7807 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.461  1941  7807 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.461  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 13:57:27.461  1035  1035 E WifiServerServiceExt: No p2p device connected
09-12 13:57:27.462  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 13:57:27.462  1941  2316 W WfdsService: DefaultState - msg [9441285] is not handled
09-12 13:57:27.462  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 13:57:27.462  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-12 13:57:27.462  1035  7803 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.462  1035  7803 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.462  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.462  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.462  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:27.463  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 13:57:27.463  7781  7781 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:27.464  7781  7781 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 13:57:27.464  7781  7781 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.464  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 13:57:27.464  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:27.464  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-12 13:57:27.464  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 13:57:27.464  1035  7803 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.464  1035  7803 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-12 13:57:27.464  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.464  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.464  7781  7781 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.465  1941  7807 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.465  1941  7807 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.465  1035  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-12 13:57:27.465  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:27.466  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:27.466  1035  7803 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 13:57:27.466  1035  7803 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.466  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.466  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 13:57:27.466  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-12 13:57:27.466  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-12 13:57:27.467  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-12 13:57:27.467  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-12 13:57:27.467  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-12 13:57:27.467  7781  7781 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:27.467  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-12 13:57:27.468  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:27.468  1035  7803 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:27.468  1035  7803 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 13:57:27.468  1035  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-12 13:57:27.468  1035  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-12 13:57:27.468  6796  7808 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-12 13:57:27.468  6796  7808 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-12 13:57:27.468  1035  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-12 13:57:27.468  1035  1538 D WifiNative-wlan0: doBoolean: SCAN
09-12 13:57:27.469  1035  1538 D WifiNative-wlan0: SCAN: returned false
09-12 13:57:27.469  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:27.469  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=137618  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 13:57:27.470  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=137619  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 13:57:27.470  1035  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:27.471  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:27.471  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:27.471  1035  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:27.471  1035  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:27.471  1035  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:27.472  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:27.472  1035  1538 E WifiStateMachine:  DefaultState P2P_CONNECTIO,N_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 13:57:27.472  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:27.472  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:27.473  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 13:57:27.475  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:27.475  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 13:57:27.477  5613  5613 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:57:27.477  5613  5613 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-12 13:57:27.478  5613  5613 V [BNRBootReceiver]: Boot Receiver Return
09-12 13:57:27.478  6796  7808 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-12 13:57:27.478  6796  7808 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:57:27.478  6796  7808 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:27.479  6796  7808 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:27.479  4834  7813 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 13:57:27.481  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:27.481  6796  7808 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 13:57:27.482  6796  7810 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-12 13:57:27.482  6796  7810 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:57:27.482  6796  7810 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:27.483  6796  7810 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:27.483  6796  7810 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-12 13:57:27.486  4834  7818 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 13:57:27.486  4834  7818 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:27.486  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:27.488  6796  7817 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 956, name: IncomingSocketThread/Receiver)
09-12 13:57:27.489  6796  7814 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 953, name: OutgoingSocketThread/Sender)
09-12 13:57:27.491  6796  7815 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 954, name: OutgoingSocketThread/Receiver)
09-12 13:57:27.491  6796  7815 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 954, thread name: OutgoingSocketThread/Receiver)
09-12 13:57:27.491  6796  7815 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 13:57:27.491  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:27.491  6796  7815 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 954, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 13:57:27.492  6796  7817 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 956, thread name: IncomingSocketThread/Receiver)
,09-12 13:57:27.492  6796  7817 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 13:57:27.492  6796  7817 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 956, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-12 13:57:27.493  6796  7816 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 955, name: IncomingSocketThread/Sender)
09-12 13:57:27.496  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:27.496  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:27.497  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 13:57:27.994  6796  6863 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-12 13:57:27.996  6796  6863 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:57:28.007  6796  6863 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@77d1cf8 Bundle[{}]
09-12 13:57:28.008  6796  6863 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 13:57:28.009  6796  6863 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 13:57:28.009  6796  6863 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 13:57:28.010  6796  6863 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 13:57:28.011  6796  6863 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 13:57:28.011  6796  6863 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-12 13:57:28.025  6796  7828 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-12 13:57:28.025  6796  7828 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:57:28.032  7781  7781 E wpa_supplicant: USIM:  scard_init function
,09-12 13:57:28.033  7781  7781 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-12 13:57:28.036  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-12 13:57:28.036  1035  7803 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-12 13:57:28.036  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-12 13:57:28.036  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-12 13:57:28.036  1035  7803 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-12 13:57:28.036  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-12 13:57:28.036  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-12 13:57:28.038  1035  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 13:57:28.038  1035  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 13:57:28.039  1035  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,09-12 13:57:28.045  1035  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 13:57:28.045  1035  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-12 13:57:28.058  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138206  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-12 13:57:28.064  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.064  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:28.067  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.069  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.069  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.070  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-12 13:57:28.080  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.080  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.080  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 13:57:28.081  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138230  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 13:57:28.082  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:28.082  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-12 13:57:28.083  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-12 13:57:28.087  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.087  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-12 13:57:28.092  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.101  7089  7089 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-12 13:57:28.106  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.121  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:28.133  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.145  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.145  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 13:57:28.149  7112  7112 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 13:57:28.154  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.158  7781  7781 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-12 13:57:28.162  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 13:57:28.165  1035  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:28.166  1035  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:28.169  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-12 13:57:28.169  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-12 13:57:28.169  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-12 13:57:28.169  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-12 13:57:28.169  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:28.169  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:28.166  1035  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:28.172  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:28.172  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 13:57:28.173  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138322  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 13:57:28.174  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138322  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 13:57:28.174  1035  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138323
09-12 13:57:28.175  1035  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138324
09-12 13:57:28.175  1035  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138324
09-12 13:57:28.177  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138326
09-12 13:57:28.177  1035  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138326
09-12 13:57:28.178  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138326  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 13:57:28.188  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:57:28.188  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:28.192  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.195  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.195  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.195  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 13:57:28.199  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138348  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 13:57:28.203  7781  7781 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:57:28.203  7781  7781 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-12 13:57:28.205  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-12 13:57:28.205  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:28.205  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-12 13:57:28.205  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:57:28.205  1035  7803 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:57:28.205  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-12 13:57:28.205  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 13:57:28.206  1035  7803 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 13:57:28.206  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:28.207  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:28.207  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.208  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.208  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-12 13:57:28.208  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:28.208  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-12 13:57:28.208  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138357  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 13:57:28.210  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138358  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 13:57:28.210  1035  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138359
09-12 13:57:28.211  1035  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138360
09-12 13:57:28.211  1035  1538 D WifiNative-wlan0: doString: [STATUS]
09-12 13:57:28.212  1035  7803 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 13:57:28.212  1035  7803 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 13:57:28.212  1035  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 13:57:28.214  1035  1538 I WifiServiceExtension: setVHTCapabilityType  : false
09-12 13:57:28.215  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:28.216  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.216  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-12 13:57:28.217  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.223  1035  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-12 13:57:28.223  1035  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-12 13:57:28.225  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.227  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.227  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.227  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-12 13:57:28.231  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.231  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.231  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 13:57:28.235  1035  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-12 13:57:28.235  1035  1545 D ConnectivityService: Got NetworkAgent Messenger
09-12 13:57:28.235  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:57:28.235  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 13:57:28.235  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-12 13:57:28.235  1035  1545 D ConnectivityService: NetworkAgent connected
09-12 13:57:28.236  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 13:57:28.236  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 13:57:28.238  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.238  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.238  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:28.239  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 13:57:28.240  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:57:28.240  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 13:57:28.240  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 13:57:28.240  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 13:57:28.242  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:28.242  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 13:57:28.242  7089  7089 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 13:57:28.242  7089  7089 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 13:57:28.243  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-12 13:57:28.244  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.244  7089  7089 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 13:57:28.244  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:28.244  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-12 13:57:28.244  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 13:57:28.244  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 13:57:28.244  7089  7089 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 13:57:28.244  7089  7089 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-12 13:57:28.245  7089  7089 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 13:57:28.246  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.246  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 13:57:28.248   316   893 D CommandListener: Setting iface cfg
09-12 13:57:28.248  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.249  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.249  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:28.251  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.252  1035  1538 E WifiStateMachine: Start Dhcp Watchdog 3
09-12 13:57:28.252  1035  7848 D DhcpStateMachine: StoppedState
09-12 13:57:28.253  1035  7848 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.253  1035  7848 D DhcpStateMachine: WaitBeforeStartState
09-12 13:57:28.253  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138402  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:28.253  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138402  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:28.254  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138403  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-12 13:57:28.255  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:28.256  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:28.256  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-12 13:57:28.256  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:28.257  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138406  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:28.257  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138406  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 13:57:28.259  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1916] from screen [on:0 period:507665731] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:28.260  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:507665732] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:28.260  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-12 13:57:28.263  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.266  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:28.267  1035  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-12 13:57:28.267  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:28.267  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:28.268  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:28.268  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:28.268  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:28.269  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 13:57:28.269  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 13:57:28.269  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=187,0,0
09-12 13:57:28.270  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=187,0,0
09-12 13:57:28.270  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-12 13:57:28.270  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.270  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-12 13:57:28.270  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.271  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-12 13:57:28.271  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 0
09-12 13:57:28.271  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:28.271  1035  1538 D WifiNative-wlan0: SET ps 0: returned true
09-12 13:57:28.271  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-12 13:57:28.271  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-12 13:57:28.272  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-12 13:57:28.272  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1451dbda target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.272  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1451dbda target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.272  1035  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-12 13:57:28.272  1035  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 13:57:28.272  1035  7848 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.272  1035  7848 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-12 13:57:28.272  1035  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 13:57:28.274  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.274   316   893 D CommandListener: Setting iface cfg
09-12 13:57:28.274   316   893 D CommandListener: Trying to bring up wlan0
09-12 13:57:28.274  1035  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-12 13:57:28.278  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:28.278  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-12 13:57:28.282  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:28.283  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-12 13:57:28.283  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-12 13:57:28.283  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 13:57:28.283  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.283  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 13:57:28.283  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 13:57:28.284  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 13:57:28.284  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.284  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 13:57:28.284  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-12 13:57:28.284  7781  7781 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-12 13:57:28.285  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-12 13:57:28.285  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 13:57:28.287  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.294  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.294  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.294  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 13:57:28.298  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.300  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-12 13:57:28.301  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 13:57:28.302  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:28.302  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:28.302  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:28.303  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:28.303  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:28.303  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:28.304  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 13:57:28.305  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 13:57:28.305  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 13:57:28.305  1035  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 13:57:28.305  1035  1545 D ConnectivityService: ignoring duplicate network state non-change
09-12 13:57:28.306  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:28.310  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.310  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:28.311  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.313  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.314  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.314  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 13:57:28.315  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 13:57:28.316  1035  1545 D ConnectivityService: Adding iface wlan0 to network 102
09-12 13:57:28.316  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 13:57:28.321  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.322  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.322  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 13:57:28.324  1035  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 13:57:28.325  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 13:57:28.326  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.327  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.327  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 13:57:28.327  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 13:57:28.328  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-12 13:57:28.335  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.335  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 13:57:28.336  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.336  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:28.336  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 13:57:28.336  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:28.340  1035  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 13:57:28.340  1035  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-12 13:57:28.342  1035  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-12 13:57:28.342  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:28.342  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 13:57:28.343  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.343   316   893 E Netd    : netlink response contains error (File exists)
09-12 13:57:28.343  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.343  1035  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-12 13:57:28.343  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.344  1035  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-12 13:57:28.344  1035  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-12 13:57:28.344  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:28.344  1035  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-12 13:57:28.346  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:57:28.346  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.346  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 13:57:28.347  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.347  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 13:57:28.347  1035  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:28.347  1035  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:28.347  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.347  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-12 13:57:28.347  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:28.347  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 13:57:28.347  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 13:57:28.348  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:28.348  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:28.349  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:28.349  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.349  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-12 13:57:28.349  1035  1545 D ConnectivityService: currentScore = 0, newScore = 20
09-12 13:57:28.349  1035  1545 D ConnectivityService:    accepting network in place of null
09-12 13:57:28.351  1035  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.352  1035  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.352  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:28.352  1035  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 13:57:28.352  1035  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 13:57:28.353  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 13:57:28.354   316  7852 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-12 13:57:28.355  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.356  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 13:57:28.360  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:28.360  1035  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-12 13:57:28.360  1035  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-12 13:57:28.361  1035  1545 D ConnectivityService: validation of new default Network = false
09-12 13:57:28.361  1035  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-12 13:57:28.361  1035  1545 D DSQN    : enableDataServiceNotify 
09-12 13:57:28.362  1035  1545 D DSQN    : start dsqn bin
09-12 13:57:28.363  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-12 13:57:28.363  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 13:57:28.363  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 13:57:28.363  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-12 13:57:28.368  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:28.368  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.368  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:28.369  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:28.366  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:28.369  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:57:28.359  7853  7853 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:28.359  7853  7853 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:28.377  1035  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-12 13:57:28.385  7853  7853 E DSQN    : DSQN ssw
,09-12 13:57:28.385  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.392  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.393  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.394  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:28.397  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 13:57:28.404  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:28.406   316  7852 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-12 13:57:28.410  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-12 13:57:28.410  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.411  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.412  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.416  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.417  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.417  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:28.422  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 13:57:28.432  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 13:57:28.440  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.440   316  7852 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-12 13:57:28.451  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:28.451  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.453  7112  7112 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 13:57:28.461  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.466  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 13:57:28.467  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:28.468   316   892 D LGDataListener: argv[0]=dsqncommand
09-12 13:57:28.468   316   892 D LGDataListener: argv[1]=wlan0
09-12 13:57:28.468   316   892 D LGDataListener: argv[2]=1
09-12 13:57:28.468   316   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-12 13:57:28.469  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-12 13:57:28.469  1035  1115 D DSQN    : start to monitor internet connection
09-12 13:57:28.475  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:28.475  1035  7848 D DhcpStateMachine: DHCPV4 request on wlan0
09-12 13:57:28.476  1035  7848 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-12 13:57:28.476  1035  7848 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-12 13:57:28.469  7860  7860 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:28.469  7860  7860 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 13:57:28.489  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 13:57:28.494  7860  7860 I dhcpcd  : version 5.5.6 starting
,09-12 13:57:28.499  7860  7860 E dhcpcd  : get_duid: m
09-12 13:57:28.499  7860  7860 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-12 13:57:28.499  7860  7860 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-12 13:57:28.501  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:28 GMT], X-Android-Received-Millis=[1473681448501], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681448468]}
09-12 13:57:28.501  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:28.501  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 13:57:28.501  1035  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-12 13:57:28.502  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 13:57:28.502  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:28.502  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:28.502  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:28.502  1035  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-12 13:57:28.502  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:28.502  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.502  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:28.503  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:28.503  1035  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.503  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:57:28.504  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 13:57:28.504  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.504  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 13:57:28.505  1035  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:28.505  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:28.511  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 13:57:28.512  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.513  7112  7112 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 13:57:28.514  7112  7112 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 13:57:28.515  7112  7112 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-12 13:57:28.524  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 13:57:28.533  7068  7068 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 13:57:28.535  7068  7068 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-12 13:57:28.541  7089  7089 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 13:57:28.541  6796  7828 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-12 13:57:28.541  6796  7828 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:57:28.542  6796  7828 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:28.542  6796  7828 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:28.542  6796  7863 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-12 13:57:28.542  6796  7863 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:57:28.542  6796  7863 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:28.542  6796  7828 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 13:57:28.543  6796  7863 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:28.545  6796  7870 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 969, name: IncomingSocketThread/Sender)
09-12 13:57:28.546  6796  7869 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 968, name: OutgoingSocketThread/Receiver)
09-12 13:57:28.547  6796  7869 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 968, thread name: OutgoingSocketThread/Receiver)
09-12 13:57:28.547  6796  7869 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 13:57:28.547  6796  7869 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 968, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-12 13:57:28.548  6796  7863 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 13:57:28.551  6796  7867 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 967, name: OutgoingSocketThread/Sender)
,09-12 13:57:28.553  6796  7871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 970, name: IncomingSocketThread/Receiver)
09-12 13:57:28.554  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 13:57:28.554  6796  7871 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 970, thread name: IncomingSocketThread/Receiver)
09-12 13:57:28.554  6796  7871 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 13:57:28.554  6796  7871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 970, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 13:57:28.555  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.556  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 13:57:28.560  7089  7089 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 13:57:28.568  7112  7112 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 13:57:28.568  7112  7112 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 13:57:28.569  7112  7112 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 13:57:28.570  7112  7112 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 13:57:28.570  7112  7112 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 13:57:28.575  7860  7860 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 13:57:28.576  7860  7860 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 13:57:28.576  7860  7860 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 13:57:28.576  7860  7860 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-12 13:57:28.576  7860  7860 D dhcpcd  : wlan0: sending REQUEST (xid 0x675fc903), next in 3.93 seconds
,09-12 13:57:28.592  7860  7860 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-12 13:57:28.598  7860  7860 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-12 13:57:28.598  7860  7860 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-12 13:57:28.598  7860  7860 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-12 13:57:28.598  7860  7860 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-12 13:57:28.598  7860  7860 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 13:57:28.599  7860  7860 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 13:57:28.599  7860  7860 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 13:57:28.599  7860  7860 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-12 13:57:28.981  7553  7584 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-12 13:57:28.990  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:28.992  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-12 13:57:28.998  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:29.003  5865  5865 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-12 13:57:29.009  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.010  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 13:57:29.010  1035  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:29.011  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.012  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:57:29.019  1035  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:29.019  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:29.024  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:29.026  6537  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-12 13:57:29.027  5865  5865 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:29.030  6796  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:29.035  6796  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:29.037  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:29.042  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:29.046  6796  6863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 979)
09-12 13:57:29.047  6796  6863 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 13:57:29.047  6796  6863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 980)
09-12 13:57:29.050  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:57:29.050  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e30c27 added. We now have 4 listener(s)
,09-12 13:57:29.053  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:29.055  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 13:57:29.055  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:57:29.055  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:57:29.056  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:57:29.056  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8a3ed4 added. We now have 4 listener(s)
09-12 13:57:29.056  6796  6863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:57:29.056  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:57:29.058  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.059  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:29.065   316  7901 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:29.065   316  7901 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,09-12 13:57:29.068  1035  1050 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-12 13:57:29.068  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:29.069  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:29.069  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:57:29.069  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:29.069  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 13:57:29.071  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 13:57:29.072  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.072  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 13:57:29.072  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:29.072  6796  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:29.074  7322  7322 I AppUp4:CustModeStarterReceiver: onReceive
09-12 13:57:29.075  6796  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:29.075  6796  6863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:57:29.078  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:29.081  1035  7848 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-12 13:57:29.082  1035  7848 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-12 13:57:29.082  1035  7848 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 13:57:29.083  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:29.083  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:29.083  1035  7848 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-12 13:57:29.083  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:29.083  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:57:29.083  1035  7848 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-12 13:57:29.083  1035  7848 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 13:57:29.083  1035  7848 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-12 13:57:29.083  6796  6863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e30c27 removed from the list
09-12 13:57:29.083  1035  7848 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-12 13:57:29.083  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:29.083  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8a3ed4 removed from the list
09-12 13:57:29.083  1035  7848 D DhcpStateMachine: RunningState
09-12 13:57:29.084  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:29.084  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:29.084  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:29.086  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:29.086  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:57:29.086  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:57:29.086  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:29.086  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:29.088  7322  7322 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c445186
09-12 13:57:29.088  7322  7322 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 13:57:29.088  7322  7322 D AppUp4:CustFacade: isPhone : true
09-12 13:57:29.088  6796  6863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:57:29.089  1035  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 13:57:29.089  7322  7322 D AppUp4:CustModeStarterReceiver: begin check event
09-12 13:57:29.089  7322  7322 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 13:57:29.092  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.093  4834  4834 D LGDMClient: [DmDeviceActionReceiver.ja,va] [doAction()] : [60] : Device Action doAction
,09-12 13:57:29.094  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:57:29.094  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:29 GMT], X-Android-Received-Millis=[1473681449094], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681449070]}
09-12 13:57:29.095  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:29.095  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 13:57:29.095  1035  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-12 13:57:29.095  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 13:57:29.095  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:29.095  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:29.095  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:29.095  1035  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-12 13:57:29.095  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:29.095  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:29.096  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:29.096  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:29.096  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:57:29.097  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:57:29.098  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:29.100  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:29.100  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:29.100  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:29.100   316  7901 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-12 13:57:29.103  6796  6863 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 13:57:29.105  3388  3388 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.105  4834  7902 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:29.107  4834  7902 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full ,Mode]--> NetworkType : WIFI is connected.
09-12 13:57:29.108  3388  3388 V DownloadManager: DownloadService onCreate
,09-12 13:57:29.115  3388  7904 I DownloadManager: in removeSpuriousFiles
,09-12 13:57:29.116  3388  7904 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-12 13:57:29.117  3388  7904 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c974821 on behalf of 3388
09-12 13:57:29.119  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-12 13:57:29.119  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-12 13:57:29.120  3388  7904 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-12 13:57:29.124  4834  7902 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-12 13:57:29.125  4834  7903 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.125  4834  7903 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-12 13:57:29.130  3388  7904 I DownloadManager: in trimDatabase
09-12 13:57:29.130  3388  7904 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-12 13:57:29.131  3388  7904 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@62e8607 on behalf of 3388
09-12 13:57:29.131  4834  4834 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-12 13:57:29.132  4834  4834 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-12 13:57:29.132  4834  4834 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-12 13:57:29.133  4834  4834 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-12 13:57:29.135  3388  3388 V DownloadManager: DownloadService onStartCommand
09-12 13:57:29.135  3388  7905 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-12 13:57:29.138  4834  4834 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-12 13:57:29.138  3388  7905 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@37ff455d on behalf of 3388
,09-12 13:57:29.141  3388  7905 V DownloadManager: processing inserted download 1
09-12 13:57:29.142  3388  7905 V DownloadManager: processing inserted download 4
09-12 13:57:29.143  3388  7905 V DownloadManager: processing inserted download 7
09-12 13:57:29.145  3388  7905 V DownloadManager: processing inserted download 8
09-12 13:57:29.146  3388  7905 V DownloadManager: processing inserted download 9
09-12 13:57:29.147  3388  7905 V DownloadManager: processing inserted download 10
09-12 13:57:29.149  3388  7905 V DownloadManager: processing inserted download 11
09-12 13:57:29.149  7352  7911 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:29.150  3388  7905 V DownloadManager: processing inserted download 12
09-12 13:57:29.151  3388  7905 V DownloadManager: processing inserted download 13
09-12 13:57:29.152  3388  7905 V DownloadManager: processing inserted download 14
09-12 13:57:29.153  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 13:57:29.153  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.153  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 13:57:29.153  3388  7905 V DownloadManager: processing inserted download 16
,09-12 13:57:29.161  7412  7412 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 13:57:29.162  7412  7412 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 13:57:29.168  3388  3388 V DownloadManager: DownloadService onDestroy
,09-12 13:57:29.174   316  7918 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:29.174   316  7918 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-12 13:57:29.176  7535  7535 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:29
09-12 13:57:29.178  7535  7535 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 13:57:29.178  7535  7535 D Weather.Utils: 2 : All the weather widget is gone.
09-12 13:57:29.179  7535  7535 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 13:57:29.179  7535  7535 D WeatherAncestor: connectivity changed - connection : true
09-12 13:57:29.179  7535  7535 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27b82274
09-12 13:57:29.180  7535  7535 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 13:57:29.180  7535  7535 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 13:57:29.180  7535  7535 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 13:57:29.180  7535  7535 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 13:57:29.180  7535  7535 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:29
,09-12 13:57:29.200  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 13:57:29.203  6537  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 13:57:29.216   316  7918 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-12 13:57:29.219  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.229  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 13:57:29.229  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.229  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 13:57:29.229  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-12 13:57:29.231  7322  7322 I AppUp4:CustModeStarterReceiver: onReceive
09-12 13:57:29.234  1035  1973 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-12 13:57:29.234  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:29.234  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:29.234  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:57:29.234  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:29.235  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 13:57:29.239  7322  7322 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c445186
09-12 13:57:29.239  7322  7322 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 13:57:29.239  7322  7322 D AppUp4:CustFacade: isPhone : true
09-12 13:57:29.239  7322  7322 D AppUp4:CustModeStarterReceiver: begin check event
09-12 13:57:29.240  7322  7322 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 13:57:29.243  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.244  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:29.246  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 13:57:29.249  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:29.254  3388  3388 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.255  4834  7923 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:29.257  7132  7915 V FormManager: There are no updated forms. The schedule will be deleted.
09-12 13:57:29.258  3388  3388 V DownloadManager: DownloadService onCreate
09-12 13:57:29.258  4834  7923 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-12 13:57:29.259  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:29 GMT], X-Android-Received-Millis=[1473681449259], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681449236]}
09-12 13:57:29.259  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:29.260  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 13:57:29.260  1035  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-12 13:57:29.260  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 13:57:29.260  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:29.260  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:29.260  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:29.260  1035  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-12 13:57:29.260  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:29.260  3388  7925 I DownloadManager: in removeSpuriousFiles
09-12 13:57:29.260  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:29.260  7132  7915 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-12 13:57:29.260  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:29.261  3388  7925 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-12 13:57:29.261  4834  7924 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.261  4834  7924 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-12 13:57:29.262  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:29.263  3388  7925 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a237ba3 on behalf of 3388
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-12 13:57:29.264  3388  7925 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-12 13:57:29.266  3388  7925 I DownloadManager: in trimDatabase
09-12 13:57:29.266  3388  7925 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-12 13:57:29.267  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:57:29.268  3388  7925 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@13d97ea0 on behalf of 3388
,09-12 13:57:29.273  4834  7923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-12 13:57:29.370  1035  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 13:57:29.379  1035  1751 I art     : Explicit concurrent mark sweep GC freed 128465(5MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.818ms total 110.008ms
09-12 13:57:29.392  3388  3388 V DownloadManager: DownloadService onStartCommand
09-12 13:57:29.392  3388  7926 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-12 13:57:29.393  4834  4834 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-12 13:57:29.393  4834  4834 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-12 13:57:29.393  4834  4834 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-12 13:57:29.394  4834  4834 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-12 13:57:29.396  3388  7926 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3ce82eff on behalf of 3388
09-12 13:57:29.398  3388  7926 V DownloadManager: processing inserted download 1
09-12 13:57:29.399  3388  7926 V DownloadManager: processing inserted download 4
09-12 13:57:29.400  3388  7926 V DownloadManager: processing inserted download 7
09-12 13:57:29.400  3388  7926 V DownloadManager: processing inserted download 8
09-12 13:57:29.401  3388  7926 V DownloadManager: processing inserted download 9
09-12 13:57:29.402  3388  7926 V DownloadManager: processing inserted download 10
09-12 13:57:29.402  3388  7926 V DownloadManager: processing inserted download 11
09-12 13:57:29.403  3388  7926 V DownloadManager: processing inserted download 12
09-12 13:57:29.404  4834  4834 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-12 13:57:29.406  3388  7926 V DownloadManager: processing inserted download 13
09-12 13:57:29.407  3388  7926 V DownloadManager: processing inserted download 14
09-12 13:57:29.407  3388  7926 V DownloadManager: processing inserted download 16
09-12 13:57:29.412  7352  7929 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:29.414  3388  3388 V DownloadManager: DownloadService onDestroy
09-12 13:57:29.419  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 13:57:29.419  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:29.419  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 13:57:29.421  7412  7412 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 13:57:29.421  7412  7412 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 13:57:29.429  7535  7535 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:29
,09-12 13:57:29.430  7535  7535 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 13:57:29.430  7535  7535 D Weather.Utils: 2 : All the weather widget is gone.
09-12 13:57:29.430  7535  7535 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 13:57:29.430  7535  7535 D WeatherAncestor: connectivity changed - connection : true
09-12 13:57:29.430  7535  7535 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27b82274
09-12 13:57:29.431  7535  7535 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 13:57:29.431  7535  7535 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 13:57:29.431  7535  7535 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 13:57:29.431  7535  7535 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 13:57:29.431  7535  7535 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:29
09-12 13:57:29.448  7132  7932 V FormManager: There are no updated forms. The schedule will be deleted.
,09-12 13:57:29.450  7132  7932 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-12 13:57:29.501  1035  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:29.502  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:29.504  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:29.505  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:29.506  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:29.507  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 13:57:29.509  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-12 13:57:29.509  1035  1545 D ConnectivityService: identical MTU - not setting
09-12 13:57:29.509  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 13:57:29.509  1035  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:29.510  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:29.510  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:29.511  1035  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-12 13:57:29.514  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-12 13:57:29.601  1035  1693 I ActivityManager: Killing 7226:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-12 13:57:29.659  1035  1867 W libprocessgroup: failed to open /acct/uid_10037/pid_7226/cgroup.procs: No such file or directory
,09-12 13:57:30.231  1035  2006 I ActivityManager: Killing 7256:com.lge.settings.easy/1000 (adj 15): empty #17
,09-12 13:57:30.263  1035  2031 W libprocessgroup: failed to open /acct/uid_1000/pid_7256/cgroup.procs: No such file or directory
,09-12 13:57:30.954  1035  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:30.954  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:30.954  1035  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:30.992  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 13:57:30.994  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 13:57:30.995  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 13:57:30.996  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 13:57:30.997  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 13:57:31.010  1035  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 13:57:31.267  1035  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=93.5, 0.0, 0.0  rx=88.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:507668739] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-12 13:57:31.280  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=93.5, 0.0, 0.0  rx=88.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:507668751] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:31.280  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-12 13:57:31.294  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 13:57:31.330  1035  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-12 13:57:31.362  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:31.376  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:57:31.393  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:31.401  6796  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:31.406  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 13:57:31.408  6537  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-12 13:57:31.417  5865  5865 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-12 13:57:31.444  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:31.465  1035  2006 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,09-12 13:57:31.467  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:31.468  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:31.468  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:57:31.469   316  7945 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:31.469   316  7945 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-12 13:57:31.469   316  7945 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-12 13:57:31.471  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:31.471  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-12 13:57:31.487  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 13:57:31.487  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:31.487  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 13:57:31.487  7322  7322 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 13:57:31.489  7322  7322 I AppUp4:CustModeStarterReceiver: onReceive
09-12 13:57:31.493  7322  7322 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c445186
09-12 13:57:31.493  7322  7322 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 13:57:31.493  7322  7322 D AppUp4:CustFacade: isPhone : true
,09-12 13:57:31.496  7322  7322 D AppUp4:CustModeStarterReceiver: begin check event
09-12 13:57:31.497  7322  7322 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 13:57:31.502  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:31.502  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 13:57:31.503  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 13:57:31.506  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 13:57:31.511  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:31 GMT], X-Android-Received-Millis=[1473681451511], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681451486]}
09-12 13:57:31.511  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:31.512  1035  7846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-12 13:57:31.513  1035  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-12 13:57:31.513  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 13:57:31.513  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:31.513  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:31.513  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 13:57:31.513  1035  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-12 13:57:31.513  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 13:57:31.514  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:31.514  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:31.514  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 13:57:31.515  1603  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:57:31.522  3388  3388 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:31.531  3388  3388 V DownloadManager: DownloadService onCreate
09-12 13:57:31.541  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:31.546  1035  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:31.547  3388  7951 I DownloadManager: in removeSpuriousFiles
09-12 13:57:31.547  3388  7951 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-12 13:57:31.556  3388  3388 V DownloadManager: DownloadService onStartCommand
,09-12 13:57:31.558  3388  7952 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-12 13:57:31.560  4834  7956 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 13:57:31.561  3388  7951 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d1abc1b on behalf of 3388
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-12 13:57:31.562  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-12 13:57:31.563  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-12 13:57:31.563  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-12 13:57:31.563  3388  7951 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-12 13:57:31.564  3388  7951 I DownloadManager: in trimDatabase
09-12 13:57:31.564  3388  7951 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-12 13:57:31.565  3388  7952 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@19481b8 on behalf of 3388
09-12 13:57:31.568  3388  7951 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@38117b91 on behalf of 3388
,09-12 13:57:31.574  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-12 13:57:31.574  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:31.574  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = true
09-12 13:57:31.574  3219  3219 D PhoneState: setPdpRejectCasuse : false
09-12 13:57:31.577  7412  7412 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 13:57:31.577  7412  7412 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 13:57:31.587  7352  7968 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:31.595  4834  7956 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-12 13:57:31.596  7535  7535 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:31
09-12 13:57:31.597  7535  7535 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 13:57:31.597  7535  7535 D Weather.Utils: 2 : All the weather widget is gone.
09-12 13:57:31.598  7535  7535 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 13:57:31.598  7535  7535 D WeatherAncestor: connectivity changed - connection : true
09-12 13:57:31.598  7535  7535 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27b82274
09-12 13:57:31.599  7535  7535 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 13:57:31.599  7535  7535 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 13:57:31.599  7535  7535 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 13:57:31.599  7535  7535 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 13:57:31.599  7535  7535 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:57:31
,09-12 13:57:31.602  4834  7966 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:31.602  4834  7966 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 13:57:31.606  3388  7952 V DownloadManager: processing inserted download 1
09-12 13:57:31.608  3388  7952 V DownloadManager: processing inserted download 4
09-12 13:57:31.609  4834  7956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-12 13:57:31.612  3388  7952 V DownloadManager: processing inserted download 7
09-12 13:57:31.613  4834  4834 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-12 13:57:31.614  4834  4834 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-12 13:57:31.614  4834  4834 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-12 13:57:31.614  3388  7952 V DownloadManager: processing inserted download 8
09-12 13:57:31.615  3388  7952 V DownloadManager: processing inserted download 9
09-12 13:57:31.616  3388  7952 V DownloadManager: processing inserted download 10
09-12 13:57:31.618  3388  7952 V DownloadManager: processing inserted download 11
,09-12 13:57:31.621  3388  7952 V DownloadManager: processing inserted download 12
09-12 13:57:31.629  3388  7952 V DownloadManager: processing inserted download 13
09-12 13:57:31.630  3388  7952 V DownloadManager: processing inserted download 14
,09-12 13:57:31.632  3388  7952 V DownloadManager: processing inserted download 16
,09-12 13:57:31.632  4834  4834 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-12 13:57:31.635  3388  3388 V DownloadManager: DownloadService onDestroy
09-12 13:57:31.637  4834  4834 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-12 13:57:31.656  7132  7971 V FormManager: There are no updated forms. The schedule will be deleted.
,09-12 13:57:31.658  7132  7971 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-12 13:57:32.104  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-12 13:57:32.104  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:57:32.122  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:32.122  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:32.122  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:32.122  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e30c27 not in the list
09-12 13:57:32.122  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:32.122  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8a3ed4 not in the list
09-12 13:57:32.123  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:32.123  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:32.123  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:32.125  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:32.128  6796  6863 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-12 13:57:32.133  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-12 13:57:32.142  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:32.142  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:57:32.142  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:32.143  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:32.145  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:57:32.146  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:57:32.146  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:57:32.147  6796  6796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:57:32.149  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:32.149  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:57:32.149  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:32.149  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:32.155  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:57:32.159  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:32.161  6796  6863 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 13:57:32.161  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:32.161  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:57:32.161  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:57:32.161  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:32.161  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:32.162  6796  6863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:32.162  6796  6796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:57:32.162  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e30c27 not in the list
09-12 13:57:32.162  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:32.162  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8a3ed4 not in the list
09-12 13:57:32.162  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:32.162  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:32.162  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:32.163  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:32.163  6796  6863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:57:32.163  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:57:32.164  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:32.164  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:32.165  6796  7985 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:32.166  6796  7985 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:57:32.166  6796  6796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:32.171  6796  6863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:57:32.177  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:32.179  6796  6863 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-12 13:57:32.549   316  7986 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-12 13:57:32.560   316  7986 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-12 13:57:32.599   316  7986 D libc-netbsd: res_queryN name = www.google.com succeed
,09-12 13:57:32.609   316  7988 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-12 13:57:32.609   316  7988 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-12 13:57:32.610   316  7988 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-12 13:57:32.681  1035  1541 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-12 13:57:32.857  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-12 13:57:32.861  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-12 13:57:32.883  1035  1485 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:57:32.967  1035  1095 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7989 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-12 13:57:32.973  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-12 13:57:32.974  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-12 13:57:32.977  1035  1035 D administrator: Handling package changes for user 0
,09-12 13:57:33.033  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 13:57:33.052  7989  7989 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 13:57:33.093  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-12 13:57:33.093  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-12 13:57:33.128  7989  7989 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 13:57:33.128  7989  7989 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:57:33.147  1035  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:57:33.152  1035  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-12 13:57:33.158  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-12 13:57:33.159  2508  2508 V GmsNetworkLocationProvi: DISABLE
09-12 13:57:33.187  1035  1092 D LocationProviderProxy: applying state to connected service
,09-12 13:57:33.190  2508  2508 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-12 13:57:33.244  7989  8033 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-12 13:57:33.246  7989  8033 I Babel   : MmsConfig.loadMmsSettings
09-12 13:57:33.256  7989  8033 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-12 13:57:33.256  7989  8033 I Babel   : MmsConfig.loadFromDatabase
,09-12 13:57:33.293  7989  8033 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-12 13:57:33.293  7989  8033 I Babel   : MmsConfig.loadFromResources
09-12 13:57:33.295  7989  8033 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-12 13:57:33.295  7989  8033 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-12 13:57:33.306  7989  7989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:33.325  7989  8032 W AudioCapabilities: Unsupported mime audio/evrc
09-12 13:57:33.327  7989  8032 W AudioCapabilities: Unsupported mime audio/qcelp
09-12 13:57:33.329  7989  8032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-12 13:57:33.338  7322  7322 I AppUp4:CustModeStarterReceiver: onReceive
,09-12 13:57:33.339  1815  8037 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-12 13:57:33.339  1815  8037 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-12 13:57:33.342  7322  7322 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c445186
09-12 13:57:33.342  7322  7322 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 13:57:33.342  7322  7322 D AppUp4:CustFacade: isPhone : true
09-12 13:57:33.342  7322  7322 D AppUp4:CustModeStarterReceiver: begin check event
09-12 13:57:33.342  7322  7322 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-12 13:57:33.361  7989  8032 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-12 13:57:33.362  7989  8032 W AudioCapabilities: Unsupported mime audio/qcelp
09-12 13:57:33.363  7989  8032 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 13:57:33.384  1035  1867 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8040 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-12 13:57:33.384  7989  8032 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 13:57:33.392  7989  8032 W VideoCapabilities: Unsupported mime video/divx
09-12 13:57:33.392  1035  1693 I ActivityManager: Killing 5613:com.lge.bnr/1000 (adj 15): empty #17
09-12 13:57:33.394  7989  8032 W VideoCapabilities: Unsupported mime video/divx311
09-12 13:57:33.395  7989  8032 W VideoCapabilities: Unsupported mime video/divx4
09-12 13:57:33.400  7989  8032 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-12 13:57:33.402  1815  5261 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-12 13:57:33.404   350   350 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 340us total 20.545ms
,09-12 13:57:33.419  7989  8032 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 13:57:33.420   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 273us total 15.134ms
,09-12 13:57:33.422  7989  8032 W AudioCapabilities: Unsupported mime audio/eac3
09-12 13:57:33.423  7989  8032 W AudioCapabilities: Unsupported mime audio/ac3
09-12 13:57:33.424  7989  8032 W AudioCapabilities: Unsupported mime audio/g726
09-12 13:57:33.425  7989  8032 W AudioCapabilities: Unsupported mime audio/wma-voice
09-12 13:57:33.426  7989  8032 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-12 13:57:33.427  7989  8032 W AudioCapabilities: Unsupported mime audio/adpcm
09-12 13:57:33.429  7989  8032 W VideoCapabilities: Unsupported mime video/theora
09-12 13:57:33.430  7989  8032 W VideoCapabilities: Unsupported mime video/mjpg
09-12 13:57:33.437   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 13.171ms
,09-12 13:57:33.493  1035  1867 W libprocessgroup: failed to open /acct/uid_1000/pid_5613/cgroup.procs: No such file or directory
,09-12 13:57:33.520  8040  8040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:33.520  8040  8040 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-12 13:57:33.521  8040  8040 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-12 13:57:33.522  8040  8040 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-12 13:57:33.522  8040  8040 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 13:57:33.602  8040  8040 I SystemConfig: BUILD Country: EU
09-12 13:57:33.602  8040  8040 I SystemConfig: BUILD Operator: OPEN
,09-12 13:57:33.654  1035  1751 I ActivityManager: Killing 7068:com.lge.sync/1000 (adj 15): empty #17
,09-12 13:57:33.804  1035  1903 W libprocessgroup: failed to open /acct/uid_1000/pid_7068/cgroup.procs: No such file or directory
,09-12 13:57:33.818  8040  8058 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-12 13:57:33.818  8040  8058 I SystemConfig: existFile = false
09-12 13:57:33.818  8040  8058 I SystemConfig: canReadFile = false
09-12 13:57:33.818  8040  8058 I SystemConfig: systemFeature RCS result false
09-12 13:57:33.819  8040  8058 D SystemConfig: refreshRcsSupport() :false
09-12 13:57:33.877  1035  1751 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8063 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-12 13:57:33.950  8063  8063 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:57:33.950  8063  8063 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 13:57:33.950  8063  8063 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-12 13:57:33.951  8063  8063 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 13:57:34.046  8063  8063 I AppConfig: Total System Memory = 2995761152
,09-12 13:57:34.062  8063  8063 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-12 13:57:34.167  1035  1940 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8082 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:34.169  1035  1940 I ActivityManager: Killing 6966:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-12 13:57:34.187  7112  7112 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-12 13:57:34.187  7112  7112 W System.err: android.os.DeadObjectException
09-12 13:57:34.187  7112  7112 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 13:57:34.187  7112  7112 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-12 13:57:34.187  7112  7112 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-12 13:57:34.187  7112  7112 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-12 13:57:34.188  7112  7112 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 13:57:34.188  7112  7112 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 13:57:34.188  7112  7112 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:34.188  7112  7112 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:34.189  7112  7112 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 13:57:34.191  7112  7112 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 13:57:34.197  7112  7112 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:34.197  7112  7112 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:34.197  7112  7112 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:34.197  7112  7112 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 13:57:34.198  7112  7112 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-12 13:57:34.198  7112  7112 W System.err: android.os.DeadObjectException
09-12 13:57:34.199  7112  7112 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-12 13:57:34.199  7112  7112 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 13:57:34.199  7112  7112 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-12 13:57:34.199  7112  7112 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-12 13:57:34.199  7112  7112 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 13:57:34.199  7112  7112 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 13:57:34.199  7112  7112 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:34.199  7112  7112 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:34.199  7112  7112 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 13:57:34.199  7112  7112 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 13:57:34.199  7112  7112 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:34.199  7112  7112 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:34.199  7112  7112 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:34.199  7112  7112 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 13:57:34.199  7112  7112 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-12 13:57:34.200  7112  7112 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-12 13:57:34.224  1035  1904 W libprocessgroup: failed to open /acct/uid_1000/pid_6966/cgroup.procs: No such file or directory
,09-12 13:57:34.225  1035  1904 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-12 13:57:34.227  7112  7112 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-12 13:57:34.228  7112  7112 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-12 13:57:34.295  1035  1693 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8100 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 13:57:34.296  1035  1426 V AlarmManager: ELAPSED_WAKEUP set : Alarm{17876429 type 2 when 144407 com.google.android.gms} when 144407
09-12 13:57:34.297  1035  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=62.8, 0.0, 0.0  rx=55.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:507671769] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:34.298  7112  7112 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-12 13:57:34.298  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=62.8, 0.0, 0.0  rx=55.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:507671770] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:34.298  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-12 13:57:34.389  8100  8100 D UEI.SmartControl: Quickset Services start...
09-12 13:57:34.391  8100  8100 I UEI.SmartControl: Manufacture = LGE
09-12 13:57:34.391  8100  8100 D UEI.SmartControl: Id = LGNevo
09-12 13:57:34.393  8100  8100 D UEI.SmartControl: File observer start...
,09-12 13:57:34.395  8100  8100 E UEI.SmartControl: IR Port is disabled: false
09-12 13:57:34.395  8100  8100 D UEI.SmartControl: Starting file observer...
09-12 13:57:34.395  8100  8100 D UEI.SmartControl: Extracting JNI libs...
09-12 13:57:34.395  8100  8100 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-12 13:57:34.424  8082  8082 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-12 13:57:34.462  8100  8100 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-12 13:57:34.462  8100  8100 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-12 13:57:34.462  8100  8100 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-12 13:57:34.483  8100  8100 I UEI.SmartControl: --- Selecting new region: 6
09-12 13:57:34.484  8100  8100 I UEI.SmartControl: Model = LG-D855
09-12 13:57:34.485  8100  8100 D UEI.SmartControl: QS Service created
09-12 13:57:34.494  8100  8100 I UEI.SmartControl: Service initServices...
,09-12 13:57:34.495  8082  8082 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:57:34.495  8082  8082 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 13:57:34.497  8100  8100 D UEI.SmartControl: QS start get config
,09-12 13:57:34.523  8100  8100 D UEI.SmartControl: Loading JNI Libs...
09-12 13:57:34.534  8082  8082 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-12 13:57:34.549  8082  8082 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 13:57:34.550  8082  8082 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-12 13:57:34.563  8082  8082 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 13:57:34.563  8082  8082 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-12 13:57:34.588  1035  1904 I ActivityManager: Killing 7089:com.android.settings/1000 (adj 15): empty #17
,09-12 13:57:34.712  1035  1867 W libprocessgroup: failed to open /acct/uid_1000/pid_7089/cgroup.procs: No such file or directory
,09-12 13:57:34.728  3388  7569 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-12 13:57:34.731  5092  8141 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-12 13:57:34.732  3388  7569 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b1efef7 on behalf of 8082
09-12 13:57:34.745  8100  8100 I UEI.SmartControl: Supports setup maps: true
09-12 13:57:34.748  8100  8100 D UEI.SmartControl: QS start statue = true Error code = 0
09-12 13:57:34.748  8100  8100 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-12 13:57:34.748  8100  8100 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-12 13:57:34.748  8100  8100 I UEI.SmartControl: ### init IR Blaster...
,09-12 13:57:34.760  8100  8100 D serial_port: Configuring serial port
09-12 13:57:34.771  1035  1050 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8144 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:34.774  8100  8100 E UEI.SmartControl: UEIBLaster setting for 616
09-12 13:57:34.774  8100  8100 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 13:57:34.774  8100  8100 I UEI.SmartControl: configuring settings for MAXQ616
,09-12 13:57:34.774  8100  8100 I UEI.SmartControl: Get version...
09-12 13:57:34.793  8100  8143 D UEI.SmartControl: serial port data available: 21
,09-12 13:57:34.796  8082  8082 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-12 13:57:34.814  8082  8082 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-12 13:57:34.822  8100  8100 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-12 13:57:34.822  8100  8100 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 13:57:34.822  8144  8144 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
09-12 13:57:34.822  8100  8100 I UEI.SmartControl: QS saving settings...
09-12 13:57:34.822  8100  8100 D UEI.SmartControl: IR Blaster version: 25672567
09-12 13:57:34.836  8100  8143 D UEI.SmartControl: serial port data available: 4
,09-12 13:57:34.840  8144  8144 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-12 13:57:34.840  8144  8144 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-12 13:57:34.840  8144  8144 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-12 13:57:34.840  8144  8144 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-12 13:57:34.840  8144  8144 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-12 13:57:34.840  8144  8144 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-12 13:57:34.853  7112  7112 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-12 13:57:34.853  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1142
,09-12 13:57:34.858  1035  2031 I ActivityManager: Killing 7478:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-12 13:57:34.858   316  8167 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 13:57:34.858   316  8167 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-12 13:57:34.858   316  8167 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-12 13:57:34.864  8100  8169 I UEI.SmartControl: Device manager: loading config....
09-12 13:57:34.865  8100  8100 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-12 13:57:34.865  8100  8169 D UEI.SmartControl: ----------- loading internal config...
,09-12 13:57:34.870  8100  8169 E UEI.SmartControl: Loading SETTINGS...
09-12 13:57:34.874  8100  8169 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-12 13:57:34.883  8100  8168 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-12 13:57:34.884  8100  8168 D UEI.SmartControl: -----service ready thread exits
09-12 13:57:34.899  8100  8100 E UEI.SmartControl: Services init done
09-12 13:57:34.899  8100  8100 D UEI.SmartControl: QS Service init finished
09-12 13:57:34.899  1035  1050 W libprocessgroup: failed to open /acct/uid_10005/pid_7478/cgroup.procs: No such file or directory
,09-12 13:57:34.903  8100  8100 D UEI.SmartControl: QS Service version name: 2.1.91
09-12 13:57:34.903  8100  8100 D UEI.SmartControl: QS Service version code: 201091
09-12 13:57:34.903  8100  8100 D UEI.SmartControl: Service requested: Control
09-12 13:57:34.904  8100  8100 D UEI.SmartControl: Internal service binding...
09-12 13:57:34.905  7112  7112 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-12 13:57:34.905  1035  1576 I ActivityManager: Killing 7352:com.lge.email/u0a23 (adj 15): empty #17
09-12 13:57:34.906  8100  8115 I UEI.SmartControl: ------ IControl API: 11
09-12 13:57:34.906  8100  8115 I UEI.SmartControl: Registering callback...
09-12 13:57:34.911  8100  8116 I UEI.SmartControl: ------ IControl API: 19
09-12 13:57:34.913  8100  8116 I UEI.SmartControl: Registering Services Ready callback...
09-12 13:57:34.913  8100  8116 I UEI.SmartControl: Notify client services are ready...
09-12 13:57:34.914  7112  7128 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-12 13:57:34.915  7112  7166 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-12 13:57:34.915  7112  7166 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-12 13:57:34.916  7112  7112 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-12 13:57:34.916  7112  7112 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-12 13:57:34.917  8100  8115 I UEI.SmartControl: ------ IControl API: 8
,09-12 13:57:34.921  7112  7112 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,09-12 13:57:34.922  7112  7112 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-12 13:57:34.923  7112  7112 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-12 13:57:34.923  7112  7112 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-12 13:57:34.924  7112  7112 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-12 13:57:34.925  7112  7112 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-12 13:57:35.042  7112  7112 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-12 13:57:35.057  1035  2359 W libprocessgroup: failed to open /acct/uid_10023/pid_7352/cgroup.procs: No such file or directory
,09-12 13:57:35.065  7112  7112 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-12 13:57:35.067  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-12 13:57:35.068  7112  7112 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 13:57:35.068  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 13:57:35.069  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-12 13:57:35.071  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-12 13:57:35.071  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-12 13:57:35.072  7112  7112 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473681455071]
,09-12 13:57:35.093  7112  8173 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-12 13:57:35.100  7112  7112 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-12 13:57:35.101  7112  7112 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 13:57:35.101  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-12 13:57:35.102  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,09-12 13:57:35.102  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-12 13:57:35.102  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-12 13:57:35.102  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-12 13:57:35.104  7112  7112 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-12 13:57:35.153  2206  8172 D GCM     : Connected
,09-12 13:57:35.173  2206  8172 D GCM     : Message class com.google.e.a.a.q
,09-12 13:57:35.183  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:35.183  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:35.183  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:35.184  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e30c27 not in the list
09-12 13:57:35.184  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:35.184  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8a3ed4 not in the list
09-12 13:57:35.184  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:35.184  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:35.184  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:35.185  6796  6863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:35.185  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:35.185  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:35.185  6796  6863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e30c27 not in the list
09-12 13:57:35.185  6796  6863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:57:35.185  6796  6863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8a3ed4 not in the list
09-12 13:57:35.185  6796  6863 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:35.185  6796  6863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:35.186  6796  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:35.188  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 13:57:35.189  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 13:57:35.189  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:35.189  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:35.189  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:57:35.190  6796  6863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:57:35.203  6796  8174 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 999, name: My test thread name)
09-12 13:57:35.222  1035  1992 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:57:35.243  5092  8141 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 512 ms] updated apps [took 512 ms] 
,09-12 13:57:37.202  6796  6863 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 999
,09-12 13:57:37.202  6796  6863 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 999, name: My test thread name)
,09-12 13:57:37.220  6796  8184 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1000, name: My test thread name)
09-12 13:57:37.220  6796  8184 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1000, thread name: My test thread name)
09-12 13:57:37.220  6796  8184 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1000, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-12 13:57:37.223  6796  6863 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:37.226  6796  8185 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1004, name: My test thread name)
09-12 13:57:37.226  6796  8185 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1004, thread name: My test thread name): Test exception.
09-12 13:57:37.227  6796  8185 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1004, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 13:57:37.233  6796  6863 I jxcore-log: Total number of executed tests:  82
09-12 13:57:37.233  6796  6863 I jxcore-log: 
,09-12 13:57:37.233  6796  6863 I jxcore-log: Number of passed tests:  82
09-12 13:57:37.233  6796  6863 I jxcore-log: 
09-12 13:57:37.233  6796  6863 I jxcore-log: Number of failed tests:  0
09-12 13:57:37.233  6796  6863 I jxcore-log: 
09-12 13:57:37.234  6796  6863 I jxcore-log: Number of ignored tests:  0
09-12 13:57:37.234  6796  6863 I jxcore-log: 
09-12 13:57:37.234  6796  6863 I jxcore-log: Total duration:  19747
09-12 13:57:37.234  6796  6863 I jxcore-log: 
09-12 13:57:37.236  6796  6863 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 13:57:37.236  6796  6863 I jxcore-log: 
09-12 13:57:37.237  6796  6863 I jxcore-log: My device name is: LGE-LG-D855
09-12 13:57:37.237  6796  6863 I jxcore-log: 
09-12 13:57:37.241  6796  6863 I jxcore-log: WARN testUtils: myNameCallback not set!
09-12 13:57:37.241  6796  6863 I jxcore-log: 
09-12 13:57:37.242  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.242  6796  6863 I jxcore-log: 
,09-12 13:57:37.258  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.258  6796  6863 I jxcore-log: 
09-12 13:57:37.259  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.259  6796  6863 I jxcore-log: 
09-12 13:57:37.261  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.261  6796  6863 I jxcore-log: 
09-12 13:57:37.264  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.264  6796  6863 I jxcore-log: 
09-12 13:57:37.266  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.266  6796  6863 I jxcore-log: 
09-12 13:57:37.267  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:37.267  6796  6863 I jxcore-log: 
,09-12 13:57:37.274  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:37.274  6796  6863 I jxcore-log: 
09-12 13:57:37.276  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:37.276  6796  6863 I jxcore-log: 
09-12 13:57:37.277  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:57:37.277  6796  6863 I jxcore-log: 
09-12 13:57:37.279  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.279  6796  6863 I jxcore-log: 
09-12 13:57:37.280  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.280  6796  6863 I jxcore-log: 
09-12 13:57:37.281  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.281  6796  6863 I jxcore-log: 
09-12 13:57:37.281  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.281  6796  6863 I jxcore-log: 
09-12 13:57:37.282  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.282  6796  6863 I jxcore-log: 
09-12 13:57:37.283  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.283  6796  6863 I jxcore-log: 
09-12 13:57:37.284  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.284  6796  6863 I jxcore-log: 
09-12 13:57:37.285  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.285  6796  6863 I jxcore-log: 
09-12 13:57:37.285  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.285  6796  6863 I jxcore-log: 
09-12 13:57:37.286  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.286  6796  6863 I jxcore-log: 
09-12 13:57:37.287  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.287  6796  6863 I jxcore-log: 
09-12 13:57:37.288  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.288  6796  6863 I jxcore-log: 
09-12 13:57:37.289  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.289  6796  6863 I jxcore-log: 
,09-12 13:57:37.295  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.295  6796  6863 I jxcore-log: 
09-12 13:57:37.296  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.296  6796  6863 I jxcore-log: 
09-12 13:57:37.297  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.297  6796  6863 I jxcore-log: 
09-12 13:57:37.297  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.297  6796  6863 I jxcore-log: 
09-12 13:57:37.299  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.299  6796  6863 I jxcore-log: 
09-12 13:57:37.300  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:37.300  6796  6863 I jxcore-log: 
09-12 13:57:37.300  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:37.300  6796  6863 I jxcore-log: 
09-12 13:57:37.301  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:37.301  6796  6863 I jxcore-log: 
09-12 13:57:37.302  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.302  6796  6863 I jxcore-log: 
09-12 13:57:37.303  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.303  6796  6863 I jxcore-log: 
09-12 13:57:37.304  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:37.304  6796  6863 I jxcore-log: 
09-12 13:57:37.304  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.304  6796  6863 I jxcore-log: 
09-12 13:57:37.305  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.305  6796  6863 I jxcore-log: 
09-12 13:57:37.306  6796  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:37.306  6796  6863 I jxcore-log: 
09-12 13:57:37.310  1035  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=40.9, 0.0, 0.0  rx=34.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:507674782] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:37.310  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=40.9, 0.0, 0.0  rx=34.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:507674782] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 13:57:37.311  1035  1538 D WifiNative-wlan0: doStrin,g: [SIGNAL_POLL]
,09-12 13:57:37.369  6796  8174 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 999, name: My test thread name), during the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
,09-12 13:57:37.580  8186  8186 D AndroidRuntime: 
09-12 13:57:37.580  8186  8186 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 13:57:37.584  8186  8186 D AndroidRuntime: CheckJNI is OFF
,09-12 13:57:37.793  8186  8186 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 13:57:37.804  1035  1095 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-12 13:57:37.805  1035  1095 I ActivityManager: Killing 6796:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-12 13:57:37.869  1035  1051 I WindowState: WIN DEATH: Window{113b71c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 13:57:37.870  1035  1544 D WifiService: Client connection lost with reason: 4
,09-12 13:57:37.876  1035  1051 D InputDispatcher: Window went away: Window{113b71c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 13:57:38.025  1035  1095 I ActivityManager:   Force finishing activity ActivityRecord{3968b58c u0 com.test.thalitest/.MainActivity t6}
,09-12 13:57:38.088   346   359 E GBMv2   : DFP En is all cleared set to be enabled
,09-12 13:57:38.091  1035  1576 W ActivityManager: Spurious death for ProcessRecord{25683ac2 6796:com.test.thalitest/u0a118}, curProc for 6796: null
09-12 13:57:38.091  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-12 13:57:38.095  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{3968b58c u0 com.test.thalitest/.MainActivity t6 f}
09-12 13:57:38.095  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3968b58c u0 com.test.thalitest/.MainActivity t6 f}
,09-12 13:57:38.145  5092  5092 I art     : Explicit concurrent mark sweep GC freed 8172(466KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 548us total 43.274ms
09-12 13:57:38.148  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-12 13:57:38.149  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{300b7e2 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-12 13:57:38.150  1941  2949 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-12 13:57:38.150  1941  2949 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a215773 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-12 13:57:38.163  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,09-12 13:57:38.165  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-12 13:57:38.169  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-12 13:57:38.171  1035  1485 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 13:57:38.178  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,09-12 13:57:38.179  2032  2124 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-12 13:57:38.182  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-12 13:57:38.183  6537  6537 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-12 13:57:38.183  4342  4342 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-12 13:57:38.183  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-12 13:57:38.187  3814  3814 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-12 13:57:38.191  2508  2697 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 13:57:38.193  1905  1905 D ActionManagerService: notifyUserLog: 1000003
09-12 13:57:38.193  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-12 13:57:38.194  3814  5016 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-12 13:57:38.196  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-12 13:57:38.196  4993  4993 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-12 13:57:38.199  4993  4993 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-12 13:57:38.199  4993  4993 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-12 13:57:38.199  4993  4993 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-12 13:57:38.199  4993  4993 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:38.199  4993  4993 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:38.199  4993  4993 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 13:57:38.200  4993  4993 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 13:57:38.200  4993  4993 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:38.200  4993  4993 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:38.200  4993  4993 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:38.200  4993  4993 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 13:57:38.203  1035  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
09-12 13:57:38.205  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-12 13:57:38.225  1035  1867 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:57:38.250  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-12 13:57:38.282  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-12 13:57:38.284  1868  1868 D SplitUIService: removed split : 
,09-12 13:57:38.287  1035  1035 I art     : Explicit concurrent mark sweep GC freed 48752(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.901ms total 155.843ms
09-12 13:57:38.293  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-12 13:57:38.300  1035  1940 V SIM_STK : Menu title from STK is T-Mobile
09-12 13:57:38.300  1035  1940 V SIM_STK : Menu title from STK is T-Mobile
,09-12 13:57:38.310  1603  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-12 13:57:38.310  1603  1660 D KeyguardModel: createShortcutInfo...
09-12 13:57:38.317  1603  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-12 13:57:38.317  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-12 13:57:38.317  1603  1660 D KeyguardModel: createShortcutInfo...
,09-12 13:57:38.318  2206  2206 I ConfigService: onCreate
09-12 13:57:38.318  2206  2206 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-12 13:57:38.322  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-12 13:57:38.322  1603  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:38.323  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-12 13:57:38.323  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 13:57:38.326  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-12 13:57:38.326  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-12 13:57:38.327  3814  5010 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 13:57:38.328  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-12 13:57:38.328  1868  1868 I SplitUIService: split app #11
09-12 13:57:38.329  1905  1905 D ActionManagerService: notifyUserLog: 1000004
09-12 13:57:38.329  3814  5016 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , display: false
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , animation: false }
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , display: false
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , animation: false }
09-12 13:57:38.329  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , create_time: 1473420113195
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , display: false
09-12 13:57:38.329  2032  2032 I GBoardWebViewUtils: , animation: false }
09-12 13:57:38.329  1603  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-12 13:57:38.334  1603  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-12 13:57:38.334  1603  1660 D KeyguardModel: createShortcutInfo...
09-12 13:57:38.339  2206  2206 I ConfigService: onBind returning update interface
,09-12 13:57:38.340  2032  8221 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-12 13:57:38.341  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-12 13:57:38.341  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-12 13:57:38.350  1035  1939 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 13:57:38.351  4342  4342 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-12 13:57:38.354  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-12 13:57:38.355  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-12 13:57:38.361  2206  2206 I art     : Explicit concurrent mark sweep GC freed 12053(734KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.193ms total 21.596ms
09-12 13:57:38.367  1035  1035 D administrator: Handling package changes for user 0
,09-12 13:57:38.376  2206  2206 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-12 13:57:38.376  2206  2206 I ConfigService: onBind returning config service
09-12 13:57:38.380  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,09-12 13:57:38.380  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 13:57:38.383  2206  2206 I ConfigService: onDestroy
09-12 13:57:38.385  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 13:57:38.385  1603  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-12 13:57:38.386  1815  8224 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-12 13:57:38.388  1603  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-12 13:57:38.388  1603  1660 D KeyguardModel: createShortcutInfo...
09-12 13:57:38.392  1603  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:38.392  1603  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 13:57:38.392  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-12 13:57:38.392  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 13:57:38.392  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 13:57:38.393  1603  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-12 13:57:38.393  1603  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-12 13:57:38.393  1603  1660 D KeyguardModel: createShortcutInfo...
,09-12 13:57:38.402  1603  1603 D KeyguardModel: handleShortcutListChanged...
09-12 13:57:38.402  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-12 13:57:38.406  1603  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-12 13:57:38.406  1603  1660 D KeyguardModel: createShortcutInfo...
,09-12 13:57:38.417  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-12 13:57:38.418  1603  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-12 13:57:38.418  1603  1660 D KeyguardModel: createShortcutInfo...
,09-12 13:57:38.419  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 13:57:38.419  1603  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-12 13:57:38.422  1603  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-12 13:57:38.422  1603  1660 D KeyguardModel: createShortcutInfo...
09-12 13:57:38.423  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 13:57:38.423  1603  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-12 13:57:38.424  1603  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-12 13:57:38.424  1603  1660 D KeyguardModel: createShortcutInfo...
,09-12 13:57:38.425  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 13:57:38.425  1603  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-12 13:57:38.426  1035  1867 V SIM_STK : Menu title from STK is T-Mobile
09-12 13:57:38.426  1603  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-12 13:57:38.426  1603  1660 D KeyguardModel: createShortcutInfo...
09-12 13:57:38.427  5900  8230 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-12 13:57:38.437  1815  8231 I PeopleContactsSync: CP2 sync disabled
,09-12 13:57:38.443  1815  5261 I Icing   : doRemovePackageData com.test.thalitest
09-12 13:57:38.443  2032  2046 I art     : Background partial concurrent mark sweep GC freed 7076(322KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 6.373ms total 38.691ms
09-12 13:57:38.450  7322  7322 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-12 13:57:38.467  1603  1603 D KeyguardModel: handleShortcutListChanged...
09-12 13:57:38.467  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-12 13:57:38.501  2335  8232 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-12 13:57:38.517  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-12 13:57:38.518  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-12 13:57:38.518  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 13:57:38.539  1035  1939 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8235 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-12 13:57:38.542  1035  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-12 13:57:38.543  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-12 13:57:38.545  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 13:57:38.547  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-12 13:57:38.548  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-12 13:57:38.549  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-12 13:57:38.550  1815  8229 W GmsApplication: Using Auth Proxy for data requests.
09-12 13:57:38.550  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-12 13:57:38.555  1815  8229 W GmsApplication: Using Auth Proxy for data requests.
09-12 13:57:38.564  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19959548 u0 com.lge.launcher2/.Launcher t5} time:148725
,09-12 13:57:38.567  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-12 13:57:38.567  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 13:57:38.569  2032  2165 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-12 13:57:38.569  2032  2165 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-12 13:57:38.587  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-12 13:57:38.588  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-12 13:57:38.588  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-12 13:57:38.597  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-12 13:57:38.598  2576  2576 D [Concierge]Service: onStartCommand(). Type : 8
09-12 13:57:38.598  2576  2576 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-12 13:57:38.600  2576  2576 D [Concierge]Service: Update widget ID : 11
09-12 13:57:38.600  2032  2032 D [Concierge]WidgetView: change position of spinner
,09-12 13:57:38.602  2576  2576 D [Concierge]Service: onStartCommand(). Type : 0
09-12 13:57:38.603  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1473681458603
09-12 13:57:38.610  8235  8235 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:38.611  8235  8235 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 13:57:38.614  8235  8235 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 13:57:38.614  8235  8235 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 13:57:38.618  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 893887385
,09-12 13:57:38.619  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-12 13:57:38.620  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-12 13:57:38.623  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1bf42765
09-12 13:57:38.623  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-12 13:57:38.624  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-12 13:57:38.624  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 13:57:38.629  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-12 13:57:38.629  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
,09-12 13:57:38.629  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-12 13:57:38.630  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473681338031, New one : 1473681458603
09-12 13:57:38.630  2032  2032 D [Concierge]WidgetView: Unregister all receivers
09-12 13:57:38.630  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-12 13:57:38.631  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 13:57:38.632  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-12 13:57:38.634  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,09-12 13:57:38.635  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-12 13:57:38.636  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-12 13:57:38.637  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-12 13:57:38.641  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 13:57:38.641  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-12 13:57:38.648  1035  1123 W art     : Suspending all threads took: 8.411ms
09-12 13:57:38.691  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-12 13:57:38.692  8235  8235 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-12 13:57:38.696  1035  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:38.699  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-12 13:57:38.700  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-12 13:57:38.700  1035  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-12 13:57:38.701  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 13:57:38.701  8235  8235 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-12 13:57:38.703  1035  1123 I art     : Explicit concurrent mark sweep GC freed 13109(845KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 14.187ms total 380.787ms
09-12 13:57:38.720  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@163dfaf6 time:148882
,09-12 13:57:38.726  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-12 13:57:38.730  8235  8235 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 13:57:38.752  8235  8235 D LgDataFeature: LgDataFeature() Constructor: none
09-12 13:57:38.752  8235  8235 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 13:57:38.770  8186  8186 D AndroidRuntime: Shutting down VM
,09-12 13:57:38.824  8235  8235 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-12 13:57:38.845  1035  1903 I ActivityManager: Killing 7132:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-12 13:57:38.850  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-12 13:57:38.895  2032  2893 I GBoardtInterface: onReloaded()
,09-12 13:57:38.897  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-12 13:57:38.901  1994  1994 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-12 13:57:38.901  1994  1994 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-12 13:57:38.903  1035  1867 W libprocessgroup: failed to open /acct/uid_10026/pid_7132/cgroup.procs: No such file or directory
09-12 13:57:38.910  3814  3829 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 13:57:38.910  1994  1994 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,09-12 13:57:38.917  3814  5010 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 13:57:38.917  6537  6537 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-12 13:57:38.966  1035  2030 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8260 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:38.978  1905  1905 D ActionManagerService: notifyUserLog: 1000001
09-12 13:57:38.981  3814  5016 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-12 13:57:38.981  3814  5016 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-12 13:57:38.986  1905  1905 D ActionManagerService: notifyUserLog: 1000001
09-12 13:57:38.989  3814  5016 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-12 13:57:38.990  3814  5016 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-12 13:57:38.990  3814  5016 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-12 13:57:38.990  3814  5016 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-12 13:57:38.992  3814  3829 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 13:57:38.997  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-12 13:57:38.997  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,09-12 13:57:39.001  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-12 13:57:39.001  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-12 13:57:39.005  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-12 13:57:39.005  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-12 13:57:39.058  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8279 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-12 13:57:39.114  8260  8260 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:39.114  8260  8260 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: Unable to open database for writing.
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:39.114  8260  8260 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 13:57:39.114  8260  8260 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
