#### Test 8326889394b7a14_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
09-02 12:23:49.183  6588  6588 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:23:49.184  6588  6588 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 12:23:49.184  6588  6588 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 12:23:49.185  6588  6588 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
--------- beginning of main
09-02 12:23:49.290  6588  6588 I AppConfig: Total System Memory = 2995761152
09-02 12:23:49.298  6588  6588 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-02 12:23:49.333  1035  1996 I ActivityManager: Killing 6083:com.android.vending/u0a44 (adj 15): empty #17
09-02 12:23:49.378  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-02 12:23:49.378  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-02 12:23:49.379  1035  1957 W libprocessgroup: failed to open /acct/uid_10044/pid_6083/cgroup.procs: No such file or directory
09-02 12:23:49.386  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-02 12:23:49.424  6446  6446 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-02 12:23:49.431  6446  6446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-02 12:23:49.512  1035  1052 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6613 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:23:49.750  6613  6613 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-02 12:23:49.829   331   420 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-02 12:23:49.831  3344  6646 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-02 12:23:49.835  6613  6613 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:23:49.835  6613  6613 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:23:49.886  6613  6613 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-02 12:23:49.905  6613  6613 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-02 12:23:49.906  6613  6613 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-02 12:23:49.923  6613  6613 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-02 12:23:49.923  6613  6613 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-02 12:23:49.935  1035  1976 I ActivityManager: Killing 5498:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-02 12:23:49.995  1035  1957 W libprocessgroup: failed to open /acct/uid_10085/pid_5498/cgroup.procs: No such file or directory
09-02 12:23:50.005  5051  6651 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-02 12:23:50.044  1035  1052 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6652 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:23:50.058  1035  1996 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:23:50.081  3491  3507 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-02 12:23:50.084  3491  3507 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@37fa5dcf on behalf of 6613
09-02 12:23:50.114  6613  6613 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-02 12:23:50.127  6613  6613 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-02 12:23:50.236  1817  1817 I art     : Explicit concurrent mark sweep GC freed 30017(1868KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 1.699ms total 62.030ms
09-02 12:23:50.252  5051  6651 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 247 ms] updated apps [took 247 ms] 
09-02 12:23:50.310  6652  6652 D DocsApplication: Installing DEX configuration.
09-02 12:23:50.326  6652  6652 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-02 12:23:50.329  6652  6652 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2e01d059 com.google.android.apps.docs}
09-02 12:23:50.344  6652  6652 D TAG     : onCreate()
09-02 12:23:50.361  6652  6652 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-02 12:23:50.557  6683  6683 D AndroidRuntime: 
09-02 12:23:50.557  6683  6683 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 12:23:50.571  6683  6683 D AndroidRuntime: CheckJNI is OFF
09-02 12:23:50.740  6683  6683 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 12:23:50.746  1035  1904 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 12:23:50.756  1941  4426 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-02 12:23:50.761  1035  1904 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-02 12:23:50.762  1035  1904 D ActivityManager: setTaskToReturnTo : TaskRecord{3d5baca2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 12:23:50.762  1035  1904 D ActivityManager: setTaskToReturnTo : TaskRecord{3d5baca2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 12:23:50.764  1035  1904 D WindowStateEx: AppWindowTokenEx init.. 
09-02 12:23:50.765   345   363 E GBMv2   : DFP En is all cleared set to be enabled
09-02 12:23:50.799  1035  1904 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6705 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 12:23:50.801  6683  6683 D AndroidRuntime: Shutting down VM
09-02 12:23:50.818   349   349 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 297us total 15.806ms
09-02 12:23:50.832   349   349 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 12.816ms
09-02 12:23:50.847   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 12.180ms
09-02 12:23:50.863  1941  4426 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-02 12:23:50.863  1941  4426 D SplitWindowPolicy: topRunningActivity=ActivityInfo{325e3025 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 12:23:50.864  1941  4426 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-02 12:23:50.865  1941  4426 D SplitWindowPolicy: topRunningActivity=ActivityInfo{663f5fa co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 12:23:50.909  6705  6705 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-02 12:23:50.982  6705  6705 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-02 12:23:50.989  6705  6705 I LibraryLoader: Loading: webviewchromium
09-02 12:23:50.992  6705  6705 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4438-4441)
09-02 12:23:50.992  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
--------- beginning of crash
09-02 12:23:51.009  6683  6702 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb45a0840 in tid 6702 (Binder_1)
,09-02 12:23:51.016  6705  6705 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {72d021b}
,09-02 12:23:51.017  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:23:51.017  6705  6705 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 12:23:51.025  6705  6705 I BrowserStartupController: Initializing chromium process, renderers=0
09-02 12:23:51.025  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 12:23:51.035   320  2159 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 10118
,09-02 12:23:51.036  6705  6705 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-02 12:23:51.037  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-02 12:23:51.039  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-02 12:23:51.039  1035  1118 D BluetoothManagerService: Message: 20
09-02 12:23:51.039  1035  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@392d141c:true
09-02 12:23:51.053  6705  6705 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:23:51.053  6705  6705 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:23:51.053  6705  6705 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:23:51.053  6705  6705 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:23:51.053  6705  6705 I Adreno-EGL: Remote Branch: 
09-02 12:23:51.053  6705  6705 I Adreno-EGL: Local Patches: 
09-02 12:23:51.053  6705  6705 I Adreno-EGL: Reconstruct Branch: 
,09-02 12:23:51.059   317   317 E DEBUG   : unexpected waitpid response: n=6702, status=00000001
09-02 12:23:51.059   317   317 E         : ptrace detach from 6702 failed: No such process
09-02 12:23:51.059   317   317 E         : debuggerd committing suicide to free the zombie!
09-02 12:23:51.057  6742  6742 W debuggerd: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:debuggerd:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:23:51.057  6742  6742 W debuggerd: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:debuggerd:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:23:51.070  6742  6742 I         : debuggerd: Jan 19 2015 15:59:27
,09-02 12:23:51.151  6705  6740 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-02 12:23:51.158  6705  6705 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-02 12:23:51.172  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:23:51.177  6705  6705 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-02 12:23:51.180  6705  6705 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-02 12:23:51.184  6705  6705 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,09-02 12:23:51.184  6705  6705 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-02 12:23:51.199  6705  6705 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-02 12:23:51.205  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 12:23:51.205  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:23:51.231  6705  6753 D OpenGLRenderer: Render dirty regions requested: true
09-02 12:23:51.231  6705  6753 I OpenGLRenderer: Initialized EGL, version 1.4
09-02 12:23:51.237  6705  6753 D OpenGLRenderer: Enabling debug mode 0
09-02 12:23:51.243  6705  6705 D Atlas   : Validating map...
,09-02 12:23:51.246  1035  1768 D SplitWindow: check instance of lgWin Window{1b371676 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-02 12:23:51.256  1817  5227 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,09-02 12:23:51.276  1817  5227 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,09-02 12:23:51.289  6705  6751 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:23:51.289  6705  6751 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:23:51.314  1817  5227 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-02 12:23:51.369  1035  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +509ms (total +604ms)
,09-02 12:23:51.370  1035  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35ee0d33 u0 com.test.thalitest/.MainActivity t6} time:104820
09-02 12:23:51.371  6705  6705 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10e80ba6 time:104820
09-02 12:23:51.461  6705  6705 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 12:23:51.515  6705  6705 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-02 12:23:51.515  6705  6705 I chromium: 
,09-02 12:23:51.551  6705  6751 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-02 12:23:51.551  6705  6751 I chromium: 
,09-02 12:23:51.678  6705  6773 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435044352
,09-02 12:23:51.686  6705  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 12:23:51.686  6705  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 12:23:51.686  6705  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 12:23:51.686  6705  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 12:23:51.686  6705  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-02 12:23:51.686  6705  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a581f8a added. We now have 1 listener(s)
09-02 12:23:51.689  1035  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:23:51.691  6705  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-02 12:23:51.693  6705  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:23:51.694  6705  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:23:51.694  6705  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 12:23:51.699  6705  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ddcc71 added. We now have 1 listener(s)
09-02 12:23:51.699  6705  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:23:51.702  1035  1407 D WifiService: New client listening to asynchronous messages
,09-02 12:23:51.707  6705  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:23:51.708  6705  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-02 12:23:51.708  6705  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 12:23:51.708  6705  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 12:23:51.709  6705  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-02 12:23:51.713  6705  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:23:51.713  1035  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:23:51.715  6705  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,09-02 12:23:51.724  6705  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:23:51.725  6705  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:23:51.726  6705  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 12:23:51.726  6705  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:23:51.726  6705  6773 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 12:23:51.727  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:23:51.729  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:23:51.765  6705  6705 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 12:23:51.849  6652  6652 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:23:51.849  6652  6652 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:23:52.031  1035  1996 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6783 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-02 12:23:52.032  1035  1996 I ActivityManager: Killing 6154:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-02 12:23:52.121  1035  1917 W libprocessgroup: failed to open /acct/uid_10097/pid_6154/cgroup.procs: No such file or directory
,09-02 12:23:52.126  6652  6652 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-02 12:23:52.184  6783  6783 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-02 12:23:52.197  6783  6783 I LockScreenSettings: New app installed broadcast received ..
,09-02 12:23:52.200  6783  6783 I LockScreenSettings: Number of installed packages  1
09-02 12:23:52.260  1035  1768 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6805 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-02 12:23:52.331  6805  6805 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:23:52.369  6705  6776 W jxcore-log: Initializing JXcore engine
,09-02 12:23:52.369  6705  6776 W jxcore-log: JXcore engine is ready
09-02 12:23:52.380   345   365 E GBMv2   : DFP En is all cleared set to be enabled
09-02 12:23:52.381   345   365 E GBMv2   : Set value is all cleared set the max
09-02 12:23:52.381   345   365 I GBMv2   : DFP Enabled. Ignore VFP set
09-02 12:23:52.397  6776  6776 W Thread-792: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9566]" dev="sockfs" ino=9566 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 12:23:52.397  6776  6776 W Thread-792: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-02 12:23:52.397  6776  6776 W Thread-792: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[8675]" dev="sockfs" ino=8675 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 12:23:52.397  6776  6776 W Thread-792: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-02 12:23:52.397  6776  6776 W Thread-792: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[30148]" dev="sockfs" ino=30148 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-02 12:23:52.416  6705  6776 W jxcore-log: Starting JXcore engine
09-02 12:23:52.493  6705  6776 W jxcore-log: Platform android
09-02 12:23:52.493  6705  6776 W jxcore-log: 
09-02 12:23:52.493  6705  6776 W jxcore-log: Process ARCH arm
09-02 12:23:52.493  6705  6776 W jxcore-log: 
,09-02 12:23:52.580  1035  1052 I art     : Explicit concurrent mark sweep GC freed 29100(1383KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.475ms total 154.110ms
,09-02 12:23:52.678  6705  6776 I jxcore-log: JXcore Cordova bridge is ready!
09-02 12:23:52.678  6705  6776 I jxcore-log: 
09-02 12:23:52.678  6705  6776 W jxcore-log: JXcore engine is started
,09-02 12:23:52.686  6705  6773 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-02 12:23:52.690  6705  6705 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 12:23:52.842  1035  1940 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:23:52.921  1035  1052 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6840 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:23:52.995  6840  6840 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-02 12:23:52.995  6840  6840 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-02 12:23:53.000  5632  5632 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
09-02 12:23:53.019  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-02 12:23:53.059  1035  1052 I ActivityManager: Killing 6178:com.google.android.gm/u0a64 (adj 15): empty #17
,09-02 12:23:53.283  1035  1769 W libprocessgroup: failed to open /acct/uid_10064/pid_6178/cgroup.procs: No such file or directory
,09-02 12:23:55.921  6652  6652 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-02 12:23:55.922  1035  1917 I ActivityManager: Killing 5973:com.google.android.talk/u0a72 (adj 15): empty #17
09-02 12:23:56.011  1035  1996 W libprocessgroup: failed to open /acct/uid_10072/pid_5973/cgroup.procs: No such file or directory
,09-02 12:23:56.924  6652  6777 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-02 12:23:57.810  1035  1904 I ActivityManager: Killing 5754:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-02 12:23:57.827  5730  5730 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-02 12:23:57.828  5730  5730 W System.err: android.os.DeadObjectException
09-02 12:23:57.828  5730  5730 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 12:23:57.828  5730  5730 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 12:23:57.828  5730  5730 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-02 12:23:57.828  5730  5730 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-02 12:23:57.828  5730  5730 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 12:23:57.828  5730  5730 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 12:23:57.828  5730  5730 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:23:57.828  5730  5730 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:23:57.828  5730  5730 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:23:57.828  5730  5730 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:23:57.828  5730  5730 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:23:57.828  5730  5730 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:23:57.829  5730  5730 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:23:57.829  5730  5730 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:23:57.829  5730  5730 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-02 12:23:57.829  5730  5730 W System.err: android.os.DeadObjectException
09-02 12:23:57.829  5730  5730 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 12:23:57.829  5730  5730 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 12:23:57.829  5730  5730 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-02 12:23:57.829  5730  5730 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-02 12:23:57.829  5730  5730 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 12:23:57.829  5730  5730 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 12:23:57.830  5730  5730 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:23:57.830  5730  5730 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:23:57.830  5730  5730 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:23:57.830  5730  5730 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:23:57.830  5730  5730 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:23:57.830  5730  5730 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:23:57.830  5730  5730 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:23:57.830  5730  5730 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:23:57.830  5730  5730 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-02 12:23:57.830  5730  5730 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-02 12:23:58.052  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_5754/cgroup.procs: No such file or directory
09-02 12:23:58.053  1035  1051 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-02 12:23:58.064  5730  5730 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-02 12:23:58.065  5730  5730 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 12:23:58.117  1035  1768 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6868 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 12:23:58.117  5730  5730 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-02 12:23:58.192  6868  6868 D UEI.SmartControl: Quickset Services start...
,09-02 12:23:58.195  1817  6479 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-02 12:23:58.197  6868  6868 I UEI.SmartControl: Manufacture = LGE
09-02 12:23:58.198  6868  6868 D UEI.SmartControl: Id = LGNevo
09-02 12:23:58.199  6868  6868 D UEI.SmartControl: File observer start...
09-02 12:23:58.199  6868  6868 E UEI.SmartControl: IR Port is disabled: false
09-02 12:23:58.199  6868  6868 D UEI.SmartControl: Starting file observer...
09-02 12:23:58.200  6868  6868 D UEI.SmartControl: Extracting JNI libs...
09-02 12:23:58.200  6868  6868 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-02 12:23:58.213   315  6886 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-02 12:23:58.214   315  6886 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-02 12:23:58.214   315  6886 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-02 12:23:58.287  6868  6868 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-02 12:23:58.287  6868  6868 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-02 12:23:58.287  6868  6868 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-02 12:23:58.326  6868  6868 I UEI.SmartControl: --- Selecting new region: 6
,09-02 12:23:58.329  6868  6868 I UEI.SmartControl: Model = LG-D855
09-02 12:23:58.331  6868  6868 D UEI.SmartControl: QS Service created
09-02 12:23:58.348  6868  6868 I UEI.SmartControl: Service initServices...
,09-02 12:23:58.353  6868  6868 D UEI.SmartControl: QS start get config
,09-02 12:23:58.407  6868  6868 D UEI.SmartControl: Loading JNI Libs...
,09-02 12:23:58.444  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
,09-02 12:23:58.445  1817  1817 I ConfigFetchService: stopping self
09-02 12:23:58.451  2211  2211 I ConfigService: onDestroy
09-02 12:23:58.662  2785  2785 I MusicWidget: mDelayedStopHandler : unbind
09-02 12:23:58.666  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-02 12:23:58.667  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-02 12:23:58.667  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,09-02 12:23:58.671  2124  2124 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-02 12:23:58.672  2124  2124 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-02 12:23:58.673  2124  2124 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-02 12:23:58.677  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-02 12:23:58.677  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-02 12:23:58.679  1035  2014 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1b316e8com.lge.music.MediaPlaybackService$5@29aba101
09-02 12:23:58.681  2124  2124 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-02 12:23:58.682  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.684  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.685  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.687  2124  2124 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@b0fa4f7
,09-02 12:23:58.689  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.691  2124  2124 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-02 12:23:58.691  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.692  2124  2124 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-02 12:23:58.692  2124  2124 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-02 12:23:58.692  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.693  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.693  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.694  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.695  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 12:23:58.696  2124  2124 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-02 12:23:58.697  2124  2124 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-02 12:23:58.697  2124  2124 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-02 12:23:58.698  2124  2124 V MediaPlayer[Native]: reset
09-02 12:23:58.704  2124  2124 V MediaPlayer[Native]: setListener
09-02 12:23:58.704  2124  2124 V MediaPlayer[Native]: disconnect
09-02 12:23:58.704  2124  2124 V MediaPlayer[Native]: destructor
09-02 12:23:58.704   320   320 V AudioFlinger: releasing 16 from 2124 for -1
09-02 12:23:58.704   320   320 V AudioFlinger:  decremented refcount to 0
,09-02 12:23:58.704   320   320 V AudioFlinger: purging stale effects
09-02 12:23:58.704  2124  2124 V MediaPlayer[Native]: disconnect
09-02 12:23:58.706  2124  2124 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-02 12:23:58.707  2124  2124 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-02 12:23:58.707  2124  2124 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-02 12:23:58.708  2124  2124 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-02 12:23:58.709  2124  2124 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-02 12:23:58.709  2124  2124 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
,09-02 12:23:58.709  2124  2124 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 283642790
09-02 12:23:58.709  2124  2124 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 283642790
09-02 12:23:58.721  2124  2124 I SmartShareClient: [SmartShareManagerClient] terminate service: 2124/MediaPlaybackService/720771349
09-02 12:23:58.725  2124  2124 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-02 12:23:58.725  2124  2124 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@ebdb9e7
09-02 12:23:58.727  2124  2124 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-02 12:23:58.728  2124  2124 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-02 12:23:58.729  2124  2124 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-02 12:23:58.729  2124  2124 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,09-02 12:23:58.732  1035  1995 I ActivityManager: Killing 5730:com.lge.qremote/u0a112 (adj 15): empty #17
09-02 12:23:58.735  2124  2124 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
09-02 12:23:58.756  6868  6868 I UEI.SmartControl: Supports setup maps: true
,09-02 12:23:58.763  6868  6868 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 12:23:58.763  6868  6868 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 12:23:58.763  6868  6868 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 12:23:58.763  6868  6868 I UEI.SmartControl: ### init IR Blaster...
09-02 12:23:58.768  6868  6868 D serial_port: Configuring serial port
,09-02 12:23:58.773  6868  6868 E UEI.SmartControl: UEIBLaster setting for 616
09-02 12:23:58.773  6868  6868 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 12:23:58.773  6868  6868 I UEI.SmartControl: configuring settings for MAXQ616
09-02 12:23:58.773  6868  6868 I UEI.SmartControl: Get version...
09-02 12:23:58.789  6868  6900 D UEI.SmartControl: serial port data available: 21
,09-02 12:23:58.813  1035  1976 W libprocessgroup: failed to open /acct/uid_10112/pid_5730/cgroup.procs: No such file or directory
,09-02 12:23:58.819  6868  6868 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 12:23:58.819  6868  6868 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 12:23:58.820  6868  6868 I UEI.SmartControl: QS saving settings...
09-02 12:23:58.822  6868  6868 D UEI.SmartControl: IR Blaster version: 25672567
09-02 12:23:58.839  6868  6900 D UEI.SmartControl: serial port data available: 4
,09-02 12:23:58.878  6868  6903 I UEI.SmartControl: Device manager: loading config....
09-02 12:23:58.879  6868  6903 D UEI.SmartControl: ----------- loading internal config...
09-02 12:23:58.880  6868  6868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-02 12:23:58.887  6868  6868 E UEI.SmartControl: Services init done
09-02 12:23:58.887  6868  6868 D UEI.SmartControl: QS Service init finished
09-02 12:23:58.889  6868  6868 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 12:23:58.890  6868  6868 D UEI.SmartControl: QS Service version code: 201091
09-02 12:23:58.891  6868  6868 D UEI.SmartControl: Service requested: Control
09-02 12:23:58.894  6868  6903 E UEI.SmartControl: Loading SETTINGS...
,09-02 12:23:58.897  6868  6868 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 12:23:58.898  6868  6868 D UEI.SmartControl: Service.onUnbind: IControl
09-02 12:23:58.899  6868  6868 D UEI.SmartControl: Service.onDestroy
09-02 12:23:58.899  6868  6868 D UEI.SmartControl: Lock is in USE false
09-02 12:23:58.899  6868  6868 D UEI.SmartControl: unbind internal service
09-02 12:23:58.900  6868  6868 D serial_port: close(fd = 25)
09-02 12:23:58.903  6868  6868 I UEI.SmartControl: Serial port is closed.
09-02 12:23:58.904  6868  6868 I UEI.SmartControl: Serial port is closed.
09-02 12:23:58.904  6868  6868 D UEI.SmartControl: Blaster closed
09-02 12:23:58.904  6868  6868 D UEI.SmartControl: Shut down QS...
09-02 12:23:58.904  6868  6868 D UEI.SmartControl: Stopping QS lib
09-02 12:23:58.904  6868  6868 D UEI.SmartControl: QS lib stop result = true
09-02 12:23:58.904  6868  6868 D UEI.SmartControl: Stopped QS lib
09-02 12:23:58.905  6868  6868 D UEI.SmartControl: Stopped file observer...
09-02 12:23:58.905  6868  6868 D UEI.SmartControl: QS shutdown complete
09-02 12:23:58.906  6868  6868 D UEI.SmartControl: QS Service created
09-02 12:23:58.908  6868  6903 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-02 12:23:58.916  6868  6902 I UEI.SmartControl: Notify AllClients services are ready: 11
,09-02 12:23:58.916  6868  6902 D UEI.SmartControl: -----service ready thread exits
09-02 12:23:58.923  6868  6868 I UEI.SmartControl: Service initServices...
09-02 12:23:58.923  6868  6868 D UEI.SmartControl: QS start get config
09-02 12:23:59.239  6868  6868 I UEI.SmartControl: Supports setup maps: true
,09-02 12:23:59.243  6868  6868 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 12:23:59.243  6868  6868 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 12:23:59.244  6868  6868 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 12:23:59.244  6868  6868 I UEI.SmartControl: ### init IR Blaster...
09-02 12:23:59.248  6868  6868 D serial_port: Configuring serial port
09-02 12:23:59.248  6868  6868 E UEI.SmartControl: UEIBLaster setting for 616
09-02 12:23:59.248  6868  6868 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 12:23:59.248  6868  6868 I UEI.SmartControl: configuring settings for MAXQ616
09-02 12:23:59.248  6868  6868 I UEI.SmartControl: Get version...
09-02 12:23:59.264  6868  6909 D UEI.SmartControl: serial port data available: 21
,09-02 12:23:59.292  6868  6868 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 12:23:59.292  6868  6868 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 12:23:59.292  6868  6868 I UEI.SmartControl: QS saving settings...
09-02 12:23:59.293  6868  6868 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 12:23:59.307  6868  6909 D UEI.SmartControl: serial port data available: 4
,09-02 12:23:59.337  6868  6868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-02 12:23:59.340  6868  6868 E UEI.SmartControl: Services init done
09-02 12:23:59.340  6868  6868 D UEI.SmartControl: QS Service init finished
,09-02 12:23:59.347  6868  6912 I UEI.SmartControl: Device manager: loading config....
09-02 12:23:59.348  6868  6912 D UEI.SmartControl: ----------- loading internal config...
09-02 12:23:59.359  6868  6912 E UEI.SmartControl: Loading SETTINGS...
09-02 12:23:59.361  6868  6868 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 12:23:59.361  6868  6868 D UEI.SmartControl: QS Service version code: 201091
,09-02 12:23:59.364  6868  6868 D UEI.SmartControl: Service requested: Control
09-02 12:23:59.367  1035  1574 I ActivityManager: Killing 5678:com.android.calendar/u0a13 (adj 15): empty #17
09-02 12:23:59.369  6868  6912 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 12:23:59.385  6868  6911 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 12:23:59.385  6868  6911 D UEI.SmartControl: -----service ready thread exits
,09-02 12:23:59.453  1035  1940 W libprocessgroup: failed to open /acct/uid_10013/pid_5678/cgroup.procs: No such file or directory
,09-02 12:23:59.459  6868  6868 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@b0fa4f7 that was originally bound here
09-02 12:23:59.459  6868  6868 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@b0fa4f7 that was originally bound here
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:23:59.459  6868  6868 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:23:59.460  6868  6868 D UEI.SmartControl: Internal service binding...
09-02 12:23:59.901  6868  6905 D UEI.SmartControl: Internal timer expired: 2
,09-02 12:24:00.000  1035  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=538773828, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-02 12:24:00.051  2575  2575 D [Concierge]Service: onStartCommand(). Type : 9
,09-02 12:24:00.061  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-02 12:24:00.061  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
09-02 12:24:00.061  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-02 12:24:00.061  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
09-02 12:24:00.067  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
09-02 12:24:00.067  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-02 12:24:00.067  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-02 12:24:00.068  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,09-02 12:24:00.144  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=538773828 [*alarm*], flags=0x0
,09-02 12:24:00.154  4959  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-02 12:24:03.190  6868  6879 E UEI.SmartControl: file observer is disposed!
,09-02 12:24:03.250  1035  1105 I ActivityManager: Waited long enough for: ServiceRecord{80ab0bf u0 com.google.android.gms/.wearable.service.WearableService}
,09-02 12:24:04.055  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 12:24:04.055  6705  6776 I jxcore-log: 
,09-02 12:24:04.058  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 12:24:04.058  6705  6776 I jxcore-log: 
,09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:04.063  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:04.066  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.068  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 12:24:04.068  6705  6776 I jxcore-log: 
09-02 12:24:04.070  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 12:24:04.070  6705  6776 I jxcore-log: 
09-02 12:24:04.337  6868  6913 D UEI.SmartControl: Internal timer expired: 3
09-02 12:24:04.337  6868  6913 D UEI.SmartControl: unbind internal service
,09-02 12:24:04.348  6868  6868 D UEI.SmartControl: Service.onUnbind: IControl
09-02 12:24:04.361  6868  6868 D UEI.SmartControl: Service.onDestroy
09-02 12:24:04.361  6868  6868 D UEI.SmartControl: Lock is in USE false
09-02 12:24:04.361  6868  6868 D UEI.SmartControl: unbind internal service
09-02 12:24:04.362  6868  6868 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3c9ab0ce
09-02 12:24:04.362  6868  6868 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-02 12:24:04.363  6868  6868 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-02 12:24:04.363  6868  6868 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-02 12:24:04.363  6868  6868 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-02 12:24:04.363  6868  6868 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-02 12:24:04.363  6868  6868 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-02 12:24:04.363  6868  6868 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-02 12:24:04.363  6868  6868 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-02 12:24:04.363  6868  6868 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:24:04.363  6868  6868 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,09-02 12:24:04.364  6868  6868 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:24:04.364  6868  6868 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:24:04.364  6868  6868 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:24:04.364  6868  6868 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:24:04.364  6868  6868 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-02 12:24:04.364  6868  6868 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3c9ab0ce
,09-02 12:24:04.401  6868  6868 D serial_port: close(fd = 24)
,09-02 12:24:04.440  6868  6868 I UEI.SmartControl: Serial port is closed.
,09-02 12:24:04.445  6868  6868 I UEI.SmartControl: Serial port is closed.
,09-02 12:24:04.445  6868  6868 D UEI.SmartControl: Blaster closed
09-02 12:24:04.445  6868  6868 D UEI.SmartControl: Shut down QS...
09-02 12:24:04.445  6868  6868 D UEI.SmartControl: Stopping QS lib
09-02 12:24:04.446  6868  6868 D UEI.SmartControl: QS lib stop result = true
09-02 12:24:04.446  6868  6868 D UEI.SmartControl: Stopped QS lib
09-02 12:24:04.446  6868  6868 D UEI.SmartControl: QS shutdown complete
09-02 12:24:04.584  6705  6776 D executeNativeTests: Running unit tests
,09-02 12:24:04.668  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:04.668  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda added. We now have 2 listener(s)
,09-02 12:24:04.668  1035  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:04.670  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:04.670  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:04.670  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:04.670  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:04.670  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b added. We now have 2 listener(s)
09-02 12:24:04.670  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:04.671  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:24:04.673  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:04.677  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:04.679  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.679  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:24:04.681  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:04.682  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:04.688  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:24:04.688  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:24:04.688  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:24:04.694  6705  6776 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-02 12:24:04.696  6705  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:24:04.696  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:24:04.697  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:24:04.697  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:24:04.698  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.700  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.700  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.701  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.701  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.702  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:04.702  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:04.702  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda removed from the list
09-02 12:24:04.702  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.702  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b removed from the list
09-02 12:24:04.702  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.702  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.703  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.703  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.704  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.704  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.704  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.704  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.709  6705  6776 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-02 12:24:04.710  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.710  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.711  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.711  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.711  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.711  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.711  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.711  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.711  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.711  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.711  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.711  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.711  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.711  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.712  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.712  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.712  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.712  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemov,eAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:24:04.717  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:24:04.718  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.718  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:24:04.718  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.718  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.718  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.718  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.718  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.718  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.718  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.718  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:24:04.718  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.718  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.718  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.718  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-02 12:24:04.719  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.719  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.719  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.719  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
,09-02 12:24:04.719  6705  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:24:04.720  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,09-02 12:24:04.723  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:04.724  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:24:04.724  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:24:04.725  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:04.726  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:04.727  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-02 12:24:04.727  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:24:04.727  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 12:24:04.727  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:04.727  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:24:04.730  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:24:04.731  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:04.735  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:24:04.739  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:24:04.741  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
09-02 12:24:04.742  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:24:04.742  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:04.743  6705  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:24:04.744  6705  6776 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:24:04.746  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.746  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.746  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:24:04.746  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.746  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.746  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:04.746  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.746  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.746  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.746  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.746  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.747  6705  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:24:04.748  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:04.750  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:04.751  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.751  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:24:04.752  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-02 12:24:04.753  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:04.754  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:24:04.754  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:24:04.754  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 12:24:04.754  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:04.754  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:24:04.757  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:24:04.757  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:04.758  6705  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:24:04.758  6705  6776 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 12:24:04.759  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.759  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.759  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.759  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.759  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.759  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:24:04.760  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.760  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.760  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.760  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.760  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.760  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:04.760  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.761  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.761  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.762  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.762  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.762  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:24:04.762  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.763  6705  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:24:04.764  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:04.766  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:04.767  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.767  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:24:04.768  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:24:04.768  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:24:04.768  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:24:04.768  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:04.768  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:24:04.769  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:04.771  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:04.773  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:24:04.773  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:04.774  6705  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:24:04.774  6705  6776 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:24:04.774  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:24:04.774  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.774  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.775  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.775  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.775  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:24:04.775  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.775  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.775  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:04.775  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.775  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.775  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
,09-02 12:24:04.775  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.775  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.776  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.776  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.776  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:24:04.777  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.777  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.777  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.777  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.777  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.777  6705  6776 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-02 12:24:04.778  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.778  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.778  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.778  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.778  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.778  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.778  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.778  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.778  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.778  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:24:04.778  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.778  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.778  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.778  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.779  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.779  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:24:04.779  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.779  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.779  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.779  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.780  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:24:04.780  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:24:04.780  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.780  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.781  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.781  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.781  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.781  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.781  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.781  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.781  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.781  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.781  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.781  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.781  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.782  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.782  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.782  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.782  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.782  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.782  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
,09-02 12:24:04.783  6705  6776 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 12:24:04.783  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.783  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.783  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.784  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.784  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:04.784  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.784  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.784  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.784  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.784  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.784  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.784  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.784  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.784  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.784  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.785  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.785  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.785  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 12:24:04.785  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.785  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.785  6705  6776 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 12:24:04.786  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.786  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.786  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.786  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.786  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.786  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.786  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.786  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.786  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.786  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.786  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-02 12:24:04.786  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.786  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.786  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.787  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.787  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:24:04.787  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.787  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.788  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.788  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.788  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:24:04.789  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:24:04.789  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 12:24:04.789  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:24:04.789  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:24:04.789  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:24:04.789  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.789  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.790  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:24:04.790  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.790  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.790  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.790  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.790  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.790  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
,09-02 12:24:04.790  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.790  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.790  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.790  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.790  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.792  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:24:04.792  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.793  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.793  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.793  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.793  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.793  6705  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:24:04.793  6705  6776 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-02 12:24:04.793  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:24:04.797  6705  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:24:04.797  6705  6776 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:24:04.797  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:24:04.798  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-02 12:24:04.798  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:24:04.798  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:24:04.798  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:24:04.798  6705  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 12:24:04.798  6705  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:24:04.798  6705  6776 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 12:24:04.800  6705  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-02 12:24:04.800  6705  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:24:04.800  6705  6776 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 12:24:04.800  6705  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:24:04.800  6705  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:24:04.800  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-02 12:24:04.802  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
09-02 12:24:04.802  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 12:24:04.802  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 12:24:04.803  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 12:24:04.803  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 12:24:04.803  6705  6776 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 12:24:04.804  6705  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:24:04.804  6705  6776 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 12:24:04.804  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.804  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.804  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.805  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.805  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.805  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.805  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 12:24:04.806  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.806  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.806  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
,09-02 12:24:04.806  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.806  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.806  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.806  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.806  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.807  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.807  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.807  6705  6967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 856)
09-02 12:24:04.807  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.807  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.807  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.807  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.808  6705  6776 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 12:24:04.808  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.808  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.808  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.808  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.808  6705  6968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 856
,09-02 12:24:04.808  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.808  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.808  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.808  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.808  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.808  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.808  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.808  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.808  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.808  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.809  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.809  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.809  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.809  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.809  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.809  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.810  6705  6776 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 12:24:04.813  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:24:04.813  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:24:04.813  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:24:04.813  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.813  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.813  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.813  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.813  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.813  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.813  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.813  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.813  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.813  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.813  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.815  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.815  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:24:04.815  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.815  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 12:24:04.815  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:24:04.815  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.817  6705  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 12:24:04.817  6705  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-02 12:24:04.817  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:24:04.818  6705  6776 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 12:24:04.818  6705  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-02 12:24:04.818  6705  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 12:24:04.818  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:24:04.819  6705  6776 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-02 12:24:04.819  6705  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:24:04.819  6705  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:24:04.819  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-02 12:24:04.819  6705  6776 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 12:24:04.819  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.820  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:24:04.820  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.820  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.820  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:04.820  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.820  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
,09-02 12:24:04.820  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.821  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.821  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:24:04.821  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.821  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.821  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:04.821  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.831  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.831  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 12:24:04.832  6705  6776 D BluetoothLeScanner: could not find callback wrapper
,09-02 12:24:04.832  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.832  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.832  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
,09-02 12:24:04.832  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.832  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.832  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.832  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.832  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.832  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list,
09-02 12:24:04.832  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.832  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:04.832  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.833  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.833  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
,09-02 12:24:04.833  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.834  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.834  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:04.835  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.835  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.835  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:24:04.835  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.836  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:24:04.836  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.836  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.836  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
,09-02 12:24:04.836  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.836  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.836  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:24:04.836  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.838  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.838  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.838  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.839  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.839  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.840  6705  6776 D BluetoothLeScanner: could not find callback wrapper
,09-02 12:24:04.840  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.840  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.840  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.842  6705  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 12:24:04.843  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:04.844  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 12:24:04.845  6705  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-02 12:24:04.845  6705  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 12:24:04.845  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 12:24:04.845  6705  6705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 12:24:04.846  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 12:24:04.848  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.849  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 12:24:04.849  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 12:24:04.849  1035  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:04.850  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 12:24:04.850  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.851  6705  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 12:24:04.851  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.851  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.851  6705  6705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 12:24:04.851  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:24:04.851  6705  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:24:04.851  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:24:04.852  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:24:04.853  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:04.853  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:04.853  6705  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:24:04.853  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.853  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.854  6705  6970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:04.855  6705  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:24:04.855  4279  4299 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-02 12:24:04.855  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.855  6705  6705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:24:04.856  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.856  6705  6705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:24:04.856  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.856  6705  6705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:24:04.856  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.856  6705  6776 I o,rg.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.856  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.856  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.856  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.856  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.857  6705  6970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 12:24:04.857  6705  6970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 12:24:04.857  6705  6970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 12:24:04.857  6705  6705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 12:24:04.858  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.858  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.859  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.859  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.859  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.859  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.860  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.860  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.860  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.860  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.862  6705  6776 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 12:24:04.862  6705  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:24:04.862  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:24:04.864  6705  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:24:04.865  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.865  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.865  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.865  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.866  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.866  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.866  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.866  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.866  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.866  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.866  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.866  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.866  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.866  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.868  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.868  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.868  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.868  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.870  1035  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:04.871  1035  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:04.873  1035  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:04.873  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.874  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.874  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.874  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.874  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.874  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.874  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.874  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.874  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.874  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.874  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.874  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.874  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.874  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.875  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.875  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.875  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.875  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.876  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:04.877  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:04.877  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:04.877  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:04.877  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.877  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.877  6705  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f4ffda not in the list
09-02 12:24:04.877  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.877  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.877  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:04.877  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.877  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.877  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:04.877  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:04.878  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:04.878  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:04.878  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:04.878  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e18c0b not in the list
09-02 12:24:04.880  6705  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 12:24:04.881  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:24:04.881  6705  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 12:24:04.881  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:24:04.881  6705  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 12:24:04.881  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:24:04.892  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-02 12:24:04.892  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 12:24:04.893  6705  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 12:24:04.894  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:24:04.894  6705  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 12:24:04.894  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:24:04.894  6705  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 12:24:04.894  6705  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 12:24:04.895  6705  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 12:24:04.895  6705  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 12:24:04.896  6705  6776 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 12:24:04.896  6705  6776 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 12:24:04.896  6705  6776 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 12:24:04.896  6705  6776 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 12:24:04.898  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:04.898  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33c16f00 added. We now have 2 listener(s)
09-02 12:24:04.898  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:04.900  6705  6776 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 12:24:04.902  1035  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:24:04.902  1035  1052 D WifiService: setWifiEnabled: true pid=6705, uid=10118
09-02 12:24:04.902  1035  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:24:04.904  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:04.904  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@132e7339 added. We now have 3 listener(s)
09-02 12:24:04.904  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:04.909  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:04.909  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28f89d7e added. We now have 4 listener(s)
09-02 12:24:04.909  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:04.911  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:04.911  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f4ba2df added. We now have 5 listener(s)
09-02 12:24:04.911  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:04.914  1035  2042 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:24:04.914  1035  2042 D WifiService: setWifiEnabled: false pid=6705, uid=10118
09-02 12:24:04.914  1035  2042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:24:04.929  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:24:04.930  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:04.930  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-02 12:24:04.931  1035  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:04.931  1035  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:04.931  1035  1768 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21fbec5e mBinding = false
09-02 12:24:04.931  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:04.932  1035  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:04.933  1035  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:04.933  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:04.933  1035  1392 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 12:24:04.933  1035  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:24:04.933  1035  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:24:04.934  1035  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:24:04.934  1035  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:24:04.942  6705  6967 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-02 12:24:04.942  6705  6967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:24:04.942  1035  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:24:04.942  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:04.943  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:04.943  4279  4299 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:04.943  4279  4561 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-02 12:24:04.943  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:24:04.943  2719  2719 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:24:04.944  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:24:04.944  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:24:04.945  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:24:04.945  1035  2859 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:04.945   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:24:04.948  1035  1118 D BluetoothManagerService: Message: 2
09-02 12:24:04.952  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:24:04.952  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:04.952  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-02 12:24:04.954  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:04.954  1035  1118 D BluetoothManagerService: Sending off request.
,09-02 12:24:04.956  4279  4492 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 12:24:04.957  4279  4404 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 12:24:04.957  4279  4404 D BluetoothAdapterProperties: Setting state to 13
09-02 12:24:04.957  4279  4404 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:24:04.958  4279  4404 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:24:04.958  4279  4404 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 12:24:04.958  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:04.958  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:24:04.959  4279  4417 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:24:04.959  4279  4404 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 12:24:04.960  4279  4790 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:04.961  6705  6967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 856)
09-02 12:24:04.961  4279  4719 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:04.961  4279  4768 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:04.961  4279  4404 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:24:04.961  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 12:24:04.962  4279  4561 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 12:24:04.962  4279  4786 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:04.962  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:04.962  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.963  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 12:24:04.963  4279  4718 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 12:24:04.964  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 12:24:04.965  4279  4561 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 12:24:04.969  6705  6705 W org.thaliproject.p2p.btconnect,orlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:04.969  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:24:04.975  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:04.975  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 12:24:04.975  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 12:24:04.979  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:04.979  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.991  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:04.995  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:04.995  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:04.995  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:04.995  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:04.997  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:04.997  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 12:24:04.998  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-02 12:24:04.998  1035  1904 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-02 12:24:04.999  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:04.999  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:04.999  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-02 12:24:04.999  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:04.999  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-02 12:24:05.019  1035  1105 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6976 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-02 12:24:05.033  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-02 12:24:05.035  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.036  4279  4279 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.036  4279  4279 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:24:05.036  4279  4279 V BtOppService: Receiver DISABLED_ACTION 
09-02 12:24:05.036  4279  4279 V BluetoothMapService: Handler(): got msg=4
09-02 12:24:05.037  4279  4279 D BluetoothMapService: MAP Service closeService in
09-02 12:24:05.037  4279  4279 D BluetoothMapMasInstance: MAP Service shutdown
09-02 12:24:05.038  4279  4279 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:24:05.038  4279  4279 V BluetoothMapService: MAP Service closeService out
09-02 12:24:05.038  4279  4279 I BtOppRfcommListener: stopping Accept Thread
09-02 12:24:05.038  4279  4279 V BtOppRfcommListener: close mBtServerSocket
09-02 12:24:05.039  4279  4279 V BtOppRfcommListener: waiting for thread to terminate
09-02 12:24:05.039  4279  4768 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 12:24:05.039  4279  4279 V BtOppRfcommListener: done waiting for thread to terminate
09-02 12:24:05.040  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:05.040  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:05.042  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.042  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:05.043  1035  1432 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 12:24:05.043  1035  1432 D DSQN    : disableDataServiceNotify
09-02 12:24:05.043  1035  1432 D DSQN    : stop dsqn bin
09-02 12:24:05.044  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:05.044  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi:, true
09-02 12:24:05.045  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.045  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:05.045   315  6995 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 12:24:05.046  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-02 12:24:05.046  1035  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-02 12:24:05.049  1035  1432 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 12:24:05.049  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:05.049  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:05.049  1035  1432 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:05.050  1035  1432 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 12:24:05.050  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.050  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.051  1035  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 12:24:05.051  1035  1432 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 12:24:05.051  1035  1432 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 12:24:05.051  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:24:05.051  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 12:24:05.078  1035  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6996 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:24:05.079  1035  1432 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:05.079  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:24:05.079  1035  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.079  1035  1432 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:05.080  1035  1432 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:05.080  1035  1432 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:05.080  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.080  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.080  1035  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.080  1035  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.081  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.081  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.081  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@274b2831
09-02 12:24:05.081  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.081  1035  1432 D NetworkManagementService: Removing idletimer
09-02 12:24:05.081  4279  4279 V BtOppService: onDestroy
09-02 12:24:05.082  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:05.082  1035  1432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.082  1035  1392 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:24:05.082  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:24:05.082  1035  1432 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 12:24:05.082  1035  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.082  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.083  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:05.083  1035  1392 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:05.083  1035  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:05.087  1035  1390 D LGWifiP2pService: P2pDisablingState
09-02 12:24:05.087  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-02 12:24:05.088  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.088  1035  1390 D LGWifiP2pService: p2p socket connection lost
09-02 12:24:05.088  1035  1390 D LGWifiP2pService: P2pDisabledState
09-02 12:24:05.089  1035  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 12:24:05.089  1035  1392 D WifiN,ative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:24:05.089  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.089  1035  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.089  2719  2719 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:24:05.090  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:24:05.090  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:24:05.090  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 12:24:05.090  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:24:05.090   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:24:05.091  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.091  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.091  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:05.091  1035  1035 D WifiHS20: hidePasspointNotification off =false
,09-02 12:24:05.096  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.096  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.096  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:05.097  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 12:24:05.097  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-02 12:24:05.097  1035  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.097  1035  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.099  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:24:05.100  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 12:24:05.101  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:24:05.101  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:24:05.101  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:24:05.102  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:24:05.102  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 12:24:05.102  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:24:05.102  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:24:05.102  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:24:05.103  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:24:05.103  1941  1941 D WfdsService: WifiP2pState is changed : false
09-02 12:24:05.104  1941  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 12:24:05.104  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:05.104  1941  2345 D WfdsService: Set the WFDS Monitor: false
,09-02 12:24:05.104  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:24:05.106  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:24:05.106  1941  2345 D WfdsService: STATE : WfdsDisabledState - enter
09-02 12:24:05.106  1941  2773 D CtrlSupplicant: Received on exit socket, terminate
09-02 12:24:05.106  1941  2773 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 12:24:05.106  1941  2773 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 12:24:05.106  1941  2773 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 12:24:05.106  1941  2349 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 12:24:05.107  1035  1392 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 12:24:05.107  1941  2345 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 12:24:05.107  4279  4279 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 12:24:05.107  1035  1392 D WifiNative-p2p0: TERMINATE: returned true
09-02 12:24:05.108  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:05.108  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:05.108  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:24:05.108  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.109  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-02 12:24:05.111  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.111  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.111  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:05.117  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-02 12:24:05.121  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 12:24:05.121  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:05.121  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 12:24:05.121  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:05.121  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:05.121  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.122  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:05.124  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:05.124  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:05.126  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:05.126  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:24:05.139  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:05.139  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:05.144  6996  6996 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:05.144  6996  6996 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-02 12:24:05.144  6996  6996 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:05.144  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.144  6996  6996 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-02 12:24:05.145  6996  6996 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 12:24:05.146  6996  6996 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 12:24:05.154  1035  2859 D DhcpStateMachine: StoppedState
09-02 12:24:05.154  1035  2859 D DhcpStateMachine: StoppedState{ when=-64ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:05.156  1035  1392 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 12:24:05.156  1035  1392 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-02 12:24:05.162  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:24:05.163  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.164  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.171  2719  2719 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 12:24:05.172  2719  2719 I wpa_supplicant: monitor socket send errors count : 1
09-02 12:24:05.172  2719  2719 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,09-02 12:24:05.173  1035  2767 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,09-02 12:24:05.173  1035  2767 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 12:24:05.182  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:24:05.183  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.183  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.184  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 12:24:05.184  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:05.185  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.187  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.187  6976  6976 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-02 12:24:05.188  6976  6976 W LG Account v2.2: No ProfileInfo entries
09-02 12:24:05.188  6976  6976 I LG Account v2.2: isEnabled: false
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Country: EU
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Operator: OPEN
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Ranking support: false
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Comfort support: false
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Accessory: true
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Health device: true
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Extra Pedometer: false
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Blood glucose device: false
09-02 12:24:05.188  6976  6976 I Feature : [Lifetracker]Device Number: 3
09-02 12:24:05.196  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:05.234  1035  1574 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7016 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:24:05.236  1035  1574 I ActivityManager: Killing 6236:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-02 12:24:05.271  2719  2719 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 12:24:05.272  1035  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 12:24:05.272  1035  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:24:05.272  2719  2719 W wpa_supplicant: USIM:  scard_deinit function
09-02 12:24:05.273  1035  2767 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:24:05.274  1035  2767 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 12:24:05.274  1035  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:05.274  1035  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:05.275  1035  1118 D Tethering: InitialState.processMessage what=4
09-02 12:24:05.275  1035  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118708
09-02 12:24:05.276  1035  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118709
09-02 12:24:05.277  1035  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118710  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:24:05.278  1035  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:24:05.302  1035  1645 W libprocessgroup: failed to open /acct/uid_10014/pid_6236/cgroup.procs: No such file or directory
,09-02 12:24:05.313  2719  2719 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 12:24:05.313  1035  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 12:24:05.313  1035  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 12:24:05.314  1035  2767 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-02 12:24:05.316  1035  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-02 12:24:05.317  1035  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:24:05.356  6705  6705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:24:05.373  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-02 12:24:05.380  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:05.381  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:05.385  1035  1769 I ActivityManager: Killing 6308:com.android.defcontainer/u0a4 (adj 15): empty #17
09-02 12:24:05.390  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 12:24:05.424  1035  1768 W libprocessgroup: failed to open /acct/uid_10004/pid_6308/cgroup.procs: No such file or directory
,09-02 12:24:05.427  1035  1392 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 12:24:05.427  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:05.427  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:05.427  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:24:05.428  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-02 12:24:05.428  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 12:24:05.428  1941  2345 D WfdsService: Set the WFDS Monitor: false
09-02 12:24:05.428  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:24:05.429  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:24:05.429  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 12:24:05.429  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:05.430  1035  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 12:24:05.430  1035  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 12:24:05.431  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:05.431  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:05.432  4279  4279 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:24:05.432  4279  4279 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.432  4279  4279 V BluetoothPbapReceiver: ***********state = 13
09-02 12:24:05.434  4279  4279 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-02 12:24:05.434  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:05.434  4279  4279 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.435  4279  4279 V BluetoothPbapService: state: 13
,09-02 12:24:05.435  4279  4279 V BluetoothPbapService: Pbap Service closeService in
09-02 12:24:05.438  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:05.438  4279  4279 V BluetoothPbapService: successfully stopped pbap service
09-02 12:24:05.438  4279  4279 V BluetoothPbapService: Pbap Service closeService out
09-02 12:24:05.439  4279  4279 V BluetoothPbapService: Pbap Service onDestroy
09-02 12:24:05.439  4279  4279 V BluetoothPbapService: Pbap Service closeService in
09-02 12:24:05.439  4279  4279 V BluetoothPbapService: Pbap Service closeService out
09-02 12:24:05.439  4279  4279 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-02 12:24:05.442  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:05.470  6996  6996 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:24:05.470  6996  6996 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:24:05.477  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:24:05.483  1035  1118 D BluetoothManagerService: Message: 20
09-02 12:24:05.483  1035  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fb17ad1:true
,09-02 12:24:05.491  1035  1118 D BluetoothManagerService: Message: 30
09-02 12:24:05.496  1035  1118 D BluetoothManagerService: Message: 30
09-02 12:24:05.498  6996  6996 D LocalBluetoothProfileManager: Adding local MAP profile
,09-02 12:24:05.499  6996  6996 D BluetoothMap: Create BluetoothMap proxy object
,09-02 12:24:05.500  1035  1118 D BluetoothManagerService: Message: 30
09-02 12:24:05.503  1035  1118 D BluetoothManagerService: Message: 30
09-02 12:24:05.505  6996  6996 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-02 12:24:05.506  6996  6996 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-02 12:24:05.518  6996  6996 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-02 12:24:05.525  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-02 12:24:05.541  6996  6996 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:24:05.551  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 12:24:05.555  6996  6996 D BluetoothInputDevice: Proxy object connected
09-02 12:24:05.556  6996  6996 D HidProfile: Bluetooth service connected
09-02 12:24:05.558  6996  6996 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:24:05.559  6996  6996 D PanProfile: Bluetooth service connected
09-02 12:24:05.560  6996  6996 D BluetoothMap: Proxy object connected
09-02 12:24:05.560  6996  6996 D MapProfile: Bluetooth service connected
09-02 12:24:05.561  6996  6996 D BluetoothMap: getConnectedDevices()
09-02 12:24:05.561  6996  6996 D BluetoothMap: Bluetooth is Not enabled
09-02 12:24:05.561  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 12:24:05.564  6996  6996 D BluetoothPermissionRequest: onReceive
09-02 12:24:05.569  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 12:24:05.577  1035  1574 I ActivityManager: Killing 6484:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-02 12:24:05.582  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 12:24:05.630  1035  1392 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
,09-02 12:24:05.632  1035  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-02 12:24:05.646  4279  4279 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 12:24:05.647  4279  4279 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 12:24:05.647  1035  2014 W libprocessgroup: failed to open /acct/uid_10008/pid_6484/cgroup.procs: No such file or directory
,09-02 12:24:05.652  4279  4279 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 12:24:05.770  1035  1996 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7047 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-02 12:24:05.771  4279  4279 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.771  4279  4279 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 12:24:05.776  4279  4279 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:24:05.776  4279  4279 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.777  4279  4279 V BluetoothFtpService: Ftp Service closeService
09-02 12:24:05.777  4279  4279 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 12:24:05.780  4279  4279 V BluetoothFtpService: successfully stopped ftp service
09-02 12:24:05.781  4279  4279 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:05.781  4279  4279 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:05.781  4279  4279 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:05.781  4279  4279 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.781  4279  4279 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 12:24:05.781  4279  4279 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:24:05.782  4279  4279 V BluetoothFtpService: Ftp Service onDestroy
09-02 12:24:05.782  4279  4279 V BluetoothFtpService: Ftp Service closeService
,09-02 12:24:05.848  1035  2014 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7064 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:24:05.863  4279  4279 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:05.863  4279  4279 V BluetoothSapService: state: 13
09-02 12:24:05.863  4279  4279 V BluetoothSapService: Stopping SAP server process
,09-02 12:24:05.866  4279  4279 V BluetoothSapService: Sap Service closeSapService in
09-02 12:24:05.866  4279  4279 V BluetoothSapService: Close listen Socket : 
09-02 12:24:05.866  4279  4279 V BluetoothSapService: Close rfcomm Socket : 
09-02 12:24:05.866  4279  4279 V BluetoothSapService: Close sapd  Socket : 
09-02 12:24:05.867  4279  4279 V BluetoothSapService: Sap Service closeSapService out
09-02 12:24:05.868  4279  4279 V BluetoothSapService: Sap Service onDestroy
09-02 12:24:05.868  4279  4279 V BluetoothSapService: Sap Service closeSapService in
09-02 12:24:05.868  4279  4279 V BluetoothSapService: Close listen Socket : 
09-02 12:24:05.868  4279  4279 V BluetoothSapService: Close rfcomm Socket : 
09-02 12:24:05.868  4279  4279 V BluetoothSapService: Close sapd  Socket : 
09-02 12:24:05.869  4279  4279 V BluetoothSapService: Sap Service closeSapService out
09-02 12:24:05.893  7047  7047 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 12:24:05.918  7047  7047 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-02 12:24:05.922  7064  7064 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:05.942  1035  1769 I ActivityManager: Killing 6522:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-02 12:24:05.954  7047  7047 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-02 12:24:05.954  7047  7047 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 12:24:05.955  7047  7047 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-02 12:24:05.955  7047  7047 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-02 12:24:05.955  7047  7047 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-02 12:24:05.957  7047  7047 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-02 12:24:05.963  7047  7047 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-02 12:24:05.968  4279  4417 D bt_hci_bdroid: cleanup
09-02 12:24:05.969  4279  4704 I bt_userial_mct: exiting userial_read_thread
,09-02 12:24:05.969  4279  4704 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 12:24:05.969  4279  4417 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 12:24:05.969  4279  4563 I bt_lpm  : LPM is already off!!!
09-02 12:24:05.969  4279  4561 W bt-btif : ag scb idx 1 not allocated
,09-02 12:24:05.969  4279  4563 I bt_vendor: hw_epilog_process
09-02 12:24:05.969  4279  4561 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:24:05.969  4279  4561 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:05.970  4279  4561 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:05.970  4279  4561 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 12:24:05.970  4279  4417 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 12:24:05.970  4279  4417 D bt_userial_mct: userial_close
09-02 12:24:05.970  4279  4417 E bt_userial_mct: pthread_join() FAILED result:3
09-02 12:24:05.970  4279  4417 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 12:24:05.983  1035  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_6522/cgroup.procs: No such file or directory
,09-02 12:24:05.995  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:06.002  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:06.033  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:24:06.038  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:06.042  7047  7047 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-02 12:24:06.045  7047  7047 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-02 12:24:06.046  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:24:06.046  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:06.046  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:06.054  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:06.061  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:06.061  4279  4417 D bt_hci_bdroid: set_power 0
09-02 12:24:06.061  4279  4417 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 12:24:06.061  4279  4417 I bt_vendor: bluetooth satus is on
09-02 12:24:06.061  4279  4417 I bt_vendor: bt-vendor : resetting BT status
09-02 12:24:06.061  4279  4417 I bt_vendor: Starting hciattach daemon
09-02 12:24:06.061  4279  4417 I bt_vendor: try to set false
09-02 12:24:06.062  4279  4417 I bt_vendor: Starting hciattach daemon
09-02 12:24:06.062  4279  4417 I bt_vendor: try to set false
09-02 12:24:06.063  4279  4417 I bt_vendor: cleanup
09-02 12:24:06.064  4279  4561 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 12:24:06.064  4279  4417 I GKI_LINUX: GKI_exit_task 0 done
09-02 12:24:06.064  4279  4417 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 12:24:06.065  4279  4404 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 12:24:06.070  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:06.070  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:06.075  4279  4279 D HeadsetService: Received stop request...Stopping profile...
09-02 12:24:06.076  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:24:06.076  4279  4279 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:24:06.076  4279  4279 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:24:06.076  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b04fb8
09-02 12:24:06.076  4279  4474 D HeadsetStateMachine: Exit Disconnected: -1
09-02 12:24:06.084  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:06.084  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:06.084  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 12:24:06.084  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:06.084  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:06.086  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:06.088  4279  4279 D A2dpService: Received stop request...Stopping profile...
09-02 12:24:06.088  4279  4544 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:24:06.089  4279  4279 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 12:24:06.094  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:24:06.094  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:06.094  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:06.098  4279  4279 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 12:24:06.098  4279  4279 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:24:06.098  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b04fb8
,09-02 12:24:06.100  4279  4404 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 12:24:06.101  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-02 12:24:06.101  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 12:24:06.101  4279  4279 D HidService: Received stop request...Stopping profile...
09-02 12:24:06.102  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b04fb8
09-02 12:24:06.106  4279  4279 D HeadsetStateMachine: Unbinding service...
09-02 12:24:06.107  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:06.108  4279  4279 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:24:06.108  4279  4279 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:24:06.108  4279  4279 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:24:06.108  4279  4279 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:24:06.109  4279  4279 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:24:06.109  4279  4279 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:24:06.109  4279  4279 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:24:06.110  4279  4279 D HealthService: Received stop request...Stopping profile...
09-02 12:24:06.110  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b04fb8
,09-02 12:24:06.114  4279  4279 D PanService: Received stop request...Stopping profile...
09-02 12:24:06.114  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b04fb8
09-02 12:24:06.116  4279  4279 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:24:06.117  4279  4279 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 12:24:06.117  4279  4279 D BtGatt.GattService: stop()
09-02 12:24:06.118  4279  4279 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 12:24:06.119  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b04fb8
09-02 12:24:06.120  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:06.121  6996  6996 D BluetoothInputDevice: Proxy object disconnected
09-02 12:24:06.121  6996  6996 D HidProfile: Bluetooth service disconnected
09-02 12:24:06.121  6996  6996 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:24:06.121  6996  6996 D PanProfile: Bluetooth service disconnected
09-02 12:24:06.126  4279  4279 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:24:06.126  4279  4279 D BluetoothMapService: stop()
09-02 12:24:06.127  4279  4279 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 12:24:06.127  4279  4279 D BluetoothMapEmailAppObserver: removeReceiver()
,09-02 12:24:06.132  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:06.133  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:06.133  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b04fb8
09-02 12:24:06.134  6996  6996 D BluetoothMap: Proxy object disconnected
09-02 12:24:06.135  6996  6996 D MapProfile: Bluetooth service disconnected
09-02 12:24:06.135  4279  4279 I BluetoothA2dpServiceJni: cleanupNative
09-02 12:24:06.136  4279  4545 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 12:24:06.136  4279  4279 I GKI_LINUX: GKI_exit_task 2 done
09-02 12:24:06.136  4279  4279 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 12:24:06.137  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:24:06.137  4279  4279 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:24:06.137  4279  4279 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:24:06.137  4279  4279 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:24:06.137  4279  4279 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:24:06.137  4279  4279 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:24:06.138  4279  4279 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:24:06.138  4279  4279 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 12:24:06.139  4279  4279 V BluetoothMapService: Handler(): got msg=4
09-02 12:24:06.139  4279  4279 D BluetoothMapService: MAP Service closeService in
09-02 12:24:06.139  4279  4279 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:24:06.139  4279  4279 V BluetoothMapService: MAP Service closeService out
09-02 12:24:06.140  4279  4279 D BluetoothMapService: cleanup()
09-02 12:24:06.140  4279  4279 D BluetoothMapService: MAP Service closeService in
09-02 12:24:06.140  4279  4279 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:24:06.140  4279  4279 V BluetoothMapService: MAP Service closeService out
09-02 12:24:06.140  4279  4404 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 12:24:06.140  4279  4404 D BluetoothAdapterProperties: Setting state to 10
09-02 12:24:06.140  4279  4404 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 12:24:06.142  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:06.142  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 12:24:06.142  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-02 12:24:06.142  4279  4404 I BluetoothAdapterState: Entering OffState
09-02 12:24:06.143  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 12:24:06.206  1035  2042 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7085 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 12:24:06.207  6996  7012 D BluetoothPan: onBluetoothStateChange on: false
09-02 12:24:06.208  1853  2429 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:24:06.209  1035  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 12:24:06.209  1853  4475 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:24:06.210  6996  7011 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:24:06.214  1035  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:24:06.215  6996  7012 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:24:06.215  6996  7011 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:24:06.217  1035  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 12:24:06.217  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 12:24:06.220  1035  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 12:24:06.220  1035  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 12:24:06.220  1035  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21fbec5e mBinding = false
09-02 12:24:06.221  1035  1118 D BluetoothManagerService: Sending unbind request.
,09-02 12:24:06.228  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 12:24:06.230  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:06.230  1941  2145 D LGBluetoothAPIService: Message: 2
09-02 12:24:06.231  1941  2145 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@26de17ab mBinding = false
09-02 12:24:06.231  1941  2145 D LGBluetoothAPIService: Sending unbind request.
09-02 12:24:06.233  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:06.233  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:06.235  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:24:06.237  4279  4417 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-02 12:24:06.237  4279  4279 I GKI_LINUX: GKI_exit_task 1 done
09-02 12:24:06.237  4279  4279 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 12:24:06.237  4279  4279 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 12:24:06.238  4279  4279 I art     : --- WEIRD: removing null entry 246
09-02 12:24:06.238  4279  4279 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-02 12:24:06.238  4279  4279 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 12:24:06.239  1601  1601 D BluetoothAdapter: 843221584: getState() :  mService = null. Returning STATE_OFF
09-02 12:24:06.239  1601  1601 D BluetoothAdapter: 843221584: getState() :  mService = null. Returning STATE_OFF
09-02 12:24:06.242  4279  4279 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 12:24:06.245  4279  4279 I art     : System.exit called, status: 0
09-02 12:24:06.245  4279  4279 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:24:06.246  6996  6996 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 12:24:06.247  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 12:24:06.247  6996  6996 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 12:24:06.250  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 12:24:06.266   320  1402 V AudioFlinger: 4279 died, releasing its sessions
09-02 12:24:06.266   320  1402 V AudioFlinger:  pid 1853 @ 0
09-02 12:24:06.266   320  1402 V AudioFlinger:  pid 3428 @ 1
09-02 12:24:06.266   320  1402 V AudioFlinger:  pid 3428 @ 2
09-02 12:24:06.268  6996  6996 D DockEventReceiver: finishStartingService: stopping service
09-02 12:24:06.269  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 12:24:06.301  1035  1917 I ActivityManager: Process com.android.bluetooth (pid 4279) has died
09-02 12:24:06.301  1035  1917 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-02 12:24:06.306  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:06.319  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:06.325  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:24:06.331  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:06.333  6996  6996 D BluetoothPermissionRequest: onReceive
,09-02 12:24:06.336  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-02 12:24:06.336  6996  6996 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 12:24:06.338  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:24:06.394  1035  1957 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7108 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 12:24:06.416   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 492us total 22.912ms
,09-02 12:24:06.429  7085  7106 W FormManager: Network not available. Please check & try again.
09-02 12:24:06.438   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 20.651ms
,09-02 12:24:06.440  7085  7107 V FormManager: Network unavailable.
09-02 12:24:06.443  7085  7107 V FormManager: Network unavailable.
09-02 12:24:06.451  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:24:06.451  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:24:06.451  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:24:06.452  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-02 12:24:06.453  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:24:06.460   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 21.397ms
09-02 12:24:06.476  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-02 12:24:06.477  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 12:24:06.477  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:24:06.477  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:24:06.477  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:24:06.477  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:24:06.478  1035  1052 I ActivityManager: Killing 6036:com.android.contacts/u0a19 (adj 15): empty #17
09-02 12:24:06.484  7108  7108 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-02 12:24:06.485  7108  7108 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:06.485  7108  7108 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 12:24:06.486  7108  7108 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 12:24:06.503  7108  7108 D BluetoothAdapterApp: Loading JNI Library
,09-02 12:24:06.537  7108  7108 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2e01d059 Instance Count = 1
,09-02 12:24:06.545  1035  2042 W libprocessgroup: failed to open /acct/uid_10019/pid_6036/cgroup.procs: No such file or directory
09-02 12:24:06.547  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:24:06.548  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:06.548  7108  7108 D BluetoothAdapterApp: onCreate
09-02 12:24:06.554  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:24:06.562  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:06.573  4792  7132 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:24:06.574  7108  7108 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 12:24:06.574  7108  7108 D ProfileConfigQcom: Adding HeadsetService
09-02 12:24:06.574  7108  7108 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 12:24:06.575  7108  7108 D ProfileConfigQcom: Adding A2dpService
09-02 12:24:06.575  7108  7108 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 12:24:06.575  7108  7108 D ProfileConfigQcom: Adding HidService
09-02 12:24:06.575  7108  7108 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 12:24:06.576  7108  7108 D ProfileConfigQcom: Adding HealthService
,09-02 12:24:06.576  7108  7108 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-02 12:24:06.577  7108  7108 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 12:24:06.577  7108  7108 D ProfileConfigQcom: Adding PanService
09-02 12:24:06.577  7108  7108 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 12:24:06.577  7108  7108 D ProfileConfigQcom: Adding GattService
09-02 12:24:06.578  7108  7108 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 12:24:06.578  7108  7108 D ProfileConfigQcom: Adding BluetoothMapService
09-02 12:24:06.578  7108  7108 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 12:24:06.579  7016  7016 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 12:24:06.579  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:06.579  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:06.580  7108  7108 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 12:24:06.584  4792  7136 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:24:06.584  4792  7136 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:06.586  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:24:06.593  7108  7108 V LGMDMManagerInternal: Create singleton instance
09-02 12:24:06.595  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:06.596  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 12:24:06.596  7085  7137 W FormManager: Network not available. Please check & try again.
09-02 12:24:06.600  7085  7138 V FormManager: Network unavailable.
,09-02 12:24:06.610  7047  7047 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-02 12:24:06.611  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-02 12:24:06.612  7047  7047 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-02 12:24:06.612  7085  7138 V FormManager: Network unavailable.
09-02 12:24:06.645  7047  7047 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:24:06.645  7047  7047 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:06.652  7047  7047 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-02 12:24:06.653  7047  7047 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-02 12:24:06.653  7047  7047 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-02 12:24:06.653  7047  7047 V SoundPool: doLoad: loading sample sampleID=1
09-02 12:24:06.653  7047  7047 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 12:24:06.656  7047  7141 V SoundPool: Start decode
,09-02 12:24:06.656  7047  7141 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-02 12:24:06.656  7047  7047 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-02 12:24:06.657  6868  6868 D UEI.SmartControl: QS Service created
09-02 12:24:06.660  7047  7047 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 12:24:06.660  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 12:24:06.661   320   320 V MediaPlayerService: decode(23, 10857164, 17813)
,09-02 12:24:06.661   320   320 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-02 12:24:06.661   320   320 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-02 12:24:06.661   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-02 12:24:06.661   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-02 12:24:06.661   320   320 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-02 12:24:06.661   320   320 V MediaPlayerService: player type = 3
09-02 12:24:06.661   320   320 V AwesomePlayer: AwesomePlayer create()
09-02 12:24:06.662   320   320 V AwesomePlayer: reset_l() 
09-02 12:24:06.662   320   320 V AwesomePlayer: cancelPlayerEvents
09-02 12:24:06.662   320   320 V AwesomePlayer: setAudioSink() 
09-02 12:24:06.662   320   320 V AwesomePlayer: reset_l() 
09-02 12:24:06.662   320   320 V AudioCache: notify(0xb102d2c0, 8, 0, 0)
09-02 12:24:06.662   320   320 V AudioCache: ignored
09-02 12:24:06.662   320   320 V AwesomePlayer: cancelPlayerEvents
09-02 12:24:06.662   320   320 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-02 12:24:06.662   320   320 V AwesomePlayer: setDataSource_l dataSource
09-02 12:24:06.662   320   320 V LGParserOSAL: SniffLGParser start
09-02 12:24:06.662   320   320 V LGParserOSAL: MainType:5, SubType=0
09-02 12:24:06.662   320   320 V LGParserOSAL: #### check Mime : application/ogg
09-02 12:24:06.662   320   320 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-02 12:24:06.662   320   320 E MediaExtractor: Use LGExtractor :application/ogg 
09-02 12:24:06.670  7108  7108 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:06.672  7108  7108 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:06.673  7108  7108 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:06.673  7108  7108 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:06.674  7108  7108 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:06.674  7108  7108 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 12:24:06.680  7064  7064 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-02 12:24:06.686  6868  6868 I UEI.SmartControl: Service initServices...
09-02 12:24:06.686  6868  6868 D UEI.SmartControl: QS start get config
09-02 12:24:06.687  7047  7047 V LGMDMManager: Create singleton instance
,09-02 12:24:06.698   320   320 V LGParserOSAL: supported mime: application/ogg
09-02 12:24:06.698   320   320 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-02 12:24:06.698   320   320 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-02 12:24:06.698   320   320 V AwesomePlayer: mBitrate = -1 bits/sec
09-02 12:24:06.698   320   320 V AwesomePlayer: AudioTrack Setting
09-02 12:24:06.698   320   320 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-02 12:24:06.698   320   320 V AwesomePlayer: setAudioSource() 
09-02 12:24:06.698   320   320 V MediaPlayerService: prepare
09-02 12:24:06.698   320   320 V AwesomePlayer: prepareAsync_l() 
09-02 12:24:06.698   320   320 V MediaPlayerService: wait for prepare
09-02 12:24:06.698   320  7143 V AwesomePlayer: onPrepareAsyncEvent() 
09-02 12:24:06.698   320  7143 V AwesomePlayer: initAudioDecoder() 
09-02 12:24:06.698   320  7143 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 12:24:06.698   320  7143 V AudioSystem: isOffloadSupported()
09-02 12:24:06.698   320  7143 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 12:24:06.698   320  7143 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 12:24:06.699   320  7143 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 12:24:06.699   320  7143 V AwesomePlayer: getUseOffload() = 0 
09-02 12:24:06.699   320  7143 V OMXCodec: OMXCodec::Create
09-02 12:24:06.699   320  7143 V OMXCodec: findMatchingCodecs()
09-02 12:24:06.699   320  7143 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-02 12:24:06.699   320  7143 V OMXCodec: matchingCodecs.size()=1
09-02 12:24:06.699   320  7143 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-02 12:24:06.701   320  7143 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-02 12:24:06.701   320  7143 V LGCodecAdapter: LG Codec Adapter start
09-02 12:24:06.701   320  7143 V OMXCodec: OMXCodec Createtor
09-02 12:24:06.701   320  7143 V OMXCodec: setComponentRole
09-02 12:24:06.701   320  7143 V OMXCodec: configureCodec protected=0
09-02 12:24:06.701   320  7143 V LGCodecAdapter: called getLGCodecSpecificData
09-02 12:24:06.701   320  7143 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-02 12:24:06.701   320  7143 V LGCodecOSAL: Called LGconfigureCodecMETA
09-02 12:24:06.701   320  7143 V LGCodecOSAL: Called LGconfigureCodecMSG
09-02 12:24:06.701   320  7143 V LGCodecOSAL: Not support LGCodec
09-02 12:24:06.701   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 12:24:06.702   320  7143 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-02 12:24:06.702   320  7143 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-02 12:24:06.702   320  7143 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-02 12:24:06.702   320  7143 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 12:24:06.702   320  7143 V AudioSystem: isOffloadSupported()
09-02 12:24:06.702   320  7143 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 12:24:06.702   320  7143 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-02 12:24:06.702   320  7143 V OMXCodec: init()
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-02 12:24:06.702   320  7143 V OMXCodec: allocateBuffers
09-02 12:24:06.702   320  7143 V OMXCodec: allocateBuffersOnPort portIndex=0
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-02 12:24:06.702   320  7143 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-02 12:24:06.702   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-02 12:24:06.703   320  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-02 12:24:06.703   320  7143 V OMXCodec: init() mAsyncCompletion wait!!! 
09-02 12:24:06.703   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 12:24:06.703   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 12:24:06.703   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-02 12:24:06.703   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-02 12:24:06.703   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-02 12:24:06.703   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
09-02 12:24:06.703   320  7143 V OMXCodec: init() mAsyncCompletion wait free! 
09-02 12:24:06.703   320  7143 V AwesomePlayer: finishAsyncPrepare_l() 
09-02 12:24:06.703   320  7143 V AudioCache: notify(0xb102d2c0, 5, 0, 0)
09-02 12:24:06.703   320  7143 V AudioCache: ignored
09-02 12:24:06.703   320  7143 V AudioCache: notify(0xb102d2c0, 1, 0, 0)
09-02 12:24:06.703   320  7143 V AudioCache: prepared
09-02 12:24:06.703   320   320 V AudioCache: wait - success
09-02 12:24:06.703   320   320 V MediaPlayerService: start
09-02 12:24:06.703   320   320 V AwesomePlayer: play_l() 
09-02 12:24:06.703   320   320 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-02 12:24:06.703   320   320 V AwesomePlayer: createAudioPlayer_l
09-02 12:24:06.703   320   320 V AwesomePlayer: seekAudioIfNecessary_l() 
09-02 12:24:06.703   320   320 V AwesomePlayer: startAudioPlayer_l() 
09-02 12:24:06.703   320   320 D AudioPlayer: start of Playback, useOffload 0
09-02 12:24:06.703   320   320 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 12:24:06.703   320   320 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 12:24:06.705   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-02 12:24:06.705   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-02 12:24:06.705   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-02 12:24:06.706   320  7145 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 12:24:06.706   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 12:24:06.707   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-02 12:24:06.707   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-02 12:24:06.707   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
09-02 12:24:06.707   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bf650 on output port
09-02 12:24:06.707   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-02 12:24:06.707   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-02 12:24:0,6.708   320   320 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-02 12:24:06.708   320   320 V AudioCache: notify(0xb102d2c0, 6, 0, 0)
09-02 12:24:06.708   320   320 V AudioCache: ignored
09-02 12:24:06.708   320   320 V MediaPlayerService: wait for playback complete
09-02 12:24:06.709   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.709   320  7146 V AudioCache: memcpy(0xaf006000, 0xb17fd000, 4096)
09-02 12:24:06.712   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.712   320  7146 V AudioCache: memcpy(0xaf007000, 0xb17fd000, 4096)
09-02 12:24:06.712   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.712   320  7146 V AudioCache: memcpy(0xaf008000, 0xb17fd000, 4096)
09-02 12:24:06.713   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.713   320  7146 V AudioCache: memcpy(0xaf009000, 0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: memcpy(0xaf00a000, 0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: memcpy(0xaf00b000, 0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: memcpy(0xaf00c000, 0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.714   320  7146 V AudioCache: memcpy(0xaf00d000, 0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: memcpy(0xaf00e000, 0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: memcpy(0xaf00f000, 0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: memcpy(0xaf010000, 0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.716   320  7146 V AudioCache: memcpy(0xaf011000, 0xb17fd000, 4096)
09-02 12:24:06.717   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.717   320  7146 V AudioCache: memcpy(0xaf012000, 0xb17fd000, 4096)
09-02 12:24:06.717   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.717   320  7146 V AudioCache: memcpy(0xaf013000, 0xb17fd000, 4096)
09-02 12:24:06.717   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.717   320  7146 V AudioCache: memcpy(0xaf014000, 0xb17fd000, 4096)
09-02 12:24:06.718   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.718   320  7146 V AudioCache: memcpy(0xaf015000, 0xb17fd000, 4096)
09-02 12:24:06.718   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.718   320  7146 V AudioCache: memcpy(0xaf016000, 0xb17fd000, 4096)
09-02 12:24:06.719   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.719   320  7146 V AudioCache: memcpy(0xaf017000, 0xb17fd000, 4096)
09-02 12:24:06.719   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.719   320  7146 V AudioCache: memcpy(0xaf018000, 0xb17fd000, 4096)
09-02 12:24:06.720   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.720   320  7146 V AudioCache: memcpy(0xaf019000, 0xb17fd000, 4096)
09-02 12:24:06.720   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.720   320  7146 V AudioCache: memcpy(0xaf01a000, 0xb17fd000, 4096)
09-02 12:24:06.721   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.721   320  7146 V AudioCache: memcpy(0xaf01b000, 0xb17fd000, 4096)
09-02 12:24:06.722   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.722   320  7146 V AudioCache: memcpy(0xaf01c000, 0xb17fd000, 4096)
09-02 12:24:06.722   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.722   320  7146 V AudioCache: memcpy(0xaf01d000, 0xb17fd000, 4096)
09-02 12:24:06.723   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.723   320  7146 V AudioCache: memcpy(0xaf01e000, 0xb17fd000, 4096)
09-02 12:24:06.723   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.723   320  7146 V AudioCache: memcpy(0xaf01f000, 0xb17fd000, 4096)
09-02 12:24:06.724   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.724   320  7146 V AudioCache: memcpy(0xaf020000, 0xb17fd000, 4096)
09-02 12:24:06.724   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.724   320  7146 V AudioCache: memcpy(0xaf021000, 0xb17fd000, 4096)
09-02 12:24:06.725   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.725   320  7146 V AudioCache: memcpy(0xaf022000, 0xb17fd000, 4096)
09-02 12:24:06.725   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.725   320  7146 V AudioCache: memcpy(0xaf023000, 0xb17fd000, 4096)
09-02 12:24:06.726   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.726   320  7146 V AudioCache: memcpy(0xaf024000, 0xb17fd000, 4096)
09-02 12:24:06.726   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.726   320  7146 V AudioCache: memcpy(0xaf025000, 0xb17fd000, 4096)
09-02 12:24:06.727   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.727   320  7146 V AudioCache: memcpy(0xaf026000, 0xb17fd000, 4096)
09-02 12:24:06.727   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.727   320  7146 V AudioCache: memcpy(0xaf027000, 0xb17fd000, 4096)
09-02 12:24:06.728   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.728   320  7146 V AudioCache: memcpy(0xaf028000, 0xb17fd000, 4096)
09-02 12:24:06.728   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.728   320  7146 V AudioCache: memcpy(0xaf029000, 0xb17fd000, 4096)
09-02 12:24:06.729   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.729   320  7146 V AudioCache: memcpy(0xaf02a000, 0xb17fd000, 4096)
09-02 12:24:06.729   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.729   320  7146 V AudioCache: memcpy(0xaf02b000, 0xb17fd000, 4096)
09-02 12:24:06.730   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.730   320  7146 V AudioCache: memcpy(0xaf02c000, 0xb17fd000, 4096)
09-02 12:24:06.731   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.731   320  7146 V AudioCache: memcpy(0xaf02d000, 0xb17fd000, 4096)
09-02 12:24:06.731   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.731   320  7146 V AudioCache: memcpy(0xaf02e000, 0xb17fd000, 4096)
09-02 12:24:06.732   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.732   320  7146 V AudioCache: memcpy(0xaf02f000, 0xb17fd000, 4096)
09-02 12:24:06.732   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.732   320  7146 V AudioCache: memcpy(0xaf030000, 0xb17fd000, 4096)
09-02 12:24:06.733   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.733   320  7146 V AudioCache: memcpy(0xaf031000, 0xb17fd000, 4096)
09-02 12:24:06.733   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.733   320  7146 V AudioCache: memcpy(0xaf032000, 0xb17fd000, 4096)
09-02 12:24:06.734   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.734   320  7146 V AudioCache: memcpy(0xaf033000, 0xb17fd000, 4096)
09-02 12:24:06.734   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.734   320  7146 V AudioCache: memcpy(0xaf034000, 0xb17fd000, 4096)
09-02 12:24:06.735   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.735   320  7146 V AudioCache: memcpy(0xaf035000, 0xb17fd000, 4096)
09-02 12:24:06.735   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.735   320  7146 V AudioCache: memcpy(0xaf036000, 0xb17fd000, 4096)
09-02 12:24:06.735   320  7146 V AudioCache: write(0xb17fd000, 4096)
09-02 12:24:06.736   320  7146 V AudioCache: memcpy(0xaf037000, 0xb17fd000, 4096)
09-02 12:24:06.736   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-02 12:24:06.736   320  7146 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-02 12:24:06.736   320  7146 V AwesomePlayer: postAudioEOS() 
09-02 12:24:06.736   320  7146 V AudioCache: write(0xb17fd000, 280)
09-02 12:24:06.736   320  7146 V AudioCache: memcpy(0xaf038000, 0xb17fd000, 280)
09-02 12:24:06.737   320  7143 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-02 12:24:06.737   320  7143 V AwesomePlayer: onStreamDone
09-02 12:24:06.737   320  7143 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-02 12:24:06.737   320  7143 V AudioCache: notify(0xb102d2c0, 2, 0, 0)
09-02 12:24:06.737   320  7143 V AudioCache: playback complete
09-02 12:24:06.737   320  7143 V AwesomePlayer: pause_l() 
09-02 12:24:06.737   320   320 V AudioCache: wait - success
09-02 12:24:06.737   320  7143 V AudioCache: notify(0xb102d2c0, 7, 0, 0)
09-02 12:24:06.737   320  7143 V AudioCache: ignored
09-02 12:24:06.738   320   320 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-02 12:24:06.738   320  7143 V AwesomePlayer: cancelPlayerEvents
09-02 12:24:06.738   320  7143 D AudioPlayer: Pause Playback at 1068125
09-02 12:24:06.738   320   320 V AwesomePlayer: reset_l() 
09-02 12:24:06.738   320   320 V AudioCache: notify(0xb102d2c0, 8, 0, 0)
09-02 12:24:06.738   320   320 V AudioCache: ignored
09-02 12:24:06.738   320   320 V AwesomePlayer: cancelPlayerEvents
09-02 12:24:06.738   320   320 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-02 12:24:06.738   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-02 12:24:06.738   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-02 12:24:06.738   320   320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-02 12:24:06.738   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 12:24:06.738   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 12:24:06.738   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 12:24:06.738   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-02 12:24:06.738   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-02 12:24:06.738   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bf650 on port 1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-02 12:24:06.739   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 12:24:06.739   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-02 12:24:06.739   320  7145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-02 12:24:06.739   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 12:24:06.739   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-02 12:24:06.739   320   320 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-02 12:24:06.740   320   320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-02 12:24:06.741   320   320 D AudioPlayer: AudioPlayer releasing audio source
09-02 12:24:06.741   320   320 D AudioPlayer: AudioPlayer done releasing audio source
09-02 12:24:06.741   320   320 V AwesomePlayer: reset_l() 
09-02 12:24:06.741   320   320 V AwesomePlayer: cancelPlayerEvents
09-02 12:24:06.741   320   320 V AwesomePlayer: ~AwesomePlayer call
09-02 12:24:06.741   320   320 V AwesomePlayer: reset_l() 
09-02 12:24:06.741   320   320 V AwesomePlayer: cancelPlayerEvents
09-02 12:24:06.742  7047  7141 V SoundPool: close(31)
09-02 12:24:06.742  7047  7141 V SoundPool: pointer = 0x9fe51000, size = 205080, sampleRate = 48000, numChannels = 2
,09-02 12:24:06.750  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 12:24:06.752  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-02 12:24:06.754  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4159
,09-02 12:24:07.135  6868  6868 I UEI.SmartControl: Supports setup maps: true
,09-02 12:24:07.141  6868  6868 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 12:24:07.141  6868  6868 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 12:24:07.141  6868  6868 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 12:24:07.141  6868  6868 I UEI.SmartControl: ### init IR Blaster...
09-02 12:24:07.144  6868  6868 D serial_port: Configuring serial port
09-02 12:24:07.145  6868  6868 E UEI.SmartControl: UEIBLaster setting for 616
09-02 12:24:07.145  6868  6868 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 12:24:07.145  6868  6868 I UEI.SmartControl: configuring settings for MAXQ616
09-02 12:24:07.145  6868  6868 I UEI.SmartControl: Get version...
09-02 12:24:07.164  6868  7154 D UEI.SmartControl: serial port data available: 21
,09-02 12:24:07.190  6868  6868 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-02 12:24:07.190  6868  6868 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-02 12:24:07.190  6868  6868 I UEI.SmartControl: QS saving settings...
,09-02 12:24:07.195  6868  6868 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 12:24:07.214  6868  7154 D UEI.SmartControl: serial port data available: 4
,09-02 12:24:07.248  6868  6868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-02 12:24:07.259  6868  7160 I UEI.SmartControl: Device manager: loading config....
09-02 12:24:07.260  6868  7160 D UEI.SmartControl: ----------- loading internal config...
09-02 12:24:07.263  6868  6868 E UEI.SmartControl: Services init done
09-02 12:24:07.263  6868  6868 D UEI.SmartControl: QS Service init finished
09-02 12:24:07.264  6868  6868 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 12:24:07.264  6868  6868 D UEI.SmartControl: QS Service version code: 201091
09-02 12:24:07.264  6868  6868 D UEI.SmartControl: Service requested: Control
09-02 12:24:07.270  6868  7160 E UEI.SmartControl: Loading SETTINGS...
,09-02 12:24:07.274  6868  6868 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 12:24:07.277  7047  7047 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-02 12:24:07.279  6868  6884 I UEI.SmartControl: ------ IControl API: 11
09-02 12:24:07.279  6868  6884 D UEI.SmartControl: File observer start...
09-02 12:24:07.280  6868  6884 E UEI.SmartControl: IR Port is disabled: false
09-02 12:24:07.280  6868  6884 D UEI.SmartControl: Starting file observer...
09-02 12:24:07.281  6868  6884 I UEI.SmartControl: Registering callback...
09-02 12:24:07.282  6868  6868 D UEI.SmartControl: Internal service binding...
09-02 12:24:07.282  6868  6883 I UEI.SmartControl: ------ IControl API: 19
09-02 12:24:07.283  6868  6883 I UEI.SmartControl: Registering Services Ready callback...
09-02 12:24:07.287  6868  7160 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-02 12:24:07.307  6868  7159 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-02 12:24:07.309  7047  7062 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,09-02 12:24:07.309  7047  7139 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-02 12:24:07.310  7047  7139 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-02 12:24:07.310  7047  7047 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-02 12:24:07.311  7047  7047 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-02 12:24:07.311  6868  6884 I UEI.SmartControl: ------ IControl API: 8
09-02 12:24:07.312  6868  7159 D UEI.SmartControl: -----service ready thread exits
09-02 12:24:07.313  7047  7047 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-02 12:24:07.313  7047  7047 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-02 12:24:07.313  7047  7047 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-02 12:24:07.314  7047  7047 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-02 12:24:07.315  7047  7047 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-02 12:24:07.315  7047  7047 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-02 12:24:07.318  7047  7047 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-02 12:24:07.325  7047  7047 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-02 12:24:07.326  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 12:24:07.327  7047  7047 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 12:24:07.327  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 12:24:07.328  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 12:24:07.329  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-02 12:24:07.330  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-02 12:24:07.332  7047  7047 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472811847332]
,09-02 12:24:07.339  7047  7047 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-02 12:24:07.342  1035  1976 I ActivityManager: Killing 6588:com.android.gallery3d/u0a27 (adj 15): empty #17
09-02 12:24:07.379  7047  7162 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-02 12:24:07.384  1035  1976 I ActivityManager: Killing 6556:com.lge.email/u0a23 (adj 15): empty #18
09-02 12:24:07.421  1035  1052 W libprocessgroup: failed to open /acct/uid_10027/pid_6588/cgroup.procs: No such file or directory
,09-02 12:24:07.427  1035  1957 W libprocessgroup: failed to open /acct/uid_10023/pid_6556/cgroup.procs: No such file or directory
09-02 12:24:07.433  7047  7047 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-02 12:24:07.436  7047  7047 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 12:24:07.436  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-02 12:24:07.436  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-02 12:24:07.437  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-02 12:24:07.437  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-02 12:24:07.437  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-02 12:24:07.447  7047  7047 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-02 12:24:07.974  1035  1940 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-02 12:24:07.975  1035  1940 D WifiService: setWifiEnabled: true pid=6705, uid=10118
09-02 12:24:07.976  1035  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,09-02 12:24:08.000  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:24:08.000  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:08.000  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-02 12:24:08.004  1035  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-02 12:24:08.004  1035  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-02 12:24:08.007  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-02 12:24:08.007  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:24:08.007  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 12:24:08.007  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:24:08.007  1035  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 12:24:08.007  1035  1392 E WifiHW  : unknown target_country: EU , set to default
,09-02 12:24:08.007  1035  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
,09-02 12:24:08.007  1035  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-02 12:24:08.007  1035  1392 I WifiUtil: gEnableBmps=1,
,09-02 12:24:08.082  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:08.108  1035  1118 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:24:08.129  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:08.135  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:08.136  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:08.139  1035  1118 D Tethering: MasterInitialState.processMessage what=3
09-02 12:24:08.152  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:08.156  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:08.156  1035  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:08.158  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 12:24:08.167  5854  5854 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 12:24:08.174  5854  5854 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 12:24:08.176  6446  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-02 12:24:08.212  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:08.292  1035  1995 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7172 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-02 12:24:08.391  7172  7172 I AppUp4:AppBoxCP: onCreate
09-02 12:24:08.392  7172  7172 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-02 12:24:08.399  1035  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:08.399  1035  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:08.400  1035  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:08.402  7172  7172 I AppUp4:DB:  setFingerPrint start
09-02 12:24:08.402  7172  7172 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-02 12:24:08.411  7172  7172 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-02 12:24:08.411  7172  7172 I AppUp4:DB:  SDK version = 21
09-02 12:24:08.411  7172  7172 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-02 12:24:08.413  7172  7172 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-02 12:24:08.415  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-02 12:24:08.415  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:08.418  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:24:08.418  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 12:24:08.426  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 12:24:08.473  7172  7172 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:24:08.473  7172  7172 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:08.484  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@72d021b
09-02 12:24:08.484  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:24:08.484  7172  7172 D AppUp4:CustFacade: isPhone : true
09-02 12:24:08.485  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:24:08.486  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-02 12:24:08.487  7172  7172 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-02 12:24:08.488  7172  7198 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-02 12:24:08.488  7172  7198 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,09-02 12:24:08.489  7172  7198 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-02 12:24:08.493  1035  1052 I ActivityManager: Killing 6613:com.android.vending/u0a44 (adj 15): empty #17
09-02 12:24:08.606  1035  1904 W libprocessgroup: failed to open /acct/uid_10044/pid_6613/cgroup.procs: No such file or directory
,09-02 12:24:08.609  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:08.610  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:08.618  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:08.624  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:24:08.640  4792  7207 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:24:08.660  4792  7208 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:08.660  4792  7208 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:08.687   315   894 D SoftapController: Softap fwReload - Ok
,09-02 12:24:08.688  1035  1392 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (674ms)
09-02 12:24:08.690   315   894 D CommandListener: Setting iface cfg
09-02 12:24:08.690   315   894 D CommandListener: Trying to bring down wlan0
09-02 12:24:08.693   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:24:08.696  1035  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 12:24:08.698  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:08.698  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:08.698  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:24:08.697  7210  7210 W wpa_supplicant: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:08.697  7210  7210 W wpa_supplicant: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:08.705  1035  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7211 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 12:24:08.708  1035  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:24:08.708  1035  1118 D Tethering: InitialState.processMessage what=4
09-02 12:24:08.709  1035  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:24:08.714  1035  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 12:24:08.714  1035  1392 D WifiMonitor: connecting to supplicant
09-02 12:24:08.718  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:08.721  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-02 12:24:08.721  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 12:24:08.725  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:08.725  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:08.732  7210  7210 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 12:24:08.741  2124  2124 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19989
09-02 12:24:08.759  7210  7210 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 12:24:08.759  7210  7210 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-02 12:24:08.794  7211  7211 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:08.794  7211  7211 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 12:24:08.796  7211  7211 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 12:24:08.796  7211  7211 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 12:24:08.899  7210  7210 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 12:24:08.899  7211  7211 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-02 12:24:08.917  7211  7211 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-02 12:24:08.968  7211  7211 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-02 12:24:09.007  7211  7211 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:24:09.008  7211  7211 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:09.021  7210  7210 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-02 12:24:09.045  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 12:24:09.046  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 12:24:09.047  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:24:09.048  1035  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:24:09.043  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-02 12:24:09.050  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-02 12:24:09.051  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 12:24:09.052  1035  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:09.052  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 12:24:09.052  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:24:09.052  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:24:09.053  1035  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 12:24:09.053  1035  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 12:24:09.054  1035  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 12:24:09.054  1035  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 12:24:09.054  1035  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 12:24:09.055  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:09.055  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:09.055  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:24:09.055  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.056  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.057  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.057  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.059  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.057  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:09.060  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-02 12:24:09.060  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 12:24:09.062  1035  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
,09-02 12:24:09.062  1035  1392 D WifiNative-wlan0: SET update_config 1: returned true
09-02 12:24:09.062  1035  1392 D WifiConfigStore: Loading config and enabling all networks 
09-02 12:24:09.062  1035  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,09-02 12:24:09.063  1035  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 12:24:09.067  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:09.067  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:09.067  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:09.067  1035  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 12:24:09.067  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:09.068  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:09.068  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:09.068  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:09.068  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:09.070  1035  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 12:24:09.078  1035  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-02 12:24:09.078  1035  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 12:24:09.079  1035  1392 D WifiStateMachine: enableVerboseLogging : level 2
09-02 12:24:09.079  1035  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-02 12:24:09.079  1035  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 12:24:09.079  1035  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 12:24:09.080  1035  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 12:24:09.080  1035  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 12:24:09.080  1035  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 12:24:09.080  1035  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 12:24:09.081  1035  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 12:24:09.081  1035  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 12:24:09.081  1035  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 12:24:09.081  1035  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 12:24:09.081  1035  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 12:24:09.082  1035  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 12:24:09.082  1035  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 12:24:09.082  1035  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:24:09.082  1035  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 12:24:09.083  1035  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 12:24:09.083  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-02 12:24:09.083  1035  1392 D WifiNative-HAL: Setting external_sim to 1
09-02 12:24:09.083  1035  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 12:24:09.083  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 12:24:09.083  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-02 12:24:09.083  1941  2345 D WfdsMonitor: WfdsMonitorThread create
09-02 12:24:09.084  1941  2345 D WfdsMonitor: WFDS Monitor is created and started
09-02 12:24:09.084  1941  2345 D WfdsService: WiFi: Supplicant connection re-established
09-02 12:24:09.084  1035  1392 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 12:24:09.084  1035  1392 I WifiNative-HAL: startHal
09-02 12:24:09.084  1035  1392 D wifi    : setting scan oui 0xaf6f30e0
09-02 12:24:09.084  1035  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:24:09.084  1035  1392 I WifiNative-HAL: startHal
09-02 12:24:09.084  1035  1392 D wifi    : setting scan oui 0xaf6f30e0
09-02 12:24:09.084  1941  7236 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 12:24:09.084  1035  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 12:24:09.084  1941  7236 E CtrlSupplicant: Succeed to open control connection
09-02 12:24:09.085  1941  7236 E CtrlSupplicant: Succeed to open monitor connection
09-02 12:24:09.085  1941  7236 D WfdsMonitor: Supplicant connection established
09-02 12:24:09.085  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-02 12:24:09.085  1035  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 12:24:09.085  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 12:24:09.085  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 12:24:09.091  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,09-02 12:24:09.091  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:24:09.091  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:24:09.091  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:24:09.091  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 12:24:09.091  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 12:24:09.092  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 12:24:09.092  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:24:09.092  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:24:09.093  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:24:09.093  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:24:09.093  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:24:09.093  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:24:09.093  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 12:24:09.093  7210  7210 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 12:24:09.093  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 12:24:09.093  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:24:09.094  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:24:09.094  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:24:09.094  1035  1392 E WifiNative: : [122,527,289 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 12:24:09.094  1035  1392 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 12:24:09.095  1035  1392 D WifiNative-wlan0: RECONNECT: returned true
09-02 12:24:09.095  1035  1392 D WifiNative-wlan0: doString: [STATUS]
09-02 12:24:09.095  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:24:09.095  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 12:24:09.096  1035  1392 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:24:09.096  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:24:09.096  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:24:09.096  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.097   315   894 D CommandListener: Setting iface cfg
09-02 12:24:09.097   315   894 D CommandListener: Trying to bring up p2p0
09-02 12:24:09.098  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 12:24:09.098  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-02 12:24:09.098  1035  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.098  1035  1555 I WifiNative-HAL: startHal
09-02 12:24:09.098  1035  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6f30e0
09-02 12:24:09.098  1035  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 12:24:09.098  1035  1555 D wifi    : failed to get capabilities : -3
09-02 12:24:09.098  1035  1555 E WifiScanningService: could not get scan capabilities
09-02 12:24:09.098  1035  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.098  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 12:24:09.098  1035  1390 D LGWifiP2pService: P2pEnablingState
09-02 12:24:09.098  1035  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 12:24:09.098  1035  1390 D LGWifiP2pServ,ice: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.098  1035  1390 D LGWifiP2pService: P2p socket connection successful
09-02 12:24:09.098  1035  1390 D LGWifiP2pService: P2pEnabledState
09-02 12:24:09.098  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 12:24:09.098  1035  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 12:24:09.099  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 12:24:09.099  1035  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 12:24:09.099  1035  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 12:24:09.099  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 12:24:09.100  1035  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 12:24:09.100  1941  1941 D WfdsService: WifiP2pState is changed : true
09-02 12:24:09.100  1035  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 12:24:09.100  1941  2345 D WfdsService: Receive the WFDS_ENABLE Method
09-02 12:24:09.100  1035  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 12:24:09.100  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-02 12:24:09.100  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-02 12:24:09.100  1941  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 12:24:09.100  7210  7210 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 12:24:09.100  7210  7210 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 12:24:09.101  1941  2345 D WfdsService: selectPreferredScanChannel [36]
09-02 12:24:09.101  1941  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 12:24:09.101  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 12:24:09.101  1941  1941 D WfdsService: isConnected: false
09-02 12:24:09.102  1035  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 12:24:09.102  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 12:24:09.102  1035  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 12:24:09.102  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3,
09-02 12:24:09.103  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
,09-02 12:24:09.103  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 12:24:09.103  1035  1390 D LGWifiP2pService: before postfix = G3
09-02 12:24:09.103  1035  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 12:24:09.103  1035  1390 D WifiServerServiceExt: postfix byte check : 2
09-02 12:24:09.103  1035  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 12:24:09.103  1035  1390 D LGWifiP2pService: after postfix = G3
09-02 12:24:09.103  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 12:24:09.103  7210  7210 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 12:24:09.103  1035  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 12:24:09.104  1035  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 12:24:09.104  1035  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 12:24:09.104  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 12:24:09.104  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 12:24:09.104  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 12:24:09.105  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 12:24:09.105  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 12:24:09.105  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 12:24:09.105  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 12:24:09.106  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 12:24:09.106  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.107  7210  7210 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:24:09.107  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.107  1941  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.107  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.108  1941  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.108  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:24:09.108  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.108  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.108  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.108  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.108  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.108  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.108  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.108  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.108  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.108  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.108  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.108  1035  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 12:24:09.109  1035  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:24:09.109  1035  1392 E WifiStateMachine:  Connect,ModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:24:09.109  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 12:24:09.109  1035  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:24:09.109  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
09-02 12:24:09.109  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 12:24:09.110  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-02 12:24:09.110  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 12:24:09.110  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:24:09.110  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-02 12:24:09.110  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 12:24:09.111  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 12:24:09.111  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:24:09.111  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:24:09.111  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:24:09.111  1035  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 12:24:09.111  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 12:24:09.111  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 12:24:09.111  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 12:24:09.111  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 12:24:09.111  1941  1941 D WfdsService: Update P2p Interface State: 3
09-02 12:24:09.112  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 12:24:09.112  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 12:24:09.112  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 12:24:09.112  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 12:24:09.112  1035  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 12:24:09.118  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-02 12:24:09.118  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-02 12:24:09.118  1035  1390 D LGWifiP2pService: InactiveState
09-02 12:24:09.118  1035  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.118  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.118  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 12:24:09.119  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-02 12:24:09.121  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.121  7210  7210 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:24:09.122  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.122  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-02 12:24:09.123  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 12:24:09.123  1941  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:24:09.123  1941  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.123  1035  1390 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.123  1941  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.123  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.123  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.123  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:24:09.123  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.123  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.123  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.123  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.123  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:09.123  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.123  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.124  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.124  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.124  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:09.124  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.124  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.124  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:09.124  1035  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.124  1035  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 12:24:09.124  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.124  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.124  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.124  1035  1392 D WifiNative-wlan0: doBoolean: SCAN
09-02 12:24:09.124  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.124  1035  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.125  1035  1392 D WifiNative-wlan0: SCAN: returned false
09-02 12:24:09.125  1035  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.125  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMac,hine$SmHandler }
09-02 12:24:09.125  1035  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:09.125  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122558  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:24:09.125  1035  1035 E WifiServerServiceExt: No p2p device connected
09-02 12:24:09.126  1941  2345 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 12:24:09.127  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122559  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:24:09.127  1035  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:09.128  1035  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:09.128  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.128  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.128  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 12:24:09.128  1035  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:09.128  1035  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:09.129  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:09.129  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:09.129  1035  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:09.130  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.131  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:09.131  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-02 12:24:09.153  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 12:24:09.179  3428  3428 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:24:09.179  3428  3428 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:09.180  3428  3428 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 12:24:09.180  7085  7243 W FormManager: Network not available. Please check & try again.
,09-02 12:24:09.192  7211  7211 I HubEmail: JNI_OnLoad()
09-02 12:24:09.192  7211  7211 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 12:24:09.192  7211  7211 I HubEmail: registerNatives()
09-02 12:24:09.192  7211  7211 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 12:24:09.192  7211  7211 I HubEmail: registerNativeMethods()
09-02 12:24:09.192  7211  7211 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 12:24:09.192  7211  7211 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-02 12:24:09.226  1035  2014 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7247 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-02 12:24:09.229  7211  7246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.233  7085  7245 V FormManager: Network unavailable.
09-02 12:24:09.236  7085  7245 V FormManager: Network unavailable.
09-02 12:24:09.240  1035  1052 I ActivityManager: Killing 6652:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-02 12:24:09.281  1035  1976 W libprocessgroup: failed to open /acct/uid_10061/pid_6652/cgroup.procs: No such file or directory
,09-02 12:24:09.373  7247  7247 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:24:09.373  7247  7247 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:09.377  7247  7247 D PhoneMonitor: Register our PhoneStateListener
,09-02 12:24:09.479  1035  1957 I art     : Explicit concurrent mark sweep GC freed 67977(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.810ms total 98.575ms
,09-02 12:24:09.500  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-02 12:24:09.504  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-02 12:24:09.522  7247  7247 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-02 12:24:09.523  7247  7247 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-02 12:24:09.524  7247  7247 D TelephonyAutoProfiling: [parse] Load xml
09-02 12:24:09.530  7247  7247 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-02 12:24:09.530  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-02 12:24:09.530  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,09-02 12:24:09.530  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-02 12:24:09.530  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-02 12:24:09.530  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-02 12:24:09.530  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-02 12:24:09.530  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-02 12:24:09.531  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-02 12:24:09.531  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-02 12:24:09.531  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-02 12:24:09.532  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-02 12:24:09.532  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-02 12:24:09.532  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-02 12:24:09.532  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-02 12:24:09.532  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-02 12:24:09.532  7247  7247 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-02 12:24:09.537  7247  7247 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-02 12:24:09.568  1035  2042 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7268 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:24:09.570  1035  2042 I ActivityManager: Killing 6783:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-02 12:24:09.623  1035  2014 W libprocessgroup: failed to open /acct/uid_10080/pid_6783/cgroup.procs: No such file or directory
,09-02 12:24:09.633  7210  7210 E wpa_supplicant: USIM:  scard_init function
09-02 12:24:09.633  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 12:24:09.633  1035  7233 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 12:24:09.634  7210  7210 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-02 12:24:09.634  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 12:24:09.634  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-02 12:24:09.634  1035  7233 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 12:24:09.634  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:24:09.634  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-02 12:24:09.636  1035  1392 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 12:24:09.638  1035  1392 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,09-02 12:24:09.639  1035  1392 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 12:24:09.640  1035  1392 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 12:24:09.640  1035  1392 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 12:24:09.653  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 12:24:09.654  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123087  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 12:24:09.657  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:09.657  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:09.658  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.658  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:24:09.658  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 12:24:09.659  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.659  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.659  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:24:09.659  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:09.659  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-02 12:24:09.659  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.661  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:09.661  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:09.662  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.758  7210  7210 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 12:24:09.763  1035  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:24:09.765  1035  1392 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:09.765  1035  1392 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:09.765  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 12:24:09.765  1035  1392 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:09.765  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 12:24:09.766  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 12:24:09.766  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 12:24:09.767  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:09.767  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:09.767  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:09.768  1035  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:09.769  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123202  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:24:09.771  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123203  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:24:09.772  1035  1392 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123205
09-02 12:24:09.773  1035  1392 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123206
09-02 12:24:09.774  1035  1392 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123207
09-02 12:24:09.775  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123208
,09-02 12:24:09.776  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-02 12:24:09.776  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:09.776  7210  7210 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:24:09.777  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:24:09.777  1035  1392 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123210
09-02 12:24:09.780  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 12:24:09.780  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:24:09.780  1035  7233 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:24:09.781  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 12:24:09.781  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-02 12:24:09.781  1035  7233 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:24:09.781  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123214  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:24:09.781  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:09.781  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:09.785  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.785  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.785  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:24:09.785  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:09.785  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:09.786  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123219  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:24:09.788  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.788  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.788  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123221  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:24:09.788  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 12:24:09.788  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.788  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:09.789  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 12:24:09.789  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123222  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:24:09.790  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:09.791  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:24:09.792  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.793  1035  1392 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123225
09-02 12:24:09.794  1035  1392 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123227
09-02 12:24:09.795  1035  1392 D WifiNative-wlan0: doString: [STATUS]
09-02 12:24:09.797  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:09.797  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:09.798  1035  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:24:09.800  1035  1392 I WifiServiceExtension: setVHTCapabilityType  : false
09-02 12:24:09.806  1035  1392 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 12:24:09.806  1035  1392 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-02 12:24:09.809  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.810  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:09.811  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:24:09.811  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.811  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.812  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 12:24:09.812  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.812  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:09.812  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 12:24:09.813  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:09.813  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:09.813  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:09.822  1035  1392 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 12:24:09.822  1035  1432 D ConnectivityService: Got NetworkAgent Messenger
09-02 12:24:09.822  1035  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:24:09.822  1035  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:24:09.822  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 12:24:09.822  1035  1432 D ConnectivityService: NetworkAgent connected
,09-02 12:24:09.823  1035  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:24:09.823  1035  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:24:09.828  1035  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:24:09.829  1035  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:24:09.829  1035  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:24:09.829  1035  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:24:09.829  1035  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:24:09.833  1035  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:24:09.834   315   894 D CommandListener: Setting iface cfg
,09-02 12:24:09.868  1035  1769 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7288 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-02 12:24:09.869  1035  1769 I ActivityManager: Killing 6805:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-02 12:24:10.068  1035  1379 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7305 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:24:10.074  1035  1379 V AlarmManager: RTC_WAKEUP set : Alarm{107bfb71 type 0 when 1472811844929 com.android.vending} when 1472811844929
09-02 12:24:10.075  1035  1392 E WifiStateMachine: Start Dhcp Watchdog 2
09-02 12:24:10.075  1035  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123508  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:10.076  1035  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123509  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:10.077  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123509  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:10.077  1035  7287 D DhcpStateMachine: StoppedState
09-02 12:24:10.077  1035  7287 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:24:10.077  1035  7287 D DhcpStateMachine: WaitBeforeStartState
,09-02 12:24:10.085  1035  1904 W libprocessgroup: failed to open /acct/uid_10097/pid_6805/cgroup.procs: No such file or directory
,09-02 12:24:10.088  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.088  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.088  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:24:10.093  1035  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123526  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:10.094  1035  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123527  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:10.094  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123527  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:10.096  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77456] from screen [on:0 period:-361932432] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 12:24:10.097  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-361932431] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 12:24:10.097  1035  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 12:24:10.102  1035  1432 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-02 12:24:10.102  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.103  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.103  1035  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.104  1035  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.104  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.105  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.105  1035  1432 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 12:24:10.106  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=97,0,0
09-02 12:24:10.106  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=97,0,0
09-02 12:24:10.106  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 12:24:10.107  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,09-02 12:24:10.109  1035  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 12:24:10.109  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 12:24:10.110  1035  1392 D WifiNative-wlan0: SET ps 0: returned true
09-02 12:24:10.110  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 12:24:10.110  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 12:24:10.110  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 12:24:10.111  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38e384cf target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.111  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38e384cf target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.111  1035  7287 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.111  1035  7287 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 12:24:10.112  1035  1392 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 12:24:10.112  1035  1392 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 12:24:10.112  1035  1392 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 12:24:10.114   315   894 D CommandListener: Setting iface cfg
09-02 12:24:10.114   315   894 D CommandListener: Trying to bring up wlan0
09-02 12:24:10.115  1035  1392 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 12:24:10.116  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:24:10.116  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:24:10.116  1035  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:24:10.117  1035  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:24:10.117  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:24:10.118  1035  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:24:10.118  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.118  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.119  1035  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.119  1035  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.120  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 12:24:10.127  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:10.128  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 12:24:10.128  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:10.129  1035  1432 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 12:24:10.129  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 12:24:10.129  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:10.129  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 12:24:10.130  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.130  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.130  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:24:10.130  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:24:10.131  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:24:10.131  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 12:24:10.131  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 12:24:10.131  1035  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 12:24:10.131  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
,09-02 12:24:10.147  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
,09-02 12:24:10.147  1035  1432 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 12:24:10.147  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:24:10.148  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:24:10.148  1035  1392 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 12:24:10.148  1035  1432 D ConnectivityService: ignoring duplicate network state non-change
,09-02 12:24:10.183  1035  1995 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7323 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:24:10.184  1035  1995 I ActivityManager: Killing 6840:com.lge.eula/1000 (adj 15): empty #17
09-02 12:24:10.285  1035  1769 W libprocessgroup: failed to open /acct/uid_1000/pid_6840/cgroup.procs: No such file or directory
,09-02 12:24:10.311  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 12:24:10.316  1035  7287 D DhcpStateMachine: DHCPV4 request on wlan0
09-02 12:24:10.317  1035  7287 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 12:24:10.317  1035  7287 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 12:24:10.319  1035  1432 D ConnectivityService: Adding iface wlan0 to network 101
,09-02 12:24:10.325  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:10.325  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:24:10.317  7340  7340 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:10.317  7340  7340 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:24:10.317  7340  7340 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:24:10.317  7340  7340 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:10.328  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.328  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.328  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 12:24:10.331  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:10.342  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.342  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.342  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 12:24:10.344  1035  1392 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 12:24:10.349  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 12:24:10.351  7340  7340 I dhcpcd  : version 5.5.6 starting
,09-02 12:24:10.352  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 12:24:10.353  7340  7340 E dhcpcd  : get_duid: m
09-02 12:24:10.353  7340  7340 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 12:24:10.353  7340  7340 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 12:24:10.356  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:10.356  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:10.361  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.362  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.362  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:24:10.362  1035  1432 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 12:24:10.362  1035  1432 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-02 12:24:10.364  1035  1432 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-02 12:24:10.365   315   894 E Netd    : netlink response contains error (File exists)
09-02 12:24:10.365  1035  1432 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-02 12:24:10.365  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 12:24:10.366  1035  1432 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 12:24:10.366  1035  1432 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-02 12:24:10.366  1035  1432 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-02 12:24:10.369  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.369  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:10.369  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:10.369  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:24:10.371  1035  1432 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 12:24:10.372  1035  1432 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 12:24:10.372  1035  1432 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-02 12:24:10.373  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.373  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 12:24:10.374  1035  1432 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,09-02 12:24:10.374  1035  1432 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:10.374  1035  1432 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:10.376  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:10.376  1035  1432 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 12:24:10.376  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 12:24:10.376  1035  1432 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:10.376  1035  1432 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 12:24:10.376  1035  1432 D ConnectivityService: currentScore = 0, newScore = 20
09-02 12:24:10.376  1035  1432 D ConnectivityService:    accepting network in place of null
09-02 12:24:10.376  1035  1432 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:10.378  1035  1392 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:10.378  1035  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:10.378   315  7347 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 12:24:10.381  1035  1432 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 12:24:10.381  1035  1432 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-02 12:24:10.381  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:24:10.382  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:10.382  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:24:10.383  1035  1432 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:10.383  1035  1432 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 12:24:10.384  1035  1432 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-02 12:24:10.384  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 12:24:10.385  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:24:10.385  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:24:10.385  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:24:10.386  1035  1432 D ConnectivityService: validation of new default Network = false
09-02 12:24:10.386  1035  1432 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 12:24:10.386  1035  1432 D DSQN    : enableDataServiceNotify 
09-02 12:24:10.386  1035  1432 D DSQN    : start dsqn bin
,09-02 12:24:10.394  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:10.394  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:24:10.395  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:10.397  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-02 12:24:10.398  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:10.398  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:24:10.398  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:10.398  1035  1432 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 12:24:10.398  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:10.398  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-02 12:24:10.399  1035  1432 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:10.399  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 12:24:10.387  7351  7351 W dsqn    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:10.387  7351  7351 W dsqn    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:10.412  7351  7351 E DSQN    : DSQN ssw
,09-02 12:24:10.420  7340  7340 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:24:10.420  7340  7340 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 12:24:10.421  7340  7340 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:24:10.421  7340  7340 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 12:24:10.421  7340  7340 D dhcpcd  : wlan0: sending REQUEST (xid 0x7045a7a6), next in 3.37 seconds
,09-02 12:24:10.429  7323  7323 I art     : Almond Protected OAT
,09-02 12:24:10.442  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-02 12:24:10.443  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:10.444  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:10.446  1817  7358 I CheckinService: active receiver: enabled
09-02 12:24:10.453  7340  7340 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-02 12:24:10.461  1817  7358 I CheckinService: Preparing to send checkin request
09-02 12:24:10.461  1817  7358 I EventLogService: Accumulating logs since 1472811769097
09-02 12:24:10.470  7305  7305 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-02 12:24:10.475  7323  7323 D WeatherApplication: removeAccount
09-02 12:24:10.476  7323  7323 D WeatherApplication: Account.length = 0
09-02 12:24:10.477  7323  7323 E WeatherApplication: OPERATOR:OPEN
09-02 12:24:10.481  7323  7323 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:10
09-02 12:24:10.484  7323  7323 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:24:10.484  7323  7323 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:24:10.486  7323  7323 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-02 12:24:10.489  7323  7323 D WeatherAncestor: connectivity changed - connection : true
09-02 12:24:10.490  7323  7323 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-02 12:24:10.490  7340  7340 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 12:24:10.490  7340  7340 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 12:24:10.491  7340  7340 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 12:24:10.491  7340  7340 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 12:24:10.491  7340  7340 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:24:10.491  7340  7340 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:24:10.491  7340  7340 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 12:24:10.491  7340  7340 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 12:24:10.505  7323  7323 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:24:10.505  7323  7323 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:24:10.505  7323  7323 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-02 12:24:10.520  7305  7305 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:24:10.520  7305  7305 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:24:10.525  7323  7323 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:24:10.525  7323  7323 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:10
,09-02 12:24:10.552  7305  7305 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-02 12:24:10.554  1035  1940 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7382 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:24:10.555  1035  1940 I ActivityManager: Killing 5632:com.lge.bnr/1000 (adj 15): empty #17
09-02 12:24:10.563  7305  7305 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-02 12:24:10.564  7305  7305 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-02 12:24:10.574  7305  7305 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-02 12:24:10.574  7305  7305 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-02 12:24:10.601  1817  7358 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-02 12:24:10.601  1035  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_5632/cgroup.procs: No such file or directory
,09-02 12:24:10.651  3491  5996 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-02 12:24:10.651  1035  1976 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:24:10.652  3491  5996 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3b49335c on behalf of 7305
09-02 12:24:10.662  7305  7305 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-02 12:24:10.670  7305  7305 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-02 12:24:10.685   280   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:24:10.685   280   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 12:24:10.685   280   386 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:24:10.685  7382  7417 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-02 12:24:10.687   280   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:24:10.687   280   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 12:24:10.687   280   386 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:24:10.688  7382  7417 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-02 12:24:10.695   280   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:24:10.695   280   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 12:24:10.695   280   386 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:24:10.695  7382  7421 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-02 12:24:10.696   280   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:24:10.696   280   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 12:24:10.696   280   386 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:24:10.697  7382  7421 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-02 12:24:10.723  1035  1645 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7422 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-02 12:24:10.725  1035  7287 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-02 12:24:10.726  1035  7287 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 12:24:10.726  1035  7287 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 12:24:10.726  1035  7287 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 12:24:10.726  1035  7287 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 12:24:10.726  1035  7287 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 12:24:10.726  1035  7287 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 12:24:10.726  1035  7287 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 12:24:10.726  1035  7287 D DhcpStateMachine: RunningState
,09-02 12:24:10.751  7422  7422 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-02 12:24:10.751  7422  7422 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-02 12:24:10.767  7422  7422 I MultiDex: VM with version 2.1.0 has multidex support
,09-02 12:24:10.768  7422  7422 I MultiDex: install
09-02 12:24:10.768  7422  7422 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-02 12:24:10.775  7422  7422 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-02 12:24:10.810  7305  7305 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-02 12:24:10.812  1035  1645 I ActivityManager: Killing 2124:com.lge.music/u0a34 (adj 15): empty #17
09-02 12:24:10.823   320  2159 V AudioFlinger: 2124 died, releasing its sessions
09-02 12:24:10.823   320  2159 V AudioFlinger:  pid 1853 @ 0
,09-02 12:24:10.824   320  2159 V AudioFlinger:  pid 3428 @ 1
09-02 12:24:10.824   320  2159 V AudioFlinger:  pid 3428 @ 2
09-02 12:24:10.891  1035  2042 W libprocessgroup: failed to open /acct/uid_10034/pid_2124/cgroup.procs: No such file or directory
,09-02 12:24:10.985  7422  7439 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:24:10.985  7422  7439 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:11.006  1035  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:24:11.006  1035  1052 D WifiService: setWifiEnabled: false pid=6705, uid=10118
09-02 12:24:11.006  1035  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:24:11.016  7382  7382 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 12:24:11.018  1035  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:11.018  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-02 12:24:11.018  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:11.018  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-02 12:24:11.018  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:11.019  1035  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:11.019  1035  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:11.019  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 12:24:11.019  1035  1392 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 12:24:11.020  1035  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:24:11.020  1035  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:24:11.020  1035  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:24:11.020  1035  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-02 12:24:11.029  1035  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:24:11.029  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:24:11.029  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:24:11.029  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.029  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.029  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:24:11.029  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:24:11.030  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:24:11.030  1035  7287 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.030   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:24:11.050  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.050  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.050  1035  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:11.050  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@274b2831
09-02 12:24:11.050  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 12:24:11.051  1035  1432 D ConnectivityService: ignoring duplicate network state non-change
09-02 12:24:11.051  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-02 12:24:11.051  1035  1390 D LGWifiP2pService: P2pDisablingState
09-02 12:24:11.051  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.051  1035  1390 D LGWifiP2pService: p2p socket connection lost
09-02 12:24:11.051  1035  1390 D LGWifiP2pService: P2pDisabledState
09-02 12:24:11.052  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-02 12:24:11.052  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:11.053  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:11.054  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:24:11.057  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:11.057  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:11.058  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:11.059  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.060  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.060  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:11.060  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-02 12:24:11.060  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.060  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.060  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:11.060  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 12:24:11.060  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-02 12:24:11.061  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 12:24:11.061  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:11.061  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:24:11.061  1941  1941 D WfdsService: WifiP2pState is changed : false
09-02 12:24:11.062  1941  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 12:24:11.062  1941  2345 D WfdsService: Set the WFDS Monitor: false
09-02 12:24:11.062  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:11.063  1035  1392 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:24:11.063  1035  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 12:24:11.063  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.063  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.064  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:24:11.064  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:24:11.064  1035  1556 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.064  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:24:11.064  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:24:11.064  1035  1555 D WifiScanningService: DefaultState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:11.065  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:24:11.065  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:24:11.065  1941  2345 D WfdsService: STATE : WfdsDisabledState - enter
09-02 12:24:11.065  1941  2349 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 12:24:11.066  1941  7236 D CtrlSupplicant: Received on exit socket, terminate
09-02 12:24:11.066  1941  7236 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 12:24:11.066  1941  7236 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 12:24:11.066  1941  7236 D ,WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 12:24:11.066  1941  2345 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 12:24:11.069  7382  7382 I LibraryLoader: Loading: webviewchromium
,09-02 12:24:11.075  7382  7382 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4518-4524)
09-02 12:24:11.075  7382  7382 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:24:11.081  7382  7382 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d793c32}
09-02 12:24:11.082  7382  7382 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:24:11.082  7382  7382 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 12:24:11.094  7382  7382 I BrowserStartupController: Initializing chromium process, renderers=0
09-02 12:24:11.095  7382  7382 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 12:24:11.105  7382  7382 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-02 12:24:11.106  7382  7382 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-02 12:24:11.106  7382  7382 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-02 12:24:11.108   320  1403 V AudioPolicyService: registerClient() client 0xb558a5a0, uid 10093
09-02 12:24:11.109  7382  7464 W AudioManagerAndroid: Requires BLUETOOTH permission
09-02 12:24:11.117  7382  7382 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:24:11.117  7382  7382 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:24:11.117  7382  7382 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:24:11.117  7382  7382 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:24:11.117  7382  7382 I Adreno-EGL: Remote Branch: 
09-02 12:24:11.117  7382  7382 I Adreno-EGL: Local Patches: 
09-02 12:24:11.117  7382  7382 I Adreno-EGL: Reconstruct Branch: 
,09-02 12:24:11.122   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:24:11.122  1035  1432 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 12:24:11.122  1035  1432 D DSQN    : disableDataServiceNotify
09-02 12:24:11.122  1035  1432 D DSQN    : stop dsqn bin
09-02 12:24:11.123  1035  1392 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 12:24:11.124  1035  1392 D WifiNative-p2p0: TERMINATE: returned true
09-02 12:24:11.124  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:11.124  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:11.124  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:24:11.125  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-02 12:24:11.125  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.125  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.125  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 12:24:11.125  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:11.125  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:11.127  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 12:24:11.127  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:11.127  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 12:24:11.128  1035  1432 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-02 12:24:11.128  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:11.128  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:11.129  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 12:24:11.129  1035  1432 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:11.129  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:11.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:11.129  1035  1432 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 12:24:11.129  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:11.129  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetwor,kChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:11.129  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 12:24:11.129  1035  1432 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 12:24:11.129  1035  1432 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 12:24:11.130  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:11.130  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:24:11.131  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:11.131  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:11.131  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:11.131  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:11.131  1035  1432 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:11.131  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:24:11.131  1035  1432 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:11.131  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:11.131  1035  1432 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:11.131  1035  1432 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:11.132  1035  1432 D NetworkManagementService: Removing idletimer
09-02 12:24:11.132  1035  1432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.132  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:11.132  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:24:11.133  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 12:24:11.133  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:24:11.133  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:24:11.133  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:24:11.133  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:24:11.134  1035  1392 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:11.134  1035  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:11.134  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:24:11.135  1035  1035 D LocSvc_java: Sending msg:, 4 arg1:0 arg2:1
09-02 12:24:11.135  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:24:11.135  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:24:11.135  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-02 12:24:11.162  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:24:11.163  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:11.163  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:24:11.174  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:24:11.175  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:11.175  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:11.183  7382  7382 I NSApplication: Starting up...
,09-02 12:24:11.211  7478  7478 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-02 12:24:11.233  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-02 12:24:11.233  7210  7210 I wpa_supplicant: monitor socket send errors count : 1
09-02 12:24:11.233  7210  7210 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
09-02 12:24:11.235  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 12:24:11.235  1035  7233 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 12:24:11.242  1035  1917 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7484 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-02 12:24:11.243  1035  1917 I ActivityManager: Killing 6976:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-02 12:24:11.249  1035  7287 D DhcpStateMachine: StoppedState
09-02 12:24:11.249  1035  7287 D DhcpStateMachine: StoppedState{ when=-184ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:24:11.257  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:24:11.258  7210  7210 W wpa_supplicant: USIM:  scard_deinit function
09-02 12:24:11.259  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 12:24:11.259  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:24:11.259  1035  7233 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:24:11.259  1035  7233 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 12:24:11.259  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:11.259  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:11.259  1035  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124692
09-02 12:24:11.260  1035  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124693
09-02 12:24:11.261  1035  1118 D Tethering: InitialState.processMessage what=4
09-02 12:24:11.261  1035  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124694  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:24:11.262  1035  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124695  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:24:11.270  7478  7478 I dex2oat : dex2oat took 58.904ms (threads: 4)
,09-02 12:24:11.280  7422  7439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:24:11.280  7422  7439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:24:11.280  7422  7439 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:24:11.280  7422  7439 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:24:11.280  7422  7439 I Adreno-EGL: Remote Branch: 
09-02 12:24:11.280  7422  7439 I Adreno-EGL: Local Patches: 
09-02 12:24:11.280  7422  7439 I Adreno-EGL: Reconstruct Branch: 
09-02 12:24:11.314  1035  1052 W libprocessgroup: failed to open /acct/uid_10037/pid_6976/cgroup.procs: No such file or directory
,09-02 12:24:11.315  1035  1392 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 12:24:11.316  1035  1392 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-02 12:24:11.316  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{bd5b6a8 type 2 when 124705 com.google.android.gms} when 124705
09-02 12:24:11.320  1035  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:24:11.322  1035  1392 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:11.322  1035  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:11.342  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 12:24:11.342  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 12:24:11.342  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 12:24:11.342  1035  7233 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 12:24:11.343  1035  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-02 12:24:11.344  7484  7484 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:11.348  7422  7439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:24:11.348  7422  7439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:24:11.348  7422  7439 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:24:11.348  7422  7439 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:24:11.348  7422  7439 I Adreno-EGL: Remote Branch: 
09-02 12:24:11.348  7422  7439 I Adreno-EGL: Local Patches: 
09-02 12:24:11.348  7422  7439 I Adreno-EGL: Reconstruct Branch: 
,09-02 12:24:11.399  1035  1432 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 12:24:11.445  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-02 12:24:11.445  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 12:24:11.445  1941  2345 D WfdsService: Set the WFDS Monitor: false
09-02 12:24:11.445  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:24:11.445  1035  1392 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 12:24:11.446  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:11.446  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:11.446  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 12:24:11.449  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:24:11.453  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:24:11.455  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:11.455  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:11.455  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:11.456  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:11.456  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:11.456  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 12:24:11.457  1035  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 12:24:11.457  1035  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 12:24:11.530  7422  7439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:24:11.530  7422  7439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:24:11.530  7422  7439 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:24:11.530  7422  7439 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:24:11.530  7422  7439 I Adreno-EGL: Remote Branch: 
09-02 12:24:11.530  7422  7439 I Adreno-EGL: Local Patches: 
09-02 12:24:11.530  7422  7439 I Adreno-EGL: Reconstruct Branch: 
,09-02 12:24:11.563  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 12:24:11.566  6446  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:24:11.581  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:11.588  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:24:11.588  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:11.589  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:24:11.589  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 12:24:11.590  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
09-02 12:24:11.593  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@72d021b
09-02 12:24:11.593  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:24:11.593  7172  7172 D AppUp4:CustFacade: isPhone : true
09-02 12:24:11.593  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:24:11.594  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:24:11.597   315  7513 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-02 12:24:11.598  1035  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 12:24:11.599  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:11.599  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:11.600  1817  7358 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-02 12:24:11.603  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:11.605  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:11.609  4792  7516 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:24:11.612  4792  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:11.612  4792  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:11.613  1817  7358 I CheckinService: active receiver: disabled
,09-02 12:24:11.625  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 12:24:11.643  7211  7519 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:24:11.647  3428  3428 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-02 12:24:11.647  3428  3428 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:11.648  3428  3428 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 12:24:11.650  7085  7520 W FormManager: Network not available. Please check & try again.
09-02 12:24:11.653  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:24:11.653  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:24:11.662  7085  7521 V FormManager: Network unavailable.
,09-02 12:24:11.665  7323  7323 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:11
09-02 12:24:11.668  7085  7521 V FormManager: Network unavailable.
09-02 12:24:11.668  7323  7323 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:24:11.668  7323  7323 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:24:11.669  7323  7323 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:24:11.669  7323  7323 D WeatherAncestor: connectivity changed - connection : true
09-02 12:24:11.669  7323  7323 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ac3191
09-02 12:24:11.670  7323  7323 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:24:11.670  7323  7323 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:24:11.670  7323  7323 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:24:11.670  7323  7323 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:24:11.670  7323  7323 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:11
09-02 12:24:11.701  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-02 12:24:11.702  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:24:11.702  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:24:11.702  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:24:11.702  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:24:11.703  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:24:11.703  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 12:24:11.703  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:24:11.703  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:24:11.703  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:24:11.704  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 12:24:11.714  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:11.723  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:24:11.728  7085  7524 W FormManager: Network not available. Please check & try again.
09-02 12:24:11.731  7085  7525 V FormManager: Network unavailable.
09-02 12:24:11.732  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:11.739  7085  7525 V FormManager: Network unavailable.
,09-02 12:24:11.766  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:11.772  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:24:11.777  7085  7527 W FormManager: Network not available. Please check & try again.
,09-02 12:24:11.787  7085  7528 V FormManager: Network unavailable.
,09-02 12:24:11.788  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:11.798  7085  7528 V FormManager: Network unavailable.
,09-02 12:24:11.820  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-02 12:24:11.821  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:11.826  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:11.831  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:11.837  4792  7529 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:24:11.841  4792  7530 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:24:11.841  4792  7530 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:11.896  1035  1940 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7531 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 12:24:11.919   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.363ms
,09-02 12:24:11.962   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 41.095ms
,09-02 12:24:11.984   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 532us total 21.610ms
,09-02 12:24:12.039  7531  7531 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 12:24:12.039  7531  7531 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 12:24:12.048  7531  7531 V [BNRBootReceiver]: Boot Receiver Return
09-02 12:24:12.051  7531  7531 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 12:24:12.053  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.065  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.081  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.093  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.093  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:12.095  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:24:12.098  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 12:24:12.106  6996  6996 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-02 12:24:12.110  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.120  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.133  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.149  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.150  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.154  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:24:12.163  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.185  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.205  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.218  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.219  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.220  7047  7047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:12.228  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.238  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.247  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.249  6868  7161 D UEI.SmartControl: Internal timer expired: 4
09-02 12:24:12.249  6868  7161 D UEI.SmartControl: unbind internal service
09-02 12:24:12.260  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.261  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.263  7047  7047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:12.268  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.278  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.286  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.296  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:24:12.296  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.297  7047  7047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:12.305  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.319  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.330  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.346  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.346  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:12.347  7047  7047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:24:12.360  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:12.376  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.383  6868  7155 D serial_port: close(fd = 24)
09-02 12:24:12.386  6868  7155 I UEI.SmartControl: Serial port is closed.
09-02 12:24:12.388  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.399  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.400  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.401  7047  7047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:12.417  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:12.429  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.438  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.449  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.449  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.457  7047  7047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:12.465  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:12.477  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.487  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.495  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.496  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.497  7047  7047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:24:12.504  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.509  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 12:24:12.518  1035  1407 D WifiService: New client listening to asynchronous messages
,09-02 12:24:12.518  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:12.523  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.531  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.541  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:24:12.541  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:12.542  7047  7047 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 12:24:12.543  7047  7047 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:24:12.543  7047  7047 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 12:24:12.549  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.557  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 12:24:12.560  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:12.565  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.576  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.588  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.588  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:24:12.589  7047  7047 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-02 12:24:12.591  7047  7047 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:24:12.591  7047  7047 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 12:24:12.597  1035  1940 I ActivityManager: Killing 7064:com.lge.settings.easy/1000 (adj 15): empty #17
09-02 12:24:12.634  1035  1645 W libprocessgroup: failed to open /acct/uid_1000/pid_7064/cgroup.procs: No such file or directory
,09-02 12:24:12.640  2211  2211 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-02 12:24:12.654  2211  2211 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-02 12:24:12.655  2211  2211 D c       : Getting all permits...
09-02 12:24:12.655  2211  2211 D a       : Opening database...
,09-02 12:24:12.663  2211  2211 D a       : Opening database auth.proximity.permit_store...
,09-02 12:24:12.665  2211  2211 D a       : Closing database...
09-02 12:24:12.681  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:12.688  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:24:12.688  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:12.689  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:12.696  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.704  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.715  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:12.715  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:12.717  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:24:12.725  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:12.731  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:24:12.731  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:12.731  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:12.738  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.749  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.761  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:24:12.762  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:12.767  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:24:12.775  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:12.783  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:24:12.783  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:12.783  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:12.791  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:12.800  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:24:12.813  7047  7047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:24:12.814  7047  7047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:12.818  7047  7047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:24:12.829  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:12.838  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:24:12.843  7085  7556 W FormManager: Network not available. Please check & try again.
,09-02 12:24:12.849  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.851  7085  7557 V FormManager: Network unavailable.
09-02 12:24:12.859  7085  7557 V FormManager: Network unavailable.
,09-02 12:24:12.889   315  7559 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-02 12:24:12.889  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:24:12.889  1035  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 12:24:12.892  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:12.897  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:24:12.906  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:24:12.916  4792  7560 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:24:12.920  4792  7561 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-02 12:24:12.921  4792  7561 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:12.922  7016  7016 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 12:24:12.922  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:24:12.922  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:12.926  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:24:12.935  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:12.935  7085  7563 W FormManager: Network not available. Please check & try again.
09-02 12:24:12.948  7085  7564 V FormManager: Network unavailable.
,09-02 12:24:12.952  7085  7564 V FormManager: Network unavailable.
,09-02 12:24:12.956  2211  2211 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-02 12:24:13.105  1035  1392 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-361929423] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:24:13.108  1035  1392 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-361929421] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-02 12:24:13.383  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:13.391  1035  1118 D Tethering: MasterInitialState.processMessage what=3
09-02 12:24:13.395  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:13.396  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:13.401  1035  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:13.405  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 12:24:13.407  6446  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:24:13.417  5854  5854 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 12:24:13.435  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:13.462  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:24:13.462  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:13.462  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:24:13.462  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-02 12:24:13.467  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
09-02 12:24:13.471  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@72d021b
09-02 12:24:13.471  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:24:13.471  7172  7172 D AppUp4:CustFacade: isPhone : true
09-02 12:24:13.473  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:24:13.473  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:24:13.477  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:13.478  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-02 12:24:13.484  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:13.488  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:13.525  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 12:24:13.527  4792  7584 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 12:24:13.535  4792  7585 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:13.535  4792  7585 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:13.539  1035  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:13.552  3428  3428 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:24:13.552  3428  3428 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:13.553  3428  3428 I LgeMiscReceiver: networkInfo.isConnected() = true
09-02 12:24:13.553  3428  3428 D PhoneState: setPdpRejectCasuse : false
,09-02 12:24:13.557  7211  7591 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:24:13.557  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:24:13.557  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:24:13.569  7085  7592 W FormManager: Network not available. Please check & try again.
,09-02 12:24:13.573  7323  7323 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:13
,09-02 12:24:13.574  7085  7594 V FormManager: Network unavailable.
,09-02 12:24:13.574  7323  7323 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:24:13.574  7323  7323 D Weather.Utils: 2 : All the weather widget is gone.
,09-02 12:24:13.575  7323  7323 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-02 12:24:13.575  7323  7323 D WeatherAncestor: connectivity changed - connection : true
09-02 12:24:13.575  7323  7323 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ac3191
09-02 12:24:13.576  7323  7323 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:24:13.576  7323  7323 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-02 12:24:13.576  7323  7323 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:24:13.576  7323  7323 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:24:13.576  7323  7323 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:13
09-02 12:24:13.577  7085  7594 V FormManager: Network unavailable.
09-02 12:24:14.020  1035  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:14.023  1035  1768 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-02 12:24:14.048  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:24:14.048  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:14.048  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-02 12:24:14.052  1035  1118 D BluetoothManagerService: Message: 1
09-02 12:24:14.052  1035  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 12:24:14.078  1035  1118 D BluetoothManagerService: Message: 20
09-02 12:24:14.079  1035  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24ca8a87:true
,09-02 12:24:14.082  7108  7108 D BluetoothAdapterState: make
09-02 12:24:14.087  7108  7108 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 12:24:14.087  7108  7108 I bluedroid-qcom: init
09-02 12:24:14.089  7108  7608 I BluetoothAdapterState: Entering OffState
09-02 12:24:14.089  7108  7108 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 12:24:14.089  7108  7108 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 12:24:14.089  7108  7108 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:24:14.089  7108  7108 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 12:24:14.089  7108  7108 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 12:24:14.091  7108  7108 I bluedroid-qcom: get_profile_interface socket
09-02 12:24:14.092  7108  7108 I bluedroid-qcom: get_profile_interface map_client
,09-02 12:24:14.096  7108  7612 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 12:24:14.099  7108  7612 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 12:24:14.087  7611  7611 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:14.097  7611  7611 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:14.110  7611  7611 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,09-02 12:24:14.115  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 12:24:14.115  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:24:14.117  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-02 12:24:14.117  1035  1118 D BluetoothManagerService: Message: 40
09-02 12:24:14.117  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 12:24:14.118  7108  7125 I bluedroid-qcom: config_hci_snoop_log
09-02 12:24:14.119  1035  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 12:24:14.119  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 12:24:14.119  7611  7611 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 12:24:14.119  7611  7611 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-02 12:24:14.122  7611  7611 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-02 12:24:14.129  7611  7611 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 12:24:14.129  7611  7611 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 12:24:14.132  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.143  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:14.147  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:14.147  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.152  7108  7608 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 12:24:14.153  1035  1118 D Tethering: MasterInitialState.processMessage what=3
09-02 12:24:14.158  1035  1118 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:24:14.161  7108  7612 D BluetoothAdapterProperties: Name is: G3
,09-02 12:24:14.163  7108  7608 D BluetoothAdapterProperties: Setting state to 11
,09-02 12:24:14.163  7108  7608 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 12:24:14.165  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:14.165  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 12:24:14.165  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 12:24:14.166  7108  7608 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 12:24:14.178  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 12:24:14.186  1035  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.191  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:24:14.192  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:14.193  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:14.196  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:14.197  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-02 12:24:14.201  6446  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:24:14.202  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:14.205  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:14.207  7108  7608 D BluetoothBondStateMachine: make
,09-02 12:24:14.212  7108  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.212  7108  7630 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 12:24:14.213  7108  7608 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 12:24:14.213  7108  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.213  7108  7608 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 12:24:14.214  1035  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.215  1035  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:14.215  7108  7608 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 12:24:14.215  1035  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:14.217  5854  5854 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 12:24:14.218  7108  7108 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:24:14.219  7108  7108 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:14.219  7108  7108 V BluetoothPbapReceiver: ***********state = 11
,09-02 12:24:14.226  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:14.228  7108  7608 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:24:14.264  1035  1768 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7633 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-02 12:24:14.271  5854  5854 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 12:24:14.272  7108  7608 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:14.274  7108  7108 D HeadsetService: Received start request. Starting profile...
09-02 12:24:14.274  7108  7108 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:24:14.275  7108  7108 D LGBluetoothHfpAdapter: Version 1.6
09-02 12:24:14.278  7108  7108 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-02 12:24:14.279  7108  7108 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:24:14.280  7108  7108 D HeadsetStateMachine: make
,09-02 12:24:14.284  7108  7608 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:14.292  7108  7608 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:24:14.299  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.301  7108  7608 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:14.306  7108  7608 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:24:14.313  7108  7608 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:14.316  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:24:14.316  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.316  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:24:14.316  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 12:24:14.322  7108  7108 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:24:14.322  7108  7108 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:24:14.401  1035  1051 I art     : Explicit concurrent mark sweep GC freed 117899(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.295ms total 85.374ms
,09-02 12:24:14.405  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
09-02 12:24:14.410  7108  7108 D HeadsetStateMachine: max_hf_connections = 1
09-02 12:24:14.410  7108  7108 I bluedroid-qcom: get_profile_interface handsfree
,09-02 12:24:14.416  7108  7108 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 12:24:14.416  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@72d021b
09-02 12:24:14.416  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:24:14.416  7172  7172 D AppUp4:CustFacade: isPhone : true
09-02 12:24:14.417  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:24:14.417  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:24:14.417   320   320 V AudioPolicyService: registerClient() client 0xb558a5c0, uid 1002
09-02 12:24:14.417   320  2159 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 12:24:14.417   320  2159 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:24:14.417   320  2159 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:24:14.417  7108  7108 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,09-02 12:24:14.420   320  1403 V AudioFlinger: registerClient() client 0xb1433160, pid 7108
09-02 12:24:14.421   320  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:14.421   320  1397 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:14.422  1035  1957 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:14.422  1035  1957 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:14.422  1601  3485 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:14.422  1601  3485 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:14.423  3428  3447 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:14.423  3428  3447 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:14.423  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:14.423  7108  7108 V ToneGenerator: Create Track: 0xb4928080
09-02 12:24:14.423  7108  7108 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 12:24:14.423  7108  7108 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 12:24:14.423  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:14.424   320  1402 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:24:14.424   320  1402 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
,09-02 12:24:14.424   320  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:24:14.424   320  1402 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:24:14.424  7108  7108 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 12:24:14.424   320  2159 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 12:24:14.424   320  1403 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:24:14.425   320  1403 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 12:24:14.425   320  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:24:14.425   320  1403 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:24:14.425   320  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:14.425   320  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:14.425  1035  1769 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:14.425  1035  1769 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:14.425  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:14.426  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:14.426  7108  7108 V AudioSystem: getLatency() output 2, latency 50
09-02 12:24:14.426  7108  7123 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:14.426  7108  7123 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 12:24:14.426  7108  7123 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:14.426  7108  7123 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 12:24:14.426  7108  7108 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 12:24:14.426  7108  7108 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 12:24:14.427   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 12:24:14.427   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:24:14.427   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 12:24:14.427   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:24:14.427   320   320 V AudioFlinger: createTrack() lSessionId: 20
09-02 12:24:14.427  3428  3448 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:14.427  3428  3448 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:14.427  1853  4473 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:14.428  1853  4473 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:14.428  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.429  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:14.430  7108  7108 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 12:24:14.430   320  2159 V AudioFlinger: acquiring 20 from 7108, for 7108
09-02 12:24:14.430   320  2159 V AudioFlinger:  added new entry for 20
09-02 12:24:14.431  7108  7108 V ToneGenerator: ToneGenerator INIT OK, time: 127880
09-02 12:24:14.431  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.431  7108  7649 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 12:24:14.431  7108  7649 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:24:14.431  7108  7649 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:24:14.431  7108  7649 D HeadsetStateMachine: ,[BTUI] change sampling rate to 8000 when device is disconnected
09-02 12:24:14.432   320  2160 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7108
09-02 12:24:14.432  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.432   320  2160 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 12:24:14.432   320  2160 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 12:24:14.432   320  2160 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 12:24:14.432   320  2160 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 12:24:14.432   320  2160 V voice   : voice_set_parameters: exit with code(0)
09-02 12:24:14.432   320  2160 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 12:24:14.433   320  2160 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 12:24:14.433   320  2160 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 12:24:14.433   320  2160 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 12:24:14.433   320  2160 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 12:24:14.433   320  2160 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 12:24:14.433  7108  7108 D A2dpService: Received start request. Starting profile...
,09-02 12:24:14.434  7108  7649 V ToneGenerator: ToneGenerator destructor
09-02 12:24:14.434  7108  7649 V ToneGenerator: stopTone
09-02 12:24:14.434  7108  7649 V ToneGenerator: Delete Track: 0xb4928080
09-02 12:24:14.434  7108  7649 V AudioTrack: ~AudioTrack, releasing session id from 7108 on behalf of 7108
09-02 12:24:14.434   320  1402 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 12:24:14.434   320  2159 V AudioFlinger: releasing 20 from 7108 for 7108
09-02 12:24:14.434   320  1402 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 12:24:14.434   320  2159 V AudioFlinger:  decremented refcount to 0
09-02 12:24:14.434   320  2159 V AudioFlinger: purging stale effects
09-02 12:24:14.434   320  1269 V AudioPolicyService: AudioCommandThread() waking up
09-02 12:24:14.434   320  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 12:24:14.434   320  1269 V AudioPolicyManager: releaseOutput() 2
09-02 12:24:14.434   320  1269 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 12:24:14.435   320  1402 V AudioFlinger: PlaybackThread::Track destructor
09-02 12:24:14.435   320  1402 V AudioFlinger: removeClient_l() pid 7108, calling pid 320
09-02 12:24:14.435  7108  7108 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 12:24:14.435  7108  7108 V Avrcp   : make
09-02 12:24:14.436  1035  1051 W Process : Unable to open /proc/7652/status
09-02 12:24:14.436  7108  7108 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 12:24:14.436  7108  7108 I bluedroid-qcom: get_profile_interface avrcp
09-02 12:24:14.437  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:14.437  7108  7608 V LGMDMManager: Create singleton instance
09-02 12:24:14.441  7108  7608 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 12:24:14.442  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:14.444  7108  7108 V AudioManager: registerRemoteController: size of Media player list: 0
09-02 12:24:14.446  4792  7654 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:24:14.446  7108  7108 E AudioManager: No RCC entry present to update
09-02 12:24:14.446  7108  7108 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 12:24:14.447  4792  7655 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.447  4792  7655 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:14.451  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 12:24:14.451  7108  7108 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 12:24:14.452  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 12:24:14.452  7108  7108 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 12:24:14.458  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-02 12:24:14.500  7085  7659 W FormManager: Network not available. Please check & try again.
,09-02 12:24:14.503  7211  7657 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:14.504  7633  7633 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-02 12:24:14.504  3428  3428 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:24:14.504  3428  3428 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:14.504  7633  7633 W LG Account v2.2: No ProfileInfo entries
09-02 12:24:14.504  7633  7633 I LG Account v2.2: isEnabled: false
09-02 12:24:14.504  3428  3428 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 12:24:14.504  7633  7633 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 12:24:14.504  7633  7633 I Feature : [Lifetracker]Country: EU
09-02 12:24:14.505  7633  7633 I Feature : [Lifetracker]Operator: OPEN
09-02 12:24:14.505  7633  7633 I Feature : [Lifetracker]Ranking support: false
09-02 12:24:14.505  7633  7633 I Feature : [Lifetracker]Comfort support: false
09-02 12:24:14.505  7633  7633 I Feature : [Lifetracker]Accessory: true
09-02 12:24:14.505  7633  7633 I Feature : [Lifetracker]Health device: true
09-02 12:24:14.505  7633  7633 I Feature : [Lifetracker]Extra Pedometer: false
09-02 12:24:14.505  7633  7633 I Feature : [Lifetracker]Blood glucose device: false
09-02 12:24:14.506  7633  7633 I Feature : [Lifetracker]Device Number: 3
09-02 12:24:14.509  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:24:14.509  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:24:14.511  7085  7660 V FormManager: Network unavailable.
09-02 12:24:14.523  7085  7660 V FormManager: Network unavailable.
,09-02 12:24:14.529  6996  6996 D BluetoothPermissionRequest: onReceive
09-02 12:24:14.535  7323  7323 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:14
09-02 12:24:14.536  1035  1574 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:24:14.536  1035  1574 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:24:14.537  7323  7323 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:24:14.537  7323  7323 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:24:14.537  7323  7323 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:24:14.538  7323  7323 D WeatherAncestor: connectivity changed - connection : true
09-02 12:24:14.538  7323  7323 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ac3191
,09-02 12:24:14.538  7323  7323 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:24:14.538  7323  7323 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:24:14.539  7323  7323 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:24:14.539  7323  7323 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:24:14.539  7323  7323 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:14
09-02 12:24:14.539  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:24:14.567  6446  6446 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 12:24:14.573  6446  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:24:14.600  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:14.609  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:24:14.610  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.610  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:24:14.610  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 12:24:14.612  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 12:24:14.616  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@72d021b
,09-02 12:24:14.616  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:24:14.617  7172  7172 D AppUp4:CustFacade: isPhone : true
09-02 12:24:14.617  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:24:14.617  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:24:14.622  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.623  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:14.627  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:24:14.630  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:14.635  4792  7664 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 12:24:14.638  4792  7665 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:14.638  4792  7665 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:14.640  1035  1957 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 12:24:14.647  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 12:24:14.649  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 12:24:14.654  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:24:14.655  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 12:24:14.656  7108  7108 I BluetoothA2dpServiceJni: classInitNative
09-02 12:24:14.656  7108  7108 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:24:14.656  7108  7108 D A2dpStateMachine: make
09-02 12:24:14.658  7108  7108 I bluedroid-qcom: get_profile_interface a2dp
09-02 12:24:14.658  7108  7667 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-02 12:24:14.662  7108  7108 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:24:14.662  7108  7108 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 12:24:14.664  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.665  7108  7108 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 12:24:14.666  7108  7108 D HidService: Received start request. Starting profile...
09-02 12:24:14.666  7108  7666 D A2dpStateMachine: Enter Disconnected: -2
09-02 12:24:14.666  7108  7108 I bluedroid-qcom: get_profile_interface hidhost
09-02 12:24:14.666  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.668  7108  7108 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:24:14.669  7108  7108 D HealthService: Received start request. Starting profile...
,09-02 12:24:14.671  7108  7108 I bluedroid-qcom: get_profile_interface health
09-02 12:24:14.672  7108  7108 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:24:14.672  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.672  3428  3428 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:24:14.672  7108  7108 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 12:24:14.672  3428  3428 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:24:14.673  3428  3428 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 12:24:14.674  7108  7108 D PanService: Received start request. Starting profile...
09-02 12:24:14.674  7108  7108 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:24:14.674  7108  7108 I bluedroid-qcom: get_profile_interface pan
09-02 12:24:14.679  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:24:14.679  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:24:14.681  7108  7108 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 12:24:14.681  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.682  7108  7108 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-02 12:24:14.686  7108  7108 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:24:14.686  7108  7108 D BtGatt.GattService: Received start request. Starting profile...
09-02 12:24:14.686  7108  7108 D BtGatt.GattService: start()
09-02 12:24:14.686  7108  7108 I bluedroid-qcom: get_profile_interface gatt
09-02 12:24:14.686  7211  7669 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:14.687  7108  7108 D BtGatt.AdvertiseManager: advertise manager created
09-02 12:24:14.688  7085  7671 W FormManager: Network not available. Please check & try again.
09-02 12:24:14.694  7323  7323 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:14
,09-02 12:24:14.695  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.695  7323  7323 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:24:14.695  7323  7323 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:24:14.696  7323  7323 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:24:14.696  7323  7323 D WeatherAncestor: connectivity changed - connection : true
09-02 12:24:14.696  7323  7323 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ac3191
09-02 12:24:14.696  7323  7323 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:24:14.697  7323  7323 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:24:14.697  7323  7323 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:24:14.697  7323  7323 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:24:14.697  7323  7323 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:14
09-02 12:24:14.697  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.697  7108  7108 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 12:24:14.698  7108  7108 V BluetoothMapService: BluetoothMapBinder()
09-02 12:24:14.699  7108  7108 D BluetoothMapService: Received start request. Starting profile...
09-02 12:24:14.699  7085  7675 V FormManager: Network unavailable.
09-02 12:24:14.699  7108  7108 D BluetoothMapService: start()
09-02 12:24:14.705  7085  7675 V FormManager: Network unavailable.
,09-02 12:24:14.706  7108  7108 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 12:24:14.706  7108  7108 D BluetoothMapEmailAppObserver: createReceiver()
09-02 12:24:14.708  7108  7108 D BluetoothMapEmailAppObserver: initObservers()
,09-02 12:24:14.708  7108  7108 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-02 12:24:14.719  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:14.720  7108  7108 D HeadsetStateMachine: Proxy object connected
,09-02 12:24:14.721  7108  7108 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 12:24:14.722  7108  7108 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 12:24:14.726  7108  7108 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:24:14.726  7108  7649 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 12:24:14.727  7108  7649 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 12:24:14.727  7108  7649 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 12:24:14.729  7108  7108 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:24:14.732  7108  7108 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 12:24:14.734  7108  7108 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:24:14.735  7108  7108 V PanService: [BTUI] SIM Extra State :ABSENT
09-02 12:24:14.737  7108  7108 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:24:14.740  7108  7108 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 12:24:14.740  7108  7108 V BluetoothMapService: Handler(): got msg=1
09-02 12:24:14.741  7108  7608 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 12:24:14.741  7108  7608 I bluedroid-qcom: enable
09-02 12:24:14.741  7108  7679 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 12:24:14.741  7108  7679 I bt-btu  : btu_task pending for preload complete event
09-02 12:24:14.742  7108  7608 I bt_hci_bdroid: init
09-02 12:24:14.743  7108  7608 I bt_vendor: bt-vendor : init
09-02 12:24:14.743  7108  7608 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 12:24:14.743  7108  7608 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 12:24:14.743  7108  7608 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 12:24:14.743  7108  7608 D bt_userial_mct: userial_init
09-02 12:24:14.744  7108  7108 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:24:14.745  7108  7608 D bt_hci_bdroid: set_power 1
09-02 12:24:14.745  7108  7608 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 12:24:14.745  7108  7608 I bt_vendor: Starting hciattach daemon
09-02 12:24:14.745  7108  7608 I bt_vendor: try to set true
09-02 12:24:14.737  7682  7682 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:14.748  7108  7108 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:14.748  7108  7108 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:14.748  7108  7108 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:14.748  7108  7108 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:14.748  7108  7108 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-02 12:24:14.737  7682  7682 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:14.772  7683  7683 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 12:24:14.819  1035  1768 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7687 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:24:14.869  7687  7687 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 12:24:14.875  7706  7706 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
09-02 12:24:14.886  1035  1995 I ActivityManager: Killing 7305:com.android.vending/u0a44 (adj 15): empty #17
,09-02 12:24:14.889  7707  7707 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-02 12:24:14.915  7709  7709 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:24:14.927  7710  7710 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-02 12:24:14.933  1035  1051 W libprocessgroup: failed to open /acct/uid_10044/pid_7305/cgroup.procs: No such file or directory
,09-02 12:24:14.940  7711  7711 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:24:14.956  7712  7712 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-02 12:24:14.991  7714  7714 I libmdmdetect: ESOC framework not supported
,09-02 12:24:14.992  7714  7714 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 12:24:15.005  7714  7714 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-02 12:24:15.005  7714  7714 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 12:24:15.005  7714  7714 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 12:24:15.005  7714  7714 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 12:24:15.005  7714  7714 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 12:24:15.005  7714  7714 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 12:24:15.005  7714  7714 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-02 12:24:15.049  7714  7718 E QC-QMI  : qmi_client [7714] 14: failed to locate client data
,09-02 12:24:15.049   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-02 12:24:15.049   469   469 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-02 12:24:15.097  7719  7719 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 12:24:15.118  7720  7720 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 12:24:15.135  1035  1105 W ProcessCpuTracker: Skipping unknown process pid 7682
09-02 12:24:15.136  1035  1105 W ProcessCpuTracker: Skipping unknown process pid 7719
,09-02 12:24:15.149  7108  7608 I bt_vendor: bluetooth satus is on
09-02 12:24:15.149  7108  7608 D bt_hci_bdroid: preload
,09-02 12:24:15.149  7108  7681 D bt_userial_mct: userial_open(port:0)
,09-02 12:24:15.149  7108  7681 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 12:24:15.153  7108  7681 I bt_vendor: Done intiailizing UART
09-02 12:24:15.154  7108  7681 I bt_vendor: Done intiailizing UART
,09-02 12:24:15.154  7108  7681 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 12:24:15.154  7108  7681 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 12:24:15.154  7108  7679 I bt-btu  : btu_task received preload complete event
09-02 12:24:15.154  7108  7722 D bt_userial_mct: Entering userial_read_thread()
09-02 12:24:15.154  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 12:24:15.155  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 12:24:15.157  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:24:15.159  7108  7679 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 12:24:15.160  7108  7679 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:24:15.160  7108  7679 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 12:24:15.250  7108  7679 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 12:24:15.251  7108  7679 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0167061 
09-02 12:24:15.251  7108  7679 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0167061 
,09-02 12:24:15.300  7108  7612 E bt-btif : Calling BTA_HhEnable
,09-02 12:24:15.301  7108  7612 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 12:24:15.301  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 12:24:15.301  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 12:24:15.301  7108  7612 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 12:24:15.301  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,09-02 12:24:15.302  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 12:24:15.302  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 12:24:15.308  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-02 12:24:15.312  7108  7612 D BluetoothAdapterProperties: Name is: G3
09-02 12:24:15.313  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:24:15.314  7108  7612 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:24:15.314  7108  7612 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:24:15.314  7108  7612 D bt_hci_bdroid: postload
09-02 12:24:15.315  7108  7681 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:24:15.317  7108  7612 D bte_conf: Device ID record 1 : primary
09-02 12:24:15.317  7108  7612 D bte_conf:   vendorId            = 00c4
09-02 12:24:15.317  7108  7612 D bte_conf:   vendorIdSource      = 0001
09-02 12:24:15.317  7108  7612 D bte_conf:   product             = 13a1
09-02 12:24:15.317  7108  7612 D bte_conf:   version             = 1000
09-02 12:24:15.317  7108  7612 D bte_conf:   clientExecutableURL = 
,09-02 12:24:15.317  7108  7612 D bte_conf:   serviceDescription  = 
09-02 12:24:15.317  7108  7612 D bte_conf:   documentationURL    = 
09-02 12:24:15.317  7108  7612 D bte_conf: bte_load_did_conf no section named DID2.
09-02 12:24:15.318  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:15.319  7108  7681 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:24:15.321  7108  7679 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 12:24:15.321  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:15.322  7108  7681 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:24:15.323  7108  7608 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 12:24:15.324  7108  7608 D BluetoothAdapterProperties: ScanMode =  20
09-02 12:24:15.324  7108  7608 D BluetoothAdapterProperties: State =  11
09-02 12:24:15.324  7108  7608 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 12:24:15.324  7108  7608 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 12:24:15.324  7108  7608 D BluetoothAdapterProperties: Setting state to 12
09-02 12:24:15.324  7108  7608 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 12:24:15.325  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:15.325  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 12:24:15.325  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-02 12:24:15.325  7108  7608 I BluetoothAdapterState: Entering On State
09-02 12:24:15.326  1853  2429 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:24:15.328  7108  7612 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 12:24:15.329  7108  7612 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:24:15.317  7724  7724 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:15.317  7724  7724 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:15.340  7108  7608 D LGBluetoothServiceAdapter: [BTUI] OnState
,09-02 12:24:15.340  7108  7608 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3,
09-02 12:24:15.340  7108  7608 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-02 12:24:15.344  7108  7608 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 12:24:15.346  7108  7612 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:24:15.347  7108  7612 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 12:24:15.347  1853  1853 D BluetoothHeadset: Proxy object connected
09-02 12:24:15.347  6996  7011 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:24:15.348  6996  7011 D BluetoothPan: onBluetoothStateChange call bindService
09-02 12:24:15.355  6996  6996 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:24:15.355  6996  6996 D PanProfile: Bluetooth service connected
,09-02 12:24:15.358  1853  4473 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:15.359  7108  7722 E bt_mct  : hci lib postload completed
09-02 12:24:15.361  1853  1853 D BluetoothHeadset: Proxy object connected
09-02 12:24:15.361  1035  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:15.362  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:15.362  1035  1035 D BluetoothHeadset: Proxy object connected
09-02 12:24:15.365  1853  1853 D BluetoothHeadset: Proxy object connected
09-02 12:24:15.365  6996  7011 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:24:15.367  1035  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:24:15.368  7108  7679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:15.368  7108  7679 W bt-smp  : Plain text(LSB ~ MSB) = 9d cc 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:15.368  7108  7679 W bt-smp  : Encrypted text(LSB ~ MSB) = 25 98 a1 13 cd 0a d8 3f 86 44 bd 1d e7 51 83 2e 
,09-02 12:24:15.368  7108  7679 W bt-btm  : Stopping oneshot timer
09-02 12:24:15.371  6996  7012 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:24:15.371  1035  1035 D BluetoothA2dp: Proxy object connected
09-02 12:24:15.375  6996  7012 D BluetoothMap: onBluetoothStateChange: up=true
09-02 12:24:15.375  6996  6996 D BluetoothInputDevice: Proxy object connected
09-02 12:24:15.375  6996  6996 D HidProfile: Bluetooth service connected
09-02 12:24:15.379  7108  7608 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 12:24:15.381  1035  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 12:24:15.381  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-02 12:24:15.383  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 12:24:15.384   315  7347 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-02 12:24:15.384   315  7347 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
09-02 12:24:15.385   315  7347 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
09-02 12:24:15.387  6996  6996 D BluetoothMap: Proxy object connected
09-02 12:24:15.387  6996  6996 D MapProfile: Bluetooth service connected
09-02 12:24:15.387  6996  6996 D BluetoothMap: getConnectedDevices()
09-02 12:24:15.387  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-02 12:24:15.387  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s258ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:15.387  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s258ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:15.387  1035  7286 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 12:24:15.388  7108  7613 V BluetoothMapService: getConnectedDevices()
09-02 12:24:15.388  1035  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 12:24:15.388  1035  1118 D BluetoothManagerService: Message: 40
09-02 12:24:15.389  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.389  1941  2145 D LGBluetoothAPIService: Message: 1
09-02 12:24:15.389  1941  2145 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 12:24:15.389  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 12:24:15.391  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:24:15.397  7108  7679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:15.397  7108  7679 W bt-smp  : Plain text(LSB ~ MSB) = 29 88 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:15.397  7108  7679 W bt-smp  : Encrypted text(LSB ~ MSB) = 2c e1 94 cc 34 dc 0c 77 b4 9f c7 51 b0 f9 14 19 
09-02 12:24:15.397  7108  7679 W bt-btm  : Stopping oneshot timer
,09-02 12:24:15.399  7108  7108 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.399  7108  7108 D BluetoothMapService: STATE_ON
09-02 12:24:15.400  6705  6705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 12:24:15.404  7108  7108 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 12:24:15.404  7108  7108 D LGBluetoothAPIServer: [BTUI] onBind()
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:15.405  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:15.407  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:24:15.410  7730  7730 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-02 12:24:15.411  1941  2145 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-02 12:24:15.415  7108  7679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:15.415  7108  7679 W bt-smp  : Plain text(LSB ~ MSB) = da 85 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:15.415  7108  7679 W bt-smp  : Encrypted text(LSB ~ MSB) = 62 40 be e7 ba 44 77 2e 76 49 9d 40 62 cc 85 50 
09-02 12:24:15.415  7108  7679 W bt-btm  : Stopping oneshot timer
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:15.415  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:15.417  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 12:24:15.417  1941  2145 D LGBluetoothAPIService: Message: 100
09-02 12:24:15.417  1941  2145 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 12:24:15.417  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:15.419  6996  6996 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 12:24:15.423  1035  1118 D BluetoothManagerService: Message: 30
,09-02 12:24:15.424  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:15.424  7108  7108 V BluetoothPbapService: Pbap Service onCreate
09-02 12:24:15.424  7108  7108 V BluetoothPbapService: Starting PBAP service
09-02 12:24:15.426  7108  7108 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 12:24:15.426  7108  7108 V BluetoothPbapService: Pbap Service onBind
09-02 12:24:15.426  6996  6996 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-02 12:24:15.427  7108  7108 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.427  7108  7108 V BluetoothPbapService: state: 12
09-02 12:24:15.427  7108  7108 V BluetoothMapService: Handler(): got msg=1
09-02 12:24:15.428  7108  7108 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 12:24:15.428  7108  7679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:15.428  7108  7679 W bt-smp  : Plain text(LSB ~ MSB) = cf 47 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:15.428  7108  7679 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b 31 46 7b 66 6c c9 d2 b6 d3 ed 02 a6 b2 ab 5b 
09-02 12:24:15.428  7108  7108 V BluetoothPbapService: Handler(): got msg=1
09-02 12:24:15.428  7108  7679 W bt-btm  : Stopping oneshot timer
09-02 12:24:15.428  7108  7108 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 12:24:15.430  1035  1118 D BluetoothManagerService: Message: 30
09-02 12:24:15.431  7108  7736 D BluetoothMapMasInstance: MAS initSocket()
09-02 12:24:15.432  7108  7736 D BluetoothMapMasInstance:   masId = 00
09-02 12:24:15.432  7108  7736 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 12:24:15.432  7108  7736 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 12:24:15.432  7108  7736 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 12:24:15.433  7108  7737 V BluetoothPbapService: Pbap Service initSocket
09-02 12:24:15.434  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:15.435  1035  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:15.435  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 12:24:15.437  7108  7736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:15.437  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 12:24:15.440  7108  7679 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:15.440  7108  7679 W bt-smp  : Plain text(LSB ~ MSB) = 70 21 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:15.440  7108  7679 W bt-smp  : Encrypted text(LSB ~ MSB) = c4 dd 2c 27 50 ca 99 7c 8e b4 ec 82 24 a0 99 14 
09-02 12:24:15.440  7108  7679 W bt-btm  : Stopping oneshot timer
09-02 12:24:15.440  7108  7737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:15.442  7108  7736 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 12:24:15.442  7108  7736 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 12:24:15.442  7108  7736 D BluetoothMapMasInstance: Accepting socket connection...
09-02 12:24:15.443  6996  6996 D BluetoothA2dp: Proxy object connected
09-02 12:24:15.443  7108  7612 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:24:15.444  7108  7612 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 12:24:15.444  6996  6996 D A2dpProfile: Bluetooth service connected
09-02 12:24:15.444  7108  7737 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 12:24:15.444  7108  7737 V BluetoothPbapService: Succeed to create listening socket 
09-02 12:24:15.444  7108  7737 V BluetoothPbapService: Accepting socket connection...
09-02 12:24:15.446  7108  7108 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:24:15.446  7108  7108 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.446  7108  7108 V BluetoothPbapReceiver: ***********state = 12
09-02 12:24:15.449  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:15.450  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:15.452  6996  6996 D BluetoothPbap: Proxy object connected
09-02 12:24:15.452  6996  6996 D PbapServerProfile: Bluetooth service connected
09-02 12:24:15.453  6996  6996 D BluetoothHeadset: Proxy object connected
09-02 12:24:15.454  6996  6996 D HeadsetProfile: Bluetooth service connected
09-02 12:24:15.455  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:15.456  2211  2211 D c       : Getting all permits...
09-02 12:24:15.456  2211  2211 D a       : Opening database...
09-02 12:24:15.460  2211  2211 D a       : Opening database auth.proximity.permit_store...
,09-02 12:24:15.462  2211  2211 D a       : Closing database...
09-02 12:24:15.469  6996  6996 D DockEventReceiver: finishStartingService: stopping service
09-02 12:24:15.478  6996  6996 D BluetoothPermissionRequest: onReceive
,09-02 12:24:15.480  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 12:24:15.482  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:24:15.485  7108  7108 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 12:24:15.487  7108  7108 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 12:24:15.496  7108  7108 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 12:24:15.527  7108  7108 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-02 12:24:15.528  7108  7108 V BtOppService: onCreate
,09-02 12:24:15.536  7108  7108 V BluetoothOppNotification: send message
09-02 12:24:15.543  7108  7108 V BtOppService: Starting RfcommListener
,09-02 12:24:15.550  7108  7108 D BluetoothOppPreference: Dumping Names:  
09-02 12:24:15.550  7108  7108 D BluetoothOppPreference: {}
09-02 12:24:15.550  7108  7108 D BluetoothOppPreference: Dumping Channels:  
09-02 12:24:15.550  7108  7108 D BluetoothOppPreference: {}
09-02 12:24:15.556  7108  7108 V BtOppService: onStartCommand
,09-02 12:24:15.561  7108  7745 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:24:15.565  7108  7108 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.565  7108  7742 V BtOppService: Deleted complete outbound shares, number =  0
09-02 12:24:15.565  7108  7108 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-02 12:24:15.568  7108  7745 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:24:15.569  7108  7742 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 12:24:15.569  7108  7742 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-02 12:24:15.572  7108  7108 V BluetoothOppNotification: new notify threadi!
09-02 12:24:15.574  7108  7108 V BluetoothOppNotification: send delay message
09-02 12:24:15.576  7108  7108 V BtOppService: start RfcommListener
09-02 12:24:15.578  7108  7742 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3df2bb92 on behalf of 
09-02 12:24:15.578  7108  7745 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a6c8963 on behalf of 
09-02 12:24:15.581  7108  7108 V BtOppService: RfcommListener started
09-02 12:24:15.582  7108  7108 V BtOppService: ContentObserver received notification
09-02 12:24:15.582  7108  7108 V BtOppService: ContentObserver received notification
,09-02 12:24:15.587  7108  7746 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 12:24:15.590  7108  7745 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:24:15.590  7108  7746 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17a4d960 on behalf of 
09-02 12:24:15.590  7108  7745 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:24:15.592  7108  7747 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 12:24:15.592  7108  7745 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@babfe19 on behalf of 
09-02 12:24:15.592  1035  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:15.593  7108  7745 V BluetoothOppNotification: update too frequent, put in queue
,09-02 12:24:15.595  7108  7747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:15.595  7108  7745 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 12:24:15.597  7108  7747 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-02 12:24:15.597  7108  7746 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 12:24:15.597  7108  7747 V BtOppRfcommListener: Started RFCOMM listener....
09-02 12:24:15.598  7108  7747 I BtOppRfcommListener: Accept thread started.
09-02 12:24:15.598  7108  7747 V BtOppRfcommListener: Accepting connection...
09-02 12:24:15.600  7108  7746 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:24:15.602  7108  7746 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ffcfede on behalf of 
09-02 12:24:15.603  7108  7746 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 12:24:15.604  7108  7746 V BluetoothOppNotification: outbound notification was removed.
09-02 12:24:15.604  7108  7746 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-02 12:24:15.606  7108  7746 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@121458bf on behalf of 
09-02 12:24:15.606  7108  7746 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 12:24:15.608  7108  7746 V BluetoothOppNotification: inbound notification was removed.
09-02 12:24:15.608  7108  7746 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:24:15.610  7108  7746 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@86e2b8c on behalf of 
09-02 12:24:15.613  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:15.613  7108  7108 V BluetoothFtpService: Ftp Service onCreate
,09-02 12:24:15.613  7108  7108 I BluetoothFtpService: Ftp Service onCreate
09-02 12:24:15.614  7108  7108 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:24:15.614  7108  7108 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.614  7108  7108 V BluetoothFtpService: Starting Listening on sockets
09-02 12:24:15.614  7108  7108 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:15.614  7108  7108 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:15.614  7108  7108 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:15.614  7108  7108 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.615  7108  7108 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 12:24:15.615  7108  7108 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:24:15.617  7108  7108 V BluetoothFtpService: Handler(): got msg=1
,09-02 12:24:15.618  7108  7108 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 12:24:15.618  7108  7108 V BluetoothFtpService: Ftp Service initSocket
09-02 12:24:15.620  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:15.622  7108  7108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:15.625  7108  7108 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-02 12:24:15.625  7108  7108 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 12:24:15.628  7108  7748 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-02 12:24:15.644  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
,09-02 12:24:15.644  7108  7108 V BluetoothSapService: Sap Service onCreate
09-02 12:24:15.647  7108  7108 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:15.647  7108  7108 V BluetoothSapService: state: 12
09-02 12:24:15.647  7108  7108 V BluetoothSapService: Starting SAP server process
09-02 12:24:15.650  7108  7108 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 12:24:15.637  7749  7749 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:15.637  7749  7749 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:15.655  7108  7750 V BluetoothSapService: Sap Service initRfcommSocket
09-02 12:24:15.656  1035  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:15.657  7108  7750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:15.658  7108  7750 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,09-02 12:24:15.658  7108  7750 V BluetoothSapService: Succeed to create listening socket 
,09-02 12:24:15.659  7108  7750 V BluetoothSapService: Accepting socket connection...
09-02 12:24:15.663  7749  7749 V BT_SAP  : Event pipe created
09-02 12:24:15.663  7749  7749 V BT_SAP  : create_server_socket qcom.sap.server
09-02 12:24:15.663  7749  7749 V BT_SAP  : created socket fd 6
09-02 12:24:15.704  7382  7419 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-02 12:24:16.056  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:24:16.056  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:24:16.128  1035  1392 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 12:24:16.135  1035  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 12:24:16.578  7108  7108 V BluetoothOppNotification: new notify threadi!
,09-02 12:24:16.579  7108  7108 V BluetoothOppNotification: send delay message
,09-02 12:24:16.592  1035  1768 I ActivityManager: Killing 7531:com.lge.bnr/1000 (adj 15): empty #17
09-02 12:24:16.601  7108  7762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-02 12:24:16.616  7108  7762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33365751 on behalf of 
09-02 12:24:16.617  7108  7762 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-02 12:24:16.622  7108  7762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:24:16.624  7108  7762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36640bb6 on behalf of 
09-02 12:24:16.624  7108  7762 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 12:24:16.626  7108  7762 V BluetoothOppNotification: outbound notification was removed.
09-02 12:24:16.626  7108  7762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 12:24:16.627  7108  7762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28eea0b7 on behalf of 
09-02 12:24:16.628  7108  7762 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-02 12:24:16.634  7108  7762 V BluetoothOppNotification: inbound notification was removed.
09-02 12:24:16.634  7108  7762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:24:16.636  7108  7762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@271c6024 on behalf of 
09-02 12:24:16.640  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_7531/cgroup.procs: No such file or directory
09-02 12:24:16.644  1035  1904 I ActivityManager: Killing 6868:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-02 12:24:16.664  7047  7047 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-02 12:24:16.665  7047  7047 W System.err: android.os.DeadObjectException
09-02 12:24:16.665  7047  7047 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 12:24:16.665  7047  7047 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 12:24:16.665  7047  7047 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-02 12:24:16.665  7047  7047 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-02 12:24:16.665  7047  7047 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 12:24:16.665  7047  7047 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 12:24:16.665  7047  7047 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:24:16.665  7047  7047 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:24:16.665  7047  7047 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:24:16.665  7047  7047 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:24:16.665  7047  7047 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:24:16.665  7047  7047 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:24:16.665  7047  7047 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:24:16.665  7047  7047 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:24:16.666  7047  7047 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-02 12:24:16.666  7047  7047 W System.err: android.os.DeadObjectException
09-02 12:24:16.666  7047  7047 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 12:24:16.666  7047  7047 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 12:24:16.666  7047  7047 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-02 12:24:16.666  7047  7047 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-02 12:24:16.666  7047  7047 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 12:24:16.666  7047  7047 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 12:24:16.666  7047  7047 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:24:16.666  7047  7047 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:24:16.666  7047  7047 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:24:16.667  7047  7047 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,09-02 12:24:16.672  7047  7047 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:24:16.672  7047  7047 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:24:16.672  7047  7047 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:24:16.672  7047  7047 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:24:16.673  7047  7047 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-02 12:24:16.673  7047  7047 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-02 12:24:16.700  1035  1996 W libprocessgroup: failed to open /acct/uid_1000/pid_6868/cgroup.procs: No such file or directory
,09-02 12:24:16.703  1035  1996 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-02 12:24:16.707  7047  7047 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-02 12:24:16.707  7047  7047 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 12:24:16.754  1035  1645 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7763 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:24:16.776  7047  7047 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-02 12:24:16.836  7763  7763 D UEI.SmartControl: Quickset Services start...
09-02 12:24:16.838  7763  7763 I UEI.SmartControl: Manufacture = LGE
09-02 12:24:16.838  7763  7763 D UEI.SmartControl: Id = LGNevo
09-02 12:24:16.840  7763  7763 D UEI.SmartControl: File observer start...
09-02 12:24:16.840  7763  7763 E UEI.SmartControl: IR Port is disabled: false
,09-02 12:24:16.844  7763  7763 D UEI.SmartControl: Starting file observer...
09-02 12:24:16.844  7763  7763 D UEI.SmartControl: Extracting JNI libs...
09-02 12:24:16.845  7763  7763 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-02 12:24:16.930  7763  7763 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-02 12:24:16.934  7763  7763 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-02 12:24:16.934  7763  7763 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-02 12:24:16.971  7763  7763 I UEI.SmartControl: --- Selecting new region: 6
09-02 12:24:16.973  7763  7763 I UEI.SmartControl: Model = LG-D855
09-02 12:24:16.974  7763  7763 D UEI.SmartControl: QS Service created
,09-02 12:24:16.995  7763  7763 I UEI.SmartControl: Service initServices...
,09-02 12:24:17.003  7763  7763 D UEI.SmartControl: QS start get config
,09-02 12:24:17.063  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:17.063  1035  2014 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@16bfdcbe mBinding = false
,09-02 12:24:17.075  7763  7763 D UEI.SmartControl: Loading JNI Libs...
09-02 12:24:17.083  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:24:17.084  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:17.084  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-02 12:24:17.087  1035  1118 D BluetoothManagerService: Message: 2
09-02 12:24:17.088  1035  1118 D BluetoothManagerService: Sending off request.
09-02 12:24:17.089  7108  7123 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 12:24:17.089  7108  7608 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 12:24:17.089  7108  7608 D BluetoothAdapterProperties: Setting state to 13
09-02 12:24:17.089  7108  7608 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:24:17.090  7108  7608 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:24:17.090  7108  7608 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 12:24:17.092  7108  7612 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:24:17.093  7108  7608 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 12:24:17.094  7108  7608 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 12:24:17.096  7108  7736 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-02 12:24:17.099  7108  7737 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:17.101  7108  7747 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:17.101  7108  7748 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:17.102  7108  7750 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:24:17.102  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 12:24:17.102  7108  7679 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 12:24:17.108  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 12:24:17.108  7108  7679 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-02 12:24:17.119  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:17.120  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:17.125  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:17.125  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:24:17.129  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:17.129  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:17.130  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:24:17.130  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:17.131  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:17.131  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 12:24:17.131  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 12:24:17.135  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.136  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:24:17.140  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:17.144  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:17.147  7108  7108 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.147  7108  7108 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:24:17.147  7108  7108 V BluetoothMapService: Handler(): got msg=4
09-02 12:24:17.147  7108  7108 D BluetoothMapService: MAP Service closeService in
09-02 12:24:17.147  7108  7108 D BluetoothMapMasInstance: MAP Service shutdown
09-02 12:24:17.148  7108  7108 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:24:17.148  7108  7108 V BluetoothMapService: MAP Service closeService out
09-02 12:24:17.149  7108  7108 V BtOppService: Receiver DISABLED_ACTION 
09-02 12:24:17.149  7108  7108 I BtOppRfcommListener: stopping Accept Thread
09-02 12:24:17.149  7108  7108 V BtOppRfcommListener: close mBtServerSocket
09-02 12:24:17.150  7108  7747 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 12:24:17.150  7108  7108 V BtOppRfcommListener: waiting for thread to terminate
09-02 12:24:17.150  7108  7108 V BtOppRfcommListener: done waiting for thread to terminate
,09-02 12:24:17.175  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-02 12:24:17.176  7108  7108 V BtOppService: onDestroy
09-02 12:24:17.176  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 12:24:17.177  7108  7108 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 12:24:17.181  7108  7108 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:24:17.181  7108  7108 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.181  7108  7108 V BluetoothPbapReceiver: ***********state = 13
09-02 12:24:17.183  7108  7108 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-02 12:24:17.188  6996  6996 D DockEventReceiver: finishStartingService: stopping service
09-02 12:24:17.190  7108  7108 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.190  7108  7108 V BluetoothPbapService: state: 13
09-02 12:24:17.190  7108  7108 V BluetoothPbapService: Pbap Service closeService in
09-02 12:24:17.192  7108  7108 V BluetoothPbapService: successfully stopped pbap service
09-02 12:24:17.192  7108  7108 V BluetoothPbapService: Pbap Service closeService out
09-02 12:24:17.192  7108  7108 V BluetoothPbapService: Pbap Service onDestroy
09-02 12:24:17.192  7108  7108 V BluetoothPbapService: Pbap Service closeService in
,09-02 12:24:17.192  7108  7108 V BluetoothPbapService: Pbap Service closeService out
09-02 12:24:17.193  7108  7108 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-02 12:24:17.193  6996  6996 D BluetoothPbap: Proxy object disconnected
09-02 12:24:17.193  6996  6996 D PbapServerProfile: Bluetooth service disconnected
09-02 12:24:17.198  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:17.217  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 12:24:17.223  6996  6996 D BluetoothPermissionRequest: onReceive
09-02 12:24:17.223  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 12:24:17.231  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:24:17.237  7108  7108 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 12:24:17.238  7108  7108 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 12:24:17.238  7108  7108 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 12:24:17.244  7108  7108 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.244  7108  7108 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-02 12:24:17.249  7108  7108 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:24:17.249  7108  7108 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.249  7108  7108 V BluetoothFtpService: Ftp Service closeService
09-02 12:24:17.249  7108  7108 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 12:24:17.250  7108  7108 V BluetoothFtpService: successfully stopped ftp service
09-02 12:24:17.251  7108  7108 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:17.251  7108  7108 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:17.251  7108  7108 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:17.251  7108  7108 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.251  7108  7108 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 12:24:17.251  7108  7108 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:24:17.252  7108  7108 V BluetoothFtpService: Ftp Service onDestroy
09-02 12:24:17.252  7108  7108 V BluetoothFtpService: Ftp Service closeService
09-02 12:24:17.257  7108  7108 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:17.257  7108  7108 V BluetoothSapService: state: 13
09-02 12:24:17.257  7108  7108 V BluetoothSapService: Stopping SAP server process
,09-02 12:24:17.258  7108  7108 V BluetoothSapService: Sap Service closeSapService in
,09-02 12:24:17.258  7108  7108 V BluetoothSapService: Close listen Socket : 
,09-02 12:24:17.258  7108  7108 V BluetoothSapService: Close rfcomm Socket : 
,09-02 12:24:17.259  7108  7108 V BluetoothSapService: Close sapd  Socket : 
,09-02 12:24:17.263  7108  7108 V BluetoothSapService: Sap Service closeSapService out
,09-02 12:24:17.263  7108  7108 V BluetoothSapService: Sap Service onDestroy
,09-02 12:24:17.263  7108  7108 V BluetoothSapService: Sap Service closeSapService in
09-02 12:24:17.263  7108  7108 V BluetoothSapService: Close listen Socket : 
,09-02 12:24:17.263  7108  7108 V BluetoothSapService: Close rfcomm Socket : 
,09-02 12:24:17.264  7108  7108 V BluetoothSapService: Close sapd  Socket : 
09-02 12:24:17.264  7108  7108 V BluetoothSapService: Sap Service closeSapService out
09-02 12:24:17.657  7763  7763 I UEI.SmartControl: Supports setup maps: true
09-02 12:24:17.665  7763  7763 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 12:24:17.665  7763  7763 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 12:24:17.665  7763  7763 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 12:24:17.666  7763  7763 I UEI.SmartControl: ### init IR Blaster...
,09-02 12:24:17.672  7763  7763 D serial_port: Configuring serial port
09-02 12:24:17.678  7763  7763 E UEI.SmartControl: UEIBLaster setting for 616
09-02 12:24:17.678  7763  7763 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 12:24:17.679  7763  7763 I UEI.SmartControl: configuring settings for MAXQ616
09-02 12:24:17.679  7763  7763 I UEI.SmartControl: Get version...
09-02 12:24:17.696  7763  7807 D UEI.SmartControl: serial port data available: 21
,09-02 12:24:17.726  7763  7763 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 12:24:17.726  7763  7763 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 12:24:17.727  7763  7763 I UEI.SmartControl: QS saving settings...
,09-02 12:24:17.730  7763  7763 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 12:24:17.748  7763  7807 D UEI.SmartControl: serial port data available: 4
,09-02 12:24:17.793  7763  7810 I UEI.SmartControl: Device manager: loading config....
,09-02 12:24:17.794  7763  7810 D UEI.SmartControl: ----------- loading internal config...
,09-02 12:24:17.799  7763  7763 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-02 12:24:17.806  7763  7763 E UEI.SmartControl: Services init done
09-02 12:24:17.807  7763  7763 D UEI.SmartControl: QS Service init finished
09-02 12:24:17.812  7763  7763 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 12:24:17.812  7763  7763 D UEI.SmartControl: QS Service version code: 201091
09-02 12:24:17.813  7763  7763 D UEI.SmartControl: Service requested: Control
,09-02 12:24:17.823  7763  7810 E UEI.SmartControl: Loading SETTINGS...
09-02 12:24:17.824  7763  7763 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-02 12:24:17.829  1035  1917 I ActivityManager: Killing 7047:com.lge.qremote/u0a112 (adj 15): empty #17
09-02 12:24:17.841  7763  7810 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-02 12:24:17.852  7763  7809 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 12:24:17.852  7763  7809 D UEI.SmartControl: -----service ready thread exits
09-02 12:24:17.882  1035  1995 W libprocessgroup: failed to open /acct/uid_10112/pid_7047/cgroup.procs: No such file or directory
09-02 12:24:17.885  7763  7763 D UEI.SmartControl: Internal service binding...
,09-02 12:24:18.012  7108  7679 W bt-btif : ag scb idx 1 not allocated
09-02 12:24:18.012  7108  7679 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:18.012  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:24:18.013  7108  7679 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:24:18.013  7108  7679 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 12:24:18.014  7108  7612 D bt_hci_bdroid: cleanup
09-02 12:24:18.014  7108  7681 I bt_lpm  : LPM is already off!!!
09-02 12:24:18.014  7108  7722 I bt_userial_mct: exiting userial_read_thread
09-02 12:24:18.014  7108  7722 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 12:24:18.015  7108  7612 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 12:24:18.016  7108  7681 I bt_vendor: hw_epilog_process
09-02 12:24:18.017  7108  7612 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 12:24:18.017  7108  7612 D bt_userial_mct: userial_close
,09-02 12:24:18.018  7108  7612 E bt_userial_mct: pthread_join() FAILED result:3
09-02 12:24:18.018  7108  7612 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-02 12:24:18.052  7108  7612 D bt_hci_bdroid: set_power 0,
09-02 12:24:18.052  7108  7612 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 12:24:18.052  7108  7612 I bt_vendor: bluetooth satus is on,
,09-02 12:24:18.052  7108  7612 I bt_vendor: bt-vendor : resetting BT status,
09-02 12:24:18.052  7108  7612 I bt_vendor: Starting hciattach daemon,
09-02 12:24:18.052  7108  7612 I bt_vendor: try to set false,
,09-02 12:24:18.061  7108  7612 I bt_vendor: Starting hciattach daemon,
09-02 12:24:18.061  7108  7612 I bt_vendor: try to set false
09-02 12:24:18.067  7108  7612 I bt_vendor: cleanup
,09-02 12:24:18.072  7108  7679 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 12:24:18.073  7108  7612 I GKI_LINUX: GKI_exit_task 0 done
09-02 12:24:18.073  7108  7612 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 12:24:18.074  7108  7608 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 12:24:18.079  7108  7108 D HeadsetService: Received stop request...Stopping profile...
09-02 12:24:18.080  7108  7108 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:24:18.080  7108  7108 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:24:18.080  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
,09-02 12:24:18.083  7108  7649 D HeadsetStateMachine: Exit Disconnected: -1
09-02 12:24:18.088  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:18.088  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:18.088  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:18.088  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-02 12:24:18.088  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 12:24:18.089  7108  7108 D A2dpService: Received stop request...Stopping profile...
09-02 12:24:18.089  7108  7666 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:24:18.091  7108  7108 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 12:24:18.096  7108  7608 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-02 12:24:18.100  7108  7108 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 12:24:18.100  7108  7108 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:24:18.100  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:18.102  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-02 12:24:18.102  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 12:24:18.103  7108  7108 D HidService: Received stop request...Stopping profile...
09-02 12:24:18.103  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:18.105  7108  7108 D HeadsetStateMachine: Unbinding service...
09-02 12:24:18.106  7108  7108 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:24:18.106  7108  7108 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:24:18.106  7108  7108 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:24:18.106  7108  7108 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:24:18.106  7108  7108 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:24:18.106  7108  7108 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:24:18.106  7108  7108 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:24:18.110  7108  7108 D HealthService: Received stop request...Stopping profile...
09-02 12:24:18.110  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
,09-02 12:24:18.117  7108  7108 D PanService: Received stop request...Stopping profile...
09-02 12:24:18.117  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:18.118  7108  7108 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:24:18.119  7108  7108 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 12:24:18.119  7108  7108 D BtGatt.GattService: stop()
09-02 12:24:18.119  7108  7108 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 12:24:18.121  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:18.123  7108  7108 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:24:18.123  7108  7108 D BluetoothMapService: stop()
,09-02 12:24:18.127  7108  7108 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 12:24:18.127  7108  7108 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 12:24:18.128  7108  7108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ac3191
09-02 12:24:18.129  7108  7108 I BluetoothA2dpServiceJni: cleanupNative
09-02 12:24:18.130  7108  7667 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 12:24:18.130  7108  7108 I GKI_LINUX: GKI_exit_task 2 done
09-02 12:24:18.130  7108  7108 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 12:24:18.131  7108  7108 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:24:18.131  7108  7108 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:24:18.132  7108  7108 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:24:18.132  7108  7108 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:24:18.132  7108  7108 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:24:18.132  7108  7108 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:24:18.132  7108  7108 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 12:24:18.135  7108  7108 V BluetoothMapService: Handler(): got msg=4
09-02 12:24:18.135  7108  7108 D BluetoothMapService: MAP Service closeService in
09-02 12:24:18.135  7108  7108 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:24:18.135  7108  7108 V BluetoothMapService: MAP Service closeService out
,09-02 12:24:18.138  7108  7608 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 12:24:18.139  7108  7608 D BluetoothAdapterProperties: Setting state to 10
09-02 12:24:18.139  7108  7608 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 12:24:18.140  7108  7108 D BluetoothMapService: cleanup()
09-02 12:24:18.140  7108  7108 D BluetoothMapService: MAP Service closeService in
09-02 12:24:18.140  7108  7108 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:24:18.140  7108  7108 V BluetoothMapService: MAP Service closeService out
09-02 12:24:18.141  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:18.141  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 12:24:18.142  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-02 12:24:18.142  7108  7608 I BluetoothAdapterState: Entering OffState
09-02 12:24:18.142  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:24:18.143  6996  7728 D BluetoothPan: onBluetoothStateChange on: false
09-02 12:24:18.144  1853  4473 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:24:18.144  1035  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:24:18.144  1853  4475 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:24:18.145  6996  7728 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:24:18.145  1035  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:24:18.146  6996  7728 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:24:18.146  6996  7728 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:24:18.147  6996  7728 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:24:18.147  6996  7728 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 12:24:18.151  1035  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 12:24:18.151  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 12:24:18.154  1035  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 12:24:18.154  1035  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 12:24:18.154  1035  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@16bfdcbe mBinding = false
09-02 12:24:18.155  1035  1118 D BluetoothManagerService: Sending unbind request.
09-02 12:24:18.159  7108  7612 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 12:24:18.161  7108  7108 I GKI_LINUX: GKI_exit_task 1 done
09-02 12:24:18.161  7108  7108 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 12:24:18.162  7108  7108 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 12:24:18.162  7108  7108 I art     : --- WEIRD: removing null entry 248
09-02 12:24:18.162  7108  7108 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-02 12:24:18.163  7108  7108 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 12:24:18.164  7108  7108 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 12:24:18.165  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 12:24:18.167  7108  7108 I art     : System.exit called, status: 0
09-02 12:24:18.167  7108  7108 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-02 12:24:18.187   320  2160 V AudioFlinger: 7108 died, releasing its sessions
09-02 12:24:18.187   320  2160 V AudioFlinger:  pid 1853 @ 0
09-02 12:24:18.187   320  2160 V AudioFlinger:  pid 3428 @ 1
09-02 12:24:18.187   320  2160 V AudioFlinger:  pid 3428 @ 2
,09-02 12:24:18.191  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-02 12:24:18.191  1941  2145 D LGBluetoothAPIService: Message: 101
09-02 12:24:18.191  1941  2145 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-02 12:24:18.192  1941  2145 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-02 12:24:18.192  1941  2145 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-02 12:24:18.193  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 12:24:18.196  1035  1052 I ActivityManager: Process com.android.bluetooth (pid 7108) has died
09-02 12:24:18.196  1035  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-02 12:24:18.196  1035  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
09-02 12:24:18.202  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:24:18.205  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:24:18.206  1941  2145 D LGBluetoothAPIService: Message: 2
09-02 12:24:18.206  1941  2145 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-02 12:24:18.207  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:18.207  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:18.212  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 12:24:18.212  6996  6996 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 12:24:18.215  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 12:24:18.245  1601  1601 D BluetoothAdapter: 843221584: getState() :  mService = null. Returning STATE_OFF
09-02 12:24:18.245  1601  1601 D BluetoothAdapter: 843221584: getState() :  mService = null. Returning STATE_OFF
,09-02 12:24:18.263  1035  1917 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7834 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 12:24:18.267  6996  6996 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:24:18.358  7834  7834 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 12:24:18.359  7834  7834 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:18.359  7834  7834 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 12:24:18.360  7834  7834 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 12:24:18.381  7834  7834 D BluetoothAdapterApp: Loading JNI Library
,09-02 12:24:18.418  7834  7834 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2e01d059 Instance Count = 1
,09-02 12:24:18.424  7834  7834 D BluetoothAdapterApp: onCreate
,09-02 12:24:18.450  7834  7834 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 12:24:18.450  7834  7834 D ProfileConfigQcom: Adding HeadsetService
09-02 12:24:18.450  7834  7834 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 12:24:18.451  7834  7834 D ProfileConfigQcom: Adding A2dpService
,09-02 12:24:18.451  7834  7834 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 12:24:18.451  7834  7834 D ProfileConfigQcom: Adding HidService
09-02 12:24:18.451  7834  7834 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 12:24:18.451  7834  7834 D ProfileConfigQcom: Adding HealthService
09-02 12:24:18.452  7834  7834 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-02 12:24:18.453  7834  7834 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 12:24:18.453  7834  7834 D ProfileConfigQcom: Adding PanService
09-02 12:24:18.453  7834  7834 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 12:24:18.454  7834  7834 D ProfileConfigQcom: Adding GattService
09-02 12:24:18.454  7834  7834 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 12:24:18.454  7834  7834 D ProfileConfigQcom: Adding BluetoothMapService
09-02 12:24:18.455  7834  7834 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 12:24:18.456  7834  7834 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:24:18.457  7834  7834 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:18.457  7834  7834 V BluetoothPbapReceiver: ***********state = 10
09-02 12:24:18.459  7834  7834 V LGMDMManagerInternal: Create singleton instance
09-02 12:24:18.550  7834  7834 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 12:24:18.550  7834  7834 D LGBluetoothAPIServer: [BTUI] onBind()
,09-02 12:24:18.556  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 12:24:18.557  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:18.557  1941  2145 D LGBluetoothAPIService: Message: 100
09-02 12:24:18.557  1941  2145 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 12:24:18.566  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-02 12:24:18.581  6996  6996 D BluetoothPermissionRequest: onReceive
,09-02 12:24:18.585  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 12:24:18.585  6996  6996 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 12:24:18.588  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:24:18.592  7834  7834 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 12:24:18.597  7834  7834 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:24:18.603  7834  7834 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:18.604  7834  7834 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:18.604  7834  7834 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:18.608  7834  7834 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:18.608  7834  7834 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 12:24:18.617  7687  7687 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-02 12:24:20.134  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:24:20.134  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:20.541  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 12:24:20.549  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-02 12:24:20.575  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-02 12:24:20.585  1035  1035 D administrator: Handling package changes for user 0
09-02 12:24:20.673  1035  1105 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7870 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-02 12:24:20.688  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-02 12:24:20.691  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-02 12:24:20.712  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 12:24:20.746  7870  7870 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 12:24:20.780  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-02 12:24:20.781  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-02 12:24:20.853  7870  7870 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:24:20.854  7870  7870 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:20.872  1035  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:24:20.880  1035  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-02 12:24:20.890  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-02 12:24:20.893  2504  2504 V GmsNetworkLocationProvi: DISABLE
,09-02 12:24:20.938  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
09-02 12:24:20.994  7870  7915 I Babel   : MmsConfig: mnc/mcc: 0/0
09-02 12:24:20.994  7870  7915 I Babel   : MmsConfig.loadMmsSettings
,09-02 12:24:21.000  7870  7915 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 12:24:21.000  7870  7915 I Babel   : MmsConfig.loadFromDatabase
,09-02 12:24:21.033  7870  7915 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-02 12:24:21.033  7870  7915 I Babel   : MmsConfig.loadFromResources
09-02 12:24:21.037  7870  7915 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-02 12:24:21.038  7870  7870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:21.039  7870  7915 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 12:24:21.052  7870  7914 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 12:24:21.054  7870  7914 W AudioCapabilities: Unsupported mime audio/qcelp
09-02 12:24:21.058  7870  7914 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-02 12:24:21.068  1817  7918 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-02 12:24:21.068  1817  7918 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-02 12:24:21.073  1035  1102 D LocationProviderProxy: applying state to connected service
09-02 12:24:21.079  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 12:24:21.086  7870  7914 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-02 12:24:21.092  1817  5227 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-02 12:24:21.093  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@72d021b
09-02 12:24:21.093  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:24:21.093  7172  7172 D AppUp4:CustFacade: isPhone : true
09-02 12:24:21.093  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:24:21.093  7172  7172 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-02 12:24:21.103  7870  7914 W AudioCapabilities: Unsupported mime audio/qcelp
09-02 12:24:21.104  7870  7914 W AudioCapabilities: Unsupported mime audio/evrc
09-02 12:24:21.113  7870  7914 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 12:24:21.115  7870  7914 W VideoCapabilities: Unsupported mime video/divx
09-02 12:24:21.117  7870  7914 W VideoCapabilities: Unsupported mime video/divx311
09-02 12:24:21.119  7870  7914 W VideoCapabilities: Unsupported mime video/divx4
09-02 12:24:21.125  7870  7914 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-02 12:24:21.128  1035  1768 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7921 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-02 12:24:21.131  1035  1996 I ActivityManager: Killing 7016:com.lge.sync/1000 (adj 15): empty #17
09-02 12:24:21.142  7870  7914 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-02 12:24:21.144  1035  1407 D WifiService: Client connection lost with reason: 4
,09-02 12:24:21.146  7870  7914 W AudioCapabilities: Unsupported mime audio/eac3
09-02 12:24:21.147  7870  7914 W AudioCapabilities: Unsupported mime audio/ac3
09-02 12:24:21.148  7870  7914 W AudioCapabilities: Unsupported mime audio/g726
09-02 12:24:21.148  7870  7914 W AudioCapabilities: Unsupported mime audio/wma-voice
09-02 12:24:21.150  7870  7914 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-02 12:24:21.151  7870  7914 W AudioCapabilities: Unsupported mime audio/adpcm
09-02 12:24:21.152  7870  7914 W VideoCapabilities: Unsupported mime video/theora
09-02 12:24:21.153  7870  7914 W VideoCapabilities: Unsupported mime video/mjpg
09-02 12:24:21.271  1035  1976 W libprocessgroup: failed to open /acct/uid_1000/pid_7016/cgroup.procs: No such file or directory
,09-02 12:24:21.315  7921  7921 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:21.316  7921  7921 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:21.316  7921  7921 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 12:24:21.318  7921  7921 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,09-02 12:24:21.318  7921  7921 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-02 12:24:21.399  7921  7921 I SystemConfig: BUILD Country: EU
,09-02 12:24:21.400  7921  7921 I SystemConfig: BUILD Operator: OPEN
,09-02 12:24:21.455  1035  1051 I ActivityManager: Killing 7211:com.lge.email/u0a23 (adj 15): empty #17
,09-02 12:24:21.513  1035  1769 W libprocessgroup: failed to open /acct/uid_10023/pid_7211/cgroup.procs: No such file or directory
,09-02 12:24:21.523  7921  7939 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-02 12:24:21.523  7921  7939 I SystemConfig: existFile = false
09-02 12:24:21.523  7921  7939 I SystemConfig: canReadFile = false
09-02 12:24:21.524  7921  7939 I SystemConfig: systemFeature RCS result false
09-02 12:24:21.524  7921  7939 D SystemConfig: refreshRcsSupport() :false
09-02 12:24:21.584  1035  1051 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7944 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-02 12:24:21.676  7944  7944 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:21.676  7944  7944 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 12:24:21.676  7944  7944 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-02 12:24:21.677  7944  7944 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-02 12:24:21.769  7944  7944 I AppConfig: Total System Memory = 2995761152
,09-02 12:24:21.779  7944  7944 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-02 12:24:21.864  1035  1645 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7963 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:24:21.866  1035  1645 I ActivityManager: Killing 7085:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-02 12:24:21.911  1035  2014 W libprocessgroup: failed to open /acct/uid_10026/pid_7085/cgroup.procs: No such file or directory
,09-02 12:24:22.119  7963  7963 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-02 12:24:22.191  7963  7963 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:24:22.192  7963  7963 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:22.243  7963  7963 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-02 12:24:22.263  7963  7963 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-02 12:24:22.265  7963  7963 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-02 12:24:22.287  7963  7963 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-02 12:24:22.287  7963  7963 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-02 12:24:22.305  1035  1995 I ActivityManager: Killing 6446:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-02 12:24:22.413  1035  1976 W libprocessgroup: failed to open /acct/uid_1000/pid_6446/cgroup.procs: No such file or directory
,09-02 12:24:22.433  5051  8003 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-02 12:24:22.484  1035  1940 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8004 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-02 12:24:22.501  3491  4375 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-02 12:24:22.507  3491  4375 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20f91665 on behalf of 7963
09-02 12:24:22.635  1035  1645 I art     : Explicit concurrent mark sweep GC freed 39549(1890KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.394ms total 126.440ms
,09-02 12:24:22.675  7963  7963 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-02 12:24:22.690  7963  7963 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-02 12:24:22.706  8004  8004 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-02 12:24:22.729  8004  8004 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-02 12:24:22.729  8004  8004 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-02 12:24:22.729  8004  8004 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-02 12:24:22.729  8004  8004 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,09-02 12:24:22.729  8004  8004 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-02 12:24:22.729  8004  8004 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-02 12:24:22.757  1035  1768 I ActivityManager: Killing 7247:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-02 12:24:22.790  7763  7811 D UEI.SmartControl: Internal timer expired: 1
,09-02 12:24:22.790  7763  7811 D UEI.SmartControl: unbind internal service
,09-02 12:24:22.802  1035  1904 W libprocessgroup: failed to open /acct/uid_10046/pid_7247/cgroup.procs: No such file or directory
,09-02 12:24:22.809  7763  7763 D UEI.SmartControl: Service.onUnbind: IControl
09-02 12:24:22.809  7763  7763 D UEI.SmartControl: Service.onDestroy
09-02 12:24:22.809  7763  7763 D UEI.SmartControl: Lock is in USE false
09-02 12:24:22.809  7763  7763 D UEI.SmartControl: unbind internal service
,09-02 12:24:22.809  7763  7763 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b0fa4f7
09-02 12:24:22.810  7763  7763 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-02 12:24:22.810  7763  7763 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-02 12:24:22.810  7763  7763 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:24:22.810  7763  7763 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:24:22.810  7763  7763 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:24:22.810  7763  7763 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:24:22.810  7763  7763 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:24:22.810  7763  7763 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:24:22.811  7763  7763 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b0fa4f7
09-02 12:24:22.812  7763  7763 D serial_port: close(fd = 25)
09-02 12:24:22.816  7763  7763 I UEI.SmartControl: Serial port is closed.
09-02 12:24:22.816  7763  7763 I UEI.SmartControl: Serial port is closed.
09-02 12:24:22.816  7763  7763 D UEI.SmartControl: Blaster closed
09-02 12:24:22.816  7763  7763 D UEI.SmartControl: Shut down QS...
09-02 12:24:22.817  7763  7763 D UEI.SmartControl: Stopping QS lib
09-02 12:24:22.817  7763  7763 D UEI.SmartControl: QS lib stop result = true
09-02 12:24:22.817  7763  7763 D UEI.SmartControl: Stopped QS lib
09-02 12:24:22.819  7763  7763 D UEI.SmartControl: Stopped file observer...
09-02 12:24:22.819  7763  7763 D UEI.SmartControl: QS shutdown complete
,09-02 12:24:22.929  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:24:22.971  5051  8003 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 538 ms] updated apps [took 538 ms] 
,09-02 12:24:23.163  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:23.163  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18fa09f5 added. We now have 6 listener(s)
09-02 12:24:23.163  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:24:23.169  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:23.169  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39fd138a added. We now have 7 listener(s)
09-02 12:24:23.169  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:23.170  6705  6776 I System.out: IsBluetoothEnabled
09-02 12:24:23.171  1035  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:23.171  1035  1904 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-02 12:24:23.172  1035  1118 D BluetoothManagerService: Message: 2
09-02 12:24:23.175  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:23.175  1035  2042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:23.175  1035  2042 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-02 12:24:23.192  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:24:23.192  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:23.192  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-02 12:24:23.193  1035  1118 D BluetoothManagerService: Message: 1
09-02 12:24:23.193  1035  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 12:24:23.218  1035  1118 D BluetoothManagerService: Message: 20
09-02 12:24:23.219  1035  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ab7d23e:true
,09-02 12:24:23.223  7834  7834 D BluetoothAdapterState: make
09-02 12:24:23.228  7834  7834 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 12:24:23.228  7834  7834 I bluedroid-qcom: init
09-02 12:24:23.229  7834  8040 I BluetoothAdapterState: Entering OffState
09-02 12:24:23.229  7834  7834 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 12:24:23.230  7834  7834 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 12:24:23.230  7834  7834 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:24:23.230  7834  7834 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 12:24:23.230  7834  7834 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 12:24:23.232  7834  7834 I bluedroid-qcom: get_profile_interface socket
09-02 12:24:23.232  7834  7834 I bluedroid-qcom: get_profile_interface map_client
,09-02 12:24:23.236  7834  8044 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 12:24:23.227  8043  8043 W bdaddr_loader: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:23.237  8043  8043 W bdaddr_loader: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:23.246  7834  8044 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 12:24:23.254  8043  8043 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 12:24:23.254  8043  8043 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 12:24:23.254  8043  8043 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-02 12:24:23.256  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-02 12:24:23.256  1035  1118 D BluetoothManagerService: Message: 40
09-02 12:24:23.256  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 12:24:23.258  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 12:24:23.258  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:24:23.260  7834  7856 I bluedroid-qcom: config_hci_snoop_log
,09-02 12:24:23.262  8043  8043 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-02 12:24:23.268  1035  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 12:24:23.268  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 12:24:23.269  7834  8044 D BluetoothAdapterProperties: Name is: G3
09-02 12:24:23.279  7834  8040 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 12:24:23.279  7834  8040 D BluetoothAdapterProperties: Setting state to 11
09-02 12:24:23.279  7834  8040 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-02 12:24:23.282  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:23.282  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 12:24:23.282  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 12:24:23.284  7834  8040 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 12:24:23.287  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:23.290  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:24:23.294  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:23.298  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-02 12:24:23.299  8043  8043 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 12:24:23.299  8043  8043 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 12:24:23.316  7834  7834 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:24:23.316  7834  7834 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:23.316  7834  7834 V BluetoothPbapReceiver: ***********state = 11
,09-02 12:24:23.326  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:23.332  7834  8040 D BluetoothBondStateMachine: make
,09-02 12:24:23.337  7834  8040 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.337  7834  8040 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 12:24:23.337  7834  8040 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.337  7834  8040 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 12:24:23.338  7834  8040 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 12:24:23.339  7834  8050 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 12:24:23.342  7834  8040 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:23.352  7834  7834 D HeadsetService: Received start request. Starting profile...
,09-02 12:24:23.357  7834  8040 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:23.357  7834  7834 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:24:23.357  6996  6996 D BluetoothPermissionRequest: onReceive
09-02 12:24:23.357  7834  7834 D LGBluetoothHfpAdapter: Version 1.6
09-02 12:24:23.360  7834  7834 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 12:24:23.362  7834  7834 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:24:23.362  7834  7834 D HeadsetStateMachine: make
09-02 12:24:23.369  7834  8040 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:24:23.372  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:24:23.379  7834  8040 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:23.384  7834  8040 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:24:23.390  7834  8040 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:24:23.395  7834  8040 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:24:23.406  7834  7834 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:24:23.407  7834  7834 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:24:23.411  7834  8040 V LGMDMManager: Create singleton instance
09-02 12:24:23.412  7834  7834 D HeadsetStateMachine: max_hf_connections = 1
09-02 12:24:23.412  7834  7834 I bluedroid-qcom: get_profile_interface handsfree
09-02 12:24:23.413  7834  8040 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 12:24:23.415  7834  7834 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 12:24:23.415   320  2159 V AudioPolicyService: registerClient() client 0xb558aa20, uid 1002
09-02 12:24:23.415   320  1402 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 12:24:23.415   320  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:24:23.415   320  1402 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:24:23.416  7834  7834 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 12:24:23.416   320  2160 V AudioFlinger: registerClient() client 0xb1433100, pid 7834
09-02 12:24:23.416   320  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:23.416   320  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:23.417  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:23.417  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:23.417  1853  4473 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:23.417  1853  4473 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:23.417   320  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,09-02 12:24:23.417   320  1397 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:23.417  7834  7834 V ToneGenerator: Create Track: 0xb4928080
09-02 12:24:23.417  7834  7834 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 12:24:23.417  7834  7834 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 12:24:23.417  1853  4473 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:23.417  1853  4473 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:23.417   320  2159 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:24:23.417   320  2159 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 12:24:23.417   320  2159 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:24:23.417   320  2159 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:24:23.417  7834  7834 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 12:24:23.418   320   320 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 12:24:23.418  3428  3447 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:23.418  1601  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:23.418  3428  3447 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:23.418  1601  1617 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:23.418  7834  7855 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:23.418  7834  7855 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 12:24:23.418  1035  1996 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:24:23.418  1035  1996 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:24:23.418  7834  7855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:23.418  1035  1996 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:23.418  1035  1996 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:23.419  3428  3447 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:24:23.419  3428  3447 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:24:23.419   320  1403 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:24:23.419   320  1403 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 12:24:23.419   320  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:24:23.419   320  1403 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:24:23.419  7834  7855 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 12:24:23.419  7834  7834 V AudioSystem: getLatency() output 2, latency 50
09-02 12:24:23.419  7834  7834 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 12:24:23.419  7834  7834 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 12:24:23.419   320  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 12:24:23.419   320  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:24:23.419   320  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 12:24:23.419   320  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:24:23.419   320  2160 V AudioFlinger: createTrack() lSessionId: 21
09-02 12:24:23.421  7834  7834 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 12:24:23.421   320  2160 V AudioFlinger: acquiring 21 from 7834, for 7834
,09-02 12:24:23.421   320  2160 V AudioFlinger:  added new entry for 21
09-02 12:24:23.421  7834  7834 V ToneGenerator: ToneGenerator INIT OK, time: 136871
09-02 12:24:23.422  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.422  7834  8059 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 12:24:23.423  7834  8059 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:24:23.423  7834  8059 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,09-02 12:24:23.423  7834  8059 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 12:24:23.423   320  2159 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7834
09-02 12:24:23.424   320  2159 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 12:24:23.424   320  2159 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 12:24:23.424   320  2159 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 12:24:23.424   320  2159 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 12:24:23.424   320  2159 V voice   : voice_set_parameters: exit with code(0)
09-02 12:24:23.424   320  2159 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
,09-02 12:24:23.424   320  2159 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
,09-02 12:24:23.424   320  2159 V msm8974_platform: platform_set_parameters: exit with code(0)
,09-02 12:24:23.424   320  2159 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 12:24:23.424   320  2159 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 12:24:23.424   320  2159 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 12:24:23.425  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.425  7834  8059 V ToneGenerator: ToneGenerator destructor
09-02 12:24:23.425  7834  8059 V ToneGenerator: stopTone
09-02 12:24:23.425  7834  8059 V ToneGenerator: Delete Track: 0xb4928080
,09-02 12:24:23.426  7834  8059 V AudioTrack: ~AudioTrack, releasing session id from 7834 on behalf of 7834
09-02 12:24:23.426   320  1403 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 12:24:23.426   320   320 V AudioFlinger: releasing 21 from 7834 for 7834
09-02 12:24:23.426   320  1403 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 12:24:23.426   320   320 V AudioFlinger:  decremented refcount to 0
09-02 12:24:23.426   320   320 V AudioFlinger: purging stale effects
09-02 12:24:23.426   320  1269 V AudioPolicyService: AudioCommandThread() waking up
,09-02 12:24:23.426   320  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 12:24:23.426   320  1269 V AudioPolicyManager: releaseOutput() 2
09-02 12:24:23.426   320  1269 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 12:24:23.426   320  1403 V AudioFlinger: PlaybackThread::Track destructor
09-02 12:24:23.426   320  1403 V AudioFlinger: removeClient_l() pid 7834, calling pid 320
09-02 12:24:23.427  7834  7834 D A2dpService: Received start request. Starting profile...
09-02 12:24:23.428  1035  1995 W Process : Unable to open /proc/8064/status
,09-02 12:24:23.428  7834  7834 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 12:24:23.429  7834  7834 V Avrcp   : make
09-02 12:24:23.429  7834  7834 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 12:24:23.430  7834  7834 I bluedroid-qcom: get_profile_interface avrcp
09-02 12:24:23.440  7834  7834 V AudioManager: registerRemoteController: size of Media player list: 0
,09-02 12:24:23.442  7834  7834 E AudioManager: No RCC entry present to update
09-02 12:24:23.442  7834  7834 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 12:24:23.446  7834  7834 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 12:24:23.447  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 12:24:23.447  7834  7834 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 12:24:23.452  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 12:24:23.607  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:24:23.608  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:24:23.787  1035  1768 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 12:24:23.802  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-02 12:24:23.816  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 12:24:23.817  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:24:23.819  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 12:24:23.819  7834  7834 I BluetoothA2dpServiceJni: classInitNative
09-02 12:24:23.819  7834  7834 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:24:23.820  7834  7834 D A2dpStateMachine: make
,09-02 12:24:23.822  7834  7834 I bluedroid-qcom: get_profile_interface a2dp
,09-02 12:24:23.823  7834  8074 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 12:24:23.826  7834  7834 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:24:23.826  7834  7834 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 12:24:23.827  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.827  7834  8073 D A2dpStateMachine: Enter Disconnected: -2
09-02 12:24:23.828  7834  7834 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 12:24:23.830  7834  7834 D HidService: Received start request. Starting profile...
09-02 12:24:23.831  7834  7834 I bluedroid-qcom: get_profile_interface hidhost
09-02 12:24:23.831  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.831  7834  7834 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 12:24:23.834  7834  7834 D HealthService: Received start request. Starting profile...
09-02 12:24:23.837  7834  7834 I bluedroid-qcom: get_profile_interface health
09-02 12:24:23.837  7834  7834 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:24:23.837  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.838  7834  7834 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 12:24:23.840  7834  7834 D PanService: Received start request. Starting profile...
09-02 12:24:23.840  7834  7834 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:24:23.840  7834  7834 I bluedroid-qcom: get_profile_interface pan
09-02 12:24:23.849  7834  7834 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 12:24:23.849  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.852  7834  7834 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-02 12:24:23.862  7834  7834 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:24:23.864  7834  7834 D BtGatt.GattService: Received start request. Starting profile...
09-02 12:24:23.864  7834  7834 D BtGatt.GattService: start()
09-02 12:24:23.864  7834  7834 I bluedroid-qcom: get_profile_interface gatt
09-02 12:24:23.864  7834  7834 D BtGatt.AdvertiseManager: advertise manager created
09-02 12:24:23.873  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
,09-02 12:24:23.877  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:23.878  7834  7834 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 12:24:23.880  7834  7834 V BluetoothMapService: BluetoothMapBinder()
09-02 12:24:23.881  7834  7834 D BluetoothMapService: Received start request. Starting profile...
09-02 12:24:23.881  7834  7834 D BluetoothMapService: start()
09-02 12:24:23.885  7834  7834 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 12:24:23.885  7834  7834 D BluetoothMapEmailAppObserver: createReceiver()
,09-02 12:24:23.887  7834  7834 D BluetoothMapEmailAppObserver: initObservers()
09-02 12:24:23.887  7834  7834 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-02 12:24:23.897  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
,09-02 12:24:23.897  7834  7834 D HeadsetStateMachine: Proxy object connected
09-02 12:24:23.898  7834  7834 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 12:24:23.899  7834  7834 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 12:24:23.904  7834  7834 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:24:23.904  7834  8059 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 12:24:23.905  7834  8059 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 12:24:23.905  7834  8059 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 12:24:23.909  7834  7834 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 12:24:23.911  7834  7834 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:23.916  7834  7834 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:24:23.919  7834  7834 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:24:23.920  7834  7834 V PanService: [BTUI] SIM Extra State :ABSENT
09-02 12:24:23.923  7834  7834 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 12:24:23.927  7834  7834 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 12:24:23.927  7834  7834 V BluetoothMapService: Handler(): got msg=1
09-02 12:24:23.928  7834  7834 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:23.928  7834  7834 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:23.928  7834  8040 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 12:24:23.928  7834  7834 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:23.928  7834  7834 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:23.928  7834  8040 I bluedroid-qcom: enable
09-02 12:24:23.928  7834  7834 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-02 12:24:23.928  7834  8040 I bt_hci_bdroid: init
09-02 12:24:23.930  7834  8040 I bt_vendor: bt-vendor : init
09-02 12:24:23.930  7834  8040 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 12:24:23.930  7834  8040 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 12:24:23.930  7834  8040 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 12:24:23.930  7834  8040 D bt_userial_mct: userial_init
09-02 12:24:23.932  7834  8040 D bt_hci_bdroid: set_power 1
09-02 12:24:23.932  7834  8040 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 12:24:23.932  7834  8040 I bt_vendor: Starting hciattach daemon
09-02 12:24:23.932  7834  8040 I bt_vendor: try to set true
09-02 12:24:23.935  7834  8081 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 12:24:23.935  7834  8081 I bt-btu  : btu_task pending for preload complete event
,09-02 12:24:23.927  8084  8084 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:24:23.927  8084  8084 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:23.958  8085  8085 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 12:24:24.027  8091  8091 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 12:24:24.052  8092  8092 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 12:24:24.086  8094  8094 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:24:24.100  8095  8095 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-02 12:24:24.113  8096  8096 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:24:24.127  8097  8097 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-02 12:24:24.169  8099  8099 I libmdmdetect: ESOC framework not supported
09-02 12:24:24.170  8099  8099 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 12:24:24.179  8099  8099 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-02 12:24:24.179  8099  8099 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 12:24:24.179  8099  8099 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 12:24:24.179  8099  8099 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 12:24:24.179  8099  8099 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 12:24:24.179  8099  8099 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 12:24:24.179  8099  8099 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 12:24:24.214  8099  8100 E QC-QMI  : qmi_client [8099] 15: failed to locate client data
09-02 12:24:24.216   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 12:24:24.216   469   469 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-02 12:24:24.255  8101  8101 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 12:24:24.272  8102  8102 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 12:24:24.336  7834  8040 I bt_vendor: bluetooth satus is on
,09-02 12:24:24.336  7834  8040 D bt_hci_bdroid: preload
,09-02 12:24:24.337  7834  8083 D bt_userial_mct: userial_open(port:0)
09-02 12:24:24.337  7834  8083 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 12:24:24.342  7834  8083 I bt_vendor: Done intiailizing UART
09-02 12:24:24.347  7834  8083 I bt_vendor: Done intiailizing UART
09-02 12:24:24.347  7834  8083 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 12:24:24.347  7834  8083 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 12:24:24.347  7834  8104 D bt_userial_mct: Entering userial_read_thread()
09-02 12:24:24.348  7834  8081 I bt-btu  : btu_task received preload complete event
09-02 12:24:24.349  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 12:24:24.349  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 12:24:24.356  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:24:24.365  7834  8081 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:24:24.366  7834  8081 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:24:24.366  7834  8081 I         : BTE_InitTraceLevels -- TRC_SMP
,09-02 12:24:24.366  7834  8081 I         : BTE_InitTraceLevels -- TRC_BTAPP,
09-02 12:24:24.366  7834  8081 I         : BTE_InitTraceLevels -- TRC_BTIF,
09-02 12:24:24.469  7834  8081 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-02 12:24:24.469  7834  8081 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0167061 
,09-02 12:24:24.469  7834  8081 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0167061 
,09-02 12:24:24.525  7834  8044 E bt-btif : Calling BTA_HhEnable
,09-02 12:24:24.526  7834  8044 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-02 12:24:24.526  7834  8044 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 12:24:24.538  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-02 12:24:24.538  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 12:24:24.538  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 12:24:24.539  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 12:24:24.539  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 12:24:24.543  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 12:24:24.545  7834  8044 D BluetoothAdapterProperties: Name is: G3
,09-02 12:24:24.551  7834  8044 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:24:24.551  7834  8044 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:24:24.552  7834  8044 D bt_hci_bdroid: postload
,09-02 12:24:24.559  7834  8083 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:24:24.562  7834  8044 D bte_conf: Device ID record 1 : primary
09-02 12:24:24.562  7834  8044 D bte_conf:   vendorId            = 00c4
09-02 12:24:24.562  7834  8044 D bte_conf:   vendorIdSource      = 0001
09-02 12:24:24.562  7834  8044 D bte_conf:   product             = 13a1
09-02 12:24:24.562  7834  8044 D bte_conf:   version             = 1000
09-02 12:24:24.562  7834  8044 D bte_conf:   clientExecutableURL = 
09-02 12:24:24.562  7834  8044 D bte_conf:   serviceDescription  = 
09-02 12:24:24.562  7834  8044 D bte_conf:   documentationURL    = 
09-02 12:24:24.562  7834  8044 D bte_conf: bte_load_did_conf no section named DID2.
09-02 12:24:24.563  7834  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 12:24:24.563  7834  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:24.563  7834  8081 W bt-smp  : Plain text(LSB ~ MSB) = cf c5 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:24.563  7834  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 d7 b3 41 8f 59 f8 42 5b e9 6b 2b 7b 28 5f 23 
09-02 12:24:24.564  7834  8083 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:24:24.564  7834  8081 W bt-btm  : Stopping oneshot timer
09-02 12:24:24.567  7834  8083 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:24:24.568  7834  8040 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 12:24:24.568  7834  8040 D BluetoothAdapterProperties: ScanMode =  20
09-02 12:24:24.568  7834  8040 D BluetoothAdapterProperties: State =  11
,09-02 12:24:24.571  7834  8040 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 12:24:24.572  7834  8040 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 12:24:24.567  8109  8109 W sh      : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:24.574  7834  8040 D BluetoothAdapterProperties: Setting state to 12
09-02 12:24:24.575  7834  8040 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 12:24:24.575  7834  8044 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 12:24:24.575  7834  8044 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:24:24.567  8109  8109 W sh      : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:24.584  1035  1118 D BluetoothManagerService: Message: 60
09-02 12:24:24.584  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 12:24:24.584  1035  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-02 12:24:24.589  7834  8083 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:24:24.592  7834  8040 I BluetoothAdapterState: Entering On State
,09-02 12:24:24.593  1853  2429 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:24.596  7834  8104 E bt_mct  : hci lib postload completed
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:24.630  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:24:24.637  7834  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:24.638  7834  8081 W bt-smp  : Plain text(LSB ~ MSB) = 1b 8b 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:24.638  7834  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 96 b8 55 1e ae a3 6a 71 31 af bf 1b c4 1a 9e 
09-02 12:24:24.638  7834  8081 W bt-btm  : Stopping oneshot timer
09-02 12:24:24.642  7834  8044 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:24:24.642  7834  8044 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 12:24:24.651  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:24:24.653  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:24:24.660  7834  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:24.660  7834  8081 W bt-smp  : Plain text(LSB ~ MSB) = 46 71 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:24.660  7834  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = b1 a1 c2 af 63 6b f9 d6 33 f8 b5 3e 15 07 f5 2a 
09-02 12:24:24.661  7834  8081 W bt-btm  : Stopping oneshot timer
09-02 12:24:24.680  7834  8040 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 12:24:24.680  7834  8040 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 12:24:24.680  7834  8040 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-02 12:24:24.685  7834  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:24.686  7834  8081 W bt-smp  : Plain text(LSB ~ MSB) = f3 8e 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:24.686  7834  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = f4 e5 12 94 2e 04 02 2c 4c 7f 5e a7 ad 79 9c a6 
09-02 12:24:24.686  7834  8081 W bt-btm  : Stopping oneshot timer
09-02 12:24:24.689  7834  8040 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 12:24:24.689  7834  8040 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 12:24:24.698  6996  7012 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:24:24.698  6996  7012 D BluetoothPan: onBluetoothStateChange call bindService
09-02 12:24:24.698  8114  8114 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-02 12:24:24.704  1853  1853 D BluetoothHeadset: Proxy object connected
09-02 12:24:24.704  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:24.705  6996  6996 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:24:24.705  6996  6996 D PanProfile: Bluetooth service connected
09-02 12:24:24.707  1853  1853 D BluetoothHeadset: Proxy object connected
09-02 12:24:24.707  1035  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:24.707  1035  1035 D BluetoothHeadset: Proxy object connected
09-02 12:24:24.708  1853  4475 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:24.710  1853  1853 D BluetoothHeadset: Proxy object connected
09-02 12:24:24.711  6996  7011 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:24:24.713  1035  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:24:24.713  7834  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:24:24.713  7834  8081 W bt-smp  : Plain text(LSB ~ MSB) = 15 21 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:24:24.713  7834  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 6c e9 c4 e3 f7 94 83 e5 f0 2f 9f 05 d7 14 f4 2e 
09-02 12:24:24.713  7834  8081 W bt-btm  : Stopping oneshot timer
,09-02 12:24:24.715  6996  7012 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:24:24.715  1035  1035 D BluetoothA2dp: Proxy object connected
09-02 12:24:24.718  6996  6996 D BluetoothA2dp: Proxy object connected
09-02 12:24:24.718  6996  6996 D A2dpProfile: Bluetooth service connected
09-02 12:24:24.718  6996  7011 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:24:24.721  6996  7012 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:24:24.722  6996  6996 D BluetoothInputDevice: Proxy object connected
09-02 12:24:24.722  6996  6996 D HidProfile: Bluetooth service connected
09-02 12:24:24.723  6996  7728 D BluetoothMap: onBluetoothStateChange: up=true
09-02 12:24:24.724  6996  6996 D BluetoothHeadset: Proxy object connected
09-02 12:24:24.724  6996  6996 D HeadsetProfile: Bluetooth service connected
09-02 12:24:24.726  1035  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,09-02 12:24:24.727  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 12:24:24.726  1035  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-02 12:24:24.728  6996  6996 D BluetoothMap: Proxy object connected
09-02 12:24:24.728  6996  6996 D MapProfile: Bluetooth service connected
09-02 12:24:24.728  6996  6996 D BluetoothMap: getConnectedDevices()
09-02 12:24:24.729  7834  8129 V BluetoothMapService: getConnectedDevices()
09-02 12:24:24.730  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:24.730  1941  2145 D LGBluetoothAPIService: Message: 1
09-02 12:24:24.731  1941  2145 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 12:24:24.731  1941  2145 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-02 12:24:24.731  1941  2145 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-02 12:24:24.731  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:24:24.735  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:24.737  7834  7834 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:24.737  7834  7834 D BluetoothMapService: STATE_ON
09-02 12:24:24.739  1035  1118 D BluetoothManagerService: Message: 40
,09-02 12:24:24.739  1035  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 12:24:24.745  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 12:24:24.746  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 12:24:24.754  6996  6996 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:24:24.755  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6,
09-02 12:24:24.755  7834  7834 V BluetoothPbapService: Pbap Service onCreate
09-02 12:24:24.755  7834  7834 V BluetoothPbapService: Starting PBAP service
09-02 12:24:24.756  7834  7834 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 12:24:24.756  7834  7834 V BluetoothMapService: Handler(): got msg=1
09-02 12:24:24.757  7834  7834 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 12:24:24.757  7834  7834 V BluetoothPbapService: Pbap Service onBind
,09-02 12:24:24.759  7834  8133 D BluetoothMapMasInstance: MAS initSocket()
09-02 12:24:24.760  7834  8133 D BluetoothMapMasInstance:   masId = 00
09-02 12:24:24.760  7834  8133 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 12:24:24.760  7834  8133 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 12:24:24.760  7834  8133 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 12:24:24.760  7834  7834 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:24.760  7834  7834 V BluetoothPbapService: state: 12
09-02 12:24:24.760  7834  7834 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:24:24.760  7834  7834 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:24.761  7834  7834 V BluetoothPbapReceiver: ***********state = 12
09-02 12:24:24.762  1035  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:24.762  6996  6996 D BluetoothPbap: Proxy object connected
09-02 12:24:24.762  7834  7834 V BluetoothPbapService: Handler(): got msg=1
09-02 12:24:24.763  7834  7834 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 12:24:24.763  6996  6996 D PbapServerProfile: Bluetooth service connected
09-02 12:24:24.763  7834  8133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:24.765  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:24:24.765  7834  8135 V BluetoothPbapService: Pbap Service initSocket
09-02 12:24:24.765  2211  2211 D c       : Getting all permits...
09-02 12:24:24.765  2211  2211 D a       : Opening database...
,09-02 12:24:24.767  7834  8133 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,09-02 12:24:24.767  7834  8133 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 12:24:24.767  7834  8133 D BluetoothMapMasInstance: Accepting socket connection...
09-02 12:24:24.767  7834  8044 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:24:24.767  7834  8044 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 12:24:24.772  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:24.772  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:24.773  2211  2211 D a       : Opening database auth.proximity.permit_store...
09-02 12:24:24.773  7834  8135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:24.774  7834  8135 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 12:24:24.774  7834  8135 V BluetoothPbapService: Succeed to create listening socket 
09-02 12:24:24.774  7834  8135 V BluetoothPbapService: Accepting socket connection...
09-02 12:24:24.775  2211  2211 D a       : Closing database...
09-02 12:24:24.788  6996  6996 D BluetoothPermissionRequest: onReceive
,09-02 12:24:24.790  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-02 12:24:24.791  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:24:24.794  7834  7834 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 12:24:24.795  7834  7834 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 12:24:24.802  7834  7834 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 12:24:24.823  7834  7834 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-02 12:24:24.823  7834  7834 V BtOppService: onCreate
,09-02 12:24:24.828  7834  7834 V BluetoothOppNotification: send message
09-02 12:24:24.831  7834  7834 V BtOppService: Starting RfcommListener
09-02 12:24:24.839  7834  7834 D BluetoothOppPreference: Dumping Names:  
09-02 12:24:24.839  7834  7834 D BluetoothOppPreference: {}
,09-02 12:24:24.839  7834  7834 D BluetoothOppPreference: Dumping Channels:  
09-02 12:24:24.839  7834  7834 D BluetoothOppPreference: {}
,09-02 12:24:24.841  7834  7834 V BtOppService: onStartCommand
09-02 12:24:24.842  7834  8142 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:24:24.843  7834  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:24:24.843  7834  8138 V BtOppService: Deleted complete outbound shares, number =  0
09-02 12:24:24.847  7834  8138 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 12:24:24.848  7834  8138 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-02 12:24:24.848  7834  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3df2bb92 on behalf of 
09-02 12:24:24.849  7834  8142 V BluetoothOppNotification: update too frequent, put in queue
09-02 12:24:24.850  7834  7834 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:24:24.851  7834  8142 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:24:24.851  7834  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:24:24.851  7834  7834 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 12:24:24.854  7834  8138 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a6c8963 on behalf of 
09-02 12:24:24.854  7834  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17a4d960 on behalf of 
09-02 12:24:24.855  7834  7834 V BluetoothOppNotification: new notify threadi!
09-02 12:24:24.857  7834  7834 V BluetoothOppNotification: send delay message
09-02 12:24:24.858  7834  7834 V BtOppService: start RfcommListener
09-02 12:24:24.858  7834  8142 V BluetoothOppNotification: update too frequent, put in queue
09-02 12:24:24.858  7834  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 12:24:24.860  7834  8142 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 12:24:24.862  7834  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@babfe19 on behalf of 
09-02 12:24:24.863  7834  8143 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-02 12:24:24.866  7834  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:24:24.866  7834  7834 V BtOppService: RfcommListener started
09-02 12:24:24.867  7834  7834 V BtOppService: ContentObserver received notification
09-02 12:24:24.867  7834  8144 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 12:24:24.868  7834  7834 V BtOppService: ContentObserver received notification
09-02 12:24:24.868  1035  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:24.868  7834  8145 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:24:24.869  7834  8145 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:24:24.870  7834  8145 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ffcfede on behalf of 
09-02 12:24:24.870  7834  8144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:24:24.870  7834  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@121458bf on behalf of 
09-02 12:24:24.871  7834  8144 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-02 12:24:24.872  7834  8144 V BtOppRfcommListener: Started RFCOMM listener....
09-02 12:24:24.872  7834  8144 I BtOppRfcommListener: Accept thread started.
09-02 12:24:24.872  7834  8144 V BtOppRfcommListener: Accepting connection...
09-02 12:24:24.872  7834  8145 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 12:24:24.873  7834  8143 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-02 12:24:24.876  7834  8143 V BluetoothOppNotification: outbound notification was removed.
09-02 12:24:24.876  7834  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 12:24:24.881  7834  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@86e2b8c on behalf of 
09-02 12:24:24.882  7834  8143 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 12:24:24.886  7834  8143 V BluetoothOppNotification: inbound notification was removed.
09-02 12:24:24.886  7834  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:24:24.888  7834  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@227562d5 on behalf of 
,09-02 12:24:24.892  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
09-02 12:24:24.892  7834  7834 V BluetoothFtpService: Ftp Service onCreate
09-02 12:24:24.892  7834  7834 I BluetoothFtpService: Ftp Service onCreate
,09-02 12:24:24.893  7834  7834 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:24:24.893  7834  7834 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:24.893  7834  7834 V BluetoothFtpService: Starting Listening on sockets
09-02 12:24:24.893  7834  7834 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:24:24.893  7834  7834 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:24:24.893  7834  7834 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:24:24.894  7834  7834 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:24.894  7834  7834 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 12:24:24.894  7834  7834 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:24:24.896  7834  7834 V BluetoothFtpService: Handler(): got msg=1
09-02 12:24:24.897  7834  7834 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 12:24:24.897  7834  7834 V BluetoothFtpService: Ftp Service initSocket
,09-02 12:24:24.899  1035  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:24.901  7834  7834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:24:24.909  7834  7834 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 12:24:24.913  7834  8147 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-02 12:24:24.931  7834  7834 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9178f6
,09-02 12:24:24.932  7834  7834 V BluetoothSapService: Sap Service onCreate
,09-02 12:24:24.936  7834  7834 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:24:24.936  7834  7834 V BluetoothSapService: state: 12
09-02 12:24:24.936  7834  7834 V BluetoothSapService: Starting SAP server process
09-02 12:24:24.939  7834  7834 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 12:24:24.927  8148  8148 W sapd    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:24.927  8148  8148 W sapd    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:24.943  7834  8149 V BluetoothSapService: Sap Service initRfcommSocket
09-02 12:24:24.944  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:24.946  7834  8149 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:24:24.949  7834  8149 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-02 12:24:24.949  7834  8149 V BluetoothSapService: Succeed to create listening socket 
09-02 12:24:24.949  7834  8149 V BluetoothSapService: Accepting socket connection...
,09-02 12:24:24.964  8148  8148 V BT_SAP  : Event pipe created
09-02 12:24:24.964  8148  8148 V BT_SAP  : create_server_socket qcom.sap.server
09-02 12:24:24.964  8148  8148 V BT_SAP  : created socket fd 6
,09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:25.222  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:24:25.226  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:24:25.232  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:25.233  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33718dfb added. We now have 8 listener(s)
09-02 12:24:25.233  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:25.238  1035  1940 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:24:25.239  1035  1940 D WifiService: setWifiEnabled: false pid=6705, uid=10118
09-02 12:24:25.239  1035  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:24:25.250  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:25.252  1035  1917 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:24:25.253  1035  1917 D WifiService: setWifiEnabled: true pid=6705, uid=10118
09-02 12:24:25.253  1035  1917 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:24:25.284  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:24:25.284  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:24:25.284  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-02 12:24:25.286  1035  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 12:24:25.286  1035  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-02 12:24:25.295  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 12:24:25.295  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:24:25.295  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 12:24:25.295  1035  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:24:25.295  1035  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 12:24:25.295  1035  1392 E WifiHW  : unknown target_country: EU , set to default
09-02 12:24:25.296  1035  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 12:24:25.296  1035  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 12:24:25.296  1035  1392 I WifiUtil: gEnableBmps=1
,09-02 12:24:25.862  7834  7834 V BluetoothOppNotification: new notify threadi!
09-02 12:24:25.862  7834  7834 V BluetoothOppNotification: send delay message
,09-02 12:24:25.884   315   894 D SoftapController: Softap fwReload - Ok
,09-02 12:24:25.910  1035  1392 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (604ms)
,09-02 12:24:25.914  1035  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:24:25.915  1035  1118 D Tethering: InitialState.processMessage what=4
09-02 12:24:25.915  1035  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 12:24:25.932   315   894 D CommandListener: Setting iface cfg
,09-02 12:24:25.932   315   894 D CommandListener: Trying to bring down wlan0
09-02 12:24:25.936   315   894 D CommandListener: Clearing all IP addresses on wlan0
,09-02 12:24:25.957  1035  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 12:24:25.957  8176  8176 W wpa_supplicant: type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:25.957  8176  8176 W wpa_supplicant: type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:25.976  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:24:25.976  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:24:25.976  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:24:25.976  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-02 12:24:25.977  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-02 12:24:25.979  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:24:25.979  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 12:24:25.979  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:24:25.979  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:24:25.979  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:24:25.980  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:24:25.986  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:24:25.986  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:24:25.986  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:24:25.987  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:24:25.988  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:24:25.989  7834  8168 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 12:24:25.989  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:24:25.990  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 12:24:25.990  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:24:25.990  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:24:25.990  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:24:25.991  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 12:24:26.001  8176  8176 I wpa_supplicant: Successfully initialized wpa_supplicant
09-02 12:24:26.004  7834  8168 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36640bb6 on behalf of 
09-02 12:24:26.005  7834  8168 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 12:24:26.006  7834  8168 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:24:26.007  7834  8168 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28eea0b7 on behalf of 
09-02 12:24:26.008  7834  8168 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 12:24:26.009  7834  8168 V BluetoothOppNotification: outbound notification was removed.
09-02 12:24:26.009  7834  8168 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-02 12:24:26.010  7834  8168 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@271c6024 on behalf of 
,09-02 12:24:26.011  7834  8168 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 12:24:26.013  7834  8168 V BluetoothOppNotification: inbound notification was removed.
09-02 12:24:26.013  7834  8168 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:24:26.014  7834  8168 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c38178d on behalf of 
09-02 12:24:26.035  8176  8176 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 12:24:26.035  8176  8176 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-02 12:24:26.058  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:26.058  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:26.058  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:24:26.058  1035  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 12:24:26.059  1035  1392 D WifiMonitor: connecting to supplicant
,09-02 12:24:26.061  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 12:24:26.062  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:26.067  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:26.108  8176  8176 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 12:24:26.128  1035  1105 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8188 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-02 12:24:26.128  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-02 12:24:26.152  8176  8176 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-02 12:24:26.164  8176  8176 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-02 12:24:26.165  8176  8176 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-02 12:24:26.166  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 12:24:26.166  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 12:24:26.167  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:24:26.168  1035  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:24:26.168  1035  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:26.168  1035  8206 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-02 12:24:26.168  1035  8206 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 12:24:26.168  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 12:24:26.169  1035  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:26.169  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 12:24:26.169  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:24:26.169  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:24:26.169  1035  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 12:24:26.169  1035  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 12:24:26.170  1035  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 12:24:26.170  1035  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 12:24:26.170  1035  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 12:24:26.171  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.171  1035  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:24:26.171  1035  1392 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:24:26.171  1035  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:24:26.171  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.171  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.172  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.172  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:24:26.173  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-02 12:24:26.174  1035  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 12:24:26.174  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 12:24:26.175  1035  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 12:24:26.175  1035  1392 D WifiNative-wlan0: SET update_config 1: returned true
09-02 12:24:26.175  1035  1392 D WifiConfigStore: Loading config and enabling all networks 
09-02 12:24:26.175  1035  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 12:24:26.175  1035  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 12:24:26.176  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor:     -, is Bluetooth enabled: true
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:26.181  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:24:26.182  1035  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 12:24:26.183  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:24:26.191  1035  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 12:24:26.191  1035  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 12:24:26.192  1035  1392 D WifiStateMachine: enableVerboseLogging : level 2
09-02 12:24:26.192  1035  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-02 12:24:26.193  1035  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 12:24:26.193  1035  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 12:24:26.193  1035  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 12:24:26.193  1035  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 12:24:26.194  1035  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 12:24:26.194  1035  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 12:24:26.194  1035  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 12:24:26.194  1035  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 12:24:26.194  1035  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 12:24:26.195  1035  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-02 12:24:26.195  1035  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 12:24:26.195  1035  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 12:24:26.196  1035  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 12:24:26.196  1035  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:24:26.196  1035  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 12:24:26.197  1035  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 12:24:26.197  1035  1392 D WifiNative-HAL: Setting external_sim to 1
09-02 12:24:26.197  1035  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 12:24:26.197  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-02 12:24:26.197  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 12:24:26.197  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-02 12:24:26.197  1941  2345 D WfdsMonitor: WfdsMonitorThread create
09-02 12:24:26.197  1035  1392 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 12:24:26.197  1035  1392 I WifiNative-HAL: startHal
09-02 12:24:26.198  1035  1392 D wifi    : setting scan oui 0xaf6f30e0
09-02 12:24:26.198  7870  7870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.198  1941  2345 D WfdsMonitor: WFDS Monitor is created and started
09-02 12:24:26.198  1941  2345 D WfdsService: WiFi: Supplicant connection re-established
09-02 12:24:26.198  1035  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:24:26.198  1035  1392 I WifiNative-HAL: startHal
09-02 12:24:26.198  1035  1392 D wifi    : setting scan oui 0xaf6f30e0
09-02 12:24:26.198  1035  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 12:24:26.199  1035  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 12:24:26.199  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 12:24:26.199  1941  8207 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 12:24:26.199  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 12:24:26.199  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 12:24:26.200  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:24:26.200  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:24:26.200  1941  8207 E CtrlSupplicant: Succeed to open control connection
09-02 12:24:26.200  1941  8207 E CtrlSupplicant: Succeed to open monitor connection
09-02 12:24:26.200  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:24:26.200  1941  8207 D WfdsMonitor: Supplicant connection established
09-02 12:24:26.201  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-02 12:24:26.201  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 12:24:26.202  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 12:24:26.202  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 12:24:26.202  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:24:26.202  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:24:26.202  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:24:26.202  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:24:26.202  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:24:26.203  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:24:26.203  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 12:24:26.203  8176  8176 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,09-02 12:24:26.203  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 12:24:26.203  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:24:26.203  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:24:26.204  1035  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:24:26.204  1035  1392 E WifiNative: : [139,637,024 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 12:24:26.204  1035  1392 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 12:24:26.205  1035  1392 D WifiNative-wlan0: RECONNECT: returned true
09-02 12:24:26.205  1035  1392 D WifiNative-wlan0: doString: [STATUS]
,09-02 12:24:26.205  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:24:26.205  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 12:24:26.205  1035  1392 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:24:26.205  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:24:26.206  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:24:26.206  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:24:26.208   315   894 D CommandListener: Setting iface cfg
09-02 12:24:26.208   315   894 D CommandListener: Trying to bring up p2p0
09-02 12:24:26.208  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 12:24:26.208  1035  1390 D LGWifiP2pService: P2pEnablingState
09-02 12:24:26.208  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.208  1035  1390 D LGWifiP2pService: P2p socket connection successful
09-02 12:24:26.208  1035  1390 D LGWifiP2pService: P2pEnabledState
09-02 12:24:26.208  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
,09-02 12:24:26.209  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 12:24:26.210  1941  1941 D WfdsService: WifiP2pState is changed : true
09-02 12:24:26.210  1941  2345 D WfdsService: Receive the WFDS_ENABLE Method
09-02 12:24:26.210  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-02 12:24:26.210  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-02 12:24:26.210  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 12:24:26.211  1941  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 12:24:26.211  8176  8176 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 12:24:26.211  1941  2345 D WfdsService: selectPreferredScanChannel [36]
09-02 12:24:26.211  1941  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 12:24:26.213  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 12:24:26.213  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 12:24:26.213  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 12:24:26.214  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
09-02 12:24:26.214  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 12:24:26.214  1035  1390 D LGWifiP2pService: before postfix = G3
09-02 12:24:26.214  1941  1941 D WfdsService: isConnected: false
09-02 12:24:26.214  1035  1390 D WifiServerServiceExt: postfix byte check : 2
09-02 12:24:26.214  1035  1390 D LGWifiP2pService: after postfix = G3
09-02 12:24:26.214  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 12:24:26.214  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 12:24:26.214  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 12:24:26.215  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 12:24:26.215  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 12:24:26.215  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 12:24:26.216  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 12:24:26.216  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 12:24:26.216  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
09-02 12:24:26.216  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-02 12:24:26.217  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-02 12:24:26.217  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 12:24:26.217  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 12:24:26.217  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 12:24:26.217  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 12:24:26.218  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 12:24:26.218  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 12:24:26.218  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 12:24:26.218  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 12:24:26.218  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 12:24:26.218  1941  1941 D WfdsService: Update P2p Interface State: 3
09-02 12:24:26.219  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 12:24:26.219  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-02 12:24:26.219  1035  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.219  1035  1555 I WifiNative-HAL: startHal
09-02 12:24:26.219  1035  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.219  1035  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,09-02 12:24:26.220  1035  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0,
09-02 12:24:26.220  1035  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 12:24:26.221  1035  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 12:24:26.221  1035  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 12:24:26.222  1035  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
,09-02 12:24:26.222  1035  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
,09-02 12:24:26.222  1035  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 12:24:26.237  8176  8176 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,09-02 12:24:26.238  1035  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 12:24:26.238  1035  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 12:24:26.238  1035  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 12:24:26.238  1035  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 12:24:26.239  8176  8176 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 12:24:26.239  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
,09-02 12:24:26.239  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-02 12:24:26.239  1035  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6f30e0
09-02 12:24:26.239  1035  1555 D wifi    : failed to get capabilities : -3
09-02 12:24:26.239  1035  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 12:24:26.239  1035  1555 E WifiScanningService: could not get scan capabilities
09-02 12:24:26.239  1035  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 12:24:26.240  1035  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 12:24:26.240  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 12:24:26.240  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 12:24:26.241  8176  8176 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.241  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:24:26.242  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.242  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.242  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.242  8176  8176 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:24:26.242  8176  8176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.242  1035  8206 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.242  1035  8206 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.242  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.242  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.242  8176  8176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.242  1035  8206 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.243  1035  8206 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.243  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.243  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.244  1035  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 12:24:26.244  1035  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:24:26.244  1035  1392 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:24:26.245  1035  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:24:26.245  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 12:24:26.245  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 12:24:26.245  8176  8176 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:24:26.245  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 12:24:26.245  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:24:26.245  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:24:26.245  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-02 12:24:26.246  1035  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 12:24:26.246  1035  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 12:24:26.246  1035  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true,
,09-02 12:24:26.246  1941  8207 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.246  1035  1392 D WifiNative-wlan0: doBoolean: SCAN
09-02 12:24:26.246  1941  8207 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.246  1035  1392 D WifiNative-wlan0: SCAN: returned false
09-02 12:24:26.247  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=139680  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:24:26.275  1035  1996 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8212 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:24:26.279  1035  1390 D LGWifiP2pService: InactiveState
09-02 12:24:26.279  1035  1390 D LGWifiP2pService: InactiveState{ when=-61ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.279  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-61ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.279  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 12:24:26.280  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 12:24:26.281  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=139714  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:24:26.281  1035  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:26.282  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:26.282  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:26.282  1035  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-02 12:24:26.282  8176  8176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.282  1035  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:26.283  1035  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:26.283  8176  8176 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:24:26.283  8176  8176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.283  1035  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:24:26.284  8176  8176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.284  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:26.286  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.286  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.286  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 12:24:26.286  1941  8207 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:24:26.286  1941  8207 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.286  1941  8207 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.286  1035  8206 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:24:26.286  1035  8206 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.286  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.286  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:24:26.287  1035  8206 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.287  1035  8206 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.287  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.287  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.287  1035  8206 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:24:26.287  1035  8206 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.287  1035  8206 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.287  1035  8206 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:24:26.287  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 12:24:26.287  1035  1390 D LGWifiP2pService: InactiveState{ when=-44ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.287  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-44ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: InactiveSta,te{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.288  1035  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:24:26.291  1941  2345 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 12:24:26.295  1035  1390 D LGWifiP2pService: InactiveState{ when=-15ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.295  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:26.295  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-02 12:24:26.295  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.295  1035  1390 D LGWifiP2pService: DefaultState{ when=-16ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:26.295  1035  1035 E WifiServerServiceExt: No p2p device connected
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:24:26.299  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:24:26.301  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:24:26.305   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 478us total 31.492ms
09-02 12:24:26.310  6705  6776 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-02 12:24:26.311  6705  6776 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-02 12:24:26.313  6705  6776 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2ed07185 Bundle[{}]
09-02 12:24:26.313  8188  8210 W FormManager: Network not available. Please check & try again.
09-02 12:24:26.313  6705  6776 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 12:24:26.314  6705  6776 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-02 12:24:26.314  6705  6776 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-02 12:24:26.315  6705  6776 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 12:24:26.316  6705  6776 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 12:24:26.317  6705  6776 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 12:24:26.324  6705  6776 I System.out: Running OutgoingSocketThread
09-02 12:24:26.326  6705  8230 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 886)
09-02 12:24:26.326   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 19.935ms
09-02 12:24:26.327  6705  8230 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 59190
09-02 12:24:26.327  6705  8230 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-02 12:24:26.328  8188  8211 V FormManager: Network unavailable.
09-02 12:24:26.334  8188  8211 V FormManager: Network unavailable.
,09-02 12:24:26.347   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.874ms
09-02 12:24:26.347  1035  1769 I ActivityManager: Killing 7268:com.android.chrome/u0a57 (adj 15): empty #17
09-02 12:24:26.369  8212  8212 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:26.411  1035  1996 W libprocessgroup: failed to open /acct/uid_10057/pid_7268/cgroup.procs: No such file or directory
,09-02 12:24:26.414  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:24:26.422  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:26.424  1035  1645 I ActivityManager: Killing 7288:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-02 12:24:26.478  1035  2042 W libprocessgroup: failed to open /acct/uid_10062/pid_7288/cgroup.procs: No such file or directory
,09-02 12:24:26.510  8212  8212 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:24:26.519  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:24:26.525  8188  8234 W FormManager: Network not available. Please check & try again.
,09-02 12:24:26.534  8188  8235 V FormManager: Network unavailable.
09-02 12:24:26.536  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:24:26.547  8188  8235 V FormManager: Network unavailable.
,09-02 12:24:26.556  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:24:26.557  4792  4792 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:24:26.565  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:24:26.570  4792  4792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:24:26.577  4792  8237 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:24:26.587  4792  8238 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:24:26.587  4792  8238 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:24:26.636  1035  1996 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8239 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 12:24:26.791  8239  8239 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 12:24:26.791  8239  8239 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 12:24:26.803  8239  8239 V [BNRBootReceiver]: Boot Receiver Return
,09-02 12:24:26.803  8239  8239 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 12:24:26.826  8176  8176 E wpa_supplicant: USIM:  scard_init function
,09-02 12:24:26.826  8176  8176 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-02 12:24:26.829  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 12:24:26.829  1035  8206 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 12:24:26.829  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 12:24:26.829  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-02 12:24:26.829  1035  8206 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 12:24:26.829  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:24:26.829  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 12:24:26.830  1035  1392 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 12:24:26.830  1035  1392 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 12:24:26.831  1035  1392 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 12:24:26.832  1035  1392 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 12:24:26.832  1035  1392 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 12:24:26.892  1035  1976 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8257 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 12:24:26.894  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140327  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 12:24:26.899  1035  1976 I ActivityManager: Killing 7323:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-02 12:24:26.949  8176  8176 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-02 12:24:26.949  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 12:24:26.949  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,09-02 12:24:26.950  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 12:24:26.950  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 12:24:26.955  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:26.955  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:26.962  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:26.962  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 12:24:26.962  8176  8176 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:24:26.962  8176  8176 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:24:26.962  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 12:24:26.963  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:24:26.963  1035  8206 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:24:26.963  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 12:24:26.963  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:24:26.963  1035  8206 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:24:26.963  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:26.963  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 12:24:26.983  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140416  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 12:24:26.983  1035  1645 W libprocessgroup: failed to open /acct/uid_10085/pid_7323/cgroup.procs: No such file or directory
09-02 12:24:26.983  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140416  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:24:26.984  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140417  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:24:26.984  1035  1392 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140417
09-02 12:24:26.989  1035  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:24:26.985  1035  1392 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140418
09-02 12:24:26.991  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.991  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.991  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 12:24:26.992  1035  1392 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140425
09-02 12:24:26.992  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140425
09-02 12:24:26.992  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.992  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:26.993  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:24:26.993  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:26.994  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:24:26.998  1035  1392 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140431
09-02 12:24:26.998  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=140431  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:24:26.999  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.001  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.001  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:27.002  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.002  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.002  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:24:27.003  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:24:27.006  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.006  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.006  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 12:24:27.007  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=140439  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:24:27.007  1035  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140440  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:24:27.008  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140441  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:24:27.008  1035  1392 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140441
09-02 12:24:27.009  1035  1392 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140442
09-02 12:24:27.009  1035  1392 D WifiNative-wlan0: doString: [STATUS]
09-02 12:24:27.010  1035  8206 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:24:27.010  1035  8206 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:24:27.010  1035  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:24:27.012  1035  1392 I WifiServiceExtension: setVHTCapabilityType  : false
09-02 12:24:27.020  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.020  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:24:27.021  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.022  1035  1392 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 12:24:27.022  1035  1392 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-02 12:24:27.023  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.023  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:27.024  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.029  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.029  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.029  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 12:24:27.031  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:24:27.031  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.031  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 12:24:27.033  1035  1392 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 12:24:27.033  1035  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:24:27.033  1035  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:24:27.033  1035  1432 D ConnectivityService: Got NetworkAgent Messenger
09-02 12:24:27.034  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 12:24:27.034  1035  1432 D ConnectivityService: NetworkAgent connected
09-02 12:24:27.034  1035  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-02 12:24:27.034  1035  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:24:27.034  8257  8257 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:27.041  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.041  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:27.042  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.043  1035  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:24:27.043  1035  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:24:27.043  1035  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:24:27.043  1035  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:24:27.043  1035  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:24:27.044  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.044  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:24:27.045  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.053  1035  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:24:27.054   315   894 D CommandListener: Setting iface cfg
09-02 12:24:27.057  1035  1392 E WifiStateMachine: Start Dhcp Watchdog 3
09-02 12:24:27.058  1035  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140491  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:27.059  1035  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140491  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:27.059  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-02 12:24:27.061  8257  8257 D PluginManager: init()
09-02 12:24:27.060  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:27.062  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:27.062  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 12:24:27.063  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:27.063  1035  1392 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:27.063  1035  1392 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:27.064  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:27.064  1035  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:24:27.065  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:27.065  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-02 12:24:27.066  1035  8282 D DhcpStateMachine: StoppedState
09-02 12:24:27.066  1035  8282 D DhcpStateMachine: StoppedState{ when=-8ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.066  1035  8282 D DhcpStateMachine: WaitBeforeStartState
09-02 12:24:27.066  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:27.066  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 12:24:27.067  1035  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140500  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:27.067  1035  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140500  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:27.068  1035  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140501  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:24:27.069  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13961] from screen [on:0 period:-361915459] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:24:27.071  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-361915457] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:24:27.071  1035  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 12:24:27.074  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:24:27.077  1035  1432 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-02 12:24:27.078  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.079  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.079  1035  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.079  1035  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.080  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.080  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.081  1035  1432 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 12:24:27.082  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:27.082  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 12:24:27.082  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=101,0,0
09-02 12:24:27.083  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=101,0,0
09-02 12:24:27.083  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 12:24:27.083  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 12:24:27.083  1035  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 12:24:27.083  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 12:24:27.084  1035  1392 D WifiNative-wlan0: SET ps 0: returned true
09-02 12:24:27.084  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 12:24:27.084  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 12:24:27.084  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 12:24:27.085  1035  1392 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 12:24:27.085  1035  1392 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 12:24:27.085  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b98f327 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.085  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b98f327 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.085  1035  1392 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 12:24:27.085  1035  8282 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.085  1035  8282 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 12:24:27.085   315   894 D CommandListener: Setting iface cfg
09-02 12:24:27.086   315   894 D CommandListener: Trying to bring up wlan0
09-02 12:24:27.087  1035  1392 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,09-02 12:24:27.088  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.089  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:24:27.089  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 12:24:27.090  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.091  1035  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.091  1035  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.092  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.092  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:24:27.092  1035  1432 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 12:24:27.093  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 12:24:27.093  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 12:24:27.093  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:24:27.093  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.093  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.093  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:24:27.094  1035  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:24:27.094  1035  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 12:24:27.094  8176  8176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 12:24:27.095  1035  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 12:24:27.095  1035  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:24:27.112  1035  1392 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:24:27.113  1035  1432 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 12:24:27.113  1035  1392 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:24:27.113  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:24:27.113  1035  1392 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-02 12:24:27.114  1035  1432 D ConnectivityService: ignoring duplicate network state non-change
09-02 12:24:27.116  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.116  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:27.117  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.119  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.119  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.119  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 12:24:27.120  1035  1432 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 12:24:27.120  1035  1432 D ConnectivityService: Adding iface wlan0 to network 102
09-02 12:24:27.126  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:24:27.126  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.126  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 12:24:27.128  1035  1392 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 12:24:27.130  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 12:24:27.132  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 12:24:27.135  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:24:27.135  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.135  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:24:27.136  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 12:24:27.138  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.138  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:24:27.141  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.143  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.143  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.143  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:24:27.144  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:24:27.144  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:24:27.144  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.146  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:24:27.146  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:24:27.146  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.152  1035  1432 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 12:24:27.152  1035  1432 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-02 12:24:27.153  1035  1432 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-02 12:24:27.154   315   894 E Netd    : netlink response contains error (File exists)
09-02 12:24:27.154  1035  1432 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-02 12:24:27.155  1035  1432 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 12:24:27.155  1035  1432 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-02 12:24:27.155  1035  1432 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-02 12:24:27.156  1035  1432 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 12:24:27.156  1035  1432 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 12:24:27.156  1035  1432 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-02 12:24:27.156  1035  1432 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-02 12:24:27.156  1035  8277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.156  1035  8277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 12:24:27.156  1035  1432 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:27.156  1035  8277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:24:27.156  1035  1432 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:27.156  1035  8277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 12:24:27.156  1035  1432 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 12:24:27.157  1035  1432 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.157  1035  1432 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 12:24:27.157  1035  1432 D ConnectivityService: currentScore = 0, newScore = 20
09-02 12:24:27.157  1035  1432 D ConnectivityService:    accepting network in place of null
09-02 12:24:27.157  1035  1432 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.157  1035  1392 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.157  1035  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:27.158   315  8288 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 12:24:27.158  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.158  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:24:27.161  1035  1432 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTE,D, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 12:24:27.162  1035  1432 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-02 12:24:27.162  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:24:27.162  1035  1432 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:24:27.162  1035  1432 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 12:24:27.163  1035  1432 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-02 12:24:27.164  1035  1432 D ConnectivityService: validation of new default Network = false
09-02 12:24:27.164  1035  1432 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 12:24:27.164  1035  1432 D DSQN    : enableDataServiceNotify 
09-02 12:24:27.164  1035  1432 D DSQN    : start dsqn bin
,09-02 12:24:27.168  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 12:24:27.168  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:24:27.168  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:24:27.168  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:24:27.172  1035  1432 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 12:24:27.172  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.173  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:27.167  8289  8289 W dsqn    : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:27.167  8289  8289 W dsqn    : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:27.174  1035  1432 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:27.174  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 12:24:27.178  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-02 12:24:27.184  8289  8289 E DSQN    : DSQN ssw
09-02 12:24:27.195  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:24:27.196  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.196  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:24:27.217   315  8288 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 12:24:27.257   315  8288 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-02 12:24:27.288  1035  8282 D DhcpStateMachine: DHCPV4 request on wlan0
,09-02 12:24:27.288  1035  8282 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 12:24:27.288  1035  8282 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 12:24:27.287  8293  8293 W dhcpcd  : type=1400 audit(0.0:197): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:27.287  8293  8293 W dhcpcd  : type=1400 audit(0.0:198): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:24:27.293   315   893 D LGDataListener: argv[0]=dsqncommand
09-02 12:24:27.293   315   893 D LGDataListener: argv[1]=wlan0
09-02 12:24:27.293   315   893 D LGDataListener: argv[2]=1
09-02 12:24:27.293   315   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 12:24:27.294  1035  1116 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 12:24:27.294  1035  1116 D DSQN    : start to monitor internet connection
09-02 12:24:27.301  8293  8293 I dhcpcd  : version 5.5.6 starting
09-02 12:24:27.303  8293  8293 E dhcpcd  : get_duid: m
09-02 12:24:27.303  8293  8293 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 12:24:27.303  8293  8293 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 12:24:27.326  1035  8277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 10:24:26 GMT], X-Android-Received-Millis=[1472811867325], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472811867293]}
09-02 12:24:27.326  1035  8277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 12:24:27.326  1035  8277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 12:24:27.327  1035  1432 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-02 12:24:27.327  1035  1432 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,09-02 12:24:27.327  1035  1432 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:27.328  1035  1432 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:27.328  1035  1432 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 12:24:27.328  1035  1432 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-02 12:24:27.328  1035  1432 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 12:24:27.328  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.328  6705  6776 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 887)
09-02 12:24:27.328  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:27.329  6705  6776 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 887)
09-02 12:24:27.329  1035  1432 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:27.331  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 12:24:27.332  6705  6776 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 892)
09-02 12:24:27.333  6705  6776 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-02 12:24:27.334  6705  6776 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 893)
09-02 12:24:27.334  1035  1432 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.335  1035  1392 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.335  1035  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:24:27.335  1035  1432 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 12:24:27.336  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:27.336  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:24:27.338  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.338  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbe1e18 added. We now have 2 listener(s)
09-02 12:24:27.338  1035  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 12:24:27.349  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.349  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.349  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.349  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.349  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bae5071 added. We now have 9 listener(s)
09-02 12:24:27.349  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.350  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:24:27.354  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:27.358  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:24:27.360  8293  8293 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:24:27.360  8293  8293 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 12:24:27.360  8293  8293 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:24:27.361  8293  8293 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 12:24:27.361  8293  8293 D dhcpcd  : wlan0: sending REQUEST (xid 0x38921c3e), next in 3.26 seconds
09-02 12:24:27.362  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.362  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:24:27.362  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.362  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4410ed7 added. We now have 3 listener(s)
09-02 12:24:27.363  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:24:27.363  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.364  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.365  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:24:27.366  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.368  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.369  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.369  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.369  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.369  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.369  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338303c4 added. We now have 10 listener(s)
09-02 12:24:27.369  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.369  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:27.369  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:24:27.369  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:27.369  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.369  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.369  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:27.369  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.369  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbe1e18 removed from the list
09-02 12:24:27.369  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.369  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bae5071 removed from the list
09-02 12:24:27.369  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:27.369  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.371  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.371  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.372  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.372  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.372  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.372  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bae5071 not in the list
09-02 12:24:27.372  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.372  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.373  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.373  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.373  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.373  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338303c4 removed from the list
09-02 12:24:27.373  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.373  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.373  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.373  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.373  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4410ed7 removed from the list
09-02 12:24:27.374  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.374  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addLi,stener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78682ad added. We now have 2 listener(s)
09-02 12:24:27.374  1035  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.376  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.376  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.376  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.376  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.376  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee489e2 added. We now have 9 listener(s)
09-02 12:24:27.376  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.376  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:24:27.378  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:27.381  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:27.382  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:24:27.382  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:24:27.383  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.385  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.385  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.385  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8e9830 added. We now have 3 listener(s)
09-02 12:24:27.386  1035  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.388  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.388  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.388  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.388  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.389  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37359ca9 added. We now have 10 listener(s)
09-02 12:24:27.389  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.389  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:24:27.389  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:24:27.389  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:24:27.389  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.389  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:24:27.391  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:24:27.391  1035  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.395  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:24:27.395  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:24:27.397  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-02 12:24:27.398  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:27.399  6705  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-02 12:24:27.399  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:27.399  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:27.400  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-02 12:24:27.400  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:27.401  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:24:27.401  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.401  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:27.401  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:27.401  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.401  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78682ad removed from the list,
09-02 12:24:27.401  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.401  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee489e2 removed from the list
,09-02 12:24:27.401  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:27.401  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.401  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:27.401  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.402  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:24:27.402  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.402  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.402  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee489e2 not in the list
,09-02 12:24:27.402  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.402  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:27.403  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.403  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:27.403  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 12:24:27.403  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.403  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.403  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37359ca9 removed from the list
,09-02 12:24:27.403  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.403  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:24:27.403  8293  8293 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-02 12:24:27.403  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.403  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.403  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8e9830 removed from the list
09-02 12:24:27.404  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.404  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7d075c added. We now have 2 listener(s)
,09-02 12:24:27.404  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.406  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.406  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:24:27.406  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.406  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:24:27.406  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23a25a65 added. We now have 9 listener(s)
09-02 12:24:27.406  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:24:27.406  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:24:27.408  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,09-02 12:24:27.412  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:24:27.413  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.414  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:24:27.414  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.414  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19bdebeb added. We now have 3 listener(s)
,09-02 12:24:27.414  1035  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.416  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.417  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:24:27.417  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-02 12:24:27.417  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-02 12:24:27.417  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.417  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.417  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36813d48 added. We now have 10 listener(s)
09-02 12:24:27.417  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.417  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 12:24:27.418  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:24:27.418  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:24:27.418  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:24:27.418  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.418  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:24:27.421  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:24:27.422  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.424  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:24:27.425  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:24:27.426  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:24:27.426  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:24:27.427  6705  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:24:27.427  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:27.427  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:27.427  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:27.428  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.428  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.428  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:27.428  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 12:24:27.428  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7d075c removed from the list
09-02 12:24:27.428  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.428  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23a25a65 removed from the list
09-02 12:24:27.428  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:27.428  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.428  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.428  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:24:27.429  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.429  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.429  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.429  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23a25a65 not in the list
09-02 12:24:27.429  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.429  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.430  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:24:27.431  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:27.431  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:27.431  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.431  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:24:27.431  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36813d48 removed from the list
09-02 12:24:27.431  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.431  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.431  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.431  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.431  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19bdebeb removed from the list
09-02 12:24:27.432  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.432  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58d5bc7 added. We now have 2 listener(s)
09-02 12:24:27.432  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.434  8257  8257 W ExternalStrings: load override strings
09-02 12:24:27.434  8257  8257 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:24:27.434  8257  8257 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:24:27.435  8257  8257 D StatusProvider: onCreate
09-02 12:24:27.436  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.436  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.436  6705  6776 D org.thaliproject.p2p.btconne,ctorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.436  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.436  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3210e5f4 added. We now have 9 listener(s)
09-02 12:24:27.436  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.436  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:24:27.439  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.441  8293  8293 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 12:24:27.441  8293  8293 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:27.441  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:24:27.441  8293  8293 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 12:24:27.442  8293  8293 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 12:24:27.442  8293  8293 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:24:27.442  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.442  8293  8293 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:24:27.442  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:24:27.442  8293  8293 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 12:24:27.442  8293  8293 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 12:24:27.446  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.448  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.448  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33872f92 added. We now have 3 listener(s)
09-02 12:24:27.448  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.450  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.451  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.451  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.451  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.451  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.451  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3df9ed63 added. We now have 10 listener(s)
09-02 12:24:27.451  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.451  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:24:27.451  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:24:27.451  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:24:27.451  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.451  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:24:27.454  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:24:27.454  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.456  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:24:27.457  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: s,etScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:24:27.458  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:24:27.459  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:27.460  6705  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-02 12:24:27.461  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:27.461  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:27.461  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:24:27.461  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.461  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.461  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:27.461  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.461  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58d5bc7 removed from the list
09-02 12:24:27.461  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.461  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3210e5f4 removed from the list
09-02 12:24:27.461  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:27.461  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.462  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.462  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.462  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.462  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.462  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.463  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3210e5f4 not in the list
09-02 12:24:27.463  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.463  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.464  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.466  6705  6776 D BluetoothLeScanner: could not find callback wrapper
09-02 12:24:27.466  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:24:27.466  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.466  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.466  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3df9ed63 removed from the list
09-02 12:24:27.466  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.466  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.466  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 1,2:24:27.466  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.466  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33872f92 removed from the list
09-02 12:24:27.466  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.466  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c64b2de added. We now have 2 listener(s)
09-02 12:24:27.467  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.468  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.469  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.469  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.469  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.469  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13fcbf added. We now have 9 listener(s)
09-02 12:24:27.469  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.469  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:24:27.471  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:24:27.473  6705  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:24:27.474  6705  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:24:27.474  6705  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:24:27.475  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:24:27.475  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13f7a6d5 added. We now have 3 listener(s)
,09-02 12:24:27.475  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:24:27.476  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.477  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:24:27.478  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:24:27.478  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:24:27.478  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:24:27.479  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:24:27.479  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13051eea added. We now have 10 listener(s)
09-02 12:24:27.479  6705  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:24:27.479  6705  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:24:27.479  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:27.479  6705  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:24:27.479  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.479  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.479  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:24:27.479  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.479  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c64b2de removed from the list
09-02 12:24:27.479  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.480  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13fcbf removed from the list
09-02 12:24:27.480  6705  6776 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:24:27.480  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.480  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.480  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.481  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.481  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.481  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.481  6705  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13fcbf not in the list
09-02 12:24:27.481  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.481  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.482  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:24:27.482  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:24:27.482  6705  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:24:27.482  6705  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13051eea removed from the list
09-02 12:24:27.482  6705  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:24:27.482  6705  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:24:27.482  6705  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:24:27.482  6705  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:24:27.482  6705  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13f7a6d5 removed from the list
09-02 12:24:27.483  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 12:24:27.483  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true, - Start operation: Should start/stop everything
09-02 12:24:27.483  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 12:24:27.483  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:24:27.483  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 12:24:27.483  6705  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:24:27.490  6705  8308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 900, name: My test thread name)
,09-02 12:24:27.491  6705  8308 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 900, thread name: My test thread name)
09-02 12:24:27.491  6705  8308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 900, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 12:24:27.498  6705  8309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 902, name: My test thread name)
09-02 12:24:27.498  6705  8309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 902, thread name: My test thread name)
09-02 12:24:27.498  6705  8309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 902, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 12:24:27.500  6705  6776 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 12:24:27.500  6705  6776 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 12:24:27.500  6705  6776 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 12:24:27.500  6705  6776 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 12:24:27.500  6705  6776 D com.test.thalitest.ThaliTestRunner: Total duration: 22835 ms
09-02 12:24:27.501  6705  6776 I jxcore-log: *Native tests were executed*
09-02 12:24:27.501  6705  6776 I jxcore-log: 
09-02 12:24:27.501  6705  6776 I jxcore-log: Total number of executed tests:  80
09-02 12:24:27.501  6705  6776 I jxcore-log: 
09-02 12:24:27.501  6705  6776 I jxcore-log: Number of passed tests:  80
09-02 12:24:27.501  6705  6776 I jxcore-log: 
09-02 12:24:27.501  6705  6776 I jxcore-log: Number of failed tests:  0
09-02 12:24:27.501  6705  6776 I jxcore-log: 
09-02 12:24:27.501  6705  6776 I jxcore-log: Number of ignored tests:  0
09-02 12:24:27.501  6705  6776 I jxcore-log: 
09-02 12:24:27.502  6705  6776 I jxcore-log: Total duration:  22835
09-02 12:24:27.502  6705  6776 I jxcore-log: 
09-02 12:24:27.502  6705  6776 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 12:24:27.502  6705  6776 I jxcore-log: 
09-02 12:24:27.504  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.504  6705  6776 I jxcore-log: 
09-02 12:24:27.506  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.506  6705  6776 I jxcore-log: 
09-02 12:24:27.506  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.506  6705  6776 I jxcore-log: 
,09-02 12:24:27.507  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.507  6705  6776 I jxcore-log: 
09-02 12:24:27.508  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.508  6705  6776 I jxcore-log: 
09-02 12:24:27.509  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.509  6705  6776 I jxcore-log: 
09-02 12:24:27.509  8257  8257 V Signer  : override build config not found
09-02 12:24:27.511  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.511  6705  6776 I jxcore-log: 
09-02 12:24:27.512  8257  8257 D Signer  : value of property debug is false
09-02 12:24:27.512  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.512  6705  6776 I jxcore-log: 
09-02 12:24:27.513  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:24:27.513  6705  6776 I jxcore-log: 
09-02 12:24:27.514  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:24:27.514  6705  6776 I jxcore-log: 
09-02 12:24:27.514  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.514  6705  6776 I jxcore-log: 
09-02 12:24:27.515  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.515  6705  6776 I jxcore-log: 
09-02 12:24:27.515  6705  6705 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 12:24:27.515  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:24:27.515  6705  6776 I jxcore-log: 
09-02 12:24:27.516  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:24:27.516  6705  6776 I jxcore-log: 
09-02 12:24:27.517  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:24:27.517  6705  6776 I jxcore-log: 
09-02 12:24:27.517  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.517  6705  6776 I jxcore-log: 
09-02 12:24:27.518  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.518  6705  6776 I jxcore-log: 
09-02 12:24:27.518  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.518  6705  6776 I jxcore-log: 
09-02 12:24:27.519  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.519  6705  6776 I jxcore-log: 
09-02 12:24,:27.522  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.522  6705  6776 I jxcore-log: 
09-02 12:24:27.523  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.523  6705  6776 I jxcore-log: 
09-02 12:24:27.524  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.524  6705  6776 I jxcore-log: 
09-02 12:24:27.524  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:24:27.524  6705  6776 I jxcore-log: 
09-02 12:24:27.525  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:24:27.525  6705  6776 I jxcore-log: 
09-02 12:24:27.526  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:24:27.526  6705  6776 I jxcore-log: 
09-02 12:24:27.527  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.527  6705  6776 I jxcore-log: 
09-02 12:24:27.528  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.528  6705  6776 I jxcore-log: 
09-02 12:24:27.529  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.529  6705  6776 I jxcore-log: 
09-02 12:24:27.530  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.530  6705  6776 I jxcore-log: 
,09-02 12:24:27.533  6705  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:24:27.533  6705  6776 I jxcore-log: 
09-02 12:24:27.555  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-02 12:24:27.555  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-02 12:24:27.556  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-02 12:24:27.556  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-02 12:24:27.556  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-02 12:24:27.556  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-02 12:24:27.556  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-02 12:24:27.557  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-02 12:24:27.557  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-02 12:24:27.557  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-02 12:24:27.557  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-02 12:24:27.557  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-02 12:24:27.558  8257  8257 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,09-02 12:24:27.570  8257  8257 V LGMDMManager: Create singleton instance
,09-02 12:24:27.618  8257  8257 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-02 12:24:27.665  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:27.672  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:27.679  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:27.685  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:27.691  1035  8282 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-02 12:24:27.693  1035  8282 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 12:24:27.693  1035  8282 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 12:24:27.693  1035  8282 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 12:24:27.693  1035  8282 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 12:24:27.693  1035  8282 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 12:24:27.693  1035  8282 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 12:24:27.693  1035  8282 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 12:24:27.693  1035  8282 D DhcpStateMachine: RunningState
,09-02 12:24:27.723  1035  1976 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8331 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-02 12:24:27.724  1035  1976 I ActivityManager: Killing 7382:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-02 12:24:27.801  8319  8319 D AndroidRuntime: 
09-02 12:24:27.801  8319  8319 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-02 12:24:27.804  8319  8319 D AndroidRuntime: CheckJNI is OFF
09-02 12:24:27.838  8257  8327 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 12:24:27.939  8319  8319 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 12:24:27.951  1035  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-02 12:24:27.952  1035  1105 I ActivityManager: Killing 6705:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-02 12:24:28.016  1035  1904 I WindowState: WIN DEATH: Window{1b371676 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 12:24:28.016  1035  1407 D WifiService: Client connection lost with reason: 4
,09-02 12:24:28.024  1035  1904 D InputDispatcher: Window went away: Window{1b371676 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 12:24:28.166  1035  1105 I ActivityManager:   Force finishing activity ActivityRecord{35ee0d33 u0 com.test.thalitest/.MainActivity t6}
,09-02 12:24:28.218   345   363 E GBMv2   : DFP En is all cleared set to be enabled
,09-02 12:24:28.232  1035  1052 W libprocessgroup: failed to open /acct/uid_10093/pid_7382/cgroup.procs: No such file or directory
09-02 12:24:28.232  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,09-02 12:24:28.236  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-02 12:24:28.239  1035  1976 W ActivityManager: Spurious death for ProcessRecord{1456a588 6705:com.test.thalitest/u0a118}, curProc for 6705: null
09-02 12:24:28.239  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-02 12:24:28.241  1035  1124 I ActivityManager:   Force finishing activity ActivityRecord{35ee0d33 u0 com.test.thalitest/.MainActivity t6 f}
09-02 12:24:28.241  1035  1124 W ActivityManager: Duplicate finish request for ActivityRecord{35ee0d33 u0 com.test.thalitest/.MainActivity t6 f}
,09-02 12:24:28.259  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-02 12:24:28.261  2033  2123 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-02 12:24:28.269  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-02 12:24:28.269  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9eb77c6 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-02 12:24:28.271  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-02 12:24:28.272  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{20e48387 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-02 12:24:28.282  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-02 12:24:28.283  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-02 12:24:28.290  8331  8331 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 12:24:28.305  3783  3783 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-02 12:24:28.311  2504  2695 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-02 12:24:28.312  7834  7834 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-02 12:24:28.312  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 12:24:28.313  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-02 12:24:28.316  4959  4959 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-02 12:24:28.317  4959  4959 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-02 12:24:28.317  4959  4959 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-02 12:24:28.317  4959  4959 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-02 12:24:28.317  4959  4959 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:24:28.317  4959  4959 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:24:28.317  4959  4959 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:24:28.317  4959  4959 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:24:28.317  4959  4959 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:24:28.317  4959  4959 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:24:28.317  4959  4959 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:24:28.317  4959  4959 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-02 12:24:28.359  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-02 12:24:28.362  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-02 12:24:28.362  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-02 12:24:28.363  1905  1905 D ActionManagerService: notifyUserLog: 1000003
09-02 12:24:28.363  3783  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-02 12:24:28.364  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-02 12:24:28.368  1905  1905 D ActionManagerService: notifyUserLog: 1000004
09-02 12:24:28.369  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-02 12:24:28.370  3783  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-02 12:24:28.371  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-02 12:24:28.372  3783  3799 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-02 12:24:28.388  1035  1996 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:24:28.391  1035  1102 W InputMethodInfo: Duplicated subtype definition found: , voice
09-02 12:24:28.397  5051  5051 I art     : Explicit concurrent mark sweep GC freed 8208(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 638us total 64.257ms
09-02 12:24:28.398  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-02 12:24:28.399  8331  8331 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-02 12:24:28.402  1601  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 12:24:28.402  1601  1657 D KeyguardModel: createShortcutInfo...
,09-02 12:24:28.406  1601  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 12:24:28.406  1601  1657 D KeyguardModel: createShortcutInfo...
09-02 12:24:28.413  1601  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 12:24:28.413  1601  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:28.413  1601  1657 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 12:24:28.414  1601  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 12:24:28.416  1601  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:24:28.417  1601  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , display: false
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , animation: false }
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , display: false
09-02 12:24:28.417  2033  2033 I GBoardWebViewUtils: , animation: false }
09-02 12:24:28.418  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
09-02 12:24:28.418  2033  2033 I GBoardWebViewUtils: , create_time: 1472216588858
09-02 12:24:28.418  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-02 12:24:28.418  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 12:24:28.418  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 12:24:28.418  2033  2033 I GBoardWebViewUtils: , display: false
09-02 12:24:28.418  2033  2033 I GBoardWebViewUtils: , animation: false }
09-02 12:24:28.418  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-02 12:24:28.422  1601  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 12:24:28.422  1601  1657 D KeyguardModel: createShortcutInfo...
09-02 12:24:28.427  1601  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 12:24:28.427  1601  1657 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:28.428  1601  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:24:28.428  1601  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-02 12:24:28.431  1601  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 12:24:28.431  1601  1657 D KeyguardModel: createShortcutInfo...
09-02 12:24:28.439  1601  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:28.440  1601  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 12:24:28.440  1601  1657 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-02 12:24:28.440  1601  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 12:24:28.443  1601  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:24:28.443  1601  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 12:24:28.446  2033  8382 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-02 12:24:28.449  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 12:24:28.450  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-02 12:24:28.452  1601  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 12:24:28.452  1601  1657 D KeyguardModel: createShortcutInfo...
,09-02 12:24:28.458  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-02 12:24:28.458  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 12:24:28.461  1870  1870 D SplitUIManager: split_name #11 / not available #0
09-02 12:24:28.461  1870  1870 D SplitUIService: removed split : 
09-02 12:24:28.465  1601  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 12:24:28.465  1601  1657 D KeyguardModel: createShortcutInfo...
,09-02 12:24:28.466  1035  1995 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:24:28.466  1035  1995 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:24:28.467  1601  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 12:24:28.467  1601  1657 D KeyguardModel: createShortcutInfo...
09-02 12:24:28.468  1601  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:24:28.469  1601  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-02 12:24:28.471  1601  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 12:24:28.471  1601  1657 D KeyguardModel: createShortcutInfo...
09-02 12:24:28.472  1601  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:24:28.472  1601  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-02 12:24:28.473  1601  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 12:24:28.473  1601  1657 D KeyguardModel: createShortcutInfo...
09-02 12:24:28.479  1601  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:24:28.479  1601  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 12:24:28.487  1601  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 12:24:28.487  1601  1657 D KeyguardModel: createShortcutInfo...
,09-02 12:24:28.494  1870  1870 D SplitUIManager: split_name #11 / not available #0
09-02 12:24:28.494  1870  1870 I SplitUIService: split app #11
09-02 12:24:28.508  8331  8331 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-02 12:24:28.508  8331  8331 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 12:24:28.509  8331  8331 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-02 12:24:28.509  8331  8331 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-02 12:24:28.509  8331  8331 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-02 12:24:28.510  1035  1035 I art     : Explicit concurrent mark sweep GC freed 78517(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.971ms total 240.348ms
09-02 12:24:28.510  8331  8331 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-02 12:24:28.514  8331  8331 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-02 12:24:28.521  1035  1124 I art     : WaitForGcToComplete blocked for 123.931ms for cause Explicit
09-02 12:24:28.522  1035  1392 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:24:28.522  1035  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:24:28.522  1035  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:24:28.522  1035  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:24:28.523  1035  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:24:28.523  1035  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:24:28.524  1035  1432 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-02 12:24:28.524  1035  1432 D ConnectivityService: identical MTU - not setting
09-02 12:24:28.524  1035  1432 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 12:24:28.524  1035  1432 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 12:24:28.524  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:24:28.524  1035  1432 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:28.524  1035  1432 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:24:28.525  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-02 12:24:28.527  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.528  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.536  8331  8331 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:24:28.537  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 12:24:28.539  8331  8331 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-02 12:24:28.543  1035  1035 D administrator: Handling package changes for user 0
09-02 12:24:28.544  1035  1940 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:24:28.545  7834  7834 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 12:24:28.553  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-02 12:24:28.553  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 12:24:28.558  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-02 12:24:28.560  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:24:28.565  6996  6996 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 12:24:28.567  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:28.567  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.572  8331  8331 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-02 12:24:28.576  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:28.582  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.586  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.586  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.587  8331  8331 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:24:28.588  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:28.592  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.593  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.597  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.602  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.602  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.603  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:24:28.605  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:24:28.605  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:24:28.605  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:24:28.605  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:24:28.606  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:24:28.607  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:24:28.608  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 12:24:28.608  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:24:28.608  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:24:28.608  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:24:28.608  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 12:24:28.609  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 12:24:28.611  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.612  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:28.614   331   420 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-02 12:24:28.615  3344  8390 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-02 12:24:28.622  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.629  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.630  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-02 12:24:28.632  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.634  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-02 12:24:28.635  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-02 12:24:28.637  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.637  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.637  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:28.637  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-02 12:24:28.639  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-02 12:24:28.643  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:28.643  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-02 12:24:28.648  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.652  1035  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cb2298b u0 com.lge.launcher2/.Launcher t5} time:142101
09-02 12:24:28.656  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,09-02 12:24:28.656  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.664  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.671  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-02 12:24:28.671  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 12:24:28.672  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.672  2033  2184 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-02 12:24:28.673  2033  2184 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-02 12:24:28.673  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.673  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.673  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:24:28.679  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.677  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:28.683  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-02 12:24:28.684  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.684  2575  2575 D [Concierge]Service: onStartCommand(). Type : 8
09-02 12:24:28.684  2575  2575 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-02 12:24:28.685  2575  2575 D [Concierge]Service: Update widget ID : 11
09-02 12:24:28.686  2033  2033 D [Concierge]WidgetView: change position of spinner
09-02 12:24:28.687  2575  2575 D [Concierge]Service: onStartCommand(). Type : 0
09-02 12:24:28.687  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1472811868687
,09-02 12:24:28.692  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.697  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.697  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.697  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:28.701  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:28.701  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.705  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.707  8257  8327 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:24:28.707  8257  8327 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:24:28.708  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-02 12:24:28.708  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 12:24:28.708  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-02 12:24:28.708  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.710  1035  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-02 12:24:28.712  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.712  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1027974143
09-02 12:24:28.713  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.713  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:28.713  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-02 12:24:28.713  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-02 12:24:28.716  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2101eb7f
09-02 12:24:28.716  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-02 12:24:28.717  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 12:24:28.717  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.718  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.719  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:28.724  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-02 12:24:28.724  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 12:24:28.725  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472811754623, New one : 1472811868687
09-02 12:24:28.725  2033  2033 D [Concierge]WidgetView: Unregister all receivers
09-02 12:24:28.725  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 12:24:28.727  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:24:28.729  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-02 12:24:28.729  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.731  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-02 12:24:28.732  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-02 12:24:28.733  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-02 12:24:28.733  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.734  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-02 12:24:28.735  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-02 12:24:28.736  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.736  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.743  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.743  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.746  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:28.749  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.749  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:24:28.768  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-02 12:24:28.770  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.771  1035  1124 I art     : Explicit concurrent mark sweep GC freed 13429(889KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 10.541ms total 246.977ms
09-02 12:24:28.775  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:24:28.778  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-02 12:24:28.779  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-02 12:24:28.780  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:24:28.780  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.780  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.780  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:24:28.787  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.787  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:28.791  8212  8212 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 12:24:28.794  8212  8212 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:28.799  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.802  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39f0d7cb time:142251
09-02 12:24:28.802  8257  8327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-02 12:24:28.809  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.813  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:24:28.813  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.814  8331  8331 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-02 12:24:28.814  8331  8331 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:24:28.814  8331  8331 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 12:24:28.823  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:24:28.824  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-02 12:24:28.825  8257  8327 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-02 12:24:28.827  8212  8212 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 12:24:28.831  8212  8212 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:24:28.831  8257  8327 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-02 12:24:28.831  8257  8327 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 12:24:28.832  8257  8327 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 12:24:28.832  8257  8327 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-02 12:24:28.832  8257  8327 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-02 12:24:28.833  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:24:28.834  8257  8327 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-02 12:24:28.836  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:24:28.836  8257  8327 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-02 12:24:28.840  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:24:28.840  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:24:28.841  8331  8331 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 12:24:28.841  8331  8331 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:24:28.841  8331  8331 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 12:24:28.843  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-02 12:24:28.844  8257  8257 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-02 12:24:28.845  8257  8328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:24:28.846  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-02 12:24:28.853  2211  2211 I ConfigService: onCreate
09-02 12:24:28.853  2211  2211 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-02 12:24:28.855  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-02 12:24:28.860  2211  2211 I ConfigService: onBind returning update interface
09-02 12:24:28.860  2211  2211 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-02 12:24:28.860  2211  2211 I ConfigService: onBind returning config service
,09-02 12:24:28.876  2211  2211 I ConfigService: onDestroy
09-02 12:24:28.881  1817  8399 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-02 12:24:28.884  8319  8319 D AndroidRuntime: Shutting down VM
09-02 12:24:28.907  5887  8405 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-02 12:24:28.912  1817  8406 I PeopleContactsSync: CP2 sync disabled
09-02 12:24:28.918  1817  5227 I Icing   : doRemovePackageData com.test.thalitest
,09-02 12:24:28.930  1817  8404 W GmsApplication: Using Auth Proxy for data requests.
,09-02 12:24:28.947  1035  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:24:28.949  2211  2323 I art     : Explicit concurrent mark sweep GC freed 6402(379KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 674us total 16.299ms
09-02 12:24:28.951  1817  8404 W GmsApplication: Using Auth Proxy for data requests.
09-02 12:24:28.953  7172  7172 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-02 12:24:28.963  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-02 12:24:28.968  1035  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-02 12:24:28.974  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-02 12:24:28.979  2334  8411 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-02 12:24:29.005  2033  2886 I GBoardtInterface: onReloaded()
,09-02 12:24:29.007  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-02 12:24:29.008  1035  1957 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8412 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-02 12:24:29.012  3783  3799 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 12:24:29.014  3783  3798 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 12:24:29.020  1905  1905 D ActionManagerService: notifyUserLog: 1000001
,09-02 12:24:29.022  3783  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 12:24:29.022  3783  4933 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 12:24:29.023  1905  1905 D ActionManagerService: notifyUserLog: 1000001
09-02 12:24:29.024  3783  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 12:24:29.024  3783  4933 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 12:24:29.024  3783  4933 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-02 12:24:29.024  3783  4933 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-02 12:24:29.024  3783  3799 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 12:24:29.026  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-02 12:24:29.026  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-02 12:24:29.028  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-02 12:24:29.028  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-02 12:24:29.029  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-02 12:24:29.029  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-02 12:24:29.054  8412  8412 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:24:29.055  8412  8412 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:24:29.056  8412  8412 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 12:24:29.056  8412  8412 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-02 12:24:29.122  1035  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8430 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-02 12:24:29.125  8412  8412 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-02 12:24:29.133  8412  8412 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-02 12:24:29.154  8412  8412 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:24:29.179  1035  1957 I ActivityManager: Killing 7422:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-02 12:24:29.179  8412  8412 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:24:29.179  8412  8412 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:24:29.270  1035  2014 W libprocessgroup: failed to open /acct/uid_10005/pid_7422/cgroup.procs: No such file or directory

```
